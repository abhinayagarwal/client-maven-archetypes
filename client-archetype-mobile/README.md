# Client Maven Archetype for simple Gluon Mobile application

The project is a Maven archetype for creating a simple [Gluon Mobile](https://gluonhq.com/products/mobile/) application
which uses the [Gluon Client](https://docs.gluonhq.com/client/) plugin to create a native application targeting desktop and mobile platforms.

### Prerequisites

* JDK 11
* Maven 3

### Create a project

You can create a new project, from the archetype, by executing the following command:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=client-archetype-mobile \
        -DarchetypeVersion=0.0.1 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version
```

The following properties can be customized while creating the project:

| Property                    | Default Value |
| --------------------------- | ------------- |
| javafx-version              | 13.0.1        |
| javafx-maven-plugin-version | 0.0.3         |
| client-maven-plugin-version | 0.1.3         |

For example:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=client-archetype-mobile \
        -DarchetypeVersion=0.0.1 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version \
        -Djavafx-version=12
```
