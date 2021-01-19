---
title: Démarrer avec PowerShell
author: Nicolas BAUDIN
date: 2021-01-18 17:30:00 +0100
categories: Beginner
tags: [débutant, powershell]
---

## Par où commencer ?

Pour ce premier article, j'ai choisi de répondre à une question qui revient régulièrement sous différentes formes :  

 - "Avez-vous un bon lien pour apprendre PowerShell ?"
 - "J'ai commencé sur tel site, mais avez-vous autre chose à me proposer ?"
 - "En termes de mise en pratique PowerShell ou de thématique pour découvrir le langage, vous avez quoi ?"

Il n'y a pas de réel chemin tracé, ou encore de source qui surpasse les autres. Cela dépend aussi de vos affinités et préférences en fonction du support.

Personnellement, j'aime assez les livres, papier ou numérique sur une liseuse. J'aime bien entendu la possibilité de 
pratiquer ou de réfléchir sur certaines problématiques.  
En revanche, je suis moins portée sur la vidéo ou encore sur les longs cours numériques
(comme on peut en trouver sur certaines plateformes en ligne).  
Après à chacun de décider !

Pour cet article, je vais essayer d'être le plus exhaustif possible et vous proposer une variété de support.

## Top départ !

### Docs PowerShell

Depuis maintenant un certain temps, Microsoft a mis à disposition une documentation détaillée sur les bases (et +) du langage :  

