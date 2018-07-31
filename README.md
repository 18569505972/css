# css
## 右边固定宽度，左边自适应  
```javascript
<div class="wrap">
	<div class="left"></div>
	<div class="right"></div>
</div>
<style>
方法一：
.wrap{
	display: table;
	width: 100%;
}
.left{
	display: table-cell;
}
.right{
	display: table-cell;
	width: 100px;
}
方法二：
.wrap{
	display: flex;
	width: 100%;
}
.left{
	flex: 1;
}
.right{
	flex: none;
	width: 100px；
}
方法三:
.wrap{
	width: 100%;
}
.left{
	width: calc(100%-100px);
}
.right{
	width: 100px；
}
</style>
```
## opacity、rgba区别       
opacity子元素可以继承，rgba不能        