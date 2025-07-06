# Simulation de pont brownien et application au pricing d'options

## Objectif du projet :

Ce projet a pour but d'étudier les propriétés probabilistes du pont brownien, en particulier la loi de son maximum, puis d’en tirer une application en finance quantitative : le **pricing d'une option barrière knock-in de type call sur le maximum**, par méthode de Monte-Carlo.

## Contenu du projet :

- Étude du maximum d'un mouvement brownien conditionné, approché par sélection de trajectoires. 
- Le pont brownien comme solution d'une équation différentielle stochastique, implémentation d'un schéma d'Euler
- Étude de $\mathbb{E}[U^2]$ où U est le maximum du pont brownien, méthode de Monte-Carlo et réduction de variance
- Application au pricing d'options barrière knock-in de type call sur le maximum
