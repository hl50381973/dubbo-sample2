安装zookeeper
安装mysql

修改配置文件
/edu-common-config/src/main/resources/jdbc.properties
ip指向安装的安装好mysql的ip地址

/edu-common-config/src/main/resources/service.properties
ip指向安装的安装好zookeeper的ip地址

依次maven clean install
edu-common-parent
edu-common
edu-common-config
edu-common-core
edu-common-web
edu-facade-user
edu-service-user

最后到edu-service-user的target目录下找到
lib包和edu-service-user.jar包

拷贝到c:\user目录下
java -jar edu-service-user.jar

