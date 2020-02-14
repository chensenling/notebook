# 酷点
<font color="red">author:弥谈</font>
### 音/视频标签
音频：
``<audio></audio>``<br>
视频：`` <video></video>``<br>
属性：<br>
    <pre>
        autoplay //自动播放
        controls //显示控制栏
    </pre>
    such:
    
    <body>
        <audio   src="./mediea/你的名字.mp3"  autoplay controls  > </audio>
		<video src="mediea/G.E.M.邓紫棋%20-%20平凡天使.mp4"  autoplay controls ></video>
		<embed src="mediea/G.E.M.邓紫棋%20-%20平凡天使.mp4" autoplay></embed>
    </body>





---
## 圆角边框
 标签：`` <border></border>``<br>
 
 属性：``radius`` 可以设置四个至分别对应上、右、下、左。单位为像素。
 <br>
 such:
    
    <border style="border-radius:10px"></br>
    
    
----
## 设置透明背景
设置背景颜色，采用十六进制即：#000000-#ffffff。
在颜色后面跟上不透明度百分比，例如，不透明度20%，就可以写为``#ffffff20``

    background:#ffffff20;
    
---
## 设计图标 | 渐进色
+ 图标推荐使用网站：**font awesome 中文网** 字体图标网站。<br>
网址：http://www.fontawesome.com.cn/

 - 网站**webgradients**提供渐进色的配色方案。 
    网址：<https://webgradients.com/>
---
## map地图

map地图上的各个区域被划分，整体到局部，使用的是坐标系：（x,y）
<br>
![map](http://note.youdao.com/noteshare?id=9ca0b982217d1e0260e899b67163368b "map")
    
    <img src="" usemap="#test">
    <map id="test"> 
        <area shape="rect" coords="" href="http://baidu.com">
        
        <area shape="rect" coords="" href="http://alibaba.com">
        
    
    </map>
    
    
上面的代码解释
:   usemap="#test" 该属性通过**锚点**与下面的<map>标签建立了联系 ，**shape**属性说明area的形状，**coords**属性为划分的坐标点（x,y）、（b,c）。
---
## 表单常见属性
+ required // 用于提示输入框不能为空
+ placeholder // 框内内容默认提示内容,特点：不用删除
+ readonly // 只读属性，特点：不能修改
+ disabled //锁定，特点：不能修改&不能提交
+ size  // 设置输入框的大小
+ maxlength //最大长度，输入的字符小于设置的个数
+ autofocus // 自动聚焦 ，加强用户体验
+ autocomplete //自动完成， 账号不安全，通常设置为 off

---
## 单选框点击字符同样选中
    
    <input type="radio" name="sex" id="nv" value=0><lable for="nv"> 女</lable>
    
checked属性 ：被选中

---
## 下拉列表
    <select name="list">
        <option value="num1">num1</option>
        <option value="num2">num2</option>
        <option value="num3">num3</option>
        <option value="num4">num4</option>
    </select>
属性：selected 被选中

---

## 过渡效果
通过选择器的hover

    选择器{
        transition： // 交互效果，过渡效果的方式
    }
    选择器：hover{
        
    }
    
---
## Demo 太极图



---
## Demo红心

---

