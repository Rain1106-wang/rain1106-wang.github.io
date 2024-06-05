---
layout: page
title: About
permalink: /about/
---
<html>
<head>
	<meta charset="utf-8"> 
	<title>Bootstrap 实例 - 标题</title>
	<link rel="stylesheet" href="/css/bootstrap.min.css">  
	<script src="/js/bootstrap.min.js"></script>
</head>
<body>

<h1>Welcome !</h1>
<h2>It is absolutely gorgeous.</h2>
<h2>Have a nice day.</h2>
</body>
</html>

<html>
<head>
	<meta charset="utf-8"> 
	<title>Bootstrap 实例 - 基本的表格</title>
	<link rel="stylesheet" href="/css/bootstrap.min.css">
    <script src="/js/bootstrap.min.js"></script>
</head>
<body>

<table class="table">
	<caption>基本的表格布局</caption>
   <thead>
      <tr>
         <th>名称</th>
         <th>城市</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>Tanmay</td>
         <td>Bangalore</td>
      </tr>
      <tr>
         <td>Sachin</td>
         <td>Mumbai</td>
      </tr>
   </tbody>
</table>









<h2>模态框（Modal）插件方法</h2>
<!-- 按钮触发模态框 -->
<button class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
	开始演示模态框
</button>
<!-- 模态框（Modal） -->
<div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
	<div class="modal-dialog">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" 
						aria-hidden="true">×
				</button>
				<h4 class="modal-title" id="myModalLabel">
					模态框（Modal）标题
				</h4>
			</div>
			<div class="modal-body">
				按下 ESC 按钮退出。
			</div>
			<div class="modal-footer">
				<button type="button" class="btn btn-default" 
						data-dismiss="modal">关闭
				</button>
				<button type="button" class="btn btn-primary">
					提交更改
				</button>
			</div>
		</div><!-- /.modal-content -->
	</div><!-- /.modal-dialog -->
</div><!-- /.modal -->












</body>

<body>

<a class="btn btn-default" href="#" role="button">链接</a>
<button class="btn btn-default" type="submit">按钮</button>
<input class="btn btn-default" type="button" value="输入">
<input class="btn btn-default" type="submit" value="提交">
</body>




<body>
<div class="container">
  <h2>进度条设置文本内容</h2>
  <div class="progress">
    <div class="progress-bar" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width:70%">
      70%
    </div>
  </div>
</div>
</body>



<body>
<p>标签式的导航菜单</p>
<ul class="nav nav-tabs">
	<li class="active"><a href="#">Home</a></li>
	<li><a href="#">SVN</a></li>
	<li><a href="#">iOS</a></li>
	<li><a href="#">VB.Net</a></li>
	<li><a href="#">Java</a></li>
	<li><a href="#">PHP</a></li>
</ul>





</body>


<body>



<div class="container">
	<h2>图片</h2>
	              
	<img src="/logo.png" class="img-rounded" > 

</div>

<div class="jumbotron">
	<div class="container">
		<h1>欢迎登陆页面！</h1>
		<p>这是一个超大屏幕（Jumbotron）的实例。</p>
		<p><a class="btn btn-primary btn-lg" role="button">
			学习更多</a>
		</p>
	</div>
</div>


</body>
</html>

<html>
<head>
	<meta charset="utf-8"> 
	<title>Bootstrap 实例 - 一个简单的网页</title>
	<link rel="stylesheet" href="/css/bootstrap.min.css">
    <script src="/js/bootstrap.min.js"></script>
	<style>
    .fakeimg {
        height: 200px;
         background: #aaa;
    }
  </style>
</head>
<body>
<div class="jumbotron text-center" style="margin-bottom:0">
  <h1>我的第一个 Bootstrap 页面</h1>
  <p>重置浏览器窗口大小查看效果！</p> 
