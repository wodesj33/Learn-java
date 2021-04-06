### 常用的javaWeb服务器

1. Tomcat
2. Jboss
3. GlassFish
4. Resin
5. WebLogic

### 版本对应关系

[官网版本对应说明](http://tomcat.apache.org/whichversion.html)

企业常用版本 7.* 8.*

Servlet程序2.5版本是使用最多的版本（XML配置）

Servlet3.0之后,就是注解版本的Servlet使用。

| Tomcat  | Servlet/JSP | JavaEE | 运行环境 |
| ------- | ----------- | ------ | -------- |
| 4.1     | 2.3/1.2     | 1.3    | JDK1.3   |
| 5.0     | 2.4/2.0     | 1.4    | JDK1.4   |
| 5.5/6.0 | 2.5/2.1     | 5.0    | JDK5.0   |
| 7.0     | 3.0/2.2     | 6.0    | JDK6.0   |
| 8.0     | 3.1/2.3     | 7.0    | JDK7.0   |
| 10.0    |             |        |          |

#### 目录说明

bin 存放 服务器的可执行程序

conf 存放服务器的配置文件

lib 存放jar包

logs 运行时输出的日记信息

temp 运行时产生的临时数据

webapps 部署的Web工程

work 是Tomcat工作时的目录，用来存Tomcat 运行时JSP 翻译为