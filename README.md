# 《反爬虫JS安全防护与逆向分析手册》

### 教程更新账户  ：
>PS：by : [@LoseNine](https://github.com/LoseNine)  [@No-Attack](https://github.com/No-Attack) <br/>

## changelog：

|date|log|
|:-:|:-|
|2020-06-20|完成目录|
|2020-06-22|1.1 Chrome开发者工具骚操作  终于开始动手了|

## 前言
### [一、前言]

## [第1章. Chrome基础]
### 1.1 [Chrome开发者工具骚操作](https://github.com/LoseNine/Restore-JS/blob/master/1.Chrome%E5%9F%BA%E7%A1%80/1.1Chrome%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7%E9%AA%9A%E6%93%8D%E4%BD%9C.md)
### 1.2 Chorme调试技巧（某易滑块）
### 1.3 JSHook原理和作用
### 1.4 JSHook过反调试
### 1.5 JSHook对象属性

## [第2章. Chrome拓展开发]
### 2.1 Chrome拓展开发之manifest.json
### 2.2 Chrome拓展开发之JS自动注入Hook
### 2.3 Chrome拓展开发之去广告插件
### 2.4 Chrome拓展开发之填表登录
### 2.5 Chrome拓展开发之发送HTTP请求

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
