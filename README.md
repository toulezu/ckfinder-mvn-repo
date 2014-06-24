CKFinder maven repository
=================

###1, add repository to pom.xml

```xml
<repositories>
	 <repository>
		<id>ckfinder-mvn-repo-on-github</id>
		<url>https://raw.github.com/buzheng/ckfinder-mvn-repo/master/</url>
	</repository>
</repositories>
```

###2, add dependency to pom.xml

```xml
<dependency>
	<groupId>com.ckfinder</groupId>
	<artifactId>CKFinder</artifactId>
	<version>2.4.1</version>
</dependency>
<dependency>
	<groupId>com.ckfinder</groupId>
	<artifactId>CKFinderPlugin-Watermark</artifactId>
	<version>2.4.1</version>
</dependency>
<dependency>
	<groupId>com.ckfinder</groupId>
	<artifactId>CKFinderPlugin-ImageResize</artifactId>
	<version>2.4.1</version>
</dependency>
<dependency>
	<groupId>com.ckfinder</groupId>
	<artifactId>CKFinderPlugin-FileEditor</artifactId>
	<version>2.4.1</version>
</dependency>
```

###3, There are some jars that it maybe depend.
activation-1.1.jar, commons-fileupload-1.2.2.jar, commons-io-2.0.1.jar, jboss-logging-3.0.0.CR1.jar, jboss-vfs-3.1.0.Final.jar, mail-1.4.1.jar, thumbnailator-0.4.5.jar.

such as the following:
```xml
<dependency>
	<groupId>com.ckeditor</groupId>
	<artifactId>ckeditor-java-core</artifactId>
	<version>3.5.3</version>
</dependency>
<dependency>
	<groupId>commons-fileupload</groupId>
	<artifactId>commons-fileupload</artifactId>
	<version>1.3.1</version>
</dependency>
<dependency>
	<groupId>javax.mail</groupId>
	<artifactId>mail</artifactId>
	<version>1.4.7</version>
</dependency>
<dependency>
	<groupId>net.coobird</groupId>
	<artifactId>thumbnailator</artifactId>
	<version>0.4.7</version>
</dependency>
<dependency>
	<groupId>org.jboss</groupId>
	<artifactId>jboss-vfs</artifactId>
	<version>3.2.2.Final</version>
</dependency>
```
