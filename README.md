# Odometer
Odometer.js 数字滚动
![image](https://github.com/Takeos/Odometer/blob/master/dist/demo.gif)

```
var odo1 = new Odometer('.Odometer',{
    len : null, //设置默认位数
    num : "", //初始化值
    speed : 1000, //动画速度
    symbol : '', //分割符
    dot : 0 //保留几位小数点 
});
odo1.update(123)  //更新数字 
```
