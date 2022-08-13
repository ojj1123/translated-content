---
title: Age
slug: Web/HTTP/Headers/Age
tags:
  - 响应头
  - 缓存
  - 首部
translation_of: Web/HTTP/Headers/Age
---
<div>{{HTTPSidebar}}</div>

<p><code><strong>Age</strong></code> 消息头里包含对象在缓存代理中存贮的时长，以秒为单位。.</p>

<p>Age 的值通常接近于 0。表示此对象刚刚从原始服务器获取不久；其他的值则是表示代理服务器当前的系统时间与此应答中的通用头 {{HTTPHeader("Date")}} 的值之差。</p>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row">报头类型</th>
   <td>{{Glossary("Response header")}}</td>
  </tr>
  <tr>
   <th scope="row">{{Glossary("Forbidden header name")}}</th>
   <td>no</td>
  </tr>
 </tbody>
</table>

<h2 id="语法">语法</h2>

<pre class="syntaxbox">Age: &lt;delta-seconds&gt;
</pre>

<h2 id="指令">指令</h2>

<dl>
 <dt>&lt;delta-seconds&gt;</dt>
 <dd>
 <p>一个非负整数，表示对象在缓存代理服务器中存贮的时长，以秒为单位。</p>
 </dd>
</dl>

<h2 id="示例">示例</h2>

<pre>Age: 24</pre>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

<p>{{Compat}}</p>

<h2 id="参见">参见</h2>

<ul>
 <li>{{HTTPHeader("Cache-Control")}}</li>
 <li>{{HTTPHeader("Expires")}}</li>
</ul>