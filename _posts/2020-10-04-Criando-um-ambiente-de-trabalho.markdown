---
layout: post
title:  "Criando um ambiente de trabalho"
subtitle: "Uma introdução ao VS Code"
date:   2020-10-04 01:00:05 -0300
categories: blog
author: João Rodrigo Olenscki
photourl: "{{'assets/images/html_image.jpg' | relative_url}}"
tags:
- vscode
- code
resumo: "Criar um ambiente de trabalho é o primeiro passo necessário para se iniciar um projeto em uma nova linguagem de programação. Neste post, explicamos como fazer isso para trabalhar com HTML!"

---

Em 2015 foi lançado pela Microsoft um editor de código destinado ao desenvolvimento de aplicações web chamado de Visual Studio Code, ou simplesmente VSCode. Anunciada durante o Build, evento voltado a desenvolvedores que ocorre nos Estados Unidos anualmente, trata-se de uma ferramenta leve e multiplataforma que está disponível tanto para Windows, quanto para Mac OS e Linux e atende a uma gama enorme de projetos, não apenas ASP.NET, como também Node.js. Adicionalmente, o editor possui suporte à sintaxe de diversas linguagens como Python, Ruby, C++.

Além de ser totalmente gratuito, ainda no segundo semestre do ano do lançamento, durante o evento Connect(), o editor foi anunciado como open source, tendo código disponibilizado no GitHub, o que permite à comunidade técnica contribuir com seu desenvolvimento e facilitando a criação de extensões e novas funcionalidades.

Veremos no decorrer do artigo os recursos oferecidos por essa ferramenta, abordando pontos relevantes referentes à utilização do IntelliSense, refatoração, depuração de código, versionamento de código com o Git, automação de tarefas com Gulp, dentre outros recursos. Para melhor compreender o editor e observar a viabilidade do seu uso em um ambiente de desenvolvimento multiplataforma, trabalharemos com um exemplo utilizando ASP.NET 5, versão mais recente do framework de desenvolvimento web do .NET e que é suportado também no Mac OS e Linux, sem dependência do Visual Studio.

Ao fim veremos como realizar o deploy da aplicação no Microsoft Azure, completando todo um ciclo básico de desenvolvimento de uma aplicação web, indo desde sua criação, configuração, até sua implantação em um servidor externo.

Instalando o Visual Studio Code
O primeiro passo para que possamos utilizar o Visual Studio Code, ou VS Code para os íntimos, é realizar a instalação do mesmo em nosso computador. O VS Code é multiplataforma, podendo ser utilizado a partir do Windows, Mac ou Linux. Nesse artigo veremos a instalação do VS Code no Windows.