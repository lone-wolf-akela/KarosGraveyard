# setTargetBox(&lt;iIndex&gt;, &lt;fXmin&gt;, &lt;fYmin&gt;, &lt;fZmin&gt;, &lt;fXmax&gt;, &lt;fYmax&gt;, &lt;fZmax&gt;) #

## 描述 ##
在.ship文件中使用，设置该船的TargetBox。其他船只在攻击该船时会瞄准设置的TargetBox攻击。
同一艘船最多设置5个不同的TargetBox，其<iIndex>参数由0到4。

## 示例 ##
	setTargetBox(NewShipType, 0, -0.1,-0.7, -0.9, 0.55, 0.5, 0.82)
	setTargetBox(NewShipType, 1, -0.9,-0.001, -0.9, 0.005, 0.6, -0.55)
## 参数 ##
- &lt;iIndex&gt;: 整数。TargetBox编号。由0开始，最大为4。
- &lt;fXmin&gt;, &lt;fYmin&gt;, &lt;fZmin&gt;, &lt;fXmax&gt;, &lt;fYmax&gt;, &lt;fZmax&gt;: 浮点数。TargetBox长方体区域的六个面的边界位置。其数值单位应该是以碰撞盒对应方向边长为单位1。

## 相关函数 ##
无

## 参考页面 ##
[【GBX Forums】HWR 2.0 modding changes](https://forums.gearboxsoftware.com/t/hwr-2-0-modding-changes/1501768/4)</br>
[【GBX Forums】(Solved) setTargetBox Effects?](https://forums.gearboxsoftware.com/t/solved-settargetbox-effects/1550968)

## 附注 ##
无
