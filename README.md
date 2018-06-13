# spring-velocity-support
An support project of legacy velocity based on Spring Framework


## Release version

````xml
<dependencies>

    ......

     <!-- Spring Framework -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-context-support</artifactId>
        <version>${spring.framework.version}</version>
    </dependency>

    <!-- Spring Context Extras -->
    <dependency>
        <groupId>com.alibaba.spring</groupId>
        <artifactId>spring-velocity-support</artifactId>
        <version>0.1.0</version>
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

| Forked modules                  | From `org.springframework`                                  |
| ------------------------------- | ----------------------------------------------------------- |
| `spring-context-velocity:0.1.0` | `spring-context-support:4.3.17.RELEASE`                     |
| `spring-webmvc-velocity:0.1.0`  | `spring-webmvc:4.3.17.RELEASE`                              |




## Document

TODO: Working in Process