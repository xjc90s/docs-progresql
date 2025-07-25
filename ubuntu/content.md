# What is Ubuntu?

Ubuntu is a Debian-based Linux operating system that runs from the desktop to the cloud, to all your internet connected things. It is the world's most popular operating system across public clouds and OpenStack clouds. It is the number one platform for containers; from Docker to Kubernetes to LXD, Ubuntu can run your containers at scale. Fast, secure and simple, Ubuntu powers millions of PCs worldwide.

Development of Ubuntu is led by Canonical Ltd. Canonical generates revenue through the sale of technical support and other services related to Ubuntu. The Ubuntu project is publicly committed to the principles of open-source software development; people are encouraged to use free software, study how it works, improve upon it, and distribute it.

> [wikipedia.org/wiki/Ubuntu](https://en.wikipedia.org/wiki/Ubuntu)

%%LOGO%%

# What's in this image?

This image is built from official rootfs tarballs provided by Canonical (see `dist-*` tags at https://git.launchpad.net/cloud-images/+oci/ubuntu-base).

The `%%IMAGE%%:latest` tag points to the "latest LTS", since that's the version recommended for general use. The `%%IMAGE%%:rolling` tag points to the latest release (regardless of LTS status).

Along a similar vein, the `%%IMAGE%%:devel` tag is an alias for whichever release the "devel" suite on the mirrors currently points to, as determined by the following one-liner: `wget -qO- http://archive.ubuntu.com/ubuntu/dists/devel/Release | awk -F ': ' '$1 == "Codename" { print $2; exit }'`

## Locales

Given that it is a minimal install of Ubuntu, this image only includes the `C`, `C.UTF-8`, and `POSIX` locales by default. For most uses requiring a UTF-8 locale, `C.UTF-8` is likely sufficient (`-e LANG=C.UTF-8` or `ENV LANG C.UTF-8`).

For uses where that is not sufficient, other locales can be installed/generated via the `locales` package. [PostgreSQL has a good example of doing so](https://github.com/docker-library/postgres/blob/69bc540ecfffecce72d49fa7e4a46680350037f9/9.6/Dockerfile#L21-L24), copied below:

```dockerfile
RUN apt-get update && apt-get install -y locales && rm -rf /var/lib/apt/lists/* \
	&& localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
ENV LANG en_US.utf8
```

## Unminimize

Starting from [Ubuntu 24.10 "Oracular Oriole"](https://discourse.ubuntu.com/t/oracular-oriole-release-notes/44878#unminimize), the `unminimize` command will no longer be shipped by default on minimal images. It has now been moved to a dedicated package which can be installed via `apt-get install -y unminimize`.

# How is the rootfs built?

The tarballs published by Canonical, referenced by `dist-*` tags in https://git.launchpad.net/cloud-images/+oci/ubuntu-base Git repository, are built from scripts that live in [the livecd-rootfs project](https://code.launchpad.net/~ubuntu-core-dev/livecd-rootfs/+git/livecd-rootfs/+ref/ubuntu/master), especially `live-build/auto/build`. The builds are run on Launchpad. For build history see `livefs` build pages of individual releases on Launchpad:

-	[Jammy](https://launchpad.net/~cloud-images-release-managers/+livefs/ubuntu/jammy/ubuntu-oci)
-	[Noble](https://launchpad.net/~cloud-images-release-managers/+livefs/ubuntu/noble/ubuntu-oci)
-	[Plucky](https://launchpad.net/~cloud-images-release-managers/+livefs/ubuntu/plucky/ubuntu-oci)
-	[Questing](https://launchpad.net/~cloud-images-release-managers/+livefs/ubuntu/questing/ubuntu-oci)
