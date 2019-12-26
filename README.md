# spring-velocity-support

An support project of legacy velocity based on Spring Framework, it is a base project of 
[Alibaba velocity-spring-boot-project](https://github.com/alibaba/velocity-spring-boot-project), and most code is 
forked from Spring Framework official implementation.


## Released version

### Non-Web Application

````xml
<dependencies>

    ......

     <!-- Spring Framework -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-context-support</artifactId>
        <version>${spring.framework.version}</version>
    </dependency>

    <!-- Spring Context Velocity -->
    <dependency>
        <groupId>com.alibaba.spring</groupId>
        <artifactId>spring-context-velocity</artifactId>
        <version>1.4.3.25.RELEASE</version>
    </dependency>

    ......

</dependencies>
````

### Web Application

````xml
<dependencies>

    ......

     <!-- Spring Web MVC -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-webmvc</artifactId>
        <version>${spring.framework.version}</version>
    </dependency>

    <!-- Spring WebMVC Velocity -->
    <dependency>
        <groupId>com.alibaba.spring</groupId>
        <artifactId>spring-webmvc-velocity</artifactId>
        <version>1.4.3.25.RELEASE</version>
    </dependency>

    ......

</dependencies>
````

If your project failed to resolve the dependency, try to add the following repository:
```xml
    <repositories>
        <repository>
            <id>sonatype-nexus</id>
            <url>https://oss.sonatype.org/content/repositories/releases</url>
            <releases>
                <enabled>true</enabled>
            </releases>
        </repository>
    </repositories>
```




## Modules


### Forked Modules

| Modules                  | From `org.springframework`                                  |
| ------------------------------- | ----------------------------------------------------------- |
| [`spring-context-velocity`](spring-context-velocity) | `spring-context-support:4.3.25.RELEASE`                     |
| [`spring-webmvc-velocity`](spring-webmvc-velocity)   | `spring-webmvc:4.3.25.RELEASE`                              |