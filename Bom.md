#####bom 获取元素宽高方式差异
---
```

	* 1.getComputedStyle/currentStyle/style
		*  获取的宽高不包括 边框和内边距
	
	* 2.offsetWidth/offsetHeight
		* 获取的宽高包括 边框和内边距
	* 3.getComputedStyle/currentStyle/offsetXXX
		*	只支持获取, 不支持设置
	* 4.style	
		*  可以获取, 也可以设置
	* 5.getComputedStyle/currentStyle/offsetXXX
		*  即可以获取行内,也可以获取外链和内联样式
	*  6.style
		*  只能获取行内样式
        