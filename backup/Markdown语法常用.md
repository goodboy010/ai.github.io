# 常用语法
```
1. 标题
在句首插入 #表示标题，有六种标题。也就是最多可以有 6 个 #号表示最小字号的标题

2. 列表
有序列表 数字加英文的点 如 1. 2. 3.
无序列表 *+- 这三个任意一种后面文本接空格

3. 引用块
在引用块的句首加 >
嵌套引用需要缩进，例如第一层嵌套用 >>

4. 代码块
使用 ``` 进行代码块引用 可以接对应的代码语言名，例如 JS、CSS 等，Markdown 会自行使用对应的背景渲染。
行内引用 可以用两个 `` 进行包裹
代码（Code）: `代码code`

5. 链接
超链接 [A](网址 "optional title")
链接（Link）：[title](https://www.example.com)

图片链接 ![A](网址/地址 可选标题) 地址也可以用本地路径，可以在 markdown 文件夹建一个 picture 文件夹，可选的标题在鼠标悬停图片上会显示，可不写。
图片链接（Image）：！[title](https://www.example.com)

6. 强调
在字两边加一个 * 为斜体
在字两边加两个 ** 为粗体
在字两边加三个 *** 为 粗斜体 记得不要有与字之间有空格

7. 分割线
连续三个或以上星号或下划线或减号 都可以生成一个分割线
---
***
___

8. 反斜杠
Markdown 支持将大部分符号前面加上反斜杠来帮助插入普通的符号

9. 居中居右居左
居中<center>文本</center>
居右<p align="right">文本</p>
居左<p align="left">文本</p>

10. 换行
</br> 或两个或以上空格
```
# 进阶语法

```
1. 表格
使用 | 分隔不同的单元格，使用 - 分隔表头与其它行
右对齐 ——: ，左对齐 :—— 居中对齐:—:，默认为居中对齐 ——
示例：
| 第一列 | 第二列 | 第三列 |
| :----- | :----: | -----: |
| B      |   A    |      C |
注意：冒号一定要在英文状态下打，不然识别不了。- 数量不限定，可以一个也可以多个。

2. 字体字号和颜色
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#0099ff size=6 face="黑体">color=#0099ff size=6 face="黑体"</font>
<font color=#00ffff size=6>color=#00ffff</font>
<font color=gray size=6>color=gray</font>
Size：规定文本的尺寸大小。可能的值：从 1 到 7 的数字。浏览器默认值是 3 。颜色是按十六进制颜色值来的。常用的红色（#FF0000）金色（#FFD700）黄色（#FFFF00）

3.图片居中
居中，在图片引用上一栏加 <div alighn=center>
改变图片大小 <img src="./xxx.png 路径" width = "300" height = "200" alt="图片名称" /> 可能会导致图变形，用的少

4.待办事宜
* [x] 男
* [ ] 女
通过方括号内加入 X 来区别已办未办，注意方括号也要有空格。
```
# 冷门用法

```
1. 删除线
使用～～将要删除文字夹起来。表示删除

2. 注脚
使用 [^footer] 表示注脚，注意一个引用要写两次。如下

玫瑰是什么颜色 [^1]
[^1]: 玫瑰是红的。

玫瑰是什么颜色 [^2]
[^2]: 玫瑰是红的。

3. 页内跳转
使用 html 代码实现页内跳转。
在要跳转到的位置定义个锚 <span id = "jump">target</span>，
然后使用 [target](#jump) 将 target 设置为一单击即跳转到锚点所在位置的效果

4. LateX 公式
行内公式：使用两个”$” 符号引用公式: $公式$
行间公式：使用两对 “$$” 符号引用公式： $$公式$$

5.首行缩进
半方大的空白 &ensp; 或 &#8194;【常用】
全方大的空白 &emsp; 或 &#8195;
不断行的空白格 &nbsp; 或 &#160;

6. 视频嵌套
<video id="video" controls="" preload="none" poster="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.jpg">
  <source id="mp4" src="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.mp4" type="video/mp4">
</video>

7. 音频嵌套
<audio id="audio" controls="" preload="none">
  <source id="mp3" src="http://oht4nlntk.bkt.clouddn.com/Music_iP%E8%B5%B5%E9%9C%B2%20-%20%E7%A6%BB%E6%AD%8C%20%28Live%29.mp3">
</audio>
```

# 总结

基本用法能解决大部分情景，高阶用法一般和 HTML 语法整合的多，但是用的少。如果想更好的进阶可以学习一下 HTML 语法。一个原则，常用的要能熟练内化为自己的潜意识，少用的要收录起来需要时可以最短时间内进行查阅。

[点这里查看Markdown官网教程](https://markdown.com.cn/)