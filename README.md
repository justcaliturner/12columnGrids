### 12列响应式栅格系统

支持PC、mobile全平台响应式布局，使用简单、轻便



### 使用说明



##### 1、引入css文件

```html
<link rel="stylesheet" href="./main.css">
```



##### 2、DOM结构

```html
<div class="container">
	<div class="row">
		<div class="col-lg-1 col-md-2 col-sm-6"></div>
		<div class="col-lg-1 col-md-2 col-sm-6"></div>
	</div>
</div>
```



##### 3、嵌套应用

```html
<div class="container">
	<div class="row">
		<div class="col-lg-1 col-md-2 col-sm-6">
        	<div class="col-lg-1 col-md-1 col-sm-1"></div>
			<div class="col-lg-1 col-md-1 col-sm-1"></div>
        </div>
	</div>
</div>
```



##### 响应式说明：

- **宽屏**：最小宽度1080px，class前缀："col-lg-x"
- **中屏**：最小宽度768px，最大宽度1079px，class前缀："col-md-x"
- **窄屏**：最大宽度767px，class前缀："col-sm-x"