# 《反爬虫JS破解与混淆还原手册》

# 市面上的爬虫书真的太烂大街了，一到逆向部分就跳过，
# 想给大家伙整点真干活，之前就在github更新，本来鸽了，但是没想到人气挺高
# 一直还有人催更，挺感动的，就一写成了书《反爬虫AST原理与还原混淆实战》，淘宝，京东等全网有售
# 希望能给大家不一样的学习体验
当当自营：http://product.dangdang.com/29290985.html



### 教程更新账户  ：
>PS：by : [@LoseNine](https://github.com/LoseNine)  [@No-Attack](https://github.com/No-Attack) <br/>

### 发布JS破解，App协议分析，Xposed和Frida教程
![](https://mmbiz.qpic.cn/mmbiz_jpg/PAFHVZCvStuRWU5jDNFTPzxURY7dXaDpzwlb3YW6hW6KgjtbVgicfwKtoqaoNSGBIfYoZeqic1NkJtibU1Cs9WVBQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)


## changelog：

|date|log|
|:-:|:-|
|2020-06-20|完成目录|
|2020-06-22|第一章|
|2020-06-23|第二章|

## 前言
### [一、前言]

## [第1章. Chrome基础]
### 1.1 [Chrome开发者工具骚操作](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.1Chrome%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7%E9%AA%9A%E6%93%8D%E4%BD%9C.md)
### 1.2 [Chorme调试技巧（易盾滑块轨迹调试）](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.2Chrome%E8%B0%83%E8%AF%95%E6%8A%80%E5%B7%A7%EF%BC%88%E6%9F%90%E6%98%93%E6%BB%91%E5%9D%97%EF%BC%89.md)
### 1.3 [JSHook原理和作用](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.3JS%20Hook%E5%8E%9F%E7%90%86%E4%B8%8E%E4%BD%9C%E7%94%A8.md)
### 1.4 [JSHook过反调试](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.4JS%20Hook%E8%BF%87%E5%8F%8D%E8%B0%83%E8%AF%95.md)
### 1.5 [JSHook对象属性](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.5JS%20Hook%E5%AF%B9%E8%B1%A1%E5%B1%9E%E6%80%A7.md)

## [第2章. Chrome拓展开发]
### 2.1 [Chrome拓展开发之manifest.json](https://github.com/LoseNine/Restore-JS/blob/master/2.Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91/2.1Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91%E4%B9%8Bmanifest.json.md)
### 2.2 [Chrome拓展开发之JS自动注入Hook](https://github.com/LoseNine/Restore-JS/blob/master/2.Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91/2.2Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91%E4%B9%8B%E8%87%AA%E5%8A%A8%E6%B3%A8%E5%85%A5Hook.md)
### 2.3 [Chrome拓展开发之去广告插件](https://github.com/LoseNine/Restore-JS/blob/master/2.Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91/2.3Chrome%E6%8B%93%E5%B1%95%E5%BC%80%E5%8F%91%E4%B9%8B%E5%8E%BB%E5%B9%BF%E5%91%8A.md)

## [第3章. JS算法调试实战]
### 3.1 条件断点
### 3.2 console暗装与Fiddler自动响应
### 3.3 webpack整体改写方案1
### 3.4 webpack整体改写方案2
### 3.5 sojson反调试
### 3.6 某视频sign算法
### 3.7 自写算法实战案例1
### 3.8 自写算法实战案例2

## [第4章. JS混淆基础]
### 4.1 JS混淆原理1
### 4.2 JS混淆原理2
### 4.3 五秒防火墙POST流程分析
### 4.4 五秒防火墙分析
### 4.5 五秒防火墙JS改写
### 4.6 流程控制混淆原理1
### 4.7 流程控制混淆原理2

## [第5章. 自制JS混淆组件]
### 5.1 AST抽象语法树入门
### 5.2 Babel组件traverse
### 5.3 Babel组件types
### 5.4 用Babel生成新函数
### 5.5 用Babel给函数加点料
### 5.6 用Babel实现变量名混淆
### 5.7 用Babel实现对象访问方式混淆
### 5.8 用Babel实现数组混淆
### 5.9 用Babel实现数组乱序
### 5.10 用Babel实现字符串加密

## [第6章. JS混淆还原组件]
### 6.1 字符串解密
### 6.2 去除字符串花指令
### 6.3 去除函数花指令
### 6.4 AST节点调试技巧
### 6.5 switch流程控制平坦化之分发器
### 6.6 switch流程控制平坦化之指令顺序
### 6.7 JS混淆实战案例——硬刚法
### 6.8 JS混淆实战案例——还原法
### 6.9 JS混淆实战案例——sojsonv6
