# vinnsl-schema
Vienna Neural Network Specification Language (ViNNSL) 2.0 XML Schema Files

as specified in the Master Thesis "Vienna Neural Network Specification Language 2.0" by Dipl.-Ing. Thomas Kopica (University of Vienna)

Released on GitHub with permission of Dipl.-Ing. Thomas Kopica

## Usage
### XSD Schema
Download files from [src/main/resources/vinnsl/schema](src/main/resources/vinnsl/schema)
### XML Examples
Generates XML examples to schema files: [src/main/resources/vinnsl/generated_examples](src/main/resources/vinnsl/generated_examples)
### Compile to Java Classes with JAXB
- Make sure you have Maven installed

Checkout and run
``mvn compile``

### Add a Maven Dependency
Get precompiled schema classes as mvn dependency

#### Dependency
```
<dependency>
    <groupId>at.ac.univie.a00908270</groupId>
    <artifactId>vinnsl-schema</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

#### Repository
```
<snapshotRepository>
    <id>snapshots</id>
    <name>oss-jfrog-artifactory-snapshots</name>
    <url>https://oss.jfrog.org/artifactory/oss-snapshot-local</url>
</snapshotRepository>
```
