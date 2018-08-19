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

### 接著定幾個class繼承上述的介面: ###


```csharp
{% highlight scss linenos %}
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
{% endhighlight %}
```

{% highlight scss linenos %}
~~~csharp
class FastCar : ICar
{
    public void Run()
    {
        Console.WriteLine("Run fast");
    }
}
~~~
{% endhighlight %}