---
layout: post
title: "Mathematical Annotation in R"
author: [rcore, yihui, yulijia]
categories: [Base Graphics]
tags: [mathematical annotation, Greek letters]
reviewer: []
---
{% include JB/setup %}

Want to write mathematical symbols and expressions in R graphics? You can use an R `expression()`
instead of normal text, e.g. `plot(1:10, main = expression(alpha + beta))`. Below is a demo that
shows you everything about plotting math in R:


{% highlight r %}
demo(plotmath)
{% endhighlight %}



![plot of chunk plotmath](http://isu.r-forge.r-project.org/vistat/2013-04-08-mathematical-annotation-in-r/plotmath1.png) ![plot of chunk plotmath](http://isu.r-forge.r-project.org/vistat/2013-04-08-mathematical-annotation-in-r/plotmath2.png) ![plot of chunk plotmath](http://isu.r-forge.r-project.org/vistat/2013-04-08-mathematical-annotation-in-r/plotmath3.png) ![plot of chunk plotmath](http://isu.r-forge.r-project.org/vistat/2013-04-08-mathematical-annotation-in-r/plotmath4.png) ![plot of chunk plotmath](http://isu.r-forge.r-project.org/vistat/2013-04-08-mathematical-annotation-in-r/plotmath5.png) 

