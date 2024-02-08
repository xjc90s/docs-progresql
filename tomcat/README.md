<!--

********************************************************************************

WARNING:

    DO NOT EDIT "tomcat/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "tomcat/" combined with a set of templates)

********************************************************************************

-->

# Quick reference

-	**Maintained by**:  
	[the Docker Community](https://github.com/docker-library/tomcat)

-	**Where to get help**:  
	[the Docker Community Slack](https://dockr.ly/comm-slack), [Server Fault](https://serverfault.com/help/on-topic), [Unix & Linux](https://unix.stackexchange.com/help/on-topic), or [Stack Overflow](https://stackoverflow.com/help/on-topic)

# Supported tags and respective `Dockerfile` links

-	[`11.0.0-M16-jdk21-temurin-jammy`, `11.0.0-jdk21-temurin-jammy`, `11.0-jdk21-temurin-jammy`, `11.0.0-M16-jdk21-temurin`, `11.0.0-jdk21-temurin`, `11.0-jdk21-temurin`, `11.0.0-M16-jdk21`, `11.0.0-jdk21`, `11.0-jdk21`, `11.0.0-M16`, `11.0.0`, `11.0`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/11.0/jdk21/temurin-jammy/Dockerfile)
-	[`11.0.0-M16-jre21-temurin-jammy`, `11.0.0-jre21-temurin-jammy`, `11.0-jre21-temurin-jammy`, `11.0.0-M16-jre21-temurin`, `11.0.0-jre21-temurin`, `11.0-jre21-temurin`, `11.0.0-M16-jre21`, `11.0.0-jre21`, `11.0-jre21`](https://github.com/docker-library/tomcat/blob/b9460102c252660bc38683cf3f68883f00dccb41/11.0/jre21/temurin-jammy/Dockerfile)
-	[`10.1.18-jdk21-temurin-jammy`, `10.1-jdk21-temurin-jammy`, `10-jdk21-temurin-jammy`, `jdk21-temurin-jammy`, `10.1.18-jdk21-temurin`, `10.1-jdk21-temurin`, `10-jdk21-temurin`, `jdk21-temurin`, `10.1.18-jdk21`, `10.1-jdk21`, `10-jdk21`, `jdk21`, `10.1.18`, `10.1`, `10`, `latest`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/10.1/jdk21/temurin-jammy/Dockerfile)
-	[`10.1.18-jre21-temurin-jammy`, `10.1-jre21-temurin-jammy`, `10-jre21-temurin-jammy`, `jre21-temurin-jammy`, `10.1.18-jre21-temurin`, `10.1-jre21-temurin`, `10-jre21-temurin`, `jre21-temurin`, `10.1.18-jre21`, `10.1-jre21`, `10-jre21`, `jre21`](https://github.com/docker-library/tomcat/blob/b6551d7785f573f92c379d916c374024fedb5465/10.1/jre21/temurin-jammy/Dockerfile)
-	[`10.1.18-jdk17-temurin-jammy`, `10.1-jdk17-temurin-jammy`, `10-jdk17-temurin-jammy`, `jdk17-temurin-jammy`, `10.1.18-jdk17-temurin`, `10.1-jdk17-temurin`, `10-jdk17-temurin`, `jdk17-temurin`, `10.1.18-jdk17`, `10.1-jdk17`, `10-jdk17`, `jdk17`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/10.1/jdk17/temurin-jammy/Dockerfile)
-	[`10.1.18-jre17-temurin-jammy`, `10.1-jre17-temurin-jammy`, `10-jre17-temurin-jammy`, `jre17-temurin-jammy`, `10.1.18-jre17-temurin`, `10.1-jre17-temurin`, `10-jre17-temurin`, `jre17-temurin`, `10.1.18-jre17`, `10.1-jre17`, `10-jre17`, `jre17`](https://github.com/docker-library/tomcat/blob/b6551d7785f573f92c379d916c374024fedb5465/10.1/jre17/temurin-jammy/Dockerfile)
-	[`10.1.18-jdk11-temurin-jammy`, `10.1-jdk11-temurin-jammy`, `10-jdk11-temurin-jammy`, `jdk11-temurin-jammy`, `10.1.18-jdk11-temurin`, `10.1-jdk11-temurin`, `10-jdk11-temurin`, `jdk11-temurin`, `10.1.18-jdk11`, `10.1-jdk11`, `10-jdk11`, `jdk11`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/10.1/jdk11/temurin-jammy/Dockerfile)
-	[`10.1.18-jre11-temurin-jammy`, `10.1-jre11-temurin-jammy`, `10-jre11-temurin-jammy`, `jre11-temurin-jammy`, `10.1.18-jre11-temurin`, `10.1-jre11-temurin`, `10-jre11-temurin`, `jre11-temurin`, `10.1.18-jre11`, `10.1-jre11`, `10-jre11`, `jre11`](https://github.com/docker-library/tomcat/blob/b6551d7785f573f92c379d916c374024fedb5465/10.1/jre11/temurin-jammy/Dockerfile)
-	[`9.0.85-jdk21-temurin-jammy`, `9.0-jdk21-temurin-jammy`, `9-jdk21-temurin-jammy`, `9.0.85-jdk21-temurin`, `9.0-jdk21-temurin`, `9-jdk21-temurin`, `9.0.85-jdk21`, `9.0-jdk21`, `9-jdk21`, `9.0.85`, `9.0`, `9`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk21/temurin-jammy/Dockerfile)
-	[`9.0.85-jre21-temurin-jammy`, `9.0-jre21-temurin-jammy`, `9-jre21-temurin-jammy`, `9.0.85-jre21-temurin`, `9.0-jre21-temurin`, `9-jre21-temurin`, `9.0.85-jre21`, `9.0-jre21`, `9-jre21`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre21/temurin-jammy/Dockerfile)
-	[`9.0.85-jdk21-corretto-al2`, `9.0-jdk21-corretto-al2`, `9-jdk21-corretto-al2`, `9.0.85-jdk21-corretto`, `9.0-jdk21-corretto`, `9-jdk21-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk21/corretto-al2/Dockerfile)
-	[`9.0.85-jdk17-temurin-jammy`, `9.0-jdk17-temurin-jammy`, `9-jdk17-temurin-jammy`, `9.0.85-jdk17-temurin`, `9.0-jdk17-temurin`, `9-jdk17-temurin`, `9.0.85-jdk17`, `9.0-jdk17`, `9-jdk17`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk17/temurin-jammy/Dockerfile)
-	[`9.0.85-jre17-temurin-jammy`, `9.0-jre17-temurin-jammy`, `9-jre17-temurin-jammy`, `9.0.85-jre17-temurin`, `9.0-jre17-temurin`, `9-jre17-temurin`, `9.0.85-jre17`, `9.0-jre17`, `9-jre17`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre17/temurin-jammy/Dockerfile)
-	[`9.0.85-jdk17-temurin-focal`, `9.0-jdk17-temurin-focal`, `9-jdk17-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk17/temurin-focal/Dockerfile)
-	[`9.0.85-jre17-temurin-focal`, `9.0-jre17-temurin-focal`, `9-jre17-temurin-focal`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre17/temurin-focal/Dockerfile)
-	[`9.0.85-jdk17-corretto-al2`, `9.0-jdk17-corretto-al2`, `9-jdk17-corretto-al2`, `9.0.85-jdk17-corretto`, `9.0-jdk17-corretto`, `9-jdk17-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk17/corretto-al2/Dockerfile)
-	[`9.0.85-jdk11-temurin-jammy`, `9.0-jdk11-temurin-jammy`, `9-jdk11-temurin-jammy`, `9.0.85-jdk11-temurin`, `9.0-jdk11-temurin`, `9-jdk11-temurin`, `9.0.85-jdk11`, `9.0-jdk11`, `9-jdk11`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk11/temurin-jammy/Dockerfile)
-	[`9.0.85-jre11-temurin-jammy`, `9.0-jre11-temurin-jammy`, `9-jre11-temurin-jammy`, `9.0.85-jre11-temurin`, `9.0-jre11-temurin`, `9-jre11-temurin`, `9.0.85-jre11`, `9.0-jre11`, `9-jre11`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre11/temurin-jammy/Dockerfile)
-	[`9.0.85-jdk11-temurin-focal`, `9.0-jdk11-temurin-focal`, `9-jdk11-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk11/temurin-focal/Dockerfile)
-	[`9.0.85-jre11-temurin-focal`, `9.0-jre11-temurin-focal`, `9-jre11-temurin-focal`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre11/temurin-focal/Dockerfile)
-	[`9.0.85-jdk11-corretto-al2`, `9.0-jdk11-corretto-al2`, `9-jdk11-corretto-al2`, `9.0.85-jdk11-corretto`, `9.0-jdk11-corretto`, `9-jdk11-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk11/corretto-al2/Dockerfile)
-	[`9.0.85-jdk8-temurin-jammy`, `9.0-jdk8-temurin-jammy`, `9-jdk8-temurin-jammy`, `9.0.85-jdk8-temurin`, `9.0-jdk8-temurin`, `9-jdk8-temurin`, `9.0.85-jdk8`, `9.0-jdk8`, `9-jdk8`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk8/temurin-jammy/Dockerfile)
-	[`9.0.85-jre8-temurin-jammy`, `9.0-jre8-temurin-jammy`, `9-jre8-temurin-jammy`, `9.0.85-jre8-temurin`, `9.0-jre8-temurin`, `9-jre8-temurin`, `9.0.85-jre8`, `9.0-jre8`, `9-jre8`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre8/temurin-jammy/Dockerfile)
-	[`9.0.85-jdk8-temurin-focal`, `9.0-jdk8-temurin-focal`, `9-jdk8-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk8/temurin-focal/Dockerfile)
-	[`9.0.85-jre8-temurin-focal`, `9.0-jre8-temurin-focal`, `9-jre8-temurin-focal`](https://github.com/docker-library/tomcat/blob/9e2cd9f76f5013325541d36aed10b815405fcdb3/9.0/jre8/temurin-focal/Dockerfile)
-	[`9.0.85-jdk8-corretto-al2`, `9.0-jdk8-corretto-al2`, `9-jdk8-corretto-al2`, `9.0.85-jdk8-corretto`, `9.0-jdk8-corretto`, `9-jdk8-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/9.0/jdk8/corretto-al2/Dockerfile)
-	[`8.5.98-jdk21-temurin-jammy`, `8.5-jdk21-temurin-jammy`, `8-jdk21-temurin-jammy`, `8.5.98-jdk21-temurin`, `8.5-jdk21-temurin`, `8-jdk21-temurin`, `8.5.98-jdk21`, `8.5-jdk21`, `8-jdk21`, `8.5.98`, `8.5`, `8`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk21/temurin-jammy/Dockerfile)
-	[`8.5.98-jre21-temurin-jammy`, `8.5-jre21-temurin-jammy`, `8-jre21-temurin-jammy`, `8.5.98-jre21-temurin`, `8.5-jre21-temurin`, `8-jre21-temurin`, `8.5.98-jre21`, `8.5-jre21`, `8-jre21`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre21/temurin-jammy/Dockerfile)
-	[`8.5.98-jdk21-corretto-al2`, `8.5-jdk21-corretto-al2`, `8-jdk21-corretto-al2`, `8.5.98-jdk21-corretto`, `8.5-jdk21-corretto`, `8-jdk21-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk21/corretto-al2/Dockerfile)
-	[`8.5.98-jdk17-temurin-jammy`, `8.5-jdk17-temurin-jammy`, `8-jdk17-temurin-jammy`, `8.5.98-jdk17-temurin`, `8.5-jdk17-temurin`, `8-jdk17-temurin`, `8.5.98-jdk17`, `8.5-jdk17`, `8-jdk17`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk17/temurin-jammy/Dockerfile)
-	[`8.5.98-jre17-temurin-jammy`, `8.5-jre17-temurin-jammy`, `8-jre17-temurin-jammy`, `8.5.98-jre17-temurin`, `8.5-jre17-temurin`, `8-jre17-temurin`, `8.5.98-jre17`, `8.5-jre17`, `8-jre17`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre17/temurin-jammy/Dockerfile)
-	[`8.5.98-jdk17-temurin-focal`, `8.5-jdk17-temurin-focal`, `8-jdk17-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk17/temurin-focal/Dockerfile)
-	[`8.5.98-jre17-temurin-focal`, `8.5-jre17-temurin-focal`, `8-jre17-temurin-focal`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre17/temurin-focal/Dockerfile)
-	[`8.5.98-jdk17-corretto-al2`, `8.5-jdk17-corretto-al2`, `8-jdk17-corretto-al2`, `8.5.98-jdk17-corretto`, `8.5-jdk17-corretto`, `8-jdk17-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk17/corretto-al2/Dockerfile)
-	[`8.5.98-jdk11-temurin-jammy`, `8.5-jdk11-temurin-jammy`, `8-jdk11-temurin-jammy`, `8.5.98-jdk11-temurin`, `8.5-jdk11-temurin`, `8-jdk11-temurin`, `8.5.98-jdk11`, `8.5-jdk11`, `8-jdk11`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk11/temurin-jammy/Dockerfile)
-	[`8.5.98-jre11-temurin-jammy`, `8.5-jre11-temurin-jammy`, `8-jre11-temurin-jammy`, `8.5.98-jre11-temurin`, `8.5-jre11-temurin`, `8-jre11-temurin`, `8.5.98-jre11`, `8.5-jre11`, `8-jre11`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre11/temurin-jammy/Dockerfile)
-	[`8.5.98-jdk11-temurin-focal`, `8.5-jdk11-temurin-focal`, `8-jdk11-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk11/temurin-focal/Dockerfile)
-	[`8.5.98-jre11-temurin-focal`, `8.5-jre11-temurin-focal`, `8-jre11-temurin-focal`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre11/temurin-focal/Dockerfile)
-	[`8.5.98-jdk11-corretto-al2`, `8.5-jdk11-corretto-al2`, `8-jdk11-corretto-al2`, `8.5.98-jdk11-corretto`, `8.5-jdk11-corretto`, `8-jdk11-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk11/corretto-al2/Dockerfile)
-	[`8.5.98-jdk8-temurin-jammy`, `8.5-jdk8-temurin-jammy`, `8-jdk8-temurin-jammy`, `8.5.98-jdk8-temurin`, `8.5-jdk8-temurin`, `8-jdk8-temurin`, `8.5.98-jdk8`, `8.5-jdk8`, `8-jdk8`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk8/temurin-jammy/Dockerfile)
-	[`8.5.98-jre8-temurin-jammy`, `8.5-jre8-temurin-jammy`, `8-jre8-temurin-jammy`, `8.5.98-jre8-temurin`, `8.5-jre8-temurin`, `8-jre8-temurin`, `8.5.98-jre8`, `8.5-jre8`, `8-jre8`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre8/temurin-jammy/Dockerfile)
-	[`8.5.98-jdk8-temurin-focal`, `8.5-jdk8-temurin-focal`, `8-jdk8-temurin-focal`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk8/temurin-focal/Dockerfile)
-	[`8.5.98-jre8-temurin-focal`, `8.5-jre8-temurin-focal`, `8-jre8-temurin-focal`](https://github.com/docker-library/tomcat/blob/4b942a0053c7c8264742a0c0bfaa4b6d99730733/8.5/jre8/temurin-focal/Dockerfile)
-	[`8.5.98-jdk8-corretto-al2`, `8.5-jdk8-corretto-al2`, `8-jdk8-corretto-al2`, `8.5.98-jdk8-corretto`, `8.5-jdk8-corretto`, `8-jdk8-corretto`](https://github.com/docker-library/tomcat/blob/97251f3bf88258f6edcb6f313970ae1971e4537b/8.5/jdk8/corretto-al2/Dockerfile)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/docker-library/tomcat/issues](https://github.com/docker-library/tomcat/issues?q=)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/tomcat/), [`arm32v7`](https://hub.docker.com/r/arm32v7/tomcat/), [`arm64v8`](https://hub.docker.com/r/arm64v8/tomcat/), [`ppc64le`](https://hub.docker.com/r/ppc64le/tomcat/), [`s390x`](https://hub.docker.com/r/s390x/tomcat/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/tomcat/` directory](https://github.com/docker-library/repo-info/blob/master/repos/tomcat) ([history](https://github.com/docker-library/repo-info/commits/master/repos/tomcat))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/tomcat` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Ftomcat)  
	[official-images repo's `library/tomcat` file](https://github.com/docker-library/official-images/blob/master/library/tomcat) ([history](https://github.com/docker-library/official-images/commits/master/library/tomcat))

-	**Source of this description**:  
	[docs repo's `tomcat/` directory](https://github.com/docker-library/docs/tree/master/tomcat) ([history](https://github.com/docker-library/docs/commits/master/tomcat))

# What is Tomcat?

Apache Tomcat (or simply Tomcat) is an open source web server and servlet container developed by the Apache Software Foundation (ASF). Tomcat implements the Java Servlet and the JavaServer Pages (JSP) specifications from Oracle, and provides a "pure Java" HTTP web server environment for Java code to run in. In the simplest config Tomcat runs in a single operating system process. The process runs a Java virtual machine (JVM). Every single HTTP request from a browser to Tomcat is processed in the Tomcat process in a separate thread.

> [wikipedia.org/wiki/Apache_Tomcat](https://en.wikipedia.org/wiki/Apache_Tomcat)

![logo](https://raw.githubusercontent.com/docker-library/docs/8e31eb93a02d504d0cfe1da435aa31b377fc627d/tomcat/logo.png)Logo &copy; Apache Software Fountation

# How to use this image.

**Note:** as of [docker-library/tomcat#181](https://github.com/docker-library/tomcat/pull/181), the upstream-provided (example) webapps are *not* enabled by default, per [upstream's security recommendations](https://tomcat.apache.org/tomcat-9.0-doc/security-howto.html#Default_web_applications), but are still available under the `webapps.dist` folder within the image to make them easier to re-enable.

Run the default Tomcat server (`CMD ["catalina.sh", "run"]`):

```console
$ docker run -it --rm tomcat:9.0
```

You can test it by visiting `http://container-ip:8080` in a browser or, if you need access outside the host, on port 8888:

```console
$ docker run -it --rm -p 8888:8080 tomcat:9.0
```

You can then go to `http://localhost:8888` or `http://host-ip:8888` in a browser (noting that it will return a 404 since there are no webapps loaded by default).

The default Tomcat environment in the image is:

	CATALINA_BASE:   /usr/local/tomcat
	CATALINA_HOME:   /usr/local/tomcat
	CATALINA_TMPDIR: /usr/local/tomcat/temp
	JRE_HOME:        /usr
	CLASSPATH:       /usr/local/tomcat/bin/bootstrap.jar:/usr/local/tomcat/bin/tomcat-juli.jar

The configuration files are available in `/usr/local/tomcat/conf/`. By default, no user is included in the "manager-gui" role required to operate the "/manager/html" web application. If you wish to use this app, you must define such a user in `tomcat-users.xml`.

# License

View [license information](https://www.apache.org/licenses/LICENSE-2.0) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `tomcat/` directory](https://github.com/docker-library/repo-info/tree/master/repos/tomcat).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
