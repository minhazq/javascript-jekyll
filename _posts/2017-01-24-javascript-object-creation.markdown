---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
---

In javaScript you create an object from constructor. That means, you declare a constructor and create object out of that constructor.  If you declare functions or variable then those are also part of the constructor. Every time you create an object those methods and variable will also be created like java constructor.  To separate methods and variable from the constructor there is a concept called Prototype exist. See Prototype section for details.

There is 6 ways you can create an Object.

1. Object Constructor

2. Literal constructor

3. Function Based

4. Object.create Based

5. Singleton Based

<u>Object Constructor:</u>
Object is created and then adding methods.

    var employee = new Employee();
    employee.name = "Richard"
    employee.sayHi = function(){
    console.log("say hi");
    }

<u>Literal constructor:</u>

    var employee = {
    // Your code here ...
    }

<u>Function Based:</u>

    function Employee(){
    // your code here
    }

<u>Object.create Based</u>
You will create an Object sending Parent Object reference. This approach is also helpful creating inheritance. The following example: employee Object created from Human Object.

    var employee = Object.create(Human);