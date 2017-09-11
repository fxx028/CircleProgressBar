# CircleProgressBar
最近项目里面需要做一个如下的控件。
![测试图片](https://github.com/Amoryan/CircleProgressBar/raw/master/screenShort/1.png)
无奈不想用别人做好的，于是自己就做了一个，先上效果图。
![测试图片](https://github.com/Amoryan/CircleProgressBar/raw/master/screenShort/result.gif)
支持以下属性
##Paint相关属性
strokeWidth指定paint的宽度
capStyle对应于Paint.Cap
##绘制相关属性
radius进度条的绘制半径
startDegree从哪个其实角度开始画
rotateDegree旋转角度
sweepDegree绘制角度
比如rotate为0，startDegree为0，sweepDegree为360，就是从3点钟方向绘制360度
##颜色相关属性
backColor设置底色
useGradient是否使用渐变色
progressColor如果不使用渐变色，这个属性会设置进度条的颜色
startColor和endColor如果使用渐变色，这两个属性是设置起始和终止颜色
##动效相关属性
openAnimation是否开启动画
animVelocity进度变化的速度
##进度相关属性
maxProgress设置最大进度
progress设置进度