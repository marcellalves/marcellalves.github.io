---
layout: post
title: Pequeno demais para falhar
date:   2017-06-26 21:50:00 -0600
categories: reflexões, TDD, cognição
excerpt_separator: <!--more-->

---

Existe um jargão no mundo dos negócios: "Too Big To Fail"; ou, "Muito Grande Para Falhar", no velho e bom pt-BR.

Mas no mundo do desenvolvimento ocorre o contrário. Se você quer falhar menos, você precisa dar pequenos passos.

<!--more-->

Portanto, estou adaptando um novo jargão para o mundo do desenvolvimento: "Too Small To Fail", ou "Pequeno Demais Para Falhar".

A lógica por trás dessa afirmação é simples: quanto menor a quantidade de código, menor o número de caminhos de execução, menor a chance de falha. Essa abordagem está intimamente ligada ao conceito de "baby steps" do TDD.

Além disso, trabalhar com pequenas implementações e cuidar para que cada método de cada classe seja bastante conciso é uma forma de trabalhar a favor da nossa limitada capacidade de guardar informações. Uma pessoa normal possui cerca de 4 espaços na memória de trabalho, e cada variável declarada, cada if, cada atribuição de valor vai ocupar espaço precioso no cérebro de quem estiver lendo o seu código.

Outra vantagem dessa abordagem é conseguir manter um controle mais preciso sobre regressões no código, pois se as alterações foram pequenas, fica fácil detectar qual foi o código que introduziu o problema.

Portanto, lembre-se: mantenha pequenos progressos, pequenas classes, pequenos métodos, pequenas refatorações.

A sua sanidade mental - e a de quem vai manter o código depois de você - agradecem.