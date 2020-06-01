# 			semantic UI

## 简介

​		这是一款语义化的UI框架，代码可读性与可理解性很强，界面简洁美观，与bootstrap风格接近，基于jquery，适用响应式布局，提供一些基本模板，兼容Firefox、Chrome、safari,IE 10+等浏览器。

​		通过使用“形容词”来改变样式

## 使用方法（ui）

引入js与css文件: （在头部导入样式）

```java
<script src="/js/semantic.min.js"></script> 

<link href="/css/semantic.min.css">
```

使用:

​		给元素添加对应class即可使用相关组件，若需使用相关组件的动态效果 如tab切换，下拉等，使用相关元素调用对应的js即可；semantic组件调用方法中都包含各类callback和相关配置项,根据需要可进行调用

​		在`div class = "XXX"`中加上你想实现的“形容词”



## 实现

### 颜色反转（inverted）

​		若不加颜色，则直接变成黑色，颜色可选：  

orange,teal 



### vertical

​		消除两边的圆角、阴影，同一`vertical`作用下的多个`segment`之间缝隙消失



### padded

​		改变内距





### segment

​		使用`semantic`自带的`ui menu`样式，第一个与最后两个使用图标插入，其余的直接输文字，这里有几个小点需要注意：

- fixed：固定菜单栏，下拉拖动时表头不会消失，一直悬浮在最上面
- fitted：大小宽度自适应
- nine item：九个图标居中显示
- borderless：去除图案之间的白色间隔线

``` HTML
<div class="ui fixed fitted inverted borderless nine item menu">
    <a href="#" class="item">
        <div class="ui image">
            ![](images\appleicon.png)
        </div>
            </a>
    <a href="#" class="item">Mac</a>
    <a href="#" class="item">iPad</a>
    <a href="#" class="item">iPhone</a>
    <a href="#" class="item">Watch</a>
    <a href="#" class="item">Music</a>
    <a href="#" class="item">技术支持</a>
    <a href="#" class="item">
    <div class="ui image">
        ![](images\searchicon.png)
    </div>
    </a>
    <a href="#" class="item">
        <div class="ui image">
            ![](images\buyicon.png)
        </div>
    </a>
</div>
```

![image-20200520000048512](C:\Users\AVE\AppData\Roaming\Typora\typora-user-images\image-20200520000048512.png)





### grid

​			网格系统，使用EX:`five column`分成五列

### text menu

​			每段文字放在里面，且用`vertical`垂直排列





### 尺寸

​		在父div上加上mini，tiny，small，large，big，huge，massive就可以实现你想要的大小了





