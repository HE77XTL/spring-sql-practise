spring-sql-practise


### 测试方式：
1、确保数据库可以连接，配置正确的参数：
```
文件： resources/application.properties

spring.datasource.url= yourUrl  (example:jdbc:mysql://localhost:3306/crawlernews)
spring.datasource.username= yourUserName
spring.datasource.password=yourPassword
```


2、发送请求（官方文档用 curl， 自己本地装有postman 直接用就好， 要是自己起有前端项目且配好跨域代理， 也可以直接发请求测试）  

```
get: localhost:8080/demo/all
post: localhost:8080/demo/add (form-data)
```

