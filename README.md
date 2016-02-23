How to run
=====

`gradle appRun`

Then visit: <http://localhost:8080/swagger-ui-demo/webjars/swagger-ui/2.1.4/?url=http://localhost:8080/swagger-ui-demo/api/swagger.json>.
 
Then click on the `Show/Hide` of the `default` api group, and you can even try to invoke it with custom parameters. 

Urls
====

There are actually 3 kinds of url to make the total:

1. API by `jersey`: <http://localhost:8080/swagger-ui-demo/api/hello/freewind>
2. swagger.json by `swagger-jersey2-jaxrs`: <http://localhost:8080/swagger-ui-demo/api/swagger.json>
3. Swagger-UI by `org.webjars:swagger-ui`: <http://localhost:8080/swagger-ui-demo/webjars/swagger-ui/2.1.4/>

Swagger-UI is actually a static web application using AJAX to provide all functionalities. But to make it easier in a Java application, we use the `webjar` version.

The swagger-ui has the default api url of <http://petstore.swagger.io/v2/swagger.json>, but we can pass our own url to it by appending `?url=my-url`.

References
====

https://github.com/swagger-api/swagger-core/wiki/Swagger-Core-Jersey-2.X-Project-Setup-1.5
