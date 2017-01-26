---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
---

There is 6 ways you can create an Object.

1. Object Constructor

2. Literal constructor

3. Function Based

4. Protoype Based

5. Function and Prototype Based

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


<u>Factory Functions:</u>

    var Emp = { 
    // Your private code here
      return {
     // your public code here
     } 
    }

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
\#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

======================

{% highlight js %}
var Emp = require("./Employee");\
var emp1 = Emp.getInstance();\
var emp2 = Emp.getInstance();\
console.log(emp1.getNum());\
console.log(emp2.getNum());
{% endhighlight %}

=======================

{% highlight java %}
String st = new String("test");

System.out.println(st);
{% endhighlight %}