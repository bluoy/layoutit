## 项目来源
本项目fork自:
>https://github.com/dodgepudding/bootout/

本项目支持bootrap3,官网地址:
>http://layoutit.com/cn

如果喜欢本项目，请于官网进行捐助(donate)
## 免责声明
本项目fork自github,原项目作者已经不再进行维护，笔者将对一些问题进行不定期维护。
请勿用于商业用途，如需用于商业用途，请与项目原作者交流，沟通。
**本项目仅作技术交流使用**

## 原版说明
基于bootstrap实现可视化布局的layoutit.com离线中文版  
新增功能:  
html5自动保存, 开启元素立即编辑模式, 增加撤销,重做跟踪操作功能, 加入ckeditor弹出编辑器.  
原版程序地址: http://www.layoutit.com/build  
demo演示地址: http://dodgepudding.github.io/layoutit  

使用说明
-----------
* 先从左侧`布局设置`选项卡拖动行列布局样式到右侧容器, 然后将基础组件拖到右侧容器内, 
通过拖动完成排布, 部分组件通过右上角浮动按钮提供样式切换, 你也可以点击组件内的文字部分启用即时编辑功能, 
如果鼠标左键触发了默认事件, 可以用右键点击触发编辑; 对于大篇幅文字内容, 
可选择组件右上角的`编辑`功能启用独立编辑框编辑.   
* 如果你的浏览器支持html5, 每一步操作都会被记录, 不担心浏览器关闭后信息丢失, 下一次打开将恢复上一次的编辑内容, 编辑过程中发现错误, 可通过`撤销`和`重做`进行还原. 
若是IE等不支持HTML5的用户希望保存临时编辑结果, 可选择顶部`源码`按钮, 把弹出框内的可再编辑源码复制下来, 自己保存成文件, 
下一次只需把文件中的可再编辑源码粘贴回`源码`弹出框的编辑框内, 点击保存后即可恢复之前的编辑状态. 
* 若然要生成干净的html代码, 可选择顶部的`生成`按钮功能, 并把生成的干净代码复制到目标文件. 生成的代码并不包含基础css和js, 你还需要引入jquery和bootstrap的css和js基础代码.    

详细的样式可参考以下网站:  
http://www.bootcss.com  bootstrap中文网站   
http://twitter.github.io/bootstrap bootstrap源网站   
http://jquery.com jquery基础框架   
