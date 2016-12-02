---
layout: post
title: Code Quiz 1
author: Michael Gattuso
---


This is one of my favorite code quiz questions.
Take a look at the following code and determine what is printed out to the screen.

What do you think? Share your [answer](https://docs.google.com/forms/d/e/1FAIpQLSewPAX85iipHbqUwiTUknVvfW3LWbX1bzX5ITPH1PmTJ3AL8Q/viewform)

```cs
void Main()
{
	var a1 = new MyClass<Int32>(1);
	var a2 = new MyClass<Int64>(2);
	var a3 = new MyClass<Int32>(3);
	var a4 = new MyClass<Int64>(4);
	
	Console.WriteLine(a1.ListContents());
}

public class MyClass<T>
{
	private static List<object> _list = new List<object>();
	
	public MyClass(object value)
	{
		_list.Add(value);
	}

	public string ListContents()
	{
		return string.Concat(_list);
	}
}
```