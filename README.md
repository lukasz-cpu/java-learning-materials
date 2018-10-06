## Welcome!

I created this list to gather all valuable materials to learn Java, frameworks (Spring, Hibernate) and a basics of Computer Science/Programming. Purpose of creating this was that nowadays many people ask that question, and don't know what choose, what they needs to know, what about bootcamps, what is needed on the market etc. When i had been starting to learn - i was forced to search everything by myself - and confront many contrary opinions so I've spent more time choosing knowledge source than learning. This list is a helping hand to everyone who wants to learn everything what is needed to create full backend server with Java. 
This is not a tutorial, there is no technical knowledge included - only collection of materials. I've gathered this materials from my experience, and community recommendations. 

### First steps

I assume that you are new to programming - and you know no programming language. If you are familiar with basics and you want to teach yourself only Java - proceed to the next points.

So - at first you should *understand* what is programming at all, and learn basics of CS. 
To do this a [Harvard CS50 course](https://online-learning.harvard.edu/course/cs50-introduction-computer-science) will be perfect. Its only ~14h, so you can do this in one weekend. 
Next - you should get basic knowledge of algorithms - so [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms) will be fine. It's only very basic knowledge, for very beginners but shows most important algorithms & data structures. 


### Java 

Learning basic of Java you should start with: 

[C. Horstmann - Core Java - Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-1-11th/dp/0135166306) - It's good book for begginers, clearly explains what java is, OOP paradigm, and all core java mechanisms. One con that I see is: there is no exercises to do. 

[C. Horstmann - Core Java - Advenced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-11th/dp/0135166314) - this is continuation Java Fundamentals. It's broaching more complex problems - like JDBC, XML parsing etc. 

[C. Martin - Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) - called a "programmer bible", it's quite old but actual. I strongly recommend this book - it shows good practises and moreover examples are writen in Java. So double gainings.

[Joshua Bloch - Effective Java](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997) - to read this book, you should have good knowledge of Java. It's collection of good practises and popular mistakes explain.

[V. Sumbramaniam - Functional Programming in Java](https://www.amazon.com/Functional-Programming-Java-Harnessing-Expressions/dp/1937785467) - Java 8 added possibility of Functional programming. This book is short - but quite well explains lambdas & streams. Functional programming is different from imperative programming wchich you know - and you should know it.

But most important - and most valuable - is of course Java documentation. Sooner or later you will have to read documentations of projects, APIs etc. so start as soon as possible be familiar with it. Jaca doc could be found on oracle website, just choose wchich version do you need. 

Also remember that Google is your best friend. Probability of that someone asked beginner question that you have trouble with, is getting to 1. So probably every problem you have - is already solved on [StackOverflow](https://stackoverflow.com/)

Remember about practical side - to learn writing you have to write a lot. When you read book - try to use what have you learned in programs. Write as much as you can. Don't read only. For practising try to solve exercises from [r/dailyprogrammer](https://www.reddit.com/r/dailyprogrammer/) and [codewars](https://www.codewars.com/). 

## Additional tools
Those tools are needed in Java programming. They are quite easy and you should not have troubles getting into it, but you must be able to use it.

- [Maven](https://maven.apache.org/what-is-maven.html) - dependency management tool, but not only. Basic usage is very easy.

- [Gradle](https://gradle.org/) - another dependency management tool. It's working similiar to maven. I recommend that you should be familiar with both.

- [Git](https://git-scm.com/docs) - There is all you need to know about it. Like DMT is required too. [There is a simple cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf) that have all most important commands

- [Tomcat](http://tomcat.apache.org/) - tomcat is web container - it will be needed in developing webapps. Spring Boot makes that you don't have to know about tomcat, but if you will creating apps without Boot, only with WebMvc - will be required.

Another, not required but very usefull things:

- [Google Guava](https://www.tutorialspoint.com/guava/) - additional java library, simplified collections usage and more.
- [Project Lombok](https://www.baeldung.com/intro-to-project-lombok) - simplified Java entity class, will be helpful later
- [Joda-Time](https://www.joda.org/joda-time/) - very useful library, it's making time classes usable again. (eg. Date, LocalTime etc)

- [libGDX](https://github.com/libgdx/libgdx/wiki) - Java library allowing you to create multiplatform games. Rather oddity.

- [Postman](https://www.getpostman.com/) - application to checking your REST-app endpoints, will be useful later, with Spring MVC

## Algorithms

Algorithms are important part of programming. You don't need to could implement Djikstra algorithm - but you have to know that something like this exists and what it is.

- [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms) - basic book of algorithms, perfect if you only want to know basics. Examples and implementations are written in Python - so it may be problem for you. 
- [T. Cormen - Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) - algorithms bible, most recomended algorithm book. One thing - half of a book is about discrete math, so math knowledge is rather required. This book describes data structures also, so it's really good knowledge source.
-[R. Sedgewick - Algorithms](https://www.amazon.com/gp/product/032157351X/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=algs4-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=032157351X) - Another very good book. I recommend this book - because all examples are writen in Java. There is also ~200 pages about Java language - so it's perfect choice if you're learning Java.


## Hibernate

To create more useful applications - you will have to connect app with database. There is a 4 (later 5) topics that you have to know.
It's JDBC, ORM, JPA and Hibernate. Hibernate is Java framework whhich simplified database management. I assume you know something about JDBC (it's in Java Advenced Features by Horstmann). JPA is Java Persistence Application Programming Interface - and Hibernate is implementation of JPA specification. [More complex definition](http://tothought.com/post/2). ORM stands for [Object-relational mapping](https://en.wikipedia.org/wiki/Object-relational_mapping).

[Java Persistence with Hibernate](https://www.manning.com/books/java-persistence-with-hibernate) - nice guidebook touching ORM, JPA and Hibernate. It's required lecture. 

[Hibernate documentation](http://hibernate.org/orm/documentation/5.3/) - also required lecture - everyting about Hibernate. Also there is a good description of Hibernate Validator and Hibernate Search, what is very helpfull.

To work with databases you have to know at least one database and know SQL. [There is a nice tutorial about SQL](https://www.tutorialspoint.com/sql/sql-overview.htm). You can choose one of this databases:
- [h2 database](http://www.h2database.com/html/main.html) - smallest client, it's working in memory. 
- [mySQL](https://www.mysql.com/)
- [PostgreSQL](https://www.postgresql.org/)

## Spring Environment
Spring is second must-have Java framework. It focalized in webdevelopment.

- [C. Walls - Spring in Action](https://www.manning.com/books/spring-in-action-fifth-edition) - covers all spring core concepts, like IoC container, Dependency Injection, AOP etc. Very good to start learning Spring.

- [Official Documentation](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#spring-core) - best source - I recommend to read all, after finishing book.

- [C. Walls - Spring Boot in Action](https://www.manning.com/books/spring-boot-in-action) - explaining core concepts of Spring Boot project.

- [Spring WebMvc](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#spring-web) - everything you need to create webapps. 

- [Spring Rest](https://www.goodreads.com/book/show/25790509-spring-rest) - this book focalize in REST architecture style. There is more about HTTP request, JSON format etc.










