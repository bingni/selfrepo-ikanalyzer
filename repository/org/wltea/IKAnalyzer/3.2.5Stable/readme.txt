IKAnalyzer是一个开源的，基于java语言开发的轻量级的中文分词工具包。
IKAnalyzer的作者为林良益（linliangyi2007@gmail.com），项目网站为http://code.google.com/p/ik-analyzer/。


================================================

Maven工程由Bing Ni创建。创建的目的是为了方便用于其他Maven工程。你可以在 https://github.com/bingni/selfrepo-ikanalyzer/tree/master/repository 网站找到本工程。

Maven用法：

将以下依赖加入工程的pom.xml中的<repositories>...</repositories>部分。
	<repository>
        <id>selfrepo-ikanalyzer</id>
        <url>https://github.com/bingni/selfrepo-ikanalyzer/tree/master/repository</url>
    </repository>

将以下依赖加入工程的pom.xml中的<dependencies>...</dependencies>部分。
	<dependency>
		<groupId>org.wltea</groupId>
		<artifactId>IKAnalyzer</artifactId>
		<version>3.2.5Stable</version>
		<type>jar</type>
	</dependency>  
	
		