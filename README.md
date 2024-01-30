打包命令：
cd hellowh
mvn clean package -P test -DskipTests  
mvn clean package -P pro -DskipTests
mvn clean package -P pre -DskipTests

环境配置：
[root@node20 hellowh]# cat /etc/environment 
JAVA_HOME=/usr/local/jdk
PATH=${PATH}:${JAVA_HOME}/bin
MAVEN_HOME=/usr/local/maven3
PATH=${PATH}:${MAVEN_HOME}/bin
