# css选择器

## 1.选择所有元素
选择器：*

## 2.根据类型选择元素
选择器：<元素类型>。比如

```
a{
	font-size:20px;
}

```
## 3.根据类选择元素
选择器: <类名> or <元素类型>.<类名>

```
.class-name{
	font-size:20px;
}

span.class-name{
	font-size:20px;
}

```

## 4.根据ID选择元素
选择器: #<id值>
```
.id-name{
	font-size:20px;
}

```
## 5.根据属性选择元素
选择器:[<条件>] 或则 <元素类型>[<条件>]

常用的有：
*	[attr]  选择定义attr属性的元素
*	[attr="val"] 
*	[attr^="val"] 
*	[attr$="val"] 
*	[attr*="val"] 
*	[attr~="val"] 
*	[attr|="val"] 	

## 6.并集选择器
选择器:<选择器>,<选择器>,<选择器>

```

a, span, h2{
	color:red;
}

```

## 7.后代选择器
选择器:<第一个选择器> <第二个选择器>

```
	p span{
	font-size:20px;
	}

```

## 8.选择子元素
选择器:<第一个选择器> > <第二个选择器>

```
	p > span{
	font-size:20px;
	}

```

## 9.选择兄弟元素
*	选择器:<第一个选择器> + <第二个选择器>

```
	p + span{
	font-size:20px;
	}

```

*	选择器:<第一个选择器> ~ <第二个选择器>

```
	p ~ span{
	font-size:20px;
	}

```

## 10.::first-line 选择器

```
::first-line{
	background-color:red;
}

```

## 11.::first-letter 选择器

```
::first-letter{
	background-color:red;
}

```

## 12.:before选择器

```
:before{
	content:"i am before";
}

```

## 13.:after选择器

```
:after{
	content:"i am after";
}

```

## 14.子元素选择器
*	:fist-child
*	:last-child
*	:only-child
*	:only-of-type

*   :nth-child(n)
*   :nth-last-child(n)
*   :nth-of-type(n)
*   :nth-last-of-type(n)

## 15.UI伪类选择器
*	:enabled
*	:disabled
*	:checked
*	:default
*	:valid
*	:invalid
*	:in-range
*	:out-of-range
*	:required

## 16.动态伪类选择器
*	:link
*	:visited
*	:hover
*	:active
*	:focus

## 17.否定选择器
:not(<选择器>)  

非常实用但是常常被忽略的一种选择器


## 18.:empty选择器
匹配没有定义任何子元素的元素。

## 19. :target选择器



