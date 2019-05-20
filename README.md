# nexus-public

## mvn 引用方式

1. 在pom.xml中添加repository

```
<repositories>
	<repository>
        <id>maven-repo-public-releases</id>
        <url>https://raw.github.com/ensean/nexus-public/master/releases</url>
    </repository>
    <repository>
        <id>maven-repo-public-snapshots</id>
        <url>https://raw.github.com/ensean/nexus-public/master/snapshots</url>
    </repository>
</repositories>
```

2. 在`pom.xml`中添加对应的依赖

## gradle 引用方式

1. 在顶级`build.gradle`添加repository

```
maven { url 'https://raw.github.com/ensean/nexus-public/master/releases' }
maven { url 'https://raw.github.com/ensean/nexus-public/master/snapshots' }
```


2. 在build.gradle引入依赖

