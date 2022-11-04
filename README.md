## 介绍
### 特点

Consistent主题修改自官方主题，主要有以下特点，前排提示佛系更新

1. 4in1，即一个主题可以在**移动端、桌面端、明亮模式、黑暗模式**中同时使用，在移动端按钮增大，更方便触摸

2. 强调阅读的一致性，将引用、超链接、标签设置为相近但不同的样式

3. 引入其他主题常用的编辑功能，如列表转导图、高亮转挖空

4. 增加标题、折叠的区分度，优化双链查看体验

5. 尽量减少体积和js代码，提高加载速度

### 预览

**桌面端效果：**

最新更新预览：

双链查看，面包屑等体验改进
![弹出面包屑2.gif](https://s2.loli.net/2022/11/04/Hfpg46uqvwXkItV.gif)

![image.png](https://s2.loli.net/2022/11/04/Es78VXtQWuH4MlJ.png)

其他效果：

![image.png](https://s2.loli.net/2022/11/02/UFECJioyNgSMnO7.png)

![image.png](https://s2.loli.net/2022/11/02/DymkaMZN2YtgBsv.png)



**手机端效果：**

增大相关触摸面积：

![image](https://user-images.githubusercontent.com/64324088/198844829-deb7def5-f22d-4257-9e0f-5365f4c9ec18.png)

通用菜单过长可滚动，不用收起键盘：

![image](https://user-images.githubusercontent.com/64324088/198844879-33398c1f-9d68-43b4-84b8-d783be663366.png)

编辑工具条，浮动工具条增宽：

![image](https://user-images.githubusercontent.com/64324088/198844913-0a22d5ac-37cc-459f-8c5f-dce6befdb663.png)


### 手机安装主题方法

手机端目前无法直接访问集市，请按以下步骤安装：

1. 在手机端`关于`中开启网络伺服

2. 在另外一台电脑浏览器中，根据提示访问手机端伺服的网址，一般为`http://192.168.1.x:6806`

3. 一般打开的就是桌面版界面，此时可以从集市下载主题，回到手机端在`外观`中选择即可

4. 其他方法：若不方便使用电脑，也可以在手机浏览器中打开伺服网址。等网页加载完毕，在网址中，手动将`mobile`更改为`desktop`并重新加载，即可访问桌面版样式的界面（此时横屏更方便操作）

### 鸣谢：

1. js代码、列表转导图等功能来自[royc01/notion-theme](https://github.com/royc01/notion-theme)

2. 手机适配更新自[Oltermare/Ori-Light-for-Mobile](https://github.com/Oltermare/Ori-Light-for-Mobile)（手机适配过往更新）

---

## 版本

### 1.0.3:
* [X] 面包屑改造
  * [X] 第一个的面包屑（文章标题）改成蓝色（包括标题，方便在多个面包屑时区分）
  * [X] 嵌入块、弹出窗、反链面板：其他面包屑去除文字，**鼠标放上去时展开**
* [x] 反链面板样式
  * [X] 多个结果用阴影划分
* [X] 弹出窗
  * [X] 多个结果用阴影划分
  * [X] 取消设置按钮
* [X] 标签面板
  * [X] 取消设置按钮

### 1.0.2:

在段落前按钮弹出菜单，在`其他选项`中可以进行样式的切换

* [X] 折叠样式调整，适配手机小字体，背景颜色调整淡蓝色更加和谐#调整#
* [X] 标签-全局明显与下划线样式切换#js/按钮切换#
* [X] 网址图片-全局切换菜单选项#js/按钮切换#
* [X] 挖空-全局与局部的样式切换#js/按钮切换#

### 1.0.1:

* [X] 列表折叠样式取消`...`，更改为开头标志深灰色边框，标题、无序列表、有序和任务的样式不同
* [X] 标题折叠样式增加背景方框，调暗颜色与link一致
* [X] 标签修改颜色与link一致

### 1.0.0：

1. 手机端修改通用菜单样式，溢出屏幕时可以上下滚动，子菜单将在按钮位置打开，比之前的方式要更容易一些

2. 手机端编辑工具栏微调

3. 在菜单中可以将该段落的高亮与挖空效果切换

4. 在菜单中可以将标签更改为更明显的样式，但不能取消以及永久更改，退出程序之后将恢复原来的样式

5. 嵌入块有多个查询结果的，每个结果单独显示为淡灰色矩形背景，不再有分割线，仿类似logseq效果

6. 弹出窗口（如引用块）缩小宽度、使头部栏与背景色一致，方便放在一旁参考
