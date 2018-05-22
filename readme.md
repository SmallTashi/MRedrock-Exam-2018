# MRedrock Exam 2018

## 聚餐
聚餐！2018年5月26日 18：00，问我为什么这个时间？我会告诉你为什么要贴春联？请遵守移动的传统，没有正当理由不许请假 （听说来者加分，不来扣分哟）。

## 考核
+ 考核题目：掌上重邮问答社区（偷懒的学长开始丢锅了，别问我这个学长是谁~）
+ 考核时间：5.25 21：00 ~ 5.27 21：00 （共48小时）
+ 提交方式：将 **代码** 及 **app** 上传到 **GitHub**并将GitHub地址发送到邮箱, **命名：半期考核-Android or iOS-姓名-学号** （例：半期考核-Android-王尼玛-2017200000）
+ 邮箱地址：mredrock@163.com（ **Android** ）、mredrock_iOS@163.com（ **iOS** ）

## 重点
+ **请认真看完下面的每一条，不会浪费你太多时间，违反会被扣分甚至考核无效**
+ （`Android`）app需兼容到`API 19`，即`Android 4.4`
+ 不许使用任何第三方库（自己封装的除外）
+ 适配不同分辨率屏幕
+ 一个好消息，本次考核不用自己设计UI，群里有一整套的视觉图
+ 一个坏消息，请严格按照群里的视觉图写UI，否则扣分（如果感觉图太难无法完成，可以自己发挥，当然肯定是会被扣分的）
+ 对于app的交互，请严格按照原型图中的描述完成，否则视为未完成
+ 请写好readme，readme中需包含你做了的功能，及功能的演示gif。不知道怎么录gif的可以试试这个：[https://licecap.en.softonic.com/](https://licecap.en.softonic.com/)
+ 请按时提交作业，超过5.27 21：00时间后的commit记录无效
+ 放心使用搜索引擎，但不要大面积复制网上代码
+ 导师不回答任何代码相关的问题（闲聊可以，如果你和我一样感觉比较闲的话）

## 加分项
+ 对不同分辨率屏幕的良好适配
+ 良好的代码规范
+ 合理的动画效果
+ 良好的封装
+ 良好的设计模式
+ 对视觉图及原型图的完美还原
+ 。。。 。。。

## 视觉图的使用
### 视觉图构成
每一个界面的视觉图都会至少包含两张图片——一张jpg格式的预览图、一张PSD格式的设计图。预览图功能不用说，PSD格式的设计图通过ps打开后你就知道了。

### 切图
做UI时会用到许多图标，这些图标是需要用ps打开PSD文件去切的，但是考虑到这不是考核重点，所以已经为你们切好了所有的图标，直接用就好了。（所有的图标都是基于Android xhdpi 或 iOS@2x的，放在对应文件夹下即可）

### 标注
如下图，将PSD上传到网站`标你妹`以后，可以很简单的获取到大部分的标注信息。地址：[http://www.biaonimeia.com](http://www.biaonimeia.com)
![](img/img01.gif)

### 注意
+ 有些重复出现的图标因为切图的学长懒（emmm，就是我~）没有每一个都切下来，但一定是可以其他文件夹下找到的
+ 如果找遍了所有文件夹都没有发现你要的图标，可以自己切图，也可以找 **李吉学长（Android）** 或 **梁霄学长（iOS）** 要
+ 有些非常简单的图标因为可以用非常简单的代码实现（也推荐这么做），所以偷懒的学长并没有切，如果感觉通过代码实现太难，可以自己切，或者找 **李吉学长（Android）** 或 **梁霄学长（iOS）** 要
+ 在查看标注前，请先在右上角设置图片的尺寸标准，本次考核的所有视觉图都采用 **Android xhdpi** 或 **iOS@2x**
+ 对于标你妹上的标注，不一定是非常准确的，有时候需要自己微调一下
+ 在标注的属性栏有一个`opcity`属性，如果这个属性不为1，那么在设置颜色时请用8个16进制位的颜色表示法，例如opcity值为0.7，字体颜色为#333333，则在Android代码中设置颜色时应设置为：#4c333333。转换关系请参考：[http://www.cnblogs.com/lianghui66/p/4537809.html](http://www.cnblogs.com/lianghui66/p/4537809.html)

## 原型图使用
对于每个界面的按钮及其他交互都在原型图中有说明，请严格按照原型图的内容完成考核。原型图地址：[https://pz1d1k.axshare.com/#g=1&p=1_版本记录](https://pz1d1k.axshare.com/#g=1&p=1_版本记录) （包含了新版的掌邮的所有原型，只看问答的即可）

## 接口文档
[api](api.md)