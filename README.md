Simple Maven Example Project Archetype
=============

Requirements
======
To build, you need

* Java 8 or higher (<http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html>) 
* Maven 3 or higher (<http://maven.apache.org/>)

Building and Setup
======
Before cloning this repository, be sure to enable automatic conversion of CRLF/LF on your machine using `git config --global core.autocrlf input`. For more information, please  refer to <http://help.github.com/dealing-with-lineendings/>

Generate a project using this archetype
======

Run `mvn archetype:generate -DarchetypeCatalog=http://nexus.farberg.de/service/local/repositories/snapshots/content/archetype-catalog.xml -DarchetypeGroupId=de.farberg.maven -DarchetypeArtifactId=simple-archetype -DarchetypeVersion=0.0.1-SNAPSHOT`

