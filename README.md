# CSS
1、word-wrap:break-word;
在长单词或 URL 地址内部进行换行。内容将在边界内换行，仅用于块对象，内联对象要用的话，必须要设定height、width或display:block或position:absolute。

>注：word-wrap 属性原本属于微软的一个私有属性，在 CSS3 现在的文本规范草案中已经被重名为 overflow-wrap 。 word-wrap 现在被当作 overflow-wrap 的 “别名”。 稳定的谷歌 Chrome 和 Opera 浏览器版本支持这种新语法。

2、word-break:break-all;
用于处理单词折断。

有些情况下使用word-wrap:break-word;会出现不可预期的情况。 就是当一个英文单词的长度超过了父级容器长度是，英文单词还是会显示一整个单词而导致超出容器范围。还有的情况是，当遇到一个单词很长时，次单词自动换行，也会使上一行空出很多空间浪费了。

在这种情况下，IE创造出一种新的属性，word-break:break-all; 它强制文字换行无论一句话到达父级容器宽度的时候是不是一整个单词，都会强制换行，使单词断句，如果碰上一个单词超出父级容器宽度，会使单词断开并换行。

3、white-space:nowrap;
用于处理元素内的空白，只在一行内显示。
文本不会换行，文本会在在同一行上继续，直到遇到 <br> 标签为止。

4、overflow:hidden;
超出边界的部分隐藏。

5、text-overflow:ellipsis;
超出部分显示省略号。
