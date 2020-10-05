---
layout: post
title:  "Iniciando em HTML"
subtitle: "Como começar?"
date:   2020-10-04 01:00:05 -0300
categories: blog
author: João Rodrigo Olenscki
photourl: 'assets/images/html_image.png'
tags:
- jekyll
- html
- css
resumo: "HTML é a base de todo desenvolvimento web. Para iniciar qualquer coisa nesta área, é necessário aprender e dominar esta linguagem."
---

<h2> HTML (HyperText Markup Language)
</h2>

<p>
A linguagem HTML serve apenas para descrever a estrutura do texto e seu conteúdo.
Ela não é uma linguagem de programação propriamente dita – não possui variáveis
nem controle de lógica. De um modo simplificado, HTML se assemelha mais a uma
linguagem para descrever documentos de texto estruturado, como Word ou Latex, mas
sem especificações de formatação (fonte, cor) ou layout/posicionamento.
Por exemplo, nesta apostila, o texto é estruturado em capítulos: o primeiro possui
o título de instalação, o segundo de HTML, assim por diante. Cada capítulo possui seções
e subseções: 1.1, 1.1.1, 1.2, 1.3, 2,1, etc. Uma versão em HTML desta apostila deve refletir
esta estrutura, além de especificar algum outros elementos e sua hierarquia.
</p>

<h3>A estrutura de uma página HTML</h3>
<p>
Antes de incrementar o nosso exemplo “Olá mundo”, vamos tentar compreender o
básico da estrutura do arquivo HTML que criamos. Relembrando, o arquivo criado tinha
mais ou menos o seguinte conteúdo:
</p>
<br>

<pre class="prettyprint">
    <code class="lang-html">
        &lt;!DOCTYPE html&gt;
        &lt;html lang ="pt-br"&gt;
            &lt;head&gt;
                &lt;meta charset ="UTF-8"&gt;
                &lt;meta name="viewport" content="width=device-width, initial-scale
                =1.0"&gt;
                &lt;title&gt; Nossa primeira página HTML válida &lt;/title&gt;
            &lt;/head&gt;
            &lt;body&gt;
                Olá Mundo
            &lt;/body&gt;
        &lt;/html&gt;
    </code>
</pre>

<p>
Apenas analisando este código, você já deve ter inferido bastante coisa sobre
a linguagem HTML. Primeiro, a tabulação (que não é obrigatória) dá a indicação da
hierarquia do documento, que pode ser esquematizada como:
</p>

<pre class="prettyprint">
    <code class="lang-html">
        html
        | head
        | | title
        | | endtitle
        | endhead
        | body
        | endbody
        endhtml
    </code>
</pre>

A partir dessa observação, também notamos que cada “seção” começa com algo do
formato &lt;algo&gt; e termina com &lt;/algo&gt;. Essas são chamadas de markup tags de abertura
e fechamento, respectivamente. Também existem tags que não precisam ser fechadas, como
as tags meta do head. Além disso, as tags podem ter atributos, como o markup meta.
O conteúdo a ser exibido está contido dentro do body, como o texto Olá mundo do
exemplo. O head contém o título da página (que é exibido na aba do browser), e outras
informações, como a codificação dos caracteres e largura da tela (para facilitar o design
responsivo). Mais tarde veremos que podemos especificar no head arquivos relacionados à
página, como arquivos CSS ou scripts Javascript. Por fim, faltou apenas falar do &lt;!DOCTYPE
html&gt;, que é responsável por indicar qual versão HTML estamos lidando, que no caso é a
HTML 5.

