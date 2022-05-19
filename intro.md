# Intro
 Introduction to Java programming
 
# Dev.java

 - java -version [openjdk version "17.0.2" 2022-01-18] Compiling and Executing
 - javac -version [javac 17.0.2] Compiling and Executing
 - which java, which javac, PowerShell Get-Command java, Get-Command javac
 - JAVA_HOME in path, PowerShell echo $ENV:JAVA_HOME echo $ENV:Path
 - MyFirstClass Creating a First Java Class
 - System.out.println Adding Code to Your Class to Run it
 - Launching Single-File Source-Code JDK 11 the 
 - MultipleClassesInSameFile
 - import class Reference JDK Classes

 + create hello world tomcat vscode (not released)


[dev.java](https://dev.java/)

[Java Releases](https://dev.java/download/releases/)

[JDK Issues](https://bugs.openjdk.java.net/secure/Dashboard.jspa)


===

# MyFirstClass.java

```java
public class MyFirstClass {
    public static void main(String[] args) {
        System.out.println("Hello, World!\nHello, java launcher!");
    }
}
```

# MultipleClassesInSameFile.java

```java
public class MultipleClassesInSameFile {
    public static void main(String[] args) {
        System.out.println(GenerateMessage.generateMessage());
        System.out.println(AnotherMessage.generateAnotherMessage());
    }
}

class GenerateMessage {
    static String generateMessage() {
        return "Hello, World!";
    }
}

class AnotherMessage {
    static String generateAnotherMessage() {
        return "Hello, java launcher!";
    }
}
```

# CreateJavaDevLink.java

```java
import java.io.IOException;
import java.nio.file.*;

public class CreateJavaDevLink {
    public static void main(String[] args) throws IOException {
        String content = "<a href=\"https://dev.java/\">Visit dev.java!</a>";
        Files.write(Paths.get("dev-java.html"), content.getBytes());
        System.out.println("the dev-java.html file has been created");
    }
}
```