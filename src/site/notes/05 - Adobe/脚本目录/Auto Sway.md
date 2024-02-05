---
{"dg-publish":true,"permalink":"/05-adobe//auto-sway/","title":"AutoSway","tags":["MG","木偶","参考","gardenEntry"]}
---


>[!Info]
> ![AutoSway参考.jpg](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%E5%8F%82%E8%80%83.jpg)
>[Just a moment... (aescripts.com)](https://aescripts.com/autosway/)
>[AE脚本-风吹自由摇曳摆动MG动画 AutoSway v1.86 + 使用教程-LookAE.com](https://www.lookae.com/autosway-186/)
```toc
```

## AutoSway
---
木偶摇摆工具，基于图层或木偶图钉来模拟风吹摇曳的运动

### 木偶图钉模式（PuppetPinTool Mode）
基于Ae内置的木偶图钉工具定点使图层摆动
![PuppetPinTool Mode.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/PuppetPinTool%20Mode.png)
![PuppetPinTool.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/PuppetPinTool.png)
![PuppetPinTool Apply.gif](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/PuppetPinTool%20Apply.gif)

### 图层模式（Layer Mode）
以多个图层作为木偶点
![AutoSway Layer Mode.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Layer%20Mode.png)
![AutoSway Layer Mode.gif](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Layer%20Mode.gif)
- 图层工具（较少使用）
    - 细分图层（带锚点和3种细分方式）
    - 复制图层（基于变换属性偏移复制图层）

![Layer Tool.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/Layer%20Tool.png)

### 控制器参数（AutoSway Pin）
![AutoSway Pin.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Pin.png)
- Sway distance 摇摆幅度
- Sway roundness 摇摆弧度
![AutoSway distance&&roundness.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20distance&&roundness.png)
- Sway Speed 摇摆速度
- Sway Decay 摇摆衰减（K帧案例触碰物体后缓慢停下）
![AutoSway Decay.gif](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Decay.gif)
- Offset 摇摆偏移（即相位偏移）
- Lag factor 滞后因子（即惯性带动，时间滞后）
![AutoSway Lag factor.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Lag%20factor.png)
- Adjustment 调节参数（特指调节原有形状）
    - Curves into straight line 曲线拉直
    - Curve Adjustment 曲线调节
    - Rotation(all) 旋转
    - Scale 比例
 - Wind settings 风力参数
     - Strength 强度
     - Interval 频率
     - Loop period 周期（100表示1秒循环一次）
![Adjustment && Wind settings.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/Adjustment%20&&%20Wind%20settings.png)

### 其他功能
![其他功能.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/%E5%85%B6%E4%BB%96%E5%8A%9F%E8%83%BD.png)
- Bake 烘培，表达式参数烘培
- Delete 删除，选择控件后删除相应图层
- CopyTool 将一个控制器参数复制给另一个控制器
![AutoSway Options.png](/img/user/05%20-%20Adobe/%E8%84%9A%E6%9C%AC%E7%9B%AE%E5%BD%95/attachments/AutoSway%20Options.png)
- Options
    - Reverse start point and end point 反转起始和结束点
    - Random lag factor 随机滞后因子
    - Reverse lag factor 反转滞后因子
    - Lock null layer 锁住空对象
    - Fix end point(PuppetPinTool use only) 固定结束点
    - Don't fix start point 不固定起始点（即要不要根部的问题）