# 页面顶部开发

![页面header](https://cdn.jsdelivr.net/gh/clover2024/img@master/imgs/muyunyou-header.png)
header中三个部分的高度（height）分别为32、40、72px，所以可以确定site-head的高度为150px。
先开发topbar也就是最上方的黑色块部分。

## 顶部header标签配置

`<header>`元素描述了文档的头部区域，主要用于定义内容的介绍展示区域。在页面中可以使用多个`<header>` 元素。

在本案例中，网站黑色的顶部和绿色的顶部还有logo的部分都可以放到一个header标签里面。类名可以叫site-head。

## 第一部分黑色topbar开发

黑色的部分放到一个div中，类名叫top-bar。高度32px，背景色#2A2A2A。

### center-wrap类配置

叫center会比较弱，叫包容器

```css
.center-wrap {
    width: 1152px;
    margin: 0 auto;
}
```

### 超链接颜色设置

不会从父类继承颜色

### 设置超链接去下划线

在reset.css中补一个

```css
a{text-decoration:none}
```

## 设置字体


## 顶部三角处理

