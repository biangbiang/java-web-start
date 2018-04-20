# java-web-start
Java Web start

## run

    cd WEB-INF
    mkdir classes
    javac -d WEB-INF/classes -cp /usr/local/Cellar/tomcat/8.5.20/libexec/lib/servlet-api.jar @javaFiles.txt // 编译
    jar cvf hello.war WEB-INF // 打包
    cp hello.war {tomcat/webapps} // 将war包放到tomcat的webapps目录下
    catalina run

## 访问

    http://localhost:8080/hello/HelloServlet（以实际配置为准）
