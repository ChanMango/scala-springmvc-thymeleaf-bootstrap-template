scala-springmvc-thymeleaf-bootstrap-template
============================================

A starter web application project combining Scala, Spring, Spring MVC, Thymeleaf 2.0, Spring Security and twitter bootstrap.

What is this?
=============
Spring MVC is a great web framework, however it needs to integrated with bunch of other libraries to make it really useful! 

In this sample project, I demonstrate using Scala with Spring MVC instead of Java. Additionally, I integrate with
Spring Security and templating with Thymeleaf.

Stack
=====
* Spring 3.2.0 RELEASE
* Spring MVC
* Spring Security 3.2.0 M1
* Spring Security Scala Extensions
* Jacks Jackson module - Handle's serialization of objects to JSON. The default Jackson based mapper does not handle scala case classes.
* Thymeleaf 2.0 + Layout Plugin - Excellent templating engine. I use the layout dialect  to use it for decorating as well.
* Bootstrap - Twitter's Bootstrap CSS
* Logback - for logging. Example showcases how to get Spring to use logback instead of Apache commons logging.
* Maven - For build and jetty integration


How to run
==========
Checkout project, and simply do a  mvn jetty:run and point your browser to http://localhost:8080/
