# spring-boot-restful-blank

[![jdk](https://img.shields.io/badge/jdk-8u181-green.svg)](https://www.oracle.com/technetwork/java/index.html)
[![spring-cloud](https://img.shields.io/badge/spring--cloud-Finchley.SR1-green.svg)](https://projects.spring.io/spring-cloud/)
[![spring-io](https://img.shields.io/badge/spring--io-Cairo--SR4-green.svg)](http://platform.spring.io/platform/)

App目录结构:
* parent
  - pom.xml
* server
  - src/main/java/${package}/server/
    - config
    - dao
    - entity
    - dto
    - service
    - openapi
    - utils
  - src/main/resource


Install：
maven环境

1.在项目根目录下运行：

```
mvn install
```
2.根据本地的archetype创建项目，选择pheiot-spring-boot-restful

```
mvn archetype:generate -DarchetypeCatalog=local
```

选择项目此模板一次输入相应信息即可。
