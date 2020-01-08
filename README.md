# SnakeGame_WeChat
##  1. 颜色拾取

Color_new

在线图片取色器：http://www.jiniannet.com/page/allcolor

色卡：http://link.fobshanghai.com/rgbcolor.htm

HTML，RGB

红色：#FF0000,rgb(255,0,0)

绿色：#00FF00,rgb(0,255,0)

蓝色：#0000FF,rgb(0,0,255)

黑色：#000000,rgb(0,0,0)

白色：#FFFFFF,rgb(255,255,255)

## 2. 微信开发者工具

Appid：身份验证

结构：默认基础结构

App.wxss：公共样式

App.json：公共配置文件

App.js：公共属性和方法

Project.config.json：项目配置文件

## 3. 团队开发步骤：

需求分析—页面原型设计—数据库建模—架构—类设计—编码—测试—部署

\4. 标签：view,modal

View标签：块元素

Text标签：行元素

单位：px rpx

换算：1rpx=0.5px

  Canvas标签：画布

  Modal标签：弹出框

![](https://github.com/TastSong/SnakeGame_WeChat/blob/master/Dome.png)

## 5. 样式：成对出现

字体颜色：color: black;

字体大小：font-size: 60rpx;

字体风格：font-style: italic;（倾斜-italic，正常-normal）

字体粗细：font-weight: 900;（100—细，400—正常，900—粗）

文字对齐方式：text-align: center;（靠左-left，靠右-right，居中-center）

文字垂直居中：line-height: 300rpx;（行高跟整个高度一致）

背景颜色：background-color: red;

宽高：width: 400rpx;height: 400rpx;

外边距：margin: 20rpx 20rpx 20rpx 20rpx;

圆角边框：border-radius: 50rpx;

浮动属性：float: right;

弹性盒子：display:flex;

## 6. 选择器

.class 选择器；:last-child 选择器

## 7. 事件

bindtouchstart（手指触摸动作开始）

bindtouchmove（手指触摸后移动） 

bindtouchend （手指触摸动作结束） 

bindtap（手指触摸后马上离开）

## 8. 渲染

wx:for（列表渲染）、wx:if（条件渲染）

## 9. 本地缓存数据

wx.setStorageSync(string key, any data)（同步请求）

wx.getStorageSync(string key)（获取本地缓存数据）

## 10.弹出框

modal标签和wx.showModal(Object object)接口