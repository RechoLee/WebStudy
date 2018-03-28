# 我的前端学习笔记
> **前端点滴**
参考网址
* [MDN](https://developer.mozilla.org/zh-CN/)
* [网易云课堂](http://study.163.com/)

## 注意script的位置
一般来说脚本的位置我们需要注意，由于浏览器在解析html的时候的从开头向结尾逐句解析，故我们在设置脚本的时候可能发生元素未加载我们就获取的情况。这里有一个函数window.onload，它的意思是页面加载完成后的调用的函数，可以将代码部分放在此函数中。
## JS
### JS的组成
|名称|关系|操作对象|
|---|---|---|
|ECMAScript :|解释器| 翻译|
|DOM:(Document Object Model) |HTML| document|
|BOM: (Brower Object Model) | 浏览器 |window|


