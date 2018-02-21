# vinnsl-schema
Vienna Neural Network Specification Language (ViNNSL) 2.0 XML Schema Files

as specified in the Master Thesis "Vienna Neural Network Specification Language 2.0" by Dipl.-Ing. Thomas Kopica (University of Vienna)

Released on GitHub with permission of Dipl.-Ing. Thomas Kopica

# Usage
## Use in your Java Project
### Add a Maven Dependency
Add this maven dependency to your project's ``pom.xml`` and get precompiled schema classes, source files and javadoc

#### Maven Dependency
```
<dependency>
  <groupId>at.ac.univie.a00908270</groupId>
  <artifactId>vinnsl-schema</artifactId>
  <version>{vinnsl-schema.version}</version>
  <type>pom</type>
</dependency>
```

### Download Binary
Download the latest jar release from [/releases](../../releases)

### Compile to Java Classes with JAXB
- Make sure you have Maven installed

Checkout and run
``mvn compile``
and run
``mvn package``
to generate the jar file

## Schema Files
### XSD Schema
Download files from [src/main/resources/vinnsl/schema](src/main/resources/vinnsl/schema)
### XML Examples
Generated XML examples to schema files: [src/main/resources/vinnsl/generated_examples](src/main/resources/vinnsl/generated_examples)

## Latest Version
 [ ![Download](https://api.bintray.com/packages/a00908270/a00908270/vinnsl-schema/images/download.svg) ](https://bintray.com/a00908270/a00908270/vinnsl-schema/_latestVersion)
