# proj37-window-manager
### 项目名称
窗口管理器动画特效实现

### 项目描述

本项目主要是研究kwin特效框架，基于c++/js实现一个或多个窗管特效的扩展。

当前kwin提供了窗口特效框架，并且实现了用于美化窗口（ubreffect）或者实现窗口交互行为（presentwindow & desktopgrid）的扩展，本项目主要的研究内容为后者，我们会通过这个项目，逐步理解kwin特效扩展框架，掌握特效扩展的开发，最终结合实际需求，实现桌面/窗口交互特效。

这个项目挑战性较强，需要学生具备较强的代码分析能力和实际动手能力，最好对于c++/qt以及接口的设计模式有一定的了解，如果有接触过linux桌面开发或者窗口管理器项目的更佳。

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

兰悦

* github https://github.com/Yue-Lan
* email lanyue@kylinos.cn

陈楚南

* github https://github.com/kylin-ccn
* email chenchunan@kylinos.cn



### 难度

高等



### 特征

1. 兼容Ubuntu20.04版本运行

2. 满足x86_64、arm64等多架构支持

3. 使用Qt实现

4. 满足轻量化要求



### 文档

https://wiki.archlinux.org/index.php/window_manager

https://techbase.kde.org/Projects/KWin

https://blog.martin-graesslin.com/blog/2009/07/how-to-write-a-kwin-effect/

https://techbase.kde.org/Development/Tutorials/KWin/Scripting

### License

[GPL-3.0-only](https://opensource.org/licenses/GPL-3.0)



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题

熟悉现有插件项目，实现一个自己的外部mockup插件

### 第二题

基于这个插件，对窗口和屏幕进行特效处理（矩阵转换、纹理混成等）

### 第三题

实现“边缘滑动最小化窗口”、“任务栏拖曳动画”、“工作区切换动画”等特效

### 第四题

实现“触摸旋转单窗口”、“触摸旋转桌面”等高级特效，并对kwin进行性能调优