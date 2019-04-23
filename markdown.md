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





## 水平分割线
Horizontal Rule 水平线 
 
 ---
用三个横岗需要注意，因为三个横杠也是定义二级标题的一种形式，需要上面的内容和三个横杠之间有一个空行的间隔，这就是因为没有空行所以字体粗大
---
Horizontal Rule 水平线 
***
Horizontal Rule 水平线 
___



## html代码demo


## 表格
**精简**表格 两边的竖线都去掉了  
需要注意的是这个文字和表格之间要有一个空行，否则显示乱  

name | 价格 |  数量  
-|-|-
香蕉 | $1 | 5
苹果 | $1 | 6
草莓 | $1 | 7  

name | 111 | 222 | 333 | 444
- | :-: | :-: | :-: | -:
aaa | bbb | ccc | ddd | eee
fff | ggg| hhh | iii | 000  

**非精**简表格，两边都有竖线

| name | 111 | 222 | 333 | 444 |
| - | :-: | :-: | :-: | -: |
| aaa | bbb | ccc | ddd | eee |
| fff | ggg| hhh | iii | 000 |

### 三、区别
  简单方法虽然是稍微简单了些，但是前后因为没有格式所以第一列和最后一列没有居中，对于极简方式来说还相当繁琐。极简方式简单，但是都是左对齐。原生方式格式更美观。个人意见强迫症患者请用原生方式，其他请随意。  
### 四、语法说明  
1）|、-、:之间的多余空格会被忽略，不影响布局。  
2）默认标题栏居中对齐，内容居左对齐。  
3）-:表示内容和标题栏居右对齐，:-表示内容和标题栏居左对齐，:-:表示内容和标题栏居中对齐。  
4）内容和|之间的多余空格会被忽略，每行第一个|和最后一个|可以省略，-的数量至少有一个。  

## GFM demo
Github Flvored Markdown-->GFM  
task list  
- [x] C  
- [x] C++  
- [x] Java  
- [x] Qt  
- [x] Android  
- [ ] C#  
- [ ] .NET  
 :smail:  
 :sunglasses:





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
