---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
Javascript Object Creaton: 
---

There is 3 ways you can create an Object.
Literal Form r:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight javascript%}
"use strict"

var Emp = require("./Employee");

var emp1 = Emp.getInstance();
var emp2 = Emp.getInstance();

console.log(emp1.getNum());
console.log(emp2.getNum());
{% endhighlight %}