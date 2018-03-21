---
layout: post
title: Facilitando a criação de construtores com ReSharper
date:   2017-05-15 22:46:00 -0600
categories: resharper, snippets, produtividade, quick post
excerpt_separator: <!--more-->

---

Esse post é uma cortesia do [ReSharper](https://www.jetbrains.com/resharper/). Não, isso não é um post patrocinado. Estou falando de um snippet que ele introduz no Visual Studio: `ctorf`.

<!--more-->

Se você está trabalhando com injeção de dependência, esse snippet vai te poupar um bocado de digitação.

Ele funciona assim: escreva a estrutura da sua classe, adicione os campos privados com as dependências que você quer injetar via construtor, digite `ctorf + tab` e voilá: temos um novo construtor já inicializando todos os nossos campos privados.

Até criei um gif para ilustrar o funcionamento:

[<img src="/images/ctorf_em_acao.gif" alt="Ctorf em ação!"/>]({{ site.baseurl }}/)

Bonito, não é? Esse é um ótimo argumento para convencer aquele seu colega que ainda é cético em relação ao ReSharper.