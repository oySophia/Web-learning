注意 div 在 float 下的使用模式；

main、main1 和 main2 主要就不同的情况做了一些示例说明；

其实本质的情况就是，html 文件是从上至下来做处理的，所以看到代码排布的格式不同，所得到的结果也会是不同的。


两栏排列的风格有如下几种实现：
flaot；（其中一栏固定宽度，且用该栏 float）

两栏都设定固定宽度，这样导致的结果可能是随着浏览器 window 的变化，出现空隙或者 overlap；

positon；其中一栏不改变，一栏作位置的设定和宽度的设定；
例如：
#siderbar {
position: absolute;
top: 128px;
right: 0px;
width: 280px;
}


>>>>>>>>>放置一个图片，且其位置不会随着滚动条的滚动而变化，也就是说，位置相对整个 window 是固定的，可以使用这样的代码 #coupon {position: fixed; top: 300px; left: 100px;}

>>>>>>>>>在位置的判断时，可以辅助绘图理解；


float an image left or right in a paragraph and you'll see your text flow around it. Don't forget to add padding to give the image a little room, and possibly a border.