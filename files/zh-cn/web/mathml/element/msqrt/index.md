---
title: <msqrt>
slug: Web/MathML/Element/msqrt
translation_of: Web/MathML/Element/msqrt
---
<div>{{MathMLRef}}</div>

<p>MathML<code><strong>&lt;msqrt&gt;</strong></code>元素用于表示一个平方根（不显示根指数）。它只接受一个参数，语法如下：<code><strong>&lt;msqrt&gt; base &lt;/msqrt&gt;</strong></code>。</p>

<h2 id="属性">属性</h2>

<dl>
 <dt>class, id, style</dt>
 <dd>供<a href="/en-US/docs/CSS">样式表</a>使用。</dd>
 <dt>href</dt>
 <dd>用来设置标签点击后跳转的链接</dd>
 <dt>mathbackground</dt>
 <dd>用来设置标签的背景色，可以使用<code><strong>#rgb</strong></code>、<strong><code>#rrggbb</code></strong>或者<a href="/zh-CN/docs/Web/CSS/color_value">HTML 颜色名</a>。</dd>
 <dt>mathcolor</dt>
 <dd>用来设置文字（包括根底数、根指数和根号本身）的颜色，同样可以使用<code><strong>#rgb</strong></code>、<strong><code>#rrggbb</code></strong>或者<a href="/zh-CN/docs/Web/CSS/color_value">HTML 颜色名</a>。</dd>
</dl>

<h2 id="例子">例子</h2>

<p>下述代码表示： <img alt="root-x" src="/files/3201/msqrt.png" style="margin-left: 10px; vertical-align: middle;"></p>

<p>您的浏览器的渲染结果： <math> <msqrt> <mi>x</mi> </msqrt> </math></p>

<pre class="brush: html">&lt;math&gt;

  &lt;msqrt&gt;
    &lt;mi&gt;x&lt;/mi&gt;
  &lt;/msqrt&gt;

&lt;/math&gt;
</pre>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

{{Compat}}

<h2 id="相关链接">相关链接</h2>

<ul>
 <li>{{ MathMLElement("mroot") }} (Radical with an index)</li>
</ul>