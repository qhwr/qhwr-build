# 前海微融Spring Cloud 构建

## 使用方式

引入仓库地址

```xml
<repositories>
    <repository>
        <id>Github Maven Build Repository</id>
        <url>https://raw.githubusercontent.com/qhwr/qhwr-build/dependencies</url>
    </repository>
</repositories>
```

导入依赖配置

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.qhwr.cloud</groupId>
            <artifactId>qhwr-cloud-dependencies</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```