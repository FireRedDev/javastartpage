# Java Quickstart - Install, Develop and Use Java

[![Java Logo](https://allvectorlogo.com/img/2016/11/java-logo.png)]()

Java is a programming language and computing platform first released by Sun Microsystems in 1995. There are lots of applications and websites that will not work unless you have Java installed, and more are created every day. Java is fast, secure, and reliable. From laptops to datacenters, game consoles to scientific supercomputers, cell phones to the Internet, Java is everywhere!

Unlike Windows executables (.EXE files) or Macintosh applications (.APP files), Java programs are not run directly by the operating system. Instead, Java programs are interpreted by the Java Virtual Machine, or JVM, which runs on multiple platforms. This means all Java programs are multiplatform and can run on different platforms, including Macintosh, Windows, and Unix computers. Java is either run by .JAR Files, as a bundled JRE or can create native wrappers with GraalVM like .EXE and .APP for each operating system.

# Is Java free to download?

Yes, Java is free to download. Get the latest version at <https://java.com>. 
Modern Java Applications actually dont need you to have Java installed though, they bundle everything with the application you are using. 
---
# Try programming with Java

## In the Browser
<https://www.codiva.io/> Codiva is an online compiler and IDE for C, C++ and Java.

<https://www.jdoodle.com/online-java-compiler/>

# With developement software
## Visual Studio Code
![alt text](https://upload.wikimedia.org/wikipedia/commons/f/f3/Visual_Studio_Code_0.10.1_icon.png)


<https://code.visualstudio.com/docs/java/java-tutorial>
## Netbeans IDE
![alt text](https://dashboard.snapcraft.io/site_media/appmedia/2018/11/frame256.png "Logo Title Text 1")

Development Environment, Tooling Platform and Application Framework.

<https://netbeans.apache.org/>
## Eclipse IDE
![alt text](https://findicons.com/files/icons/2796/metro_uinvert_dock/128/eclipse.png "Logo Title Text 1")

<https://www.eclipse.org/ide/>
## Intellij IDE
![alt text](https://cdn.iconscout.com/icon/free/png-256/intellij-idea-569199.png "Logo Title Text 1")

<https://www.jetbrains.com/de-de/idea/download/>
---
# Write your first programm 

<https://www.learnjavaonline.org/en/Hello%2C_World%21>


## Hello, World!
Java is an object oriented language (OOP). Java objects are part of so-called "Java classes".

Let's go over the Hello world program, which simply prints "Hello, World!" to the screen.
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("This will be printed");
    }
}
```
The first line defines a class called Main.
```java
public class Main {
```
In Java, every line of code that can actually run needs to be inside a class. This line declares a class named Main, which is public, that means that any other class can access it. This is not important for now, so don't worry. For now, we'll just write our code in a class called Main, and talk about objects later on.

Notice that when we declare a public class, we must declare it inside a file with the same name (Main.java), otherwise we'll get an error when compiling.

When running the examples on the site, we will not use the public keyword, since we write all our code in one file.

The next line is:
```java
public static void main(String[] args) {
This is the entry point of our Java program. the main method has to have this exact signature in order to be able to run our program.
```
public again means that anyone can access it.
static means that you can run this method without creating an instance of Main.
void means that this method doesn't return any value.
main is the name of the method.
The arguments we get inside the method are the arguments that we will get when running the program with parameters. It's an array of strings. We will use it in our next lesson, so don't worry if you don't understand it all now.
```java
System.out.println("This will be printed");
```
System is a pre-defined class that Java provides us and it holds some useful methods and variables.
out is a static variable within System that represents the output of your program (stdout).
println is a method of out that can be used to print a line.

## Exercise
Print "Hello, World!" to the console.

## Learn More

<https://www.learnjavaonline.org/>
---
## Build Systems
### Maven
![alt text](https://alternative.me/media/256/apache-maven-icon-kh9tgmmob2lmuoko-c.png "Logo Title Text 1")

<https://maven.apache.org/>
Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

### Gradle
![alt text](https://cdn.iconscout.com/icon/free/png-256/gradle-1-285287.png "Logo Title Text 1")

Gradle is a build automation tool for multi-language software development. It controls the development process in the tasks of compilation and packaging to testing, deployment, and publishing.

The methodology of Gradle builds on the concepts of Apache Ant and Apache Maven, and introduces a Groovy-based domain-specific language, rather than using the XML form used by Maven for declaring the project configuration.[2] Gradle uses a directed acyclic graph to determine the order in which tasks can be run, through providing dependency management.
<https://gradle.org/>
---
## Famous Java Frameworks
### For everything: Spring
![alt text](https://docs.spring.io/spring/docs/current/spring-framework-reference/pdf/favicon.ico "Spring Framework")

Project Site: <https://spring.io/>

Primary Sponsor: Pivotal Software

Spring is more than just a web framework. It is a complete programming model that is built on and with Java, starting with Spring Boot, which is a way to get a spring application up and running with minimal configuration and no application server required. At the other end of the spectrum is Spring Cloud, which is a combination of components that allows developers to build resilient and reliable cloud-native applications that leverage the latest distributed patterns like a microservices architecture — two examples include application security and batch processing.

There are many use cases for Spring, and with the introduction of Spring Boot, it is a great solution for companies that are moving towards containers as it greatly simplifies the components required to support the running application.

Getting started with Spring is as simple as going to Spring Initializr and selecting the build framework you desire and any and all the Spring projects you want included in the initial application. It will create the Maven or Gradle configuration and all the basic spring configuration required to start.

### Web: Play
Play is another lightweight framework that most developers enjoy. It allows you to build web applications with Java & Scala. It was designed for modern mobile and web applications’ needs.
Play is based on stateless, web-friendly, and lightweight architecture. The main distinguishing features include high speed, quality, and good scalability. It is built on Akka and gives agility to think in the more high-level way — not what to do with Data element, but how to handle a stream of things.
The framework has asynchronous APIs that allow you to scale applications without introducing additional resources. This framework provides excellent support for various microservice patterns.

### Web: Vaadin
<https://vaadin.com/>
Full stack framework for building web apps in Java
Vaadin is an open source web framework that helps Java developers build great user experiences with minimal effort. 

### JHipster
<https://www.jhipster.tech/>
JHipster provides tools to generate a project with a Java stack on the server side (using Spring Boot) and a responsive Web front-end on the client side (with Angular and Bootstrap). It can also create microservice stack with support for Netflix OSS, Docker and Kubernetes.

The term 'JHipster' comes from 'Java Hipster', as its initial goal was to use all the modern and 'hype' tools available at the time.[2] Today, it has reached a more enterprise goal, with a strong focus on developer productivity, tooling and quality.[3]

## Android Development
![alt text](https://lh3.googleusercontent.com/proxy/L-ZdL-NoMBYmXUuujCv4rwhm5pSc9i-XVSL_rp-a_OCsFjJYWodmzKC4gTdW9aeqKJ8_Le6uewGjQbe3jIWYm_I5jO0cj-juVs9cwBatETML0lO9FjgVVmUmc2Y6LIv56JrBcuAy26y2UNyHPg7ycGvJOZMdriT8 "Logo Title Text 1")
In the Android Developer Fundamentals course, you learn basic Android programming concepts and build a variety of apps, using the Java programming language. You start with Hello World and work your way up to apps that schedule jobs, update settings, and use Android Architecture Components.
<https://developer.android.com/courses/fundamentals-training/overview-v2>
## Client Desktop Developement
![alt text](https://img.icons8.com/cotton/2x/computer.png "Logo Title Text 1")
### Swing

<https://www.javatpoint.com/java-swing>

Java Swing tutorial is a part of Java Foundation Classes (JFC) that is used to create window-based applications. It is built on the top of AWT (Abstract Windowing Toolkit) API and entirely written in java.

Unlike AWT, Java Swing provides platform-independent and lightweight components.

The javax.swing package provides classes for java swing API such as JButton, JTextField, JTextArea, JRadioButton, JCheckbox, JMenu, JColorChooser etc.
### JavaFX

<https://openjfx.io/>

OpenJFX is an open source, next generation client application platform for desktop, mobile and embedded systems built on Java.
It is a collaborative effort by many individuals and companies with the goal of producing a modern, efficient, and fully featured toolkit for developing rich client applications.
## Other Java Backend frameworks
⋅⋅* Apache CFX 
⋅⋅* Jersey 
⋅⋅* RESTEasy
⋅⋅* Restlet
⋅⋅* Dropwizard
⋅⋅* Micronaut
⋅⋅* TomEE
⋅⋅* Quarkus
---
## Basic Java developer skills
While this isn’t a complete list, below is a look at some of the basic skills needed to become a Java developer:

JavaServer pages (JSP) and servlets

Web frameworks (e.g., Struts and Spring)

Service-oriented architecture/web services (SOAP/REST)

Web technologies like HTML, CSS, JavaScript, and JQuery

Markup languages like XML and JSON

Object-oriented programming (OOP) concepts and patterns

Abstract classes and interfaces

Constructors

File IO and serialization

Collections: lists, maps, sets

Access specifiers

Exceptions (checked and unchecked)

Generics

Java keywords: static, final, volatile, synchronized, transient, this super, etc.

Java virtual machine (JVM) and memory management

Multithreading and synchronization

Dependency injection

## Advanced skills for Java developers

Understanding Java doesn’t just mean knowing the language. Many other pieces are necessary to create, develop, and test code.



Here are a few advanced skills a top candidate for Java development jobs should possess:



AI and machine learning

Blockchain

Amazon Web Services

Hadoop/Big Data

Mobile technologies (Android or OS)

Advanced JavaScript framework (e.g., Angular, React, VueJS)

Spring Boot/microservices

### Repository of this webpage
This website is built via Github Pages and Markdown.
<https://github.com/FireRedDev/javastartpage/>

## Report a Java Bug
<https://bugreport.java.com/bugreport/

### Repository of OpenJDK
<https://github.com/openjdk/jdk>

## Disclaimer

This website is just a hobby project to give new java devs a starting point and to show how even a pretty lightweight java startpage would be better than no website at all. Java is a registered Trademark of Oracle. I do not own, work at, or develop any of the Software or technology mentioned. Accurracy is not garuanteed. 

>

