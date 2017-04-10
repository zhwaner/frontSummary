Flex是Flexible Box的缩写，意为"弹性布局"，用来为盒状模型提供最大的灵活性。

兼容：
display: -webkit-box;
display: -ms-flexbox;
display: -webkit-flex;
display: flex;

属性：
flex-direction: row(水平) | row-reverse | column（垂直） | column-reverse;
flex-wrap: nowrap(默认不换) | wrap | wrap-reverse(换，先写的在下面);
flex-flow: 上面两种的简写，默认值为row nowrap
justify-content: flex-start | flex-end | center | space-between | space-around(默认，主轴上对齐方式);
align-items: flex-start | flex-end | center | baseline | stretch(默认，交叉轴上对齐方式);
align-content: 


flex布局实例篇：http://www.ruanyifeng.com/blog/2015/07/flex-examples.html