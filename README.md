# quick4j

#### how to use **quick4j**：

> * the product is based on Spring + Spring MVC + Mybatis
> * using mybatis-generator to genenate the layer of dao、model、mapper to save time and energy
> * support the page query in Mysql postgresql and sql server 
> * using Apache Shiro for security
> * a lot of examples 


------

## How to get/use it
> * 1、git clone https://github.com/starzou/quick4j
* 2、import quick4j/src/test/resources/quick4j.sql  in mysql
(this version it can run  directly)
* 3、update JDBC Global Setting in  quick4j/src/main/resources/application.properties  
* 4、cd quick4j
* 5、mvn war:war 
* 6、deploy  quick4j/target/quick4j.war in tomcat or jboss

## how to run in the developing tools
> #### 1 、for IntelliJ IDEA
* File -> Import Project -> select quick4j folder -> create project form existing sources -> ...

> #### 2、 for Eclipse
* File -> Import -> Existing Maven Projects -> ...


## If you have a better suggestion,Please share out,Let's do better.

------
quick4j version 1 is developped by starzhou 
and this version is modified and optimized by Alex 
