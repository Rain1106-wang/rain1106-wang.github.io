---
layout: archive-taxonomies
type: tags
title: Tags
permalink: /tags/
---
<html>
<head>
	<meta charset="utf-8">
	<title>Bootstrap 实例 - 如何使用字形图标（Glyphicons）</title>
	<link rel="stylesheet" href="/css/bootstrap.min.css">
    <script src="/js/bootstrap.min.js"></script>
</head>
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