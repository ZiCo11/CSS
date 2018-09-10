# CSS
关于css学习中遇到的问题随记<br>
# BFC布局规则
1. 内部的Box会在垂直方向，一个接一个的放置<br>
2. Box垂直方向的距离由margin决定，属于同一个BFC的两个相邻的Box的margin会发生重叠<br>
3. 每个元素的margin box的左边，与包含border box的左边相接触（对于从左往右的格式化，否则相反），即使浮动也是如此<br>
4. BFC的区域不会与float box重叠<br>
5. BFC就是页面上的一个隔离的独立容器，容器里面的子元素不会影响到外面的元素，反之如此。<br>
6. 计算BFC的高度时，浮动元素也参与计算。
# 哪些元素会生成BFC
1. 根元素<br>
2. float属性不为none<br>
3. position为absolute或fixed<br>
4. display为inline-block,table-cell, table-caption. flex. inline-flex<br>
5. overflow不为visible 
