# spring-boot-starter-hornetq-cluster

![Build Status](https://travis-ci.org/Mercateo/spring-boot-starter-hornetq-cluster.svg)


Alternative to the original starter ``org.springframework.boot:spring-boot-starter-hornetq`` providing an easy way to connect to multiple Hornetq nodes, e. g. a fail-over setup.

### GAV

Not yet available on Maven Central.

```xml
<dependency>
    <groupId>com.mercateo</groupId>
    <artifactId>spring-boot-starter-hornetq-cluster</artifactId>
    <version>1.3.5.RELEASE</version>
</dependency>
```

### Configure

```
spring.hornetq.authorities=node1:port1,node2:port2,...
spring.hornetq.mode=native
# optional
spring.hornetq.user=
spring.hornetq.password=
```