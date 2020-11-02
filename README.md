# 人事篇
#### 参考
[知乎连接](https://www.zhihu.com/question/290543744/answer/636315003)


# 技术篇

首先需要背熟的基础题

[知乎连接](https://zhuanlan.zhihu.com/p/125720498)



> HTML&CSS：
### 1. flex布局
**[flex布局](https://juejin.im/post/589965c9128fe1006569cc9d)**

### 2. 垂直居中
**[垂直居中](https://juejin.im/post/586b94e5ac502e12d62d4ab6)**
**或者height、line-height一致**

### 3. 清除浮动
**（1） 利用CSS伪类**
**（2） 利用overflow:auto**

### 4. BFC
**[BFC](https://juejin.im/post/59b73d5bf265da064618731d)**

### 5.盒模型
**[盒模型](https://juejin.im/post/59ef72f5f265da4320026f76)**
**也可以回答padding、marggin、content、border组成的模型**

### 4. H5新特性
**[H5新特性](https://juejin.im/post/5be8d817e51d457f7a4aba13)**

> JavaScript：

### 1. call, apply, bind
**[call, apply, bind](https://zhuanlan.zhihu.com/p/71553017)**

### 2. es6新特性
**[es6新特性](https://juejin.im/post/5b9cb3336fb9a05d290ee47e)**

### 3. 防抖函数、数据去重
**[防抖函数](https://juejin.im/post/5cfe66fa6fb9a07ee1691ddb)**

**[数组去重](https://juejin.im/post/5b0284ac51882542ad774c45)**

### 4.集合
**[集合](https://www.cnblogs.com/chenwenhao/p/11253403.html)**



> vue

**[vue](https://segmentfault.com/a/1190000016344599)**

> react

**[react](https://segmentfault.com/a/1190000016885832?utm_source=tag-newest)**
**[react2](https://juejin.im/post/6844904025066831879)**

>webpack

**[webpack](https://www.jianshu.com/p/e80d38661358)**


# 可能遇到的问题和我的常忘题

## ps:以下没有标准答案或上面有答案。
### 1.有没有小程序开发经验
**用uni-app/taro制作过，用这个的优势是兼容微信、百度、uc等等APP的小程序**

### 2.有没有试过搭建前端脚手架

### 3.在开发这个项目过程中担任什么角色

### 4.在这个项目中遇到了什么难点、怎么克服的。

### 5.你的职业规划

### 6.你有计划带领团队吗？如果有机会给你带领前端，你会怎么规划工作

### 7. 我现在有一个页面，你做的话需要多长时间

这里可以回答哪些需要后台动态配置的。这些增删改查的管理端加上前端所花费的时间。

### 8.对加班有什么看法

### 9.通过什么方式学习

### 10.有开源项目吗

### 11.你怎么理解react中的hook的

### 12.vuex的操作流程或者vuex 的作用

### 13.redux的操作流程或者redux的作用

### 14.从敲入 URL 到渲染完成的整个过程

这个我从来没背完整过。

### 15.你上一个项目都用到了那些方法优化js的性能?

1、防抖函数、事件委托、push代替concat。<br/>
这里可能问到push和concat的区别，区别：<br/>
（1）push 遇到数组参数时，把整个数组参数作为一个元素；而 concat 则是拆开数组参数，一个元素一个元素地加进去。<br/>
（2）push 直接改变当前数组；concat 不改变当前数组。)、<br/>
2、利用vue的数据双向绑定和react的操作虚拟dom 来避免直接对dom元素（这里有可能会问到底层。如vue怎么实现双向绑定的，react是怎么实现虚拟dom的）<br/>
3、cdn加速<br/>
4、使用base64代替小图标减少http请求<br/>
5、把常用的工具函数封装到工具类，防止重复编写<br/>



### 16.  对 MVC、MVVM的理解
**[ MVC、MVVM的理解](https://www.jianshu.com/p/fd9c2c2d1feb)**

### 16.渐进增强和优雅降级

渐进增强 ：针对低版本浏览器进行构建页面，保证最基本的功能，然后再针对高级浏览器进行效果、交互等改进和追加功能达到更好的用户体验。

优雅降级 ：一开始就构建完整的功能，然后再针对低版本浏览器进行兼容。

### 17. 跨域

可以直接回答配置nginx或者后台配置header允许跨域。
有一些蠢一点的会问，为什么会有跨域。   答：它是由浏览器的同源策略造成的，是浏览器对JavaScript实施的安全限制。

### 18. 怎么实现聊天功能

利用websocket，这里会问到websocket是什么。 （WebSocket是一种在单个TCP连接上进行全双工通信的协议。H5的一个新特性）


### 19.你会用到es6/7哪些新特性。（经常问）


**[es6新特性](https://juejin.im/post/5b9cb3336fb9a05d290ee47e)**

### 20. 说说你对闭包的理解

使用闭包主要是为了设计私有的方法和变量。闭包的优点是可以避免全局变量的污染，缺点是闭包会常驻内存，会增大内存使用量，使用不当很容易造成内存泄露。在js中，函数即闭包，只有函数才会产生作用域的概念

闭包有三个特性：

1.函数嵌套函数

2.函数内部可以引用外部的参数和变量

3.参数和变量不会被垃圾回收机制回收

### 21.常见兼容性问题？

(1)flex布局有些低版本的浏览器不支持。
(2)浏览器默认的margin和padding不同。解决方案是加一个全局的*{margin:0;padding:0;}来统一。
(3)通过配置babel和postcss解决一些不同浏览器的css前缀

### 22.有没有做过SEO优化

1、Meta标签优化
主要包括主题（Title)，网站描述(Description)，和关键词（Keywords）。还有一些其它的隐藏文字比如Author（作者），Category（目录），Language（编码语种）等。

2、使用<a>标签

3、<img>标签添加alt 属性

### 22. 行内元素有哪些？块级元素有哪些？CSS的盒模型？（经常被坑到）

行内元素有：a b span I  img input select strong(input用于定义表单中的各个具体的表单元素)
块级元素有：div ul ol li dl dt dd
盒模型：margin border padding content

### 23.最快捷的数组求最大值

```
    var arr = [ 1,5,1,7,5,9];
    Math.max(...arr)  // 9
```

### 24.JS中的算法与数据结构——链表(Linked-list)

**[链表](https://www.jianshu.com/p/f254ec665e57)**

### 25.http缓存机制

**[http缓存机制](https://www.cnblogs.com/chengxs/p/10396066.html)**

### 26. ES6数组去重 

```
var arr = new Set([1, 2, 1, 1, 2, 3, 3, 4, 4]);
for (var el of arr) {
    console.log(el)
}
```

### 27. chunkfilename 和 filename的区别（webpack）
Output：有两个配置filename和chunkFilename
Filename：打包同步代码
chunkFilename：打包异步代码

