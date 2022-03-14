# HomeworkWeek3Lrs
通信与计算机网络 3200102890

<!doctype html>
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no, width=device-width">
    <link rel="stylesheet" href="https://a.amap.com/jsapi_demos/static/demo-center/css/demo-center.css" />
    <title>LrsHomework</title>
    <style>
        html,
        body,
        #container {
            background-color: blanchedalmond;
            width: 80%;
            height: 80%;
            margin: auto;
            font-family: "微软雅黑";
            font-size: 20px;
            font-weight: bold;
            line-height: 1.5em;
        }
    </style>
</head>

<body>
    <img src="image.png" alt="家乡美食" width="400" height="300" style="margin-left: 100px; ;" />
    <br/>
    <a href="https://baike.baidu.com/item/%E5%A4%A7%E5%90%8C/9011" style="color: brown;text-align: center;margin-left: 100px">家乡介绍</a>
    <div id="container"></div>
    <!-- 加载地图JSAPI脚本 -->
    <script src="https://webapi.amap.com/maps?v=1.4.15&key=945036ac2fc29c93f09bdd90f86a4c62"></script>
    <script>
        var map = new AMap.Map('container', {
            resizeEnable: true, //是否监控地图容器尺寸变化
            zoom: 15, //初始化地图层级
            center: [113.155112, 40.006354] //初始化地图中心点
        });
    </script>

</body>

</html>
