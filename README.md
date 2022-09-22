# SpringBoot

Java Spring Boot App using: spring-boot-starter-data-jpa, spring-boot-starter-web, spring-boot-devtools and spring-boot-starter-test.

To run this project better use the newest version of IntelliJ IDEA, Postman, JDK 1.8_x, Tomcat 9.0.x and newest version of MySQL Workbench.

Also you need to download and run this ([settings.txt](https://github.com/noleynik29/SpringMVC-AOP/files/9559543/settings.txt)) sql code to create database, that will be used in app.

If you've got any problems caused by this upgration, better look up the documents in Spring Framework Reference.

It's server application so you can only send requests using Postman, to see all employees(get), employee by id(get), change employee info(put) or remove employee (delete).

Firstly, when you start this application with Tomcat, you will see this list of employees:

![1](https://user-images.githubusercontent.com/71104368/191561953-84d6a9ef-ddb0-45bd-8c8f-abe94ba307d9.png)

To see all the employees use Postman and GET method with link http://localhost:8080/com_spring_app_rest_mvc/api/employees

![get](https://user-images.githubusercontent.com/71104368/191562620-885d902e-b84c-4231-b2cc-0199f292c4c0.png)

To see single employee with specified id you need to add /(enter id) to previous link http://localhost:8080/com_spring_app_rest_mvc/api/employees

To add employee you need to use POST method and write information about your employee is JSON body:

![post](https://user-images.githubusercontent.com/71104368/191563172-205b21bd-cd25-477e-ad11-0a747eed9d95.png)

To change employee's information use PUT method and write changed info:

![put](https://user-images.githubusercontent.com/71104368/191563311-44fdd308-90ac-46fd-9be7-bcdfa883ba00.png)

To delete employee use DELETE method and same link with specified id http://localhost:8080/com_spring_app_rest_mvc/api/employees/(enter id)

![del](https://user-images.githubusercontent.com/71104368/191563597-a7f3f5b2-d09a-4ec5-b636-097cfb6e6427.png)
