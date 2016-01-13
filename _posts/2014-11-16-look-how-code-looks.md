---
layout: post
title: Look how code is rendered
subtitle: lets try some code fragments to see how jekyll renders it
header-img: img/cascade2.jpg
---

Formatting Code
---------------

This is C# code

Code that is not highlited like a path

```c:\thisis a path```

{% highlight c# %}
/// <summary>
/// Initializes the singleton application object.  This is the first line of authored code
/// executed, and as such is the logical equivalent of main() or WinMain().
/// </summary>
public App()
{
    this.InitializeComponent();
    this.Suspending += this.OnSuspending;
}
{% endhighlight%}

{% highlight xml %}
<Application
    x:Class="App1.App"
    xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
    xmlns:local="using:App1">

</Application>

{% endhighlight%}
