# ShadeMeBaby ``1.0.0``
Just a small library for my projects.

How to implement (Maven/Gradle)
---
Maven repository:
```
<repositories>
    <repository>
        <id>jitpack</id>
        <url>https://jitpack.io</url>
    </repository>
    <!--Other repositories...-->
</repositories>
```
Maven dependency:
```
<dependencies>
    <dependency>
        <groupId>com.github.danieldieeins</groupId>
        <artifactId>shademebaby</artifactId>
        <version>1.0.0</version>
        <scope>compile</scope>
    </dependency>
    <!--Other dependencies...-->
<dependencies>
```
---
Gradle repository:
```
repositories {
    maven { url 'https://jitpack.io' }
    //Other repositories...
}
```
Gradle dependency:
```
dependencies {
    implementation 'com.github.danieldieeins:shademebaby:1.0.0'
    //Other dependencies...
}
```