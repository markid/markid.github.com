---
layout: post
title: R和Markdown测试
categories:
- 技术
tags:
- R
- Markdown

---
# Markdown测试 #

This is an R Markdown document. Markdown is a simple formatting syntax for authoring web pages (click the **MD** toolbar button for help on Markdown).

When you click the **Knit HTML** button a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

R语言加亮测试
================
## 画出自带数据集cars 
{% highlight r %}
summary(cars)

plot(cars)
{% endhighlight %}
![cars](/picture/cars.png)