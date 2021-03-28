# Api Gateway
Api gate way uses spring-boot-api-gateway. It gives an easy interface to talk with different microservices. 

![Desing Overview](https://raw.githubusercontent.com/khabib97/spring-cloud-microservice-interaction/master/overview.png)

This is a submodule. For better underesting visit main project repo:

https://github.com/khabib97/spring-cloud-microservice-interaction

We can call Currency Exchange Service and Currency Conversion Service through API gateway:
```
http://localhost:8765/currency-exchange/from/EUR/to/BDT
http://localhost:8765/currency-conversion-feign/from/USD/to/BDT/quantity/10
```
Here we can convert modify our uri, implement authentication...

- Clone api-gateway
- Import as maven porject
- And run as java application
