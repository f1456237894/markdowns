# 代码

如果是段落上的一个函数或片段的代码可以用反引号把它包起来（**`**），例如：

```
`printf()` 函数
```

显示结果如下：

`printf()` 函数



## 代码区块

代码区块使用 **4 个空格**或者一个**制表符（Tab 键）**。

实例如下：

![MARKDOWN 代码区块](https://www.runoob.com/wp-content/uploads/2019/03/55EDFE05-5F27-458E-AFE0-7B96685C9603.jpg)

显示结果如下：

```
<?php
echo 'RUNOOB'
function test(){
	echo 'test'
}
```

如果你用的是typora，你可以遵照以下操作

1.选中`段落`选项

![image-20210524184709421](/Users/mac/Library/Application Support/typora-user-images/image-20210524184709421.png)

2.在下面的弹出栏中选择

![image-20210524184753727](/Users/mac/Library/Application Support/typora-user-images/image-20210524184753727.png)

完成

******

你也可以用 **```** 包裹一段代码，并指定一种语言（也可以不指定）：

```
​```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
​```
```

显示结果如下：

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```