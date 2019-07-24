# Demo2  

语法二  

## 链接
### 内嵌式链接
- 外部链接:
[百度](https://www.baidu.com)

- 内部链接：
  - 链接查看的其他文件  
    例如：
	链接同目录下的demo1.md，[Demo1](demo1.md)  
	链接到本文档的代码块, [代码块](demo2.md#代码块-demo)
  - 链接本文档的其他  
    
### 引用式链接
- 外部链接: [百度]
- 外部链接: [百度][baidu]  相当与别名
- 内部链接：链接同目录下的demo1.md，[Demo1]
- 内部链接：链接到本文档的代码块, [代码块]



## 图片
- 图片MarkDown语法格式：  
    ![alt](url text)
	
- 外部图片  
![baidu](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1564534240&di=7ea0faf37e196aed5111aa5f642c2758&imgtype=jpg&er=1&src=http%3A%2F%2Fimage.cn.made-in-china.com%2Fprodzip%2F000-jCrQFphdyAum.jpg "百度搜索")  


- 仓库内部图片  
![](images/index.jpg)  
![](images/boy.jpg)  


- 图片的引用式链接
- 外部图片  
![][firefox_logo]  


- 仓库内部图片  
![][flower]  
![][boy] 


## 引用

>这是一段引文。  

                                                                   --出自《出处》
多次引用：
>>> 这是多重引文



## 代码块

- 行内代码

这个代码中用来声明变量是`var a = 10`,打印变量内容是`console.log`函数的调用。



- 块式代码  

```JavaScript
var a = 10;
console.log(s);
```


    var a = 10;
    console.log(s);





<!-- 下面是本文档中用到的链接-->
[百度]:https://www.baidu.com
[baidu]:https://www.baidu.com
[Demo1]:demo1.md
[代码块]:demo2.md#代码块-demo
[firefox_logo]:https://www.firefox.com.cn/media/img/logos/firefox/logo-quantum.9c5e96634f92.png
[flower]:images/index.jpg
[boy]:images/boy.jpg