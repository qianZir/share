# 人事篇

#### 参考

[知乎连接](https://www.zhihu.com/question/290543744/answer/636315003)

# 技术篇

首先需要背熟的基础题

[知乎连接](https://zhuanlan.zhihu.com/p/125720498)

> HTML&CSS：

### 1. flex 布局

**[flex 布局](https://juejin.im/post/589965c9128fe1006569cc9d)**

### 2. 垂直居中

**[垂直居中](https://juejin.im/post/586b94e5ac502e12d62d4ab6)**
**或者 height、line-height 一致**

### 3. 清除浮动

**（1） 利用 CSS 伪类**
**（2） 利用 overflow:auto**

### 4. BFC

**[BFC](https://juejin.im/post/59b73d5bf265da064618731d)**

### 5.盒模型

**[盒模型](https://juejin.im/post/59ef72f5f265da4320026f76)**
**也可以回答 padding、marggin、content、border 组成的模型**

### 4. H5 新特性

**[H5 新特性](https://juejin.im/post/5be8d817e51d457f7a4aba13)**

> JavaScript：

### 1. call, apply, bind

**[call, apply, bind](https://zhuanlan.zhihu.com/p/71553017)**

### 2. es6 新特性

**[es6 新特性](https://juejin.im/post/5b9cb3336fb9a05d290ee47e)**

### 3. 函数防抖和节流、数据去重

**[防抖函数](https://juejin.cn/post/6844903651278848014)**

**[数组去重](https://juejin.im/post/5b0284ac51882542ad774c45)**

### 4.集合

**[集合](https://www.cnblogs.com/chenwenhao/p/11253403.html)**

> vue

**[vue](https://segmentfault.com/a/1190000016344599)**

> react

**[react](https://segmentfault.com/a/1190000016885832?utm_source=tag-newest)**
**[react2](https://juejin.im/post/6844904025066831879)**

> webpack

**[webpack](https://www.jianshu.com/p/e80d38661358)**

# 可能遇到的问题和我的常忘题

## ps:以下没有标准答案或上面有答案。

### 1.有没有小程序开发经验

**用 uni-app/taro 制作过，用这个的优势是兼容微信、百度、uc 等等 APP 的小程序**

### 2.有没有试过搭建前端脚手架

### 3.在开发这个项目过程中担任什么角色

### 4.在这个项目中遇到了什么难点、怎么克服的。

### 5.你的职业规划

### 6.你有计划带领团队吗？如果有机会给你带领前端，你会怎么规划工作

### 7. 我现在有一个页面，你做的话需要多长时间

这里可以回答哪些需要后台动态配置的。这些增删改查的管理端加上前端所花费的时间。

### 8.对加班有什么看法

理论上可以回答：在我们这个行业中加班赶项目进度是很平常的一件事情，一起努力办好就行。但是我自身素质比较高，绝对不会因为我个人的问题导致整个团队加班

### 9.通过什么方式学习

### 10.有开源项目吗

### 11.你怎么理解 react 中的 hook 的

### 12.vuex 的操作流程或者 vuex 的作用

### 13.redux 的操作流程或者 redux 的作用

### 14.从敲入 URL 到渲染完成的整个过程

这个我从来没背完整过。

### 15.你上一个项目都用到了那些方法优化 js 的性能?

1、防抖函数、事件委托、push 代替 concat。<br/>
这里可能问到 push 和 concat 的区别，区别：<br/>
（1）push 遇到数组参数时，把整个数组参数作为一个元素；而 concat 则是拆开数组参数，一个元素一个元素地加进去。<br/>
（2）push 直接改变当前数组；concat 不改变当前数组。)、<br/>
2、利用 vue 的数据双向绑定和 react 的操作虚拟 dom 来避免直接对 dom 元素（这里有可能会问到底层。如 vue 怎么实现双向绑定的，react 是怎么实现虚拟 dom 的）<br/>
3、cdn 加速<br/>
4、使用 base64 代替小图标减少 http 请求<br/>
5、把常用的工具函数封装到工具类，防止重复编写<br/>

### 16. 对 MVC、MVVM 的理解

**[ MVC、MVVM 的理解](https://www.jianshu.com/p/fd9c2c2d1feb)**

### 16.渐进增强和优雅降级

渐进增强 ：针对低版本浏览器进行构建页面，保证最基本的功能，然后再针对高级浏览器进行效果、交互等改进和追加功能达到更好的用户体验。

优雅降级 ：一开始就构建完整的功能，然后再针对低版本浏览器进行兼容。

### 17. 跨域

可以直接回答配置 nginx 或者后台配置 header 允许跨域。
有一些蠢一点的会问，为什么会有跨域。 答：它是由浏览器的同源策略造成的，是浏览器对 JavaScript 实施的安全限制。

### 18. 怎么实现聊天功能

利用 websocket，这里会问到 websocket 是什么。 （WebSocket 是一种在单个 TCP 连接上进行全双工通信的协议。H5 的一个新特性）

### 19.你会用到 es6/7 哪些新特性。（经常问）

**[es6 新特性](https://juejin.im/post/5b9cb3336fb9a05d290ee47e)**

### 20. 说说你对闭包的理解

使用闭包主要是为了设计私有的方法和变量。闭包的优点是可以避免全局变量的污染，缺点是闭包会常驻内存，会增大内存使用量，使用不当很容易造成内存泄露。在 js 中，函数即闭包，只有函数才会产生作用域的概念

闭包有三个特性：

1.函数嵌套函数

2.函数内部可以引用外部的参数和变量

3.参数和变量不会被垃圾回收机制回收

### 21.常见兼容性问题？

(1)flex 布局有些低版本的浏览器不支持。
(2)浏览器默认的 margin 和 padding 不同。解决方案是加一个全局的\*{margin:0;padding:0;}来统一。
(3)通过配置 babel 和 postcss 解决一些不同浏览器的 css 前缀

### 22.有没有做过 SEO 优化

1、Meta 标签优化
主要包括主题（Title)，网站描述(Description)，和关键词（Keywords）。还有一些其它的隐藏文字比如 Author（作者），Category（目录），Language（编码语种）等。

2、使用<a>标签

3、<img>标签添加 alt 属性

### 22. 行内元素有哪些？块级元素有哪些？CSS 的盒模型？（经常被坑到）

行内元素有：a b span I img input select strong(input 用于定义表单中的各个具体的表单元素)
块级元素有：div ul ol li dl dt dd
盒模型：margin border padding content

### 23.最快捷的数组求最大值

```
    var arr = [ 1,5,1,7,5,9];
    Math.max(...arr)  // 9
```

### 24.JS 中的算法与数据结构——链表(Linked-list)

**[链表](https://www.jianshu.com/p/f254ec665e57)**

### 25.http 缓存机制

**[http 缓存机制](https://www.cnblogs.com/chengxs/p/10396066.html)**

### 26. ES6 数组去重

```
var arr = new Set([1, 2, 1, 1, 2, 3, 3, 4, 4]);
for (var el of arr) {
    console.log(el)
}
```

### 27. chunkfilename 和 filename 的区别（webpack）

Output：有两个配置 filename 和 chunkFilename
Filename：打包同步代码
chunkFilename：打包异步代码

### 28. 小程序开发中你担任什么样的角色

#### （1）性能优化

迁移非必要代码至分包，分离静态资源，减少重复 wxss，从而精简主包，减少小程序打开时间。
编写骨架屏
切换页面时，把上一页的数据带到下一页默认展示，配合骨架屏，可以达到页面“秒开”效果

#### （2）业务开发

根据产品需求做一些对应的业务开发

#### （3）报错、数据、性能埋点

利用小程序 APi，添加埋点功能，能够快速定位到报错位置
通过记录打开时间，渲染时间，上报至统计系统，从而收集用户不同机型的性能情况，然后用分析出来的数据做对应的性能优化

#### （4）业务定制编译系统

联合开发一个“业务定制编译系统”，给业务方使用。

#### (5)体积优化

**[体积优化](https://zhuanlan.zhihu.com/p/135983160)**

#### (6)滴滴出行小程序体积优化实践

**[体积优化](https://mp.weixin.qq.com/s/E8iBnQtpZloQHIYlgNLFHg)**
