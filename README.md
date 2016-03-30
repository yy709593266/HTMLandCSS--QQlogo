# HTMLandCSS--QQlogo
使用纯html和css实现QQ企鹅logo，熟练应用css3新属性-圆角属性来实现不同的形状
特别是border-top-left-radius等一个角的圆角属性的应用，设置一个边的边框并对该边的一个角进行垂直和水平方向的圆角属性的添加可以得到scarf
上的shadow
例如嘴角三角形的绘制：
一个div的hight=0时候就会是上下左右各一个三角形，如果将
border-left:none;
border-right:xxpx solid #xxx;
border-bottom:xxpx solid transparent;
border-top:xxpx solid transparent;
就可以得到一个后边的三角形，上下border必须设置，因为该属性表现了三角形上下两个角的角度，因为每个border边都是由一个矩形和两边的三角形组成，如果这里的上下border不设置，右边的border就只有矩形区域没有两边的三角形区域了就得不到三角形。
