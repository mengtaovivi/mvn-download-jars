# mvn-download-jars
A normal maven pom.xml which contains dependencies you need to download.  
一个包含需要下载的依赖包信息的pom.xml文件。  

By running maven command "mvn dependency:copy-dependencies",the jars defined in pom.xml by maven and download from remote repository to "target" directory.  
运行“mvn dependency:copy-dependencies”就可以将pom.xml中定义的jar文件下载到target目录中。
