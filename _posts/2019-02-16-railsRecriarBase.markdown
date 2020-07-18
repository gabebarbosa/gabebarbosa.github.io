---
layout: post
title:  "Dica Ruby on Rails - Recriando a base"
date:   2019-02-16 18:45:14 -0300
categories: jekyll update
icon_adress: https://image.flaticon.com/icons/svg/919/919842.svg
comments_url: http://gabebarbosa.com.br/jekyll/update/2019/02/16/railsRecriarBase.html
---
Oi todo mundo, eu sou o **Gabriel Barbosa**.

Uma dica importante para quem está começando a desennvolver com Ruby On Rails é como recriar a base de dados.

Esta dica é importante pois quando estamos começando com nossos projetos iniciais tendemos a errar na criação de alguns campos e tabelas e depois de ajustar as migrations queremos recriar a base.

Sabemos que o comando para criar a base de dados é o `rake db:create`, porém não existe(ainda) o comando `rake db:recreate`, nesse caso para recriar a base vamos dropa-la e em seguida criar uma nova base com as migrations já rodadas com o seguinte comando no terminal `rake db:drop db:create db:migrate`.

> Espero ter ajudado alguem, pois tive essa mesma dúvida em meus estudos. :D

