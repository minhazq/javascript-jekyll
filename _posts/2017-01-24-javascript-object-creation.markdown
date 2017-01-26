---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
---

There is 6 ways you can create an Object.

1. Object Constructor

2. Literal constructor

3. Function Based

5. Object.create Based

6. Singleton Based

<u>Object Constructor:</u>
Object is created and then adding methods.

```java
var employee = new Employee();
employee.name = "Richard"
employee.sayHi = function(){
console.log("say hi");
}
```
<u>Literal constructor:</u>

```java
var employee = {
// Your code here ...
}
```

<u>Function Based:</u>

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
