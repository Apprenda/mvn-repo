Apprenda Maven Repository
========

# Introduction 
This is the Apprenda maven repository for binary artifacts. 


# Usage

* Adding the Apprenda repository to access Maven dependencies

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">

    ...
    <dependencies>
        <dependency>
            <groupId>com.apprenda.framework</groupId>
            <artifactId>guestapp-api</artifactId>
            <version>5.0.2-Release</version>
        </dependency>
    </dependencies>

   <!-- Referencing the Apprenda repo for released artifacts -->
   <repositories>
        <repository>
            <id>apprenda-public</id>
            <name>Apprenda Public</name>
            <url>https://raw.github.com/Apprenda/mvn-repo/releases</url>
        </repository>
    </repositories>
</project>
```

