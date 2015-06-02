# Interview HQ
This is a simple web application built using Spring boot to hold a pool of interview questions within an organization with security enabled.



### Developer Notes

#### Using Spring-Loaded hot deployment
Use the maven target spring-boot:run to run the application with springloaded agent on your jvm, springloaded will hot deploy any classes which have changed in the target folder.

```
mvn spring-boot:run
```

> Kindly note that IDEA users will have to enable 'Make project automatically' in settings window to compile the project as and when the source is being changed. Eclipse users will not have to do any change wrt this.