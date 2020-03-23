# 前端面试题集
## 原生JS
<p>1.基本的数据类型有哪几种,null是对象吗,基本数据类型和复杂数据类型存储有什么区别？</p>
<ul>
  <li>基本数据类型有6中，分别是 undefined,null,bool,string,number,symbol(ES6新增)</li>
  <li>null不是对象，虽然typeof的结果是object,但是它属于基本数据类型</li>
  <li>基本数据类型存储于栈内存，存储的是值</li>
  <li>复杂数据类型存储堆栈内存，地址(指向堆中的值)存储在栈内存</li>
</ul>

## CSS
<p>1.16种方法实现水平居中和垂直居中</p>
<p>水平居中</p>
<p>(1)若是行内元素，给其父元素设置text-align:center,即可实现行内元素水平居中</p>
<p>(2)若是块级元素，设置margin:0 auto</p>
<p>(3)若子元素包含 flot:left属性，为了让子元素水平居中，则可让父元素宽度设置为fit-content,并且配合margin</p>
/*
.parent{<br/>
  width:-moz-fit-content;<br/>
  width:-webkit-fit-content;<br/>
  width:fit-content;<br/>
  margin:0 auto;<br/>
}
*/
