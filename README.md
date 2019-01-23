# OCA&OCP Java SE 8 Study materials #
This project contains summarized notes and Java classes for studying the Oracle certification - **OCA and OCP Java SE 8**. 

**_Note:_** This materials are not 100% exhaustive and should not be used as main study materials 
but it can be good start point or support for your studying.

Great preparation is e.g. question bank provided by [Enthuware](https://enthuware.com/).

Also there are many Android applications with questions and mock tests. 
In my preparation I used the following:

**For OCA:**
* [Core Java 8](https://play.google.com/store/apps/details?id=com.eternal.soft.corejava8)

**For OCP:**
* [OCP - Java Test SE8 1Z0–809](https://play.google.com/store/apps/details?id=com.magycbytes.ocpjavatest)
* [Java Certification Practice Test (OCPJP or OCJP)](https://play.google.com/store/apps/details?id=shreeenavnath.software.com.java)
* [Java OCJP Preparation](https://play.google.com/store/apps/details?id=com.dooarsapp.ocjp)

## Introduction ##
The main points in project structure are:
* [`doc`](doc) directory - notes for each chapter summarized to one document
* [`src/main/java/cz/jjaros/study/oca`](src/main/java/cz/jjaros/study/oca) - examples for [Oracle Certified Associate](https://education.oracle.com/oracle-certified-associate-java-se-8-programmer/trackp_333)
* [`src/main/java/cz/jjaros/study/ocp`](src/main/java/cz/jjaros/study/ocp) - examples for [Oracle Certified Professional](https://education.oracle.com/oracle-certified-professional-java-se-8-programmer/trackp_357)
* [`src/main/java/cz/jjaros/study/helper`](src/main/java/cz/jjaros/study/helper) - helper classes for examples

Examples are structured to chapters. Each chapter is stored in separate package. 
Each package contains **README.md** file with notes of concrete chapter. 
It provides easy way how to show notes here on GitHub. 
If you want to get all notes at one place, you can read [`java_oca_cz_notes.odt`](doc/cz/java_oca_cz_notes.odt) 
or [`java_ocp_cz_notes.odt`](doc/cz/java_ocp_cz_notes.odt) (**beware:** both are currently only in czech). 

Java classes with examples contains a lot of comments. 
Is it good to use examples in Java classes with notes at GitHub or notes in [`java_oca_cz_notes.odt`](doc/cz/java_oca_cz_notes.odt) 
(resp. in [`java_ocp_cz_notes.odt`](doc/cz/java_ocp_cz_notes.odt)) together.

Each Java class with examples contain `main` method. Examples provides a lot of text printed to standard output. 
You can easy verify the behavior of code. 

### Prerequisites ###
You should have Oracle Java 8 SDK installed.

### Clone repository ###
```
git clone https://github.com/jjaros/lombok-example.git
```

## OCA chapters ##
1. [Basics](src/main/java/cz/jjaros/study/oca/ch01_basics) - Classes, Static classes, Inner classes, Anonymous classes
2. [Varargs](src/main/java/cz/jjaros/study/oca/ch02_varargs)
3. [Init blocks](src/main/java/cz/jjaros/study/oca/ch03_initblocks)
4. [Packages](src/main/java/cz/jjaros/study/oca/ch04_packages) - Packages and imports
5. [Constructors](src/main/java/cz/jjaros/study/oca/ch05_constructors)
6. [Labels](src/main/java/cz/jjaros/study/oca/ch06_labels)
7. [Comparators](src/main/java/cz/jjaros/study/oca/ch07_comparators)
8. [Variables](src/main/java/cz/jjaros/study/oca/ch08_variables) - Numeric, String or Arrays variables, Enums and operators
9. [DateTime API](src/main/java/cz/jjaros/study/oca/ch09_datetime) - Java 8 DateTime API
10. [Abstract](src/main/java/cz/jjaros/study/oca/ch10_abstract) - Abstract classes and methods
11. [Interface](src/main/java/cz/jjaros/study/oca/ch11_interface)
12. [Lambda expressions](src/main/java/cz/jjaros/study/oca/ch12_lambda) - Basics of Lambda expressions (_for more info see chapter about Lambdas and Streams in OCP_)
13. [Exceptions](src/main/java/cz/jjaros/study/oca/ch13_exception)

## OCP chapters ##
1. [Functional interfaces](src/main/java/cz/jjaros/study/ocp/ch01_functionalinterfaces) - lambda expressions, standard interfaces, `Bi*` interfaces
2. [Stream API](src/main/java/cz/jjaros/study/ocp/ch02_streams)
3. [Concurrency and Synchronization](src/main/java/cz/jjaros/study/ocp/ch03_synchronization) - deadlock, daemon, pool, fork-join, cyclic barrier, ...
4. [DateTime API](src/main/java/cz/jjaros/study/ocp/ch04_datetime)
5. [Assertions](src/main/java/cz/jjaros/study/ocp/ch05_assertions)
6. [Localization](src/main/java/cz/jjaros/study/ocp/ch06_localization)
7. [JDBC](src/main/java/cz/jjaros/study/ocp/ch07_jdbc)
8. [Files and I/O Fundamentals](src/main/java/cz/jjaros/study/ocp/ch08_files)
9. [Generics](src/main/java/cz/jjaros/study/ocp/ch09_generics)
10. [DTO and object mapping](src/main/java/cz/jjaros/study/ocp/ch10_objectmapping)

## Sources and references ##
* [www.tutorialspoint.com/java/java_exceptions](https://www.tutorialspoint.com/java/java_exceptions.htm)
* [www.tutorialspoint.com/java/java_innerclasses](https://www.tutorialspoint.com/java/java_innerclasses.htm)
* [docs.oracle.com/javase/tutorial/java/nutsandbolts/operators](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)
* [docs.oracle.com/javase/tutorial/java/data/autoboxing](https://docs.oracle.com/javase/tutorial/java/data/autoboxing.html)
* [docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
* [docs.oracle.com/javase/8/docs/technotes/guides/language/assert](https://docs.oracle.com/javase/8/docs/technotes/guides/language/assert.html)