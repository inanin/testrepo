# Demo2

## 链接demo
### 内嵌式链接
- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其它文件：[demo1](demo1.md)
- 内部链接2，链接本文档的其它部分：[代码块 demo](demo2.md#代码块-demo)
                                            <!--- 代码块 demo中间的空格使用-代替 -->

### 引用式链接
<!--- 引用式链接能简化URL的条目类似于变量 -->
- 外部链接：[百度]
- 外部链接，[百度][baidu]
- 内部链接1，链接仓库的其它文件：[demo1]
- 内部链接2，链接本文档的其它部分：[代码块 demo]

## 图片 demo
- 图片的MarkDown语法:
  ![alt](url text)
### 图片内嵌式链接
- 外部图片 demo  
  ![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")
- 仓库内的图片 demo  
  ![](images/googlelogo.png)
### 图片引用式链接
- 外部图片 demo  
  ![baidu][baidu_logo]
- 仓库内的图片 demo    
  ![][google_logo]
- 混合链接  
  [![][baidu_logo]][baidu]
   
## 引用 demo
> 这是一个引文
出自<<出处>>

多重引用 
>>>这是多重引文

## 代码块 demo
- 行内代码
这个代码中用来声明变量是`var a =10`,打印变量内容`console.log`函数的调用。  
- 样式代码
```javascript
var a =10;
console.log(a);
```

<!--- 下面是本文档中引用到的链接 -->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:demo1.md
[代码块 demo]:demo2.md#代码块-demo
[baidu_logo]:https://www.baidu.com/img/bd_logo1.png
[google_logo]:images/googlelogo.png