</div>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">网站名</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">主页</a></li>
        <li><a href="#">页面 2</a></li>
        <li><a href="#">页面 3</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <h2>关于我</h2>
      <h5>我的照片:</h5>
      <div class="fakeimg">这边插入图像</div>
      <p>关于我的介绍..</p>
      <h3>链接</h3>
      <p>描述文本。</p>
      <ul class="nav nav-pills nav-stacked">
        <li class="active"><a href="#">链接 1</a></li>
        <li><a href="#">链接 2</a></li>
        <li><a href="#">链接 3</a></li>
      </ul>
      <hr class="hidden-sm hidden-md hidden-lg">
    </div>
    <div class="col-sm-8">
      <h2>标题</h2>
      <h5>副标题</h5>
      <div class="fakeimg">图像</div>
      <p>一些文本..</p>
      <p>菜鸟教程，学的不仅是技术，更是梦想！！！菜鸟教程，学的不仅是技术，更是梦想！！！菜鸟教程，学的不仅是技术，更是梦想！！！</p>
      <br>
      <h2>标题</h2>
      <h5>副标题</h5>
      <div class="fakeimg">图像</div>
      <p>一些文本..</p>
      <p>菜鸟教程，学的不仅是技术，更是梦想！！！菜鸟教程，学的不仅是技术，更是梦想！！！菜鸟教程，学的不仅是技术，更是梦想！！！</p>
    </div>
  </div>
</div>

<div class="jumbotron text-center" style="margin-bottom:0">
  <p>底部内容</p>
</div>
</body>





<body>

<div class="dropdown">
	<button type="button" class="btn dropdown-toggle" id="dropdownMenu1" 
			data-toggle="dropdown">
		主题
		<span class="caret"></span>
	</button>
	<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
		<li role="presentation">
			<a role="menuitem" tabindex="-1" href="#">Java</a>
		</li>
		<li role="presentation">
			<a role="menuitem" tabindex="-1" href="#">数据挖掘</a>
		</li>
		<li role="presentation">
			<a role="menuitem" tabindex="-1" href="#">数据通信/网络</a>
		</li>
		<li role="presentation" class="divider"></li>
		<li role="presentation">
			<a role="menuitem" tabindex="-1" href="#">分离的链接</a>
		</li>
	</ul>
</div>





<p>
	<button type="button" class="btn btn-default">
		<span class="glyphicon glyphicon-sort-by-attributes"></span>
	</button>
	<button type="button" class="btn btn-default">
		<span class="glyphicon glyphicon-sort-by-attributes-alt"></span>
	</button>
	<button type="button" class="btn btn-default">
		<span class="glyphicon glyphicon-sort-by-order"></span>
	</button>
	<button type="button" class="btn btn-default">
		<span class="glyphicon glyphicon-sort-by-order-alt"></span>
	</button>
</p>
<button type="button" class="btn btn-default btn-lg">
	<span class="glyphicon glyphicon-user"></span> User
</button>
<button type="button" class="btn btn-default btn-sm">
	<span class="glyphicon glyphicon-user"></span> User
</button>
<button type="button" class="btn btn-default btn-xs">
	<span class="glyphicon glyphicon-user"></span> User
</button>


<div class="alert alert-success alert-dismissable">
	<button type="button" class="close" data-dismiss="alert"
			aria-hidden="true">
		&times;
	</button>
	成功！很好地完成了提交。
</div>






<form role="form">
	<div class="form-group">
		<label for="name">名称</label>
		<input type="text" class="form-control" id="name" 
			   placeholder="请输入名称">
	</div>
	<div class="form-group">
		<label for="inputfile">文件输入</label>
		<input type="file" id="inputfile">
		<p class="help-block">这里是块级帮助文本的实例。</p>
	</div>
	<div class="checkbox">
		<label>
			<input type="checkbox"> 请打勾
		</label>
	</div>
	<button type="submit" class="btn btn-default">提交</button>
</form>
	







</body>

</html>