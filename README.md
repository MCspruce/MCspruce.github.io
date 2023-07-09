# 我的世界基岩版 JSON-UI 教程
欢迎来到这里编辑项目，不过编辑前请阅读下面的内容！

## 编辑须知
> 编辑的内容(以下称"内容")必须按照以下规定编辑
<br>
- 内容不能包含攻击性、涉及其他无关Minecraft UI内容
<br>- 内容不能包含第三方群聊二维码、群聊号、个人QQ
<br>- 内容不能包含钓鱼、诈骗、勒索链接
<br>- 内容不能包含付费内容
<br>- 内容不能包含涉黄、涉政、造谣、诽谤图片
<br>- 提交更改的内容需要在"修改描述"中提到**修改的地方**
<br>- 内容中的属性未验证是否正确请在明显处标明**需要验证**
<br>- 内容中的属性在新版本已失效请在明显处标明**xxx版本已失效**
<br>- 内容中的属性需要在新版本有效请在明显处标明**需要xxx版本**

## 如何编辑
>需要一定的html语法知识
>如需详细教程请转到搜索引擎搜索"如何在github修改项目内容"
<br>1. 点击项目中其中的一个文件
<br>2. 点击右上角的铅笔按钮
<br>3. 修改其中的内容(可以将内容下载到本地以方便修改)
<br>4. 修改完成后，点击下面的绿色(提交更改)按钮
<br>5. 修改完成，等待作者的审核

## html新元素

### 链接
```
<a class="link" href="这里写跳转的链接">链接文字</a>
```

### 标题
```
<h2>段落标题</h2>
```

### 提示
```
<tip>
    <b>提示</b>
    <br>提示内容
</tip>
```

### 警告
```
<warn>
    <b>警告</b>
    <br>提示内容
</warn>
```

### 表格
```
<table>
  <thead><tr><th>属性名</th><th>值</th><th>介绍</th></tr></thead>
  <tbody><tr><td>XXX</td><td>字符串</td><td>...</td></tr>
  <tr><td>XXX</td><td>布尔值</td><td>...</td></tr>
</table>
```


### 代码块
```
<c>"控件": {
  // 这个是示例代码，请自行更改
  "test": "aaa"
}</c>
```


### 代码块 [代码块顶部标题]
```
<c title="代码块顶部标题">"控件": {
  // 这个是示例代码，请自行更改
  "test": "aaa"
}</c>
```
