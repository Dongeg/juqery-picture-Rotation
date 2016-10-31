# juqery-picture-Rotation
jquery实现无缝滚动轮播图特效插件
<h3>特点</h3>

1.html结构清晰，对后端数据传输友好

2.无缝滚动

<h3>用法</h3>
在slide.js中直接配置如下参数即可
```js
var picWidth=600;//设定图片宽度
var picHeigth=400;//设定图片高度
var num=5;//设定图片数量
var stopTime=3000;  //动画间隔时间ms
var transition=350; //动画持续时间ms
```
slide.css中的样式可以根据自己的需要修改

<b>注意：前端实际插入的图片和小圆点的数量要与配置参数中的<code>num</code>一致，否则会出错</b>
