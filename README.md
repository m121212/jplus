# jplus
Fork of original jsoup library (https://github.com/jhy/jsoup) with additional request method handling "raw body".

For maven/gradle integration:

MAVEN: pom.xml
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
	  <url>https://jitpack.io</url>
	</repository>
</repositories>
<dependency>
  <groupId>com.github.m121212</groupId>
	<artifactId>jplus</artifactId>
	<version>-SNAPSHOT</version>
</dependency>
```

GRADLE

root build.gradle
```xml
allprojects {
	  repositories {
			maven { url "https://jitpack.io" }
	  }
}
```

app build.gradle
```xml
dependencies {
  compile 'com.github.m121212:jplus:-SNAPSHOT'
}
```
	
