---
layout: post
title: "Tests du catamaran"
img: Jouy_10_2019/tests_cata_jouy.jpg # Add image post (optional)
date: 2019-10-10 15:00:00 +0100
description: Tests avec le Catamaran avant le départ en mission à Nice
categories: [Recherche]
tags: [Surface robot, Research]
--- 


# Tests avec le Catamaran avant le départ en mission à Nice

Comme nous sommes en train de revoir l'intégralité de l'**architecture système** de nos robots, nous devons régulièrement valider ces changements par des **tests terrain**.

> Une mission d'acquisition d'images sous-marines est prévue à Nice dans quelques jours et on compte profiter de ce déplacement pour tester le comportement du catamaran, Kraken, en environnement marin (notamment le déplacement vis-à-vis de la houle).

On embarque donc une partie de l'équipe sur notre **zone d'essai** à Jouy-en-Josas pour tester la toute nouvelle carte mère et son tout nouveau code !


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_01.jpg){: style="width:49%;"} ![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_02.jpg){: style="width:49%;"}<br/>
**Matériel packé 👌: en route ! Installation sur la zone de test**
{: refdef}

On se déploie sur la zone et on commence les **premiers tests**. Contrôle des **moteurs** via la **télécommande** : check ! **Communication** : ok ... mais pas jusqu'au bout du lac (on perd le signal à la moitié). Il faudra qu'on s'équipe en matériel pour agrandir la **portée**. 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_03.jpg){: style="width:49%;"} ![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_04.jpg){: style="width:49%;"}<br/>
**Mise à l'eau et premiers tests**
{: refdef}

Le **mode piloté** semble opérationnel. Nous testons ensuite le **mode autonome**. Asservissement sur un **point fixe** : pas mal, peu de dérives. Réalisation de **trajectoires** : euh... 🤨

> On a l'impression que le catamaran fait un créneau pour rejoindre un point (alors qu'il est holonome, c'est-à-dire qu'il peut tourner sur lui même sans avoir à se déplacer !) et effectivement il était paramétré en mode rover !!! On corrige 😂


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_05.jpg){: style="width:49%;"} ![image]({{site.baseurl}}/assets/img/Jouy_10_2019/test_cata_06.jpg){: style="width:49%;"}<br/>
**Tests de pilotage et tests en mode autonome (asservissement position GPS)**
{: refdef}

Sur les trajectoires automatiques, il va falloir retravailler car les tests n'ont pas été concluants 😑 (interruptions nécessitant un redémarrage, points non atteints, etc.) et il est difficile de dire pour le moment d'où provient le problème. 

> On arrive au bout des batteries ! Fin de l'essai terrain 😉


*&#x21E8; Voir* : [la mission à Nice 2019]({% post_url 2019-10-14-mission_nice_2019_01 %})<br/>
*&#x21E8; Voir* : [le post suivant sur les tests du catamaran à Jouy-en-Josas]({% post_url 2020-09-11-tests_catamaran_jouy_02 %})<br/>







