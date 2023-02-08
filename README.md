# maven-repository
Private Maven Repositories

## usage
pom.xml  
```xml
<repositories>
  <repository>
    <id>nctsc</id>
    <url>https://raw.github.com/nctsc/maven-repository/</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>cp.mvnrepo</groupId>
    <artifactId>testmvnrepo</artifactId>
    <version>1.0-SNAPSHOT</version>
  </dependency>
</dependencies>  
```


## package
```xml
<plugin>
  <artifactId>maven-deploy-plugin</artifactId>
  <version>2.8.1</version>
  <configuration>
    <altDeploymentRepository>internal.repo::default::file://${project.build.directory}/repository</altDeploymentRepository>
  </configuration>
</plugin>
```


