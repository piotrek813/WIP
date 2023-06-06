---
layout: "@layouts/BlogLayout.astro"
title: Pracy nad robotami ciąg dalszy
excerpt: "Dzisiaj kontynuowaliśmy pracę nad robotami. Po wczorajszych
  ustaleniach dotyczących działania czujników, przystąpiliśmy do testowania kodu
  na świeżo przygotowanej trasie. Okazało się jednak, że kod napisany podczas
  pracy zdalnej nie zadziałał poprawnie za pierwszym razem. "
publishDate: 2023-06-02T13:08:03.826Z
image: /images/img_9822.jpg
category: Praktyki
author: Łukasz Jagiełło
tags:
  - robot
  - line-follower
  - arduino
  - wiśniowa
  - eip
---
Dzisiaj kontynuowaliśmy pracę nad robotami. Po wczorajszych ustaleniach dotyczących działania czujników, przystąpiliśmy do testowania kodu na świeżo przygotowanej trasie. Okazało się jednak, że kod napisany podczas pracy zdalnej nie zadziałał poprawnie za pierwszym razem. Robot miał tendencję do ignorowania narysowanej na kartonie linii i poruszania się po prostej.

![](/images/img_9777.jpg)

Po długim czasie, który ubiegł na testach zidentyfikowaliśmy problem. Okazało się, że aby robot skręcał poprawnie, musi przyśpieszyć na zakręcie. Po dodaniu odpowiedniego przyśpieszenia, problem zniknął, choć robot wciąż miał trudności z ostrymi zakrętami. Po kolejnych żmudnych godzinach doszliśmy do wniosku, że czujniki podczerwieni powinny znajdować się nieco bliżej podłoża. Po wprowadzeniu tych modyfikacji udało nam się doprowadzić do sytuacji, w której robot nawet najostrzejsze zakręty pokonuje z dużą skutecznością.

Kolejnym wyzwaniem, które udało nam się pokonać, było ustalenie sposobu wykrywania mety, aby robot zatrzymywał się zamiast skręcać i zjeżdżać z trasy. Ostatecznie udało nam się stworzyć działającego robota typu Line Follower. Jutro będziemy pracować nad wykrywaniem przeszkód na trasie przez robota.