mvn archetype:generate -DgroupId=com.vivekbhat.dockerapp -DartifactId=dockerapp -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

```	
mvn archetype:generate 
-DgroupId=com.vivekbhat.dockerapp 
-DartifactId=dockerapp 
-DarchetypeArtifactId=maven-archetype-quickstart 
-DinteractiveMode=false

```	
		
We get a pom.xml:
	
```<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.vivekbhat.dockerapp</groupId>
  <artifactId>dockerapp</artifactId>
  <packaging>jar</packaging>
  <version>1.0-SNAPSHOT</version>
  <name>dockerapp</name>
  <url>http://maven.apache.org</url>
  <dependencies>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>3.8.1</version>
      <scope>test</scope>
    </dependency>
  </dependencies>
</project>
```