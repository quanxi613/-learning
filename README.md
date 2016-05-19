# mobile-FE-learning
###移动端学习记录

基本的HTML文件结构

```
<!DOCTYPE HTML>
<html>
<head lang="zh-CN">
    <meta charset="UTF-8">
    <title>标题</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <!-- 设置初始缩放比例为1.0，使用设备宽度  -->
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0,user-scalable=no">
    <!-- 在iOS下开启全屏模式  -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <!-- 隐藏 Sarafi 状态栏  -->
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <link href="/static/css/your_css.css" rel="stylesheet"/>
</head>
<body>

<script src="/static/js/your_js.js"></script>
</body>
</html>
```
viewport content 参数：

- width viewport 宽度(数值/device-width)

- height viewport 高度(数值/device-height)

- initial-scale 初始缩放比例

- maximum-scale 最大缩放比例

- minimum-scale 最小缩放比例

- user-scalable 是否允许用户缩放(yes/no)

移动端开发的基础知识 参考 支付宝移动Web解决方案(http://am-team.github.io/amg/dev-exp-doc.html)


