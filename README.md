# Java esl client for netty3
A Fork from http://git.freeswitch.org/git/freeswitch-contrib/tree/dvarnes/java/esl-client

# About
This page documents the org.freeswitch.esl.client library maintained in the freeswitch-contrib git repository. See Java ESL page for overview of other options for using Java with the FreeSWITCH Event Socket.

# Features
* Licensed under Apache License version 2 http://www.apache.org/licenses/LICENSE-2.0
* Runtime dependency on Netty (Apache License) and SLF4j (MIT License) libraries
* No native library runtime dependencies
* ESL Inbound and Outbound support, see Event Socket and Event Socket Outbound.
* OSGi ready
* Built using maven

# Getting Java ESL library
## Binary jar files
Current released version
* org.freeswitch.esl.client-0.9.2.jar
* org.freeswitch.esl.client-0.9.2-sources.jar
* org.freeswitch.esl.client-0.9.2-javadoc.jar

Now it is available and update on github, welcome you to join us. ^_^

https://github.com/fivetime/esl-client-netty3

This is the hosted repository maintained by Sonatype for OSS projects. The files are automatically synced from there to the maven central repository

## From maven central repository
Assuming you are using a build tool that can resolve dependencies from the maven 2 central repository, add the following to your project pom.xml

`<dependency>
  <groupId>org.freeswitch.esl.client</groupId>
  <artifactId>esl-client-netty3</artifactId>
  <version>0.9.2</version>
  <type>pom</type>
</dependency>`
 

# Runtime dependencies
If you download and install the jar(s) manually, you must also supply the following jars on your Java classpath

* netty-3.10.6.Final.jar for async socket comms
* slf4j-api-1.7.30.jar for logging
* An slf4j implementation, use slf4j-nop.jar if no logging required.
