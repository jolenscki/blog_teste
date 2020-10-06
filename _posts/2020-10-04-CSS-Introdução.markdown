---
layout: post
title:  "CSS: Introdução"
subtitle: "Aprenda a usar esta importante ferramenta"
date:   2020-10-04 01:00:05 -0300
categories: blog
author: João Rodrigo Olenscki
photourl: 'assets/images/css_banner.webp'
tags:
- css
- html
- code
resumo: "Como fazer para deixar meu HTML mais bonito? Colocar cores, efeitos, cards? A resposta para todas estas perguntas é: CSS!"
---

<h2>Definindo o estilo com CSS (Cascading Style Sheets)</h2>

<p>Como mencionado anteriormente, e reforçado algumas vezes, os arquivos HTML não
contêm elementos presentacionais. Esta responsabilidade é terceirizada para os arquivos
CSS, que descrevem de forma declarativa os atributos de apresentação de cada elemento
HTML.</p>
<p>Os browsers já possuem um estilo padrão, como vimos, para algumas tags HTML.
O sistema de CSS funciona de modo que novas definições de estilo sobrepõem as antigas,
daí o nome “Cascading”, inclusive para as definições padrões. Assim, para cada regra,
podemos decidir por sobrescrever apenas algumas propriedades, mantendo parte do estilo
anterior.
 </p>

 <h3>Utilizando CSS: em linha (evite!), interno (às vezes) e externo (preferível)</h3>

 <p>Vamos modificar a cor do nosso título &lt;h1&gt; para vermelho. Existem três formas de especificar essa regra de estilo. O primeiro consiste em adicionar diretamente no elemento: </p>

<pre class="prettyprint">
    <code class="lang-html">
        &lt;h1 style="color:red"&gt; Título nível 1 &lt;/h1&gt;
    </code>
</pre>

<p>Outra opção é inserir as regras no cabeçalho do documento HTML:</p>

<pre class="prettyprint">
    <code class="lang-html">
        &lt;head&gt;
            ...
            &lt;style&gt;
                h1{
                color: red ;
                }
            &lt;/style&gt;
        &lt;/head&gt;
    </code>
</pre>

