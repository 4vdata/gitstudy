#  markdown 学习之路
##  标题

#  标题1
##  标题2
###  标题3
####  标题4
#####  标题5
######  标题6
<!-- 以下这种不常用 -->
标题1:=
===
标题2:-
---

##  段落 两个空格或者一个换行就是一个段落

我是周周，我喜欢Github开源社区的技术和氛围。  
  我的QQ：670807479
	hello 

##  强调
我是*斜体*样式，我是**粗体**样式，我是***倾斜+斜体***样式.  
我是_斜体_样式，我是__粗体__样式，我是___倾斜+加粗___样式。  
我是~~删除线~~


##  列表
###  无序列表  
* name:zhangsan    
* QQ:123456 

####  等价写法：
- name:zhangsan  
	- name:lisi 
	 - List:三级列表
	 - ON:45464546
	- QQ:456789
- QQ"1213132123"  
###  有序列表
 1. Name:zhangsan  
   1. List:lisi
   2. QQ:4545465
   3. QQ:4545465
 2. QQ:213123123  
 4. PQ:213123123
 3. AQ:213123123


##  连接
###  内嵌式链接    
外部链接 ：[百度](https://baidu.com)   
内部链接1：链接仓库的其他文件[入门](rumen.md)
内部链接2：链接文件的其他部分[代码快](markdown.md#代码块)

###  引用式链接  
外部链接 ：[百度]  
外部链接 ：[baidu]  
内部链接1：链接仓库的其他文件[入门]
内部链接2：链接文件的其他部分[代码快]


##  图片
  
![alt](url text)  
示例：
插入网络图片
![avatar](https://www.baidu.com/img/bd_logo1.png "baidu")  

![avatar](https://www.baidu.com/img/bd_logo1.png)  
插入本地图片  
![avatar](/home/picture/1.png)

图片的引用链接  
![avatar][baidulogo]  

##  引用
>这是一段引文。这是一段引文。 这是一段引文。 这是一段引文。  

                                       --出字《周后珍》  
多次引用  
>>>这是多重引用  

                                       --出自（张三）


##  代码块

插入程序代码的方式有两种，一种是利用缩进(Tab), 另一种是利用 ` 符号（～键）包裹代码。  

插入行内代码，即插入一个单词或者一句代码的情况，使用 `code` 这样的形式插入。  
插入多行代码，用的最多的是，用六个 ` 包裹多行代码。当然也可以使用缩进或者“` code `”的形式。  
  
- 行内代码  

- 块式代码  
```php  
<?php 
echo "hello world!";
?>  
``` 












I get 10 times more traffic from [1] than from [Yahoo][2] or [MSN][3].  

[1]: http://baidu.com/        "Google" 
[2]: http://search.yahoo.com/  "Yahoo Search" 
[3]: http://search.msn.com/    "MSN Search"


<!-- 以下是文档的引用链接 -->
[百度]: https://www.baidu.com/  
[baidu]: https://www.baidu.com  
[入门]: markdown.md  
[代码块]:markdown.md#代码块 
[baidulogo]:https://www.baidu.com/img/bd_logo1.png
