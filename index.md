---
title: Tests adaptatifs
nav: phd
layout: default
---
J'ai le plaisir de vous inviter à ma soutenance :

> *Modèles de tests adaptatifs pour le diagnostic de connaissances dans un cadre d’apprentissage à grande échelle* ([PDF](cat.pdf) du 23/11)

## Lundi 5 décembre 2016 à 15 h

Amphi Chemla  
École normale supérieure de Paris-Saclay  
61 avenue du Président-Wilson  
94230 Cachan

<div>
<input type="text" id="mail" onkeydown="if(event.keyCode == 13) {document.getElementById('btn').click(); this.value = ''};" placeholder="Entrez votre nom ou mail" />
<button id="btn" onclick="microAjax('/register/', function () {document.getElementById('btn').innerHTML = 'Merci !'}, 'mail=' + document.getElementById('mail').value)">Je viendrai !</button>
</div>

### Résumé

Cette thèse porte sur les tests adaptatifs. Vous avez sûrement déjà joué au jeu « Qui est-ce ? » où il faut localiser l'individu auquel pense l'adversaire. Poser la question : « Est-ce Bob ? » pour chaque personne ne va pas permettre de gagner rapidement. Il vaut mieux poser des questions discriminantes, qui divisent au mieux l'espace de recherche en deux (si la moitié des candidats restants ont des lunettes, demander si la cible porte des lunettes sera utile).

J'ai recensé de tels systèmes utilisés dans diverses communautés, et je les ai appliqués au diagnostic de connaissances. Ainsi, pour évaluer un apprenant, on peut à chaque tour poser la question la plus informative, afin d'identifier ses points maîtrisés ou à retravailler en peu de questions. J'ai présenté GenMA, un modèle qui pose des questions de façon adaptative, et InitialD, une stratégie pour choisir un bon groupe de questions à poser. Ces deux méthodes sont meilleures que l'existant sur tous les jeux de données testés.

### Thèse

- [PDF](cat.pdf) version du 23/11
- [Fichiers Markdown](https://github.com/jilljenn/phd) sur GitHub, merci [pandoc](http://pandoc.org), le couteau suisse qui convertit tout vers tout !
- [Code sur GitHub](https://github.com/jilljenn/qna) pour reproduire mes expériences