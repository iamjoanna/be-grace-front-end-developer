# 布局
## 两栏布局
* 左栏定宽，右栏填充剩余部分

## 多栏布局



## [宽度不固定的元素两端对齐](http://www.zhangxinxu.com/wordpress/2011/03/displayinline-blocktext-alignjustify%E4%B8%8B%E5%88%97%E8%A1%A8%E7%9A%84%E4%B8%A4%E7%AB%AF%E5%AF%B9%E9%BD%90%E5%B8%83%E5%B1%80/)

## 宽度不固定的元素水平居中

## 宽度固定元素的元素居中
* 块级
* 行内

## 绝对定位的元素水平居中

## 垂直居中
```
.demo{
    height: 30px;
    line-height: 30px;

    display: table-cell; 
    vertical-align: middle;

    position: absolute; 
    top: 50%; 
    margin-top: -?px;/*1/2 height*/
}
```