- [PowerShell Docs](https://docs.microsoft.com/fr-fr/powershell/)

On y retrouve la notion d'objet, les structures, l'aide de PowerShell, etc.  
Tout ce qu'il faut pour bien débuter avec le langage.

### L'aide intégré et ses rubriques `About`

Une fois que vous aurez compris les bases et commencé à consulter l'aide des commandes, je vous conseille de jeter un oeil aux sections `about_*` présentes dans l'aide de PowerShell.  
On y trouve des explications sur des concepts ou des thématiques du langage (ex.: `Get-Help about_wildcards`).  

{% include note.html content="Petite remarque qui pourrait en freiner certains, ces rubriques `About` sont en anglais. Elles sont également disponibles en [ligne](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about?view=powershell-7.1)." %}

### Le module PSKoans

PSKwa ?  
En PowerShell, un module permet de regrouper un certain nombre de ressources (commandes, alias, dll, etc.) exploitables en PowerShell.  
Dans le cas de PSKoans, il s'agit d'un module qui regroupe des questionnaires sous forme de scripts PowerShell.
L'idée du module est de vous poser des questions sur les mécaniques du langage.  

Le lien du projet : [PSKoans](https://github.com/vexx32/PSKoans)

Une fois le module [installé](https://github.com/vexx32/PSKoans#install-from-gallery), vous pouvez lancer un `Show-Karma` pour voir quel est votre niveau.  
Ensuite, vous rajoutez le paramètre `-Contemplate` pour continuer à répondre aux questions et à progresser.

Une fois que vous avez répondu aux questions et enregistré vos réponses, pour pouvez de nouveau 
exécuter un `Show-Karma` pour voir si vos réponses sont bonnes.

Il faut savoir que la plupart des réponses aux questions sont présentes dans les rubriques d'aides `About`.

### Pour ceux qui ont un peu plus de budgets

Dans le cas où vous disposez d'un budget formation, soit personnel, soit à travers votre entreprise, vous avez la possibilité d'opter pour différents supports.

#### La bibliothèque ENI édition

Étant moi-même auteur pour les éditions, je ne peux pas passer à côté. Même si ce n'est pas mon livre que je place en première position pour débuter. :)

Aux éditions ENI, vous trouverez des livres, mais aussi des vidéos. Pour commencer, je vous conseille ceux-ci : 

 - Le livre sur les [fondamentaux de PowerShell](https://www.editions-eni.fr/livre/powershell-core-et-windows-powershell-les-fondamentaux-du-langage-2e-edition-9782409013287)
 - Les vidéos qui décrivent également les fondamentaux :
  - [Les fondamentaux](https://www.editions-eni.fr/video/powershell-les-fondamentaux-du-scripting-vtscrpow)
  - [Optimiser l'écriture de vos scripts](https://www.editions-eni.fr/video/powershell-optimisez-l-ecriture-de-vos-scripts-a-l-aide-des-fonctions-et-des-modules-vtfomopow)

#### PluralSight

[PluralSight](https://www.pluralsight.com/fr) est une plateforme en ligne accessible sous abonnement (certains cours peuvent se retrouver gratuits). Elle regroupe un grand nombre de vidéos et d'articles sur différentes ressources (pas seulement PowerShell). Petite contrainte, la majeure partie des ressources sont en anglais.

{% include note.html content="PluralSight regroupe également des cours avancées sur PowerShell." %}

## On passe aux choses sérieuses

Maintenant que les bases sont là, on peut partir sur des ressources un peu plus avancées.

### La bibliothèque ENI éditions

Pour cette seconde partie, je vous conseille de regarder le livre sur les fonctionnalités avancées que j'ai réécrit (fallait bien le placer à un moment donné :) ) :

 - [PowerShell Fonctionnalités Avancées](https://www.editions-eni.fr/livre/powershell-fonctionnalites-avancees-nouvelle-edition-9782409014994)

Vous y trouverez comment écrire des fonctions avancées, des modules, la création d'un dépôt de module interne, etc. De quoi occuper vos soirées.

### Autres éditeurs

Il existe également des ouvrages étrangers écrits en anglais qui sont des mines d'informations. Une fois que vous aurez épluché les livres des éditions ENI, je vous conseille de jeter un oeil aux livres de ces éditions, notamment :

 - [PowerShell In action Third Edition](https://www.manning.com/books/windows-powershell-in-action-third-edition)

Celui-ci est une valeur sure. Il va plus loin dans les explications et est très fourni (environ 900 pages).

Les éditeurs :
 
 - Manning (suivre le lien au-dessus)
 - [LeanPub](https://leanpub.com/bookstore?type=all&search=powershell)
 - [PacktPub](https://www.packtpub.com/catalogsearch/result/?q=powershell)

{% include note.html content="Je n'ai pas lu tous les ouvrages présents sur ces plateformes. Certains sont très bons d'autres moins. N'hésitez pas à me faire un retour sur ceux que vous aurez lu." %}

{% include tip.html content="PacktPub réalise régulièrement des offres promotionnelles à 5$ sur la plupart des livres. Ça peut être intéressant pour les petits budgets." %}

{% include important.html content="En dehors de mon livre, je ne touche aucune rémunération, carte cadeaux ou coupons réductions sur les liens présentés ici ;) ." %}

### Devenir forgeron

Tout le monde connait le proverbe *"Il faut forger pour devenir forgeron!"*. C'est bien entendu le cas partout, et c'est d'autant plus vrai quand on parle de l'apprentissage d'une langue ou d'un langage de programmation ou d'administration.

Je conseille souvent aux personnes qui suivent mes formations de pratiquer PowerShell le plus possible. Cela peut être de la simple copie de fichier, création de dossiers, jusqu'à la modification en masse d'un attribut utilisateur dans l'AD (faites des tests avant, c'est mieux...).  
Plus vous pratiquerez, plus le langage vous sera familier et moins vous mettrez de temps à faire ce que vous voulez. Surtout le jour où vous en aurez le plus besoin.

Si jamais vous manquez d'imagination pour pratiquer PowerShell, pas de panique. Je vais vous présenter trois plateformes où vous pourrez trouver de l'inspiration, voir un peu de frustration....

#### Code Golf

[Code Golf](https://code.golf/) est une plateforme en ligne qui vous pose des problèmes à résoudre par un script. Différents langages sont disponibles, et heureusement pour nous, PowerShell en fait partie. Le but étant de répondre aux problèmes avec le moins de caractères possible.
Pour publier et apparaitre dans le classement, il vous faudra un compte sur la plateforme [GitHub](https://github.com/).

#### IronScripter Challenge

La plateforme [IronScripter](https://ironscripter.us/) publie régulièrement des challenges avec des problématiques à résoudre. Vous pouvez opter pour des problèmes [débutant](https://ironscripter.us/tag/beginner/) ou [avancé](https://ironscripter.us/tag/advanced/). Les participants publient eux-mêmes les réponses en commentaire.
 Cela vous permet également de jeter un oeil aux pratiques des autres.

#### PowerShell Scripting

Le forum [PowerShell Scripting](http://www.powershell-scripting.com/) est le premier forum français orienté PowerShell à avoir vu le jour. Vous y trouverez des postes de personnes ayant une problématique sans pour autant trouver euw-même la réponse.
 C'est un bon moyen de progresser, soit en cherchant la réponse, soit en comprenant la ou les réponses qui ont permis de répondre à la problématique.

#### GitHub

[GitHub](https://github.com/) est un énorme dépôt communautaire qui regroupe les projets de tout horizon, pas spécifiquement PowerShell.
 On peut donc trouver des montagnes de code PowerShell à explorer qui vous apprendront énormément sur l'écriture du langage.

### La communauté

Pour terminé ce poste, je vais vous parler du [French PowerShell and DevOps User Group](https://frpsug.com/). Il s'agit d'un groupe de PowerSheller français.

Depuis 2016, les organisateurs ont mis en place des évènements en ligne pour discuter de PowerShell et de tout ce qui gravite autour. Chaque année, une conférence en présentiel est également organisée (sauf 2020, COVID oblige).

Les membres du groupe sont présents sur les plateformes de discussion Slack et Discord. Il existe un pont entre ces deux plateformes, on peut ainsi communiquer avec les personnes présentes sur Slack si on est sur Discord, et inversement. On discute ainsi en temps réel sur les problématiques, évolutions et différentes découvertes PowerShell que l'on fait.

- Pour nous rejoindre : [Discord](https://discord.gg/wRprbR6y)

{% include note.html content="Concernant les invitations Slack, le site permettant de recevoir une invitation n'existe plus. Le seul moyen que je connais est de renseigner manuellement votre adresse mail par une personne déjà dans le Slack." %}