# blade last version

如果在maven仓库中下载不到最新版本的依赖，请添加maven snapshots仓库
```xml
<repositories>
 <repository>
   <id>oss-snapshots</id>
   <url>https://oss.sonatype.org/content/repositories/snapshots</url>
   <releases>
     <enabled>false</enabled>
   </releases>
   <snapshots>
     <enabled>true</enabled>
   </snapshots>
 </repository>
</repositories>
```
和`dependencies`相同级别


## [blade-kit](http://search.maven.org/#search%7Cga%7C1%7Cblade-kit)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-kit</artifactId>
    <version>1.2.8-alpha</version>
</dependency>
```

## [blade-core](http://search.maven.org/#search%7Cga%7C1%7Cblade-core)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-core</artifactId>
    <version>1.4.1</version>
</dependency>
```
## [blade-sql2o](http://search.maven.org/#search%7Cga%7C1%7Cblade-sql2o)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-sql2o</artifactId>
    <version>1.2.9</version>
</dependency>
```

## [blade-cache](http://search.maven.org/#search%7Cga%7C1%7Cblade-cache)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-cache</artifactId>
    <version>1.2.3</version>
</dependency>
```

## [blade-redis](http://search.maven.org/#search%7Cga%7C1%7Cblade-redis)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-redis</artifactId>
    <version>1.2.3</version>
</dependency>
```

## [blade-startup](http://search.maven.org/#search%7Cga%7C1%7Cblade-startup)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-startup</artifactId>
    <version>1.0.1</version>
</dependency>
```

## [blade-sample](http://search.maven.org/#search%7Cga%7C1%7Cblade-sample)
```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-sample</artifactId>
    <version>1.0.0</version>
</dependency>
```