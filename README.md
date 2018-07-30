# css
## 右边固定宽度，左边自适应  
```javascript
<div class="wrap">
	<div class="left"></div>
	<div class="right"></div>
</div>
<style>
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
</style>
```
## opacity、rgba区别       
opacity子元素可以继承，rgba不能        