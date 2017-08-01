# 微信公众号文章自动化一键排版

市面上虽然提供了很多微信公众号编辑器，出于如下几个原因我实在是不想去用：

- 排版消耗的时间太多
- 边排版边撰写打乱我的写作思绪

看到「[可能吧的文章是如何排版的？](http://mp.weixin.qq.com/s/O_f0Mg8Js3UWYPPI0DsvyQ)」之后感到神奇：居然还可以这样，果然是极客。   

于是乎就开始着手自己的一套自动化排版式样。   

排版效果请见示例文章：    
<http://mp.weixin.qq.com/s/oaDuGq4oaNUlWb3oYYbZyw>

>
> 本文的排版方法应该比可能吧的更加简单些。

## *1*操作

### 下载工具

我们首先要下载 Mac 平台下的一个 Markdown App 「MacDown」：   

<http://macdown.uranusjr.com/>

> 
> 由于我只有 Mac 电脑，也就只在 Mac 上要试验和验证过，Windows 的童鞋请先看明白思路，再结合 Windows 平台下的 Markdown 工具来举一反三。   

### 在 MacDown 中设置样式

1、下载样式文件   
<https://github.com/vincent4j/paiban/blob/master/hrule.css>

2、在 MacDown 中设置样式

把刚才的「hrule.css」文件拷贝到 MacDown 的样式目录中去，最后在「CSS」下拉列表中选择 hrule。

![](http://7xl53s.com1.z0.glb.clouddn.com/image/2017/07/macdown-setting.png)

![](http://7xl53s.com1.z0.glb.clouddn.com/image/2017/07/macdown-css.png)

![](http://7xl53s.com1.z0.glb.clouddn.com/image/2017/07/macdown-file.png)

![](http://7xl53s.com1.z0.glb.clouddn.com/image/2017/07/macdown-hrule.png)

### 在 MacDown 预览中复制

1. Ctrl + A
2. Ctrl + C

![](http://7xl53s.com1.z0.glb.clouddn.com/image/2017/07/macdown-copy.png)

### 粘贴到公众号编辑器中

打开微信公众号的编辑器，「Ctrl + V」就搞定了。

## *2*总结

这种排版由于是基于 Markdown 语法，所以只有符合 Markdown 基本语法的文字效果才能排版出来。   

例如，「**一段话里部分文字标红（就是文字着色）**」无法实现。

我们回过头来想想：排版的目的是什么？   

在节省时间的前提下达到视觉美，那 Markdown 都不支持的语法不能实现就不能实现吧，谁叫我是 Markdown 的死忠呢。







