# Groovy OSGi Bundle

This sample project contains an OSGi bundle written in Groovy & a test fragment also written in Groovy. It also provides a Maven configuration to build Groovy OSGi bundles via Tycho. 

## Build & Test via Maven Tycho

```shell
$ git clone https://github.com/groovyosgi/bundle.git   
$ cd bundles   
$ mvn clean install   
```

## Eclipse
* Import the bundle and its fragment via "File->Import->General->Existing Projects into Workspace".
* In order to execute the test from Eclipse, execute `GroovyActivatorTest.launch` via "Run As"