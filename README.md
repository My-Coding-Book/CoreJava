# CoreJava

## Contents
| Content | Content | Content |
| ------- | ------- | ------- |
| [Introduction](#introduction) | [Inheritance](#inheritance) |  |
| [JDK and JRE and JVM](#jdk-and-jre-and-jvm) | [Polymerphism](#polymerphism) |
| [Datatypes](#datatypes) | [Abstraction](#abstraction) |
| [OOPs](#oops) | [Encapsulation](#encapsulation) |
| [Object](#object) | [Collection](#collection) |
| [Class](#class) | [Streaming](#streaming) |
| [Constructor](#constructor) | [Update of New Release](#Update-of-New-Release) |
| [Static keyword](#static-keyword) |[Interview Questions](#Interview-Questions) |
| [Final keyword](#final-keyword) |


## Introduction

* Java is a

  * high level
  
  * robust
  
  * simple
  
  * portable
  
  * secure
  
  * stable
  
  * Object Oriented programming language

* Java is not a pure object-oriented language, because it supports primitive data type.

  > Languages that support or have features which treat everything inside the program as an object, and doesn’t support primitive data type(like int, char, float, boolean)
  
* Java is platform-independent.

  > JRE makes java platform independent. Once your java source code is compiled to byte code/machine independent code, that byte code will run in all devices which has JRE installed.
  
* Java is same as C/C++, so it is easy to learn and write program.

  > Java does not support low-level programming functions like pointers.
  
* Java is all about classes and objects.

* Java is developed by James Ghosling, Patrick Naughton, Mike Sheridan at Sun Microsystem Inc.

* Java released its 1st working version in 1991, took 18 month to develop.

* Initially, they named it Oak, then renamed to Java as Oak was already registered for other organisation.

* Usage of Java

  * Desktop Applications
  * Web Applications
  * Mobile Operating System (ex. Android)
  * Embedded System (ex. Digital Electronics, Telecommunications, Computer Netotking, Satellite system)
  * Robotics and Games, etc (ex. manufacturing, assembling and packing, transport, surgery, weaponry, mass production of industrial goods)

* Types of Java Applications
 
  * Standalone Applications
    * Applications that are machine-specific, one can use them directly after installation in local machine.
    * Java developers use AWT, Swing, JavaFX to develop.
    * Examples are Media Players, Antivirus Softwares, System Settings, etc.
  
  * Web Applications
    * An application, that is installed and run in a powerful machine and can be accessed from remote machine by multiple users concurrently using a client application (browsers)
    * Developers around the world are using Servlets, Struts, JSP, Spring, Hibernate, etc.
    * Some realtime examples are Social media websites, -commerce websites, bank applications, etc.
    
  * Enterprise Applications
    * An application that improves productivity and efficiency of an organization.
    * Examples are billing systems, customer relationship management systems and supplier relationship management systems.
  
  * Mobile Application
  

## JDK and JRE and JVM

## Datatypes

* Data types defines the value type which a variable will hold.
* There are 2 categories of data types in java
  * Primitive types
  * Non-primitive types

#### Primitive types are
  * boolean
  * char
  * byte
  * short
  * int
  * long
  * float
  * double

#### Non-primitive types are
  1. **String**
  
   * String class is defined in java.lang package as below,

   ```java
   public final class String extends Object implements Serializable, Comparable<String>, CharSequence {
     // fields
     // constructors
     // methods
   }
   ```
  
   * Sequence of characters
  
   ```java
   String str0 = "India";

   char[] data = { 'I', 'n', 'd', 'i', 'a' };
   String str1 = new String(data);
   ```
   > In above example we have created 2 String objects and both are same.
   
   * Each string literals are one object/instance of String class.
   * Strings are constant, their values cannot be changed after they are created. String objects are immutable.
  
   **Methods in String class**
   
   **charAt(int index)**
   
    * Returns the character located at the specific index.
    * Indexing starts from 0-zero.

     ```java
     String str = "India";

     System.out.println(str.charAt(3)); // i
     ```

   **equalsIgnoreCase(String secondString)**
   
   * Compares the equality of two Strings, and ignores the case (upper or lower)
   * Returns a boolean value (true/false)
   
   ```java
     String str = "India";

     System.out.println(str.equalsIgnoreCase("India")); // true
   ```


  
  1. **Array**


## OOPs

## Object

## Class

## Constructor

## Static keyword

## Final keyword

## Encapsulation

## Inheritance

## Polymerphism

## Abstraction

## Collection

## Streaming

## Update of New Release

## Interview Questions

| # | Questions |
| - | --------- |
| 1 | [Why Java is not a purely Object-Oriented Language?](#Why-Java-is-not-a-purely-Object-Oriented-Language?) |


#### Why Java is not a purely Object-Oriented Language?
