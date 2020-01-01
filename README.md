# 第一天

### 页面导入样式时，使用link和@import有什么区别？

区别：
1.link是HTML标签，@import是css提供的。
2.link引入的样式页面加载时同时加载，@import引入的样式需等页面加载完成后再加载。
3.link没有兼容性问题，@import不兼容ie5以下。
4.link可以通过js操作DOM动态引入样式表改变样式，而@import不可以

### CSS盒模型

标准(W3C)盒子模型：内容content+填充padding+边框border+边界margin
低版本IE盒子模型：内容（content+padding+border）+ 边界margin

### js原始数据类型有哪些？

boolean null undefined number string symbol bigint