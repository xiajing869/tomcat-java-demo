> ### SQL文件: db/tables_ly_tomcat.sql
> ### 数据库配置：src/main/resources/application.yml
> ### 对应
[root@k8s-master classes]# more  application.yml 
server:
  port: 8080
spring:
  datasource:
    url: jdbc:mysql://192.168.139.1:3306/test?characterEncoding=utf-8
    username: root
    password: xiajing367300
