---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
---

In javaScript you create an object from constructor. That means, you declare a constructor and create object out of that constructor.  If you declare functions or variable then those are also part of that constructor. Every time you create an object those methods and variable will also be created.  To separate methods and variable from the constructor there is a concept called  ```Prototype```. See Prototype section for details. Before you understand creating an Object first understand about Closure. 
<p><u>Closure:</u></p>
Whenever you see 

```java
{
// .....
}
```

is called closure. You have to define your constructor between those two curly braces. So when you create an Object whatever you put between those two curly braces is called constructor. The following is an example of creating a Object. 

```java
    var employee = {
    // here is your constructor definition ...
    }
```


There is 6 ways you can create an Object.

1. Object Constructor

2. Literal constructor

3. Function Based

4. Object.create Based

5. Singleton Based

<u>Object Constructor:</u>
Object is created and then adding methods. Notice that i did not declare any constructor, i mean there is no curly braces. Then how come the object created? Object created using the Super class definition. Whenever you use ```new``` operator And you did not define anything then Object automatically created using Super Object definition. ```toString()``` and ```value()``` and many more method is available  in the following employee Object.

```java
    var employee = new Employee();
    employee.name = "Richard"
    employee.sayHi = function(){
    console.log("say hi");
    }
```

<u>Literal constructor:</u>
You define your constructor in curly braces and at the same time you assigned the instance into a variable. You did not have to use ```new``` operator. This is very shortcut and easy way to create an Object but the problem arise when you want to do some **inheritance** or trying to make **singleton** object. 

```java
    var employee = {
    // Your code here ...
    }
```

<u>Function Based:</u>
In this approach you define function to create an Object with a name **not with variable**. In this case you **must** use ```new``` operator to create/instantiate the object. I like this approach because it is very similar to Java Class. 

```java
    function Employee(){
    // your code here
    }
```

<u>Object.create Based</u>
You will create an Object sending Parent Object reference. This approach is also helpful creating inheritance. The following example: employee Object created from Human Object.

```java
    var employee = Object.create(Human);
```

This is the best way to create object from a super Object. Look in Inheritance section for more details.
