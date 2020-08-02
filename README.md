### Project Intro
- This project is the Spring basic configuration shared by all services of the Ecommerce system, including:

|Function|Directory|
| --- | --- |
|Spring Boot project basic configuration|`src/main/java/com/ecommerce/spring/common`|
|General Exception Handling|`src/main/java/com/ecommerce/spring/common/exception`|
|Field event related|`src/main/java/com/ecommerce/spring/common/event`|


Ecommerce Project includes：

|Repo|Purpose|Link|
| --- | --- | --- |
|ecommerce-order-service|Order service|[https://github.com/e-commerce-mock/ecommerce-order-service](https://github.com/e-commerce-mock/ecommerce-order-service)|
|ecommerce-order-query-service|Order query service|[https://github.com/e-commerce-mock/ecommerce-order-query-service](https://github.com/e-commerce-mock/ecommerce-order-query-service)|
|ecommerce-product-service|Product service|[https://github.com/e-commerce-mock/ecommerce-product-service](https://github.com/e-commerce-mock/ecommerce-product-service)|
|ecommerce-inventory-service|Inventory service|[https://github.com/e-commerce-mock/ecommerce-inventory-service](https://github.com/e-commerce-mock/ecommerce-inventory-service)|
|ecommerce-shared-model|Pure Shared model without Spring context|[https://github.com/e-commerce-mock/ecommerce-shared-model](https://github.com/e-commerce-mock/ecommerce-shared-model)|
|ecommerce-spring-common|Shared basic Spring configuration|[https://github.com/e-commerce-mock/ecommerce-spring-common](https://github.com/e-commerce-mock/ecommerce-spring-common)|
|ecommerce-devops|Infrastructure|[https://github.com/e-commerce-mock/ecommerce-devops](https://github.com/e-commerce-mock/ecommerce-devops)|

# Tech stacks
Spring Boot、Gradle、MySQL、Junit 5、Rest Assured、Docker、RabbitMQ/Kafka


### Command line:

|Command|Use|
| --- | --- |
|`./idea.sh`|Generate IntelliJ project file|
|`./local-build.sh`|build the project in local|
|`./publish.sh`|Publish to the mymavenrepo.com warehouse, you need to modify the `version` variable in the `gradle.properties` file when publishing a new version|

- This project uses `mymavenrepo.com` as the maven release repository:[Website address](https://mymavenrepo.com/app/repos/F0lRvilYH123TUeMr5GN/)
- URL used when publishing: https://mymavenrepo.com/repo/Cd07WrKAtJ9Kq7PBaTuf/
- URL used for dependency: https://mymavenrepo.com/repo/2w5k9sU2AsKfaYehyqno/
