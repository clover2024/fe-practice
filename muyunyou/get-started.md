# 项目起步

该部分练习代码放于get-started-code文件夹中。

## 项目文件初始化

新建三个文件夹，css、images、js和index.html。

用!自动补全功能初始化index.html，得到html骨架代码。

## head标签中添加网站信息

修改网站title标签内容：慕云游商城 - 机票、酒店、旅游攻略
添加2个meta单标签，分别添加Keywords和Description，主要用于SEO：

```html
<title>慕云游商城 - 机票、酒店、旅游攻略</title>
<meta name="Keywords" content="机票，酒店，旅游攻略，签证，出国，自由行">
<meta name="Description" content="慕云游商城有10多年旅游行业经验，为您提供全方位旅游服务">
```

## 添加reset.css

搜索yui reset，相关介绍可见：https://clarle.github.io/yui3/yui/docs/cssreset/

由于雅虎停止了对国内的服务，所以需要走其他节点（比如新加坡）获取该文件：http://yui.yahooapis.com/3.18.1/build/cssreset/cssreset-min.css

使用以下方式引入会因为网络原因不生效：

```html
<link rel="stylesheet" type="text/css" href="http://yui.yahooapis.com/3.18.1/build/cssreset/cssreset-min.css">
```

因此直接复制文件内容到本地再引入。

```html
<link rel="stylesheet" type="text/css" href="./css/reset.css">
```

## 添加base.css

用于放置一些公共类。

### 清除浮动

clearfix，这个需要回去看一下

### 文字居中tac

```css
.tac {
    text-align: center;
}
```

### 元素居中center

```css
.center {
    margin: 0 auto;
}
```

"margin 0 auto" 是一种CSS布局技术，用于**设置元素的水平居中**。 

具体来说，"margin" 是CSS中用于控制元素外边距的属性，**"0" 表示上下外边距为0，而"auto" 表示左右外边距自动适应，以实现水平居中的效果。** 这样，该div元素就会相对于其父元素水平居中。
