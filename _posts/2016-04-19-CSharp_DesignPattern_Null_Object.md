---
layout: post
title: "C# Null Object Design Pattern"
author: "Iverson Hong"
modified: 2016-04-18
tags: [C#, Design Pattern]
---

### 建立一個interface或abstract class ###

~~~csharp
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
~~~

### 1: ###

{% highlight cs linenos %}
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
{% endhighlight %}

### 2: ###

{% highlight csharp linenos %}
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
{% endhighlight %}

### 3: ###

{% highlight c# linenos %}
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
{% endhighlight %}