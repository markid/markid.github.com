---
layout: post
title: R和Markdown写作
categories:
- 技术
tags:
- R
- Markdown

---
# 写作
## 1.Markdown测试
Markdown的目标是实现** 易读易写 **。

**兼容Html**

对于Markdown不提供的标签可以直接用html的标签来写。在html区块标签内的Markdown语法是无效的，但在行内标签间是有效地。

## 标题
> # 标题一
> ## 标题二
> ### 标题三

*区块引用*
> 这是一个区块。
可以只在整个段落第一行加\> 号。

> 这是第二段。

区块引用嵌套，使用不同数量的>就行。
> 第一层
>
>> 第二层
>
> 返回第一层

## 列表
无序列表，使用星号，加号或是减号。
> *green
> +red
> -blue

有序列表使用数字加英文句号：
> 1. 蛇
2. 年
2. 大
4. 吉

列表项目的多个段落，段落需要缩进。

## 代码区块
    简单缩进4个空格或是一个TAB。
## 分割线
三个以上的星号、减号、底线来建立一个分割线。
----------
## 链接
[百度首页](http://www.baidu.com/)。
参考式链接
[google][google]。
[google]:  https://www.google.com.hk/ "google"
## 强调
_强调_ 
**加粗**
## 代码
行内代码，可以用反引号`，例如：
> use the `printf()` function.

## 图片
![baidu首页](http://www.baidu.com/img/shouye_b5486898c692066bd2cbaeda86d74448.gif)


## 2.R语言测试
### 画出自带数据集cars 
{% highlight r %}
plot(cars)
{% endhighlight %}
![cars](/picture/cars.png)
### The Normal Distribution
{% highlight r %}
output <- rnorm(1000, 100, 15)
library(ggplot2)
ggplot2::qplot(output)
{% endhighlight %}
![norm distribution](/picture/norm.png)