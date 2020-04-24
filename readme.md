---


---

<h1 id="correción-de-errores-get-bem-website">Correción de errores <a href="http://getbem.com/">Get Bem website</a></h1>
<h1 id="la-herramienta-utilizada-ha-sido-wave">La herramienta utilizada ha sido <a href="wave.weibaim.org"><strong><em>Wave</em></strong></a></h1>
<h2 id="x-errores">❌ Errores:</h2>
<h3 id="falta-texto-alternativo-en-imágenes">1. Falta texto alternativo en imágenes</h3>
<ul>
<li>Agregar el atributo alt</li>
</ul>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>img</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>xxx.jpg<span class="token punctuation">"</span></span>  <span class="token attr-name">alt</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>XXX<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<ul>
<li>Nº de ocurrencias: <strong>15</strong></li>
</ul>
<h3 id="falta-determinar-idioma">2. Falta determinar idioma</h3>
<ul>
<li>Agregar el atributo lang</li>
</ul>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>en<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<ul>
<li>Nº de ocurrencias: <strong>1</strong></li>
</ul>
<h2 id="warning-alertas">⚠️ Alertas:</h2>
<h3 id="faltan-etiquetas-semánticas">1. Faltan etiquetas semánticas</h3>
<ul>
<li>Agregar las etiquetas correspondientes</li>
</ul>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>header</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>header</span><span class="token punctuation">&gt;</span></span>, <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>nav</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>nav</span><span class="token punctuation">&gt;</span></span>, <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>main</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>main</span><span class="token punctuation">&gt;</span></span>, <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>footer</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>footer</span><span class="token punctuation">&gt;</span></span>, etc.
</code></pre>
<ul>
<li>Nº de ocurrencias: <strong>1</strong></li>
</ul>
<h3 id="faltan-un-encabezado-de-nivel-1">2. Faltan un encabezado de nivel 1</h3>
<ul>
<li>Agregar un h1</li>
</ul>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>XXX<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<ul>
<li>Nº de ocurrencias: <strong>1</strong></li>
</ul>
<h3 id="links-redundantes">3. Links redundantes</h3>
<ul>
<li>Varios links adyacentes van a la misma URL. De ser posible combinar los links</li>
<li>Nº de ocurrencias: <strong>3</strong></li>
</ul>
<h2 id="smiling_imp-trampas">😈 Trampas:</h2>
<ol>
<li><code>&lt;img src="/assets/b_.svg" alt="b_"&gt;</code></li>
</ol>

