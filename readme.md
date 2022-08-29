# 我的世界基岩版 JSON-UI 教程
欢迎来到这里编辑项目，不过编辑前请阅读下面的内容！

## 编辑须知
> 编辑的内容(以下称"内容")必须按照以下规定编辑
<br>
* 内容不能包含攻击性、涉及其他无关Minecraft UI内容
* 内容不能包含第三方群聊二维码、群聊号、个人QQ
* 内容不能包含钓鱼、诈骗、勒索链接
* 内容不能包含付费内容
* 内容不能包含涉黄、涉政、造谣、诽谤图片
* 提交更改的内容需要在"修改描述"中提到**修改的地方**
* 内容中的属性未验证是否正确请在明显处标明**需要验证**
* 内容中的属性在新版本已失效请在明显处标明**xxx版本已失效**
* 内容中的属性需要在新版本有效请在明显处标明**需要xxx版本**

## 如何编辑
>需要一定的html语法知识
>如需详细教程请转到搜索引擎搜索"如何在github修改项目内容"
<br>1. 点击项目中其中的一个文件
<br>2. 点击右上角的铅笔按钮
<br>3. 修改其中的内容(可以将内容下载到本地以方便修改)
<br>4. 修改完成后，点击下面的绿色(提交更改)按钮
<br>5. 修改完成，等待作者的审核

## 为html添加元素
属性中的中文可以改，可以按照自己需求添加！

### 链接
```
<a class="list-link" href="这里写跳转的链接">链接文字</a>
```

### 标题
```
<br><span class="title wow fadeInLeftBig" data-wow-delay="1.5s">段落标题</span>
<hr class="title-hr wow fadeInLeftBig" data-wow-delay="1.5s"></hr>
```

### 提示
```
<div class="tip wow bounceInLeft" data-wow-delay="0.8s">
    <div class="tip-text">
        <b>提示标题</b>
        <br>提示内容
    </div>
</div>
```

### 提示
```
<div class="tip wow bounceInLeft" data-wow-delay="0.8s">
    <div class="tip-text">
        <b>提示标题</b>
        <br>提示内容
    </div>
</div>
```

### 标明内容
```
<span class="panel wow bounceInLeft" data-wow-delay="1.2s">标明内容</span>
```

### 表格
```
<table border="1" class="wow bounceInLeft" data-wow-delay="0.8s">
  <caption>表格标题</caption>
  <thead><tr><th>属性名</th><th>值</th><th>介绍</th></tr></thead>
  <tbody><tr><td>XXX</td><td>字符串</td><td>...</td></tr>
  <tr><td>XXX</td><td>布尔值</td><td>...</td></tr>
</table>
```

### 控件属性解释框
```
<div class="panel wow bounceInLeft" data-wow-delay="1.2s">
    <p><strong>属性名称</strong> <a class="panel c1-yellow c-gray" style="font-size: 10px;">属性简介</a></p>
    <p>值：字符串/布尔值/数字/数组/对象
    <p>默认值：XXX
        <br>属性的详细介绍
    </p>
</div>
```

### 无行号的高亮代码框
```
<pre><code class="hljs json">
JSON代码内容
</code></pre>
```

### 带行号和复制按钮的高亮代码框
这里有几处需要改
<br>cid_1 改成 cid_XXX(任意数字)
<br>代码中的换行都必须改为</li><li>
<br>
```
<a class="edit-btn" data-wow-delay="0.5s" href="https://github.com/MCspruce/MCspruce.github.io">在 github 上编辑</a></div>
<!--代码框-->
<ul class="code wow bounceInLeft">
    <li>
        <div style="width: 100%;">
            <span style="font-size: 15px;color: #313131;bottom: 5px;">RP/ui/start_screen.json</span>
            <button class="copy-btn wow shake" onclick="copy_code('cid_1')" style="float: right;color: #424242;">
                <ul style="list-style-type: none;padding: 0;margin:0;overflow:hidden;">
                    <li style="float: left;">复制</li>
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 25 25" wdith="22" height="22" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z">
                        </path>
                    </svg>
                </ul>
            </button>
        </div>
    </li>
    <!--下面是存放代码的-->
    <li>
        <pre class="wow fadeInRightBig" data-wow-delay="0.5s"><code id="cid_1" class="json"><ul><li>这里存放你的代码</li></ul></code></pre>
    </li>
</ul>
```