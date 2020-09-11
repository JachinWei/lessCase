## lessCase

收集关于less的资料

## 参考资料

[官网链接](https://less.bootcss.com/)

## less模块

### 安装

yarn global add less

### less转css

lessc [option option=parameter ...] <source> [destination]

> cd less
>
> lessc my.less my.css

## less不同场景用法

### html

```html
<!-- add less.js into html, required -->
<script src="less.js" type="text/javascript"></script>

<!-- add your less file into html -->
<link rel="stylesheet/less" type="text/css" href="styles.less" />
```