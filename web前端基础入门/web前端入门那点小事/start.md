前端入门指引
=============
>欢迎大家阅读这个前端入门指引，撰写这个文档的目的很简单，希望能给网络留下一点东西，由于我的自身水平问题，所以写的可能不会太透彻，可能还会有错误。希望大家能够指出。


考虑到大部分的新成员在入学的时候是完全没有接触过web开发甚至没有接触过一点点的编程的，一下子可能跨度太大，所以我希望能够用一些简单易懂的语言去把一些东西解释到通俗易懂的地步。

这个是前端分支文档，应该有个主线文档，希望大家能先阅读主线文档，掌握一定的基础知识，对web开发有了一定的理解之后再来阅读。本身前端这个行业就是在一步一步的演变中剥离出来的岗位，单独的一个前端没有任何意义。

###准备
看这个文章之前，你得先了解了基础的前端开发的主要任务就是利用一些前端开发的编程语言，去实现需求所要实现的网页布局、样式还有用户交互和数据传输。

如果你还没有看过web开发入门指引的话，先去看一下。



###最终目的
掌握HTML、CSS基础知识，能够较为熟练地使用HTML、CSS编写页面
预算耗时：11天

###基础认识
HTML:全称是超文本传输语言，是一种用尖括号包含的标签语言，浏览器能够读懂这种语言，并且根据规范，把你写的html语言按照一定规则把你要呈现的内容在浏览器上排布出来，给用户阅读查看。

这也是最早的时候网页诞生的时候的最基础的需求----阅读文章

我们可以来看看html语言长啥样：

```html
<html></html>
```
没错，就是上面这奇葩的样子。在尖括号里面包着一个英文字符串，英文不一样代表的含义不一样，浏览器会根据不同的标签帮你把内容不一样的呈现出来。


#####html标签的组成
其实一个标签不仅仅是一个尖括号包含一个英文字符串，我们来看下具体的html标签是怎么组成的。


```html
<html 属性名="属性值"> <!--前面的是标签开始-->

	<!--这里是标签内容-->

</html><!--用标签前面加斜杠表示结束标签-->
```
我们可以看到，标签有开始和结束，在内部可以是放我们的内容的。

这里有个【属性名="属性值"】，这个叫做标签的属性，不同的标签有不同的属性，我们可以在开始的标签后面用空格分开不同的属性，不同的属性可以赋值给它改变他的属性，如果不填就是默认的属性。

属性分两种，标签的默认属性，和用户自定义属性。比方说下面这个标签

```html
<a href="http://www.baidu.com/" data-info="我要链接到百度">
去百度
</a>
```

a标签是超链接标签，href属性是a标签的自带属性，表示用户点击这个a标签之后会转跳到的网页网址，data-info是我们自己定义的属性，根据最新的html5自定义属性标准，自定义的标签要以data开头，这样更规范。在这里data-info不起任何作用，就是写着玩的。


html标签有很多，这里有个[标签列表](http://www.w3cschool.cn/index-54.html)，大家可以去用来查询。
我们可以在w3cschool上看到一些常见标签的用法和他们的属性。
文章为罗列出一系列我们平时开发重点的标签做简单的讲解，大部分的标签大家可以在手册上查到。部分标签是HTML5新定义的，可能存在浏览器兼容问题，使用的时候应该注意。


###html页面结构
刚才说了，一个html页面其实最早的时候是期望用来展示文章的。所以他规定了一个页面的基本结构

```html
<html>
    <head></head>
    <body></body>
</html>
```
从结构来看，很容易理解一个html被分成了2部分，head和body部分。

head里一般是用来存一些html配置信息的，还有设置html页面的title的，
body里才是我们要写内容的地方。


###常用标签列举
我列举下常用的各种标签，大家可以重点先熟悉这几个标签。
```html
html body head title meta link script

div

a

img

span

p

table tr td

h1 h2 h3 h4 h5 h6

strong em i

ul li

iframe
```
大家把这些标签的用法都熟悉了，就可以通过各种标签组合你们想要的页面了。
[标签列表文档](http://www.w3cschool.cn/index-54.html)




