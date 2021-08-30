# Collar Maven repository

## Gradle

```
repositories {
    maven {
        name = 'Collar'
        url = 'https://raw.githubusercontent.com/collarmc/maven/main/'
    }
}
```

## Maven

```
<repositories>
    <repository>
        <id>collar</id>
        <url>https://raw.githubusercontent.com/collarmc/maven/main/</url>
        <snapshots>
            <enabled>false</enabled>
        </snapshots>
    </repository>
</repositories>
```
