# java-web-start
Java Web start

## run

    cd WEB-INF
    mkdir classes
    javac -d WEB-INF/classes -cp /usr/local/Cellar/tomcat/8.5.20/libexec/lib/servlet-api.jar @javaFiles.txt
    catalina run
