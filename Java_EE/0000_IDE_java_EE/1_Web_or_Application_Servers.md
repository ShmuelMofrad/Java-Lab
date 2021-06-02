# Web and Application Servers

## What is Web- Application Server

An application server is a server that hosts applications.
Java Platform, Enterprise Edition or Java EE (was J2EE) defines the core set of API and features of Java Application Servers.

The Java EE infrastructure is partitioned into logical containers.

EJB container: Enterprise JavaBeans (EJB) are used to manage transactions. According to the J2EE blueprints, the business logic of an application resides in Enterprise JavaBeans—a modular server component providing many features, including declarative transaction management, and improving application scalability.
Web container: The Web modules include servlets and JavaServer Pages (JSP).
JCA container (Java EE Connector Architecture)
JMS provider (Java Message Service)
Some Java Application Servers leave off many Java EE features like EJB and Java Message Service (JMS). Their focus is more on Java Servlets and JavaServer Pages.

There are many open source Java application servers that support Java EE.

Commercial Java application servers have been dominated by WebLogic Application Server by Oracle, WebSphere Application Server from IBM and the open source JBoss Enterprise Application Platform (JBoss EAP) by Red Hat.

A Java Server Page (JSP) executes in a web container. JSPs provide a way to create HTML pages by embedding references to the server logic within the page. HTML coders and Java programmers can work side by side by referencing each other's code from within their own.

The application servers mentioned above mainly serve web applications, and services via RMI, EJB, JMS and SOAP. Some application servers target networks other than web-based ones: Session Initiation Protocol servers, for instance, target telephony networks.

[Wikipedia](https://en.wikipedia.org/wiki/Application_server#Java_application_servers)

## What's the difference between application server and web server?

**Web Servers:**
  - Servlet
  - JSP
  - Expression Language
  - WebSocket
  - JTA
  - JASPIC

**Application Servers:**

  - Servlet
  - JSP
  - Expression Language
  - WebSocket
  - JTA
  - Batch
  - CDI
  - Bean Validation
  - EJB
  - JPA
  - JMS
  - JSON-P
  - JavaMail
  - JAX-RS
  - JAX-WS

## Which one??

Web Server:

  - [Tomcat](
https://tomcat.apache.org/)
  - [jetty](https://www.eclipse.org/jetty/)

Application Server:

  - [glassfish](https://javaee.github.io/glassfish/)
  - [wildfly](https://www.wildfly.org/)
  - [payara](https://www.payara.fish/)
  - [openliberty](https://openliberty.io/)
  - [IBM WebSphere Application Server](https://www.ibm.com/cloud/websphere-application-server)
  - [Oracle WebLogic Server](https://www.oracle.com/middleware/technologies/weblogic.html)
  - [Apache TomEE](https://tomee.apache.org/index.html)

others:

  -[netty](https://netty.io/)
  -[geronimo](http://geronimo.apache.org/)

** more read [List on Wikipedia](https://en.wikipedia.org/wiki/List_of_application_servers#Java)
