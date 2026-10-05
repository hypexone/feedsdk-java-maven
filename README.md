# feedsdk-java-maven

Public Maven repository for the Hypexone Java feed SDK, served by GitHub Pages at
https://hypexone.github.io/feedsdk-java-maven. Contents are published automatically
by the `publish.yml` workflow in [hypexone/feedsdk-java](https://github.com/hypexone/feedsdk-java);
do not edit by hand. No credentials are needed to download.

```xml
<repositories>
    <repository>
        <id>hypexone</id>
        <url>https://hypexone.github.io/feedsdk-java-maven</url>
        <snapshots><enabled>true</enabled></snapshots>
    </repository>
</repositories>

<dependency>
    <groupId>com.hypexone.feed.sdk</groupId>
    <artifactId>feed-sdk</artifactId>
    <version>3.3.0-SNAPSHOT</version>
</dependency>
```
