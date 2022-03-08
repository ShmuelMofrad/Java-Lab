# My first web application

## How to create?

Windows PowerShell

```
$ mvn archetype:generate "-DgroupId=org.example" "-DartifactId=my-first-web-application" "-DarchetypeArtifactId=maven-archetype-webapp" "-DinteractiveMode=false"
```

Linux

```
$ mvn archetype:generate -DgroupId=org.example -DartifactId=my-first-web-application -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
```

## How to build?

```
$ mvn clean package
```

### read more:

[maven lifecycle](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)

