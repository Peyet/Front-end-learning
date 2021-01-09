## Web、网页、浏览器

### Web

Web（World Wide Web）即全球广域网，也称为万维网。

常说的`Web端`就是网页端。

### 网页

**网页是构成网站的基本元素**。网页主要由文字、图像和超链接等元素构成。网页中还可以包含音频、视频以及Flash等。常见以htm 或 .html 后缀结尾，称为HTML文件。

### 浏览器

浏览器是网页运行的平台。

### Web 标准

**Web标准**：制作网页要遵循的规范。

Web标准不是某一个标准，而是由W3C组织和其他标准化组织制定的一系列标准的集合。

**1、Web标准包括三个方面**：

- 结构标准（HTML）：用于对网页元素进行整理和分类。
- 表现标准（CSS）：用于设置网页元素的版式、颜色、大小等外观样式。
- 行为标准（JS）：用于定义网页的交互和行为。





## 浏览器的组成

浏览器分成两部分：

- 1、渲染引擎（即：浏览器内核）
- 2、JS 引擎

### 1、渲染引擎（浏览器内核）

浏览器所采用的「渲染引擎」也称之为「浏览器内核」，用来解析 HTML与CSS。渲染引擎决定了浏览器如何显示网页的内容以及页面的格式信息。

**渲染引擎是浏览器兼容性问题出现的根本原因。**

渲染引擎的英文叫做 Rendering Engine。通俗来说，它的作用就是：读取网页内容，计算网页的显示方式并显示在页面上。

### 2、JS 引擎

也称为 JS 解释器。 用来解析网页中的JavaScript代码，对其处理后再运行。

浏览器本身并不会执行JS代码，而是通过内置 JavaScript 引擎(解释器) 来执行 JS 代码 。JS 引擎执行代码时会逐行解释每一句源码（转换为机器语言），然后由计算机去执行。所以 JavaScript 语言归为脚本语言，会逐行解释执行。



## 浏览器工作原理

[![img](https://camo.githubusercontent.com/b752284fe04a23badcb0106f9045b20a5ad26adf17f3c1354d874e67118cd14c/687474703a2f2f696d672e736d79687661652e636f6d2f32303138303132345f313730302e706e67)](https://camo.githubusercontent.com/b752284fe04a23badcb0106f9045b20a5ad26adf17f3c1354d874e67118cd14c/687474703a2f2f696d672e736d79687661652e636f6d2f32303138303132345f313730302e706e67)

1、User Interface 用户界面，我们所看到的浏览器

2、Browser engine 浏览器引擎，用来查询和操作渲染引擎

3、Rendering engine 用来显示请求的内容，负责解析HTML、CSS

4、Networking 网络，负责发送网络请求

5、JavaScript Interpreter(解析者) JavaScript解析器，负责执行JavaScript的代码

6、UI Backend UI后端，用来绘制类似组合框和弹出窗口

7、Data Persistence(持久化) 数据持久化，数据存储 cookie、HTML5中的sessionStorage