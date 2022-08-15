# 响应式布局

## 响应式布局概念
指网页能自动识别屏幕宽度，并做出相应调整的网页设计。响应式布局可以为不同终端的用户提供更加舒适的界面和更好的用户体验

## 响应式布局相关语法
1. 媒体查询语法
2. 媒体查询的编写位置及顺序
3. 响应断点（阀值）的设定
4. 响应式栅格系统

## 媒体查询
1. 媒体类型
    媒体类型（Media types）描述设备的一般类型
    all：适用于所有设备
    print：适用于在打印预览模式
    screen：主要用于屏幕
    speech：主要用于语音合成器
2. 媒体特性
    媒体特性（Media features）描述了user agent，输出设备，或是浏览器环境的具体特征
    width：viewport的宽度
    height：viewport的宽度
    aspect-ratio：viewport的宽高比
    orientation：viewport的旋转方向
3. 逻辑操作符
4. link标签方式


## 媒体查询的编写位置及顺序
1. 添加到样式表的底部，对css进行优先级的覆盖
2. 移动端 -》 PC端的适配原则：min-width 从小到大
3. PC端  -》 移动端的适配原则： max-width从大到小

## 移动优先原则，先编写移动端设备，然后响应式过度到PC端

## 响应式断点（阀值）设定
1. Extra small < 576px
2. Small >= 576px, -sm
3. Medium >= 768px, -md 
4. Large >= 992px, -lg 
5. X-Large >= 1200px, -xl 
6. XX-Large >= 1400px, -xxl 

