# spring-cloud
# 提供spring-cloud 学习简单例子
# 环境及工具

1.Jdk 1.8

2.Maven 3+

3.Spring boot 2.0+

4.Intellij Idea

Maven的setting文件中的镜像最好是配为外国的，不然依赖包下载不下来
```
	 <mirror>
	  <id>ui</id>
	  <mirrorOf>central</mirrorOf>
	  <name>Human Readable Name for this Mirror.</name>
	 <url>http://uk.maven.org/maven2/</url>
	</mirror>

	<mirror>
	  <id>sprintio</id>
	  <mirrorOf>central</mirrorOf>
	  <name>Human Readable Name for this Mirror.</name>
	 <url>https://repo.spring.io/libs-snapshot/</url>
	</mirror>

```

