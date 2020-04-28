# CASIA标注工具
---
### 软件介绍
CasiaLabeler是一款非常轻量的标注软件，支持win10和ubuntu18平台。主要适用于目标检测和实例分割等场景。可用于Faster RCNN, Mask RCNN, Yolo系列, SSD系列, Centernet系列等。
### 说明
你可以免费使用本软件，但不可用于任何商业用途(©2020 Casia RLIS)，仅供学习科研使用。如有BUG，可以在issue里面进行评论，虽然我也不一定会立即修复BUG(只有晚上才有时间啦~），不过有时间的了还是会修复的。如果觉得好用，给在github里给个小星星呗，不给也OK啦。
### 视频介绍
B站: https://www.bilibili.com/video/BV1dA411b7F4/
### 加载不出图像，去CSDN.
CSDN: https://blog.csdn.net/MSNH2012/article/details/105693120
### 概览
![](img/overview.png)
### 特点
- **1. 支持图片格式**
  png,jpg,jpeg,bmp

  **注：** 单次标注不能超过200张
- **2. 支持视频格式**
  avi,mp4,wmv,mov,asf
  
  **注：** 上述视频格式, 如压缩, 请采用H.264编码视频，或无压缩视频。
- **3. 支持标注框复制粘贴**
- **4. 导出格式**</br>
![](img/Box.png)</br>
 **<font color=#ff0000>4点矩形格式(多边形类似):</font>** <font color=#0000ff> 图片路径 [空格] x1,y1,x2,y2,x3,y3,x4,y4,标签 [空格] ... </font></br>
 ![](img/rotate.png)</br>
 **<font color=#ff0000>xywhθ矩形格式:</font>** <font color=#0000ff> 图片路径 [空格] x,y,w,h,θ,标签 [空格] ... </font></br>
 符合该格式的标注文档，同样可导入本软件。</br>
 如果想要COCO，Labelme等支持的格式，用python转换一下就行啦~</br>
 - **5. 支持平台**
  支持windows10和ubuntu1804+.
- **6. 特殊说明**
 工程路径中不能带有空格！
### 示例
- **1.添加和导入标签**
![](img/add_label.png)
- **2.矩形标注**
![](img/rect.png)
- **3.带角度标注**
![](img/rect_with_angle.png)
- **4.多边形标注**
![](img/poly.png)
- **5.视频操作**
![](img/video.png)
- **6.设置相关**
![](img/setting.png)
- ### 下载地址
链接：https://pan.baidu.com/s/18ap6wuRJrjpyq9C0OiTDeg 
提取码：9bpw 

