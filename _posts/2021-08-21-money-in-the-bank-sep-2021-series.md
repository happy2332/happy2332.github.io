---
layout: post
title: Money in the bank Sep 2021 series
subtitle: Each post also has a subtitle
<!-- gh-repo: daattali/beautiful-jekyll -->
<!-- gh-badge: [star, fork, follow] -->
tags: [money-in-the-bank, sep2021]
comments: true
---


We inititated our Sep 2021 series on Friday, Aug 20, 2021 at around 11:08 AM. Banknifty was trading at around 35000, HDFCBANK at 1502, ICICIBANK at 678, and SBIN at 409.
So we sold 1 lot of 2-3% away OTM puts for three banks, and to hedge them, we bought 1 lot of near ATM Banknifty Put. Following shows the trades taken.
![mib_entry_aug_20_2021](figs/mib_entry_aug_20_2021.png)

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.