﻿## 我想写好这个APP

Test

### 2013/10/13
1. 添加Flat UI的颜色库
2. 添加了错误提示信息界面

### 2013/10/12
1. 使已完成的今日待办不会出现在今日待办列表里

### 2013/10/11
1. 添加了当今日待办列表为空时，自动跳转到PK选择待办页面

### 2013/10/10
1. 用DialogFragment重新实现了添加添加待办对话框
2. 修复添加PK结果不正确的问题

### 2013/10/09
1. 用DialogFragment重新实现了添加PK结果至今日待办列表对话框

### 2013/10/08
1. 以对话框形式添加PK结果至今日待办列表中，并能设置预估番茄数

### 2013/10/07
1. 实现PK结果添加至今日待办列表功能

### 2013/10/06
1. 实现PK界面基本逻辑

### 2013/10/06
1. 使用Fragment显示菜单，并设置相应跳转

### 2013/10/05
1. 实现添加待办对话框

### 2013/10/04
1. 完成数据库建表
2. 实现数据库相关操作的类
3. 实现中断按钮的响应和界面刷新

### 2013/10/01
1. 实现番茄计时器
2. 实现界面定时刷新
3. 实现启动番茄计时器和放弃番茄计时器的按钮响应
4. 添加番茄计时器中止时的音效
5. 添加番茄计时器运行时的音效
6. 修复重复启动番茄闪退的问题
7. 修复计时结束后界面显示不正常问题
8. 实现计时器运行时，处于界面时屏幕常亮
9. 修复计时结束后，无法再次启动计时器的问题

### 2013/09/30
1. 应用[SlidingMenu](https://github.com/jfeinstein10/SlidingMenu)到主页面中
2. 添加了引导界面，并在引导界面启动程序主控制器MainService
3. 整合原有的待办列表界面，完善各个状态下的逻辑，使锁屏状态回到界面显示正常

### 2013/09/29
1. 使用Service组件作为控制器(Controller)，抽象了主控制器的计时器的功能

### 2013/09/27 
1. 删除了数据库操作之外的所有实现代码，重写程序，
使用MVC模式，从根本上降低代码之间的耦合度。
耦合度高的代码严重限制了进一步的思考。


### 2013/09/16 更新
1. 删除与番茄计时器相关的代码
2. 添加了基本的数据库操作(添加待办事项，查询待办事项)

### 2013/09/14 更新
1. 进一步抽象番茄计时器类

### 2013/09/11 更新
1. 为番茄钟添加运行时音效(tic ta tic ta ~)

### 2013/09/10 更新
1. 添加删除番茄钟按钮，并设置对应响应事件，完善番茄计时器逻辑
2. 使用观察者模式重新实现了番茄计时器的逻辑，降低代码的耦合度
3. 实现 当番茄钟启动时，页面禁止滑动效果

### 2013/09/09 更新
1. 待办卡片添加中断显示
2. 番茄钟计时效果，使用[AppMsg](https://github.com/johnkil/Android-AppMsg)提示框展示
3. 番茄钟启动时候，屏幕常亮
        

### 2013/09/08 更新
1. 今日待办页面添加“开启番茄钟”、标记“内部中断”、标记“外部中断”按钮
2. 修复显示第二排预估番茄钟数个数的圆圈 控件时，程序一场退出的问题

### 2013/09/07 更新
1. 为待办卡片方式添加 代表预估番茄钟个数的方格 控件
2. 修复应用从后台恢复，应用从锁屏状态恢复时，卡片背景颜色改变的问题

### 2013/09/06 更新
1. 将每个待办以卡片方式呈现，界面模仿“听会早新闻”APP，使用ViewPager实现基本效果
2. 使用[Android-ViewPagerIndicator](https://github.com/JakeWharton/Android-ViewPagerIndicator)添加分页指示器
        
