# 1. 什么是 iframe?
iframe是html里的一个标签，用来在一个网页中内嵌其他网页；

# 2. 如何在当前页面中嵌入其他页面？
使用&lt;iframe>标签，并把它的src属性设置为需要嵌入的页面的url。

# 3. iframe 有哪些常见应用？
插广告和简单的局部刷新。

# 4. 如何使用 &lt;a> 标签控制 iframe 中显示的内容？
把a标签的target属性设置为iframe的name即可。

# 5. 为什么越来越少的人使用 iframe？
因为iframe主要用于网页插广告，而别的地方很少用，所以一刀切禁止iframe对拦截广告性价比很高，不用来插广告的iframe也受到了波及，开发者为了保证网页内容能成功被用户看到，只好用其它方法代替iframe。

# 6. frame 和 iframe 有什么区别？
* frame只能在frameSet中使用，而frameSet不能在body内使用。iframe可以在body内使用。
* iframe可以控制自己的宽高，而frame不可以，要设置必须在frameSet中设置。

# 7. 请实现一个类似 gitbook 的左边点击右边局部刷新的效果
[文件名：lesson6开头的3个文件，其中lesson6_iframe.html是主页面](https://github.com/FromFire/mfs-homework.git)
