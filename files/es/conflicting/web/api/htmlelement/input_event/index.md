---
title: GlobalEventHandlers.oninput
slug: conflicting/Web/API/HTMLElement/input_event
translation_of: Web/API/GlobalEventHandlers/oninput
original_slug: Web/API/GlobalEventHandlers/oninput
---
<div>{{ ApiRef("HTML DOM") }}</div>

<p>Un controlador de eventos para el evento input en la ventana. El evento input es llamado cuando el valor de un elemento {{ HTMLElement("input") }} ha cambiado. </p>

<p>Este evento se propaga. Si está soportado en la ventana, también estará soportado en elementos {{ HTMLElement("input") }}.</p>

<h2 id="Example" name="Example">Ejemplo</h2>

<pre class="brush: html">&lt;script&gt;

window.addEventListener('input', function (e) {
 console.log("Evento keyup detectado! proveniente de este elemento:", e.target);
}, false);

&lt;/script&gt;

&lt;input placeholder="Tipee aquí y vea la consola."&gt;
</pre>

<h2 id="Specification" name="Specification">Especificaciones</h2>

<p><a class="external" href="http://www.whatwg.org/specs/web-apps/current-work/multipage/common-input-element-attributes.html#event-input-input">HTML - APIs de elementos de entrada comunes (<code>input</code>)</a></p>

<h2 id="Compatibilidad_con_navegadores">Compatibilidad con navegadores</h2>

{{Compat("api.GlobalEventHandlers.oninput")}}

<h2 id="Vea_también">Vea también</h2>

<ul>
 <li><a class="external" href="http://blog.danielfriesen.name/2010/02/16/html5-browser-maze-oninput-support/">Un laberinto de navegadores HTML5, soporte para oninput</a></li>
 <li><a class="external" href="http://www.useragentman.com/blog/2011/05/12/fixing-oninput-in-ie9-using-html5widgets/">Corrigiendo oninput en IE con html5Widgets</a> incluye cobertura para IE6-8</li>
 <li>Mathias Bynens sugiere <a class="external" href="http://mathiasbynens.be/notes/oninput">enlazando a input y keydown</a></li>
 <li><a class="external" href="http://help.dottoro.com/ljhxklln.php">evento oninput | dottoro</a> posee notas acerca de bugs en IE9</li>
</ul>