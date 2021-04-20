# Archetypes

A series of very tiny archetypes

### distribution

these archetypes are distributed with [jitpack.io](https://jitpack.io/)

### Archetypes

- junit5
- kotlin
- spring-boot


### zsh configuration

```shell

function junit5(){
mvn  -B archetype:generate -Pjitpack -DgroupId=io.mosfet -DartifactId=$1 -DprojectName=$1 -DarchetypeGroupId=com.github.kmos -DarchetypeArtifactId=junit5 -DarchetypeVersion=1.2 -Dversion=1.0-SNAPSHOT
}

function kotlin(){
mvn  -B archetype:generate -Pjitpack -DgroupId=io.mosfet -DartifactId=$1 -DprojectName=$1 -DarchetypeGroupId=com.github.kmos -DarchetypeArtifactId=kotlin -DarchetypeVersion=1.2 -Dversion=1.0-SNAPSHOT
}
function spring(){
mvn  -B archetype:generate -Pjitpack -DgroupId=io.mosfet -DartifactId=$1 -DprojectName=$1 -DarchetypeGroupId=com.github.kmos -DarchetypeArtifactId=spring-boot -DarchetypeVersion=1.2 -Dversion=1.0-SNAPSHOT
}


```
