# 用法

```javascript
$('.nav').tabNav();
```

# HTML 结构

```html
<ul class="nav">
	<li><a href="#">item</a></li>
	<li>
		<a href="#">item</a>
		<ul class="sub-menu">
			<li><a href="#">sub-item</a></li>
			<li><a href="#">sub-item</a></li>
		</ul>
	</li>
</ul>
```

# 参数

* `subMenuClass` - 子菜单自定义类
* `activeClass` - 当前菜单自定义类
* `focusClass` - 当前焦点自定义类

# 说明

代码参考 [Keyboard-accessible navigation](https://sltaylor.co.uk/blog/keyboard-accessible-navigation)，非常感谢作者。
