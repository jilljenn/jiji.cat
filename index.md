---
title: Tests adaptatifs
nav: phd
layout: default
---
J'ai eu le plaisir de vous inviter à ma soutenance :

> *Modèles de tests adaptatifs pour le diagnostic de connaissances dans un cadre d’apprentissage à grande échelle* ([PDF](cat.pdf) du 6 janvier 2017)

## Lundi 5 décembre 2016 à 15 h

<a href="/img/map.png"><img src="/img/map.png" width="300" style="float: right; max-width: 50%" /></a>

Amphi Chemla  
de l'Institut d'Alembert

ENS Paris-Saclay  
[61 avenue du Président-Wilson](http://lab.vianavigo.com/itineraire?arrival=4313%7CSite%7CEcole+Normale+Supérieure%7C94230%7CCachan%7C%7C&date=2016-12-05T14%3A40&departure=%7CFreeSel%7C%7C%7C%7C%7C&journeyProfil=00&preferences=1111%7C1&sens=-1)  
94230 Cachan

RER B station Bagneux

### Résumé

Cette thèse porte sur les tests adaptatifs. Vous avez sûrement déjà joué au jeu « Qui est-ce ? » où il faut localiser l'individu auquel pense l'adversaire. Poser la question : « Est-ce Bob ? » pour chaque personne ne va pas permettre de gagner rapidement. Il vaut mieux poser des questions discriminantes, qui divisent au mieux l'espace de recherche en deux (si la moitié des candidats restants ont des lunettes, demander si la cible porte des lunettes sera utile).

J'ai recensé de tels systèmes utilisés dans diverses communautés, et je les ai appliqués au diagnostic de connaissances. Ainsi, pour évaluer un apprenant, on peut à chaque tour poser la question la plus informative, afin d'identifier ses points maîtrisés ou à retravailler en peu de questions. J'ai présenté GenMA, un modèle qui pose des questions de façon adaptative, et InitialD, une stratégie pour choisir un bon groupe de questions à poser. Ces deux méthodes sont meilleures que l'existant sur tous les jeux de données testés.

### Thèse

- [PDF officiel](cat.pdf), valide PDF/A1-b, avec des polices de hipster, compilé avec [LuaLaTeX](http://www.luatex.org) (6 Mo)
- [PDF](cat-xelatex.pdf), avec les polices LaTeX classiques, compilé avec [XeLaTeX](https://doc.ubuntu-fr.org/xelatex) (5,6 Mo)
- [Sources de la thèse](https://github.com/jilljenn/phd) sur GitHub que je vous invite à consulter
- [Code sur GitHub](https://github.com/jilljenn/qna) pour reproduire mes expériences
- [Ces pages sur GitHub](https://github.com/jilljenn/jiji.cat) pour faire un peu de [méta](http://club-meta.fr)
