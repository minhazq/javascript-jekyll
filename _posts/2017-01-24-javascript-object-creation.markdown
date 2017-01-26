---
title: Javascript Object Creation
date: 2017-01-24 16:19:00 -05:00
---

There is 3 ways you can create an Object.
<p>Literal Form</p> :

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