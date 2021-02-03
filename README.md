# fluffy-archetype-java
An improved variety of a Maven Java project archetype. Extra fluffy ❤  
  
Contains defaults for often used maven properties and common test dependencies, e. g. [JUnit](https://junit.org/junit5) & [AssertJ](https://assertj.github.io/doc).  

The latest release version always tries to include the latest versions of all used dependencies and plugins.  

Projects created with this archetype will also contain reasonable default configuration for your favorit IDE. Have a look at the directory `ide_setup` for details.  

## Build
`mvn clean install`  
  
## Usage
Generate a new project with this command:  
`mvn archetype:generate -B -DarchetypeGroupId=de.itemis.mosig.fluffy -DarchetypeArtifactId=de.itemis.mosig.fluffy.archetype.java -DarchetypeVersion=1.1.0-SNAPSHOT -DgroupId=de.my.groupid -DartifactId=de.my.groupid.artifactid -Dversion=1.0.0-SNAPSHOT -Dpackage=de.my.groupid.artifactid`

## Development
The latest snapshot lives on the main development branch `develop`. The latest release lives on the `main` branch. Tags will be created for every release and for every new snapshot.  

## Further Reading
[https://maven.apache.org/guides/mini/guide-creating-archetypes.html](https://maven.apache.org/guides/mini/guide-creating-archetypes.html)
  