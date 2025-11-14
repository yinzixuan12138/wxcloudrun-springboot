# Dictionary Backend

这是一个基于Spring Boot的词典应用后端项目。

## 项目结构

```
dictionary-backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.dictionary/
│   │   │       ├── controller/
│   │   │       │   └── HelloController.java
│   │   │       └── Application.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
└── pom.xml
```

## 环境要求

- Java 17 或更高版本
- Maven 3.6 或更高版本

## 如何运行

1. 使用Maven构建项目：
   ```
   mvn clean package
   ```

2. 运行应用程序：
   ```
   mvn spring-boot:run
   ```

   或者
   
   ```
   java -jar target/dictionary-backend-0.0.1-SNAPSHOT.jar
   ```

3. 访问测试端点：
   ```
   http://localhost:8080/hello
   ```

## API端点

- `GET /hello` - 返回欢迎信息