<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
</head>
<body>
	<h1>2018想去的地方-地图标记</h1>
	<hr>
        <h2>多次在输入框输入不同地址，实现在地图上多点标记</h2>
	<h3>要求</h3>
	<div>1.申请百度地图开发api</div>
	<br>
	<div>2.json异步加载数据，获取经纬度 </div>
	<br>
	<div>3.Echarts绘图在地图上做标记</div>
	<br>
	<div>4.使用Bootstrap框架，栅格系统实现适配 </div>
	<br>
	<h3>项目流程</h3>
	<div>前端输入地点/前端渲染->动态更新数据</div>
	<div>->百度地图api获取经纬度</div>
	<h3>Step by Step</h3>
	<h4>First</h4>
	<div>初始化文件</div>
	<div>引入Bootstrap，jQuery和echarts</div>
	<h4>Second</h4>
	<div>准备好html内容</div>
	<div>准备好输入框和echarts容器</div>
	<h4>Third</h4>
	<div>申请百度开发者密钥ak</div>
	<div>研究geocoder接口使用</div>
	<div>绑定事件，用户可以跨越百度接口获取经纬度信息</div>
	<h4>Fourth</h4>
	<div>根据获取经纬度数据，地图标记</div>
	<div>渲染地图</div>
	<h4>Fifth</h4>
	<div>持续标记</div>
	<div>加上导出图片功能</div>

</body>
</html>
