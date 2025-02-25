---
layout: page
title:  "Tronc Commun Informatique"
category: cours
tags: informatique cours 
---

## Introduction

Tronc commun d'informatique. 

Ce cours comporte deux parties :
  
  1. algorithmie
  2. données

Chaque partie est organisée en 3 types d'enseignements :

  - séance de cours (**C,M**) : magistral.
    > pour acquérir  des connaissances de base
  - séance tableau (**ST**) : exercices fait sans machine, accompagné d'un prof ou d'un corrigé
    > pour travailler/acquérir des connaissances théoriques
  - séance machine (**SM**) : exercices fait avec votre machine, accompagné d'un prof ou d'un corrigé
    > pour travailler/acquérir des connaissances pratiques

Nous allons ici uniquement parler de la partie algorithmie du tronc commun. Pour toute question n'hésitez pas à nous écrire soit par mail soit sur le discord ([coordonnées]({{ "/about/" | relative_url }})).


## Ordonancement


  - 29/09/2020 13h30 : **C,M** : *Graphes* [**Pour tous**, Classe virtuelle]
  - 02/10/2020 
      - 13h30 :
        - **ST** : *algorithmes gloutons, 1/2* [**Groupes 1 à 5**, Présentiel]
        - **SM** : *installations d'un environnement de développement* [**Groupes 6 à 10**, Autonomie]
      - 15h45 : **C,M** : *Complexités* [**Pour tous**, Classe virtuelle]
  - 13/10/2020 13h30 
      - **ST** : *algorithmes gloutons, 2/2* [**Groupes 1 à 5**, Présentiel]
      - **ST** : *TD complexités* [**Groupes 6 à 10**, Autonomie]
  - 20/10/2020 13h30 : **C,M** : *Données* [**Pour tous**, Classe virtuelle]
  - 23/10/2020 
      - 13h30 :
        - **SM** : *installations d'un environnement de développement* [**Groupes 1 à 5**, Autonomie]
        - **ST** : *algorithmes gloutons, 1/2* [**Groupes 6 à 10**, Présentiel]
      - 15h45 : 
        - **SM** : *TD complexités* [**Groupes 1 à 5**, Autonomie]
        - **ST** : *algorithmes gloutons, 2/2* [**Groupes 6 à 10**, Présentiel]
  - 13/11/2020 
      - 13h30 :
        - **ST** : *parcours de graphes* [**Groupes 1 à 5**, Présentiel]
        - **ST** : *arbres de recherche, 1/2* [**Groupes 6 à 10**, Autonomie]
      - 15h45 : 
        - **ST** : *algorithmes de textes* [**Groupes 1 à 5**, Présentiel]
        - **SM** : *arbres de recherche, 2/2* [**Groupes 6 à 10**, Autonomie]
  - 17/11/2020 13h30 : **C,M** : *révision programmation* [**Pour tous**, Classe virtuelle]
  - 20/11/2020 
      - 13h30 :
        - **ST** : *arbres de recherche, 1/2* [**Groupes 1 à 5**, Autonomie]
        - **ST** : *parcours de graphes* [**Groupes 6 à 10**,  Présentiel]
      - 15h45 : 
        - **SM** : *arbres de recherche, 2/2* [**Groupes 1 à 5**, Autonomie]
        - **ST** : *algorithmes de textes* [**Groupes 6 à 10**,  Présentiel]
  - 24/11/2020 13h30 : **SM** *algo révisions* [**Pour tous**, Autonomie]
      - 13h30 :
        - **ST** : *flots 1/2* [**Pour tous**, Autonomie]
      - 15h45 : 
        - **SM** : *flots 2/2* [**Pour tous**, Autonomie]
  - 8/12/2020 13h30 : **C,M** : *fichiers et indexation* [**Pour tous**, Classe virtuelle]
  - 11/12/2020 
      - 13h30 :
        - **ST** : *fichiers et indexation* [**Groupes 1 à 5**, Présentiel]
        - **SM** : expressions régulières [**Groupes 6 à 10**, Autonomie]
      - 15h45 :
        - **SM** : *fichiers et indexation* [**Groupes 1 à 5**, Présentiel]
        - **SM** : dictionnaires, H-codes [**Groupes 6 à 10**, Autonomie]
  
        
## Séances


### Graphes

> Par François Brucker 

Connections :

  - [le discord](https://discord.gg/4UkDeAT)
  - lien de connection [big blue button](https://moodle.centrale-marseille.fr/mod/bigbluebuttonbn/view.php?id=11017) 


Le support du cours d'[Introduction aux graphes]({% link cours/tronc_commun/introduction_aux_graphes.md %})

### gloutons 1/2 et 2/2

La séance sur les algorithmes gloutons est séparée en deux parties :

  - séance 1 : [les gloutons exacts]({% link cours/tronc_commun/algorithmes_gloutons_1_2.md %})
  - séance 2 : [les gloutons approchés]({% link cours/tronc_commun/algorithmes_gloutons_2_2.md %})


Après cette séance vous connaîtrez presque tout sur la vie l'œuvre et comment reconnaître un glouton.

### installation d'un environnement de développement

Le but de cette séance est d'installer un environnement de développement python et de se familiariser avec les tests unitaires.

  1. **environnement de développement**. En suivant ce [tutorial sur anaconda et pycharm]({% link cours/tuto/anaconda-pycharm-pytest.md %}), créez un environnement de développement python cohérent avac anaconda et pycharm.
  2. **tests unitaires**. Suivez ce [tutorial sur les tests unitaires]({% link cours/tuto/tests-unitaires.md %}) pour mettre en place un environnement de test, puis vous pourrez faire les exercices ci-après.
  3. **code**. Suivez ce [tutorial sur les circuits eulérien]({% link cours/tronc_commun/circuits-euleriens.md %}) pour utiliser pycharm et les tests.

### Complexités

> Par Pascal Préa

  - [le discord](https://discord.gg/4UkDeAT)
  - lien de connection TBD

> Pour le Support de cours  
> Il faudra/faut/fallait être là.

### TD complexités

[sujet du TD]({{ "https://wiki.centrale-marseille.fr/informatique/tc_info:2020_td_comp" }})

### Données texte

> Par Emmanuel Daucé

  - [sujet du TD]({% link cours/tronc_commun/2020_td_texte.md %})
  - [corrigé]({% link cours/tronc_commun/2020_td_texte_corr.md %})
  - [sujet de TP](https://wiki.centrale-marseille.fr/informatique/tc_info:tp3)

### parcours de graphes

[sujet du TD]({% link cours/tronc_commun/parcours_graphes.md %})

### Arbres de recherche 1/2 et 2/2

> Par Pascal Préa

Le sujet est disponible sur le [wiki de l'informatique](https://wiki.centrale-marseille.fr/informatique/tc_info:2020_td-tp_abr).

### Révision programmation et algo révisions

TBD

### flots 1/2 et 2/2

> Par Pascal Préa

[sujet du TD]({{ "https://wiki.centrale-marseille.fr/informatique/tc_info:2020_td-tp_flo" }})

### Fichiers et indexation 

> Par Emmanuel Daucé

Les sujets sont disponibles sur le wiki de l'informatique
  - [sujet de TD](https://wiki.centrale-marseille.fr/informatique/tc_info:td2)
  - [corrigé](https://wiki.centrale-marseille.fr/informatique/tc_info:corr:td2)
  - [sujet de TP](https://wiki.centrale-marseille.fr/informatique/tc_info:tp2)
  - [corrigé](https://wiki.centrale-marseille.fr/informatique/tc_info:corr:tp2)
  
### Dictionnaires, H-codes

> Par Emmanuel Daucé et Pascal Préa
  - [séance TA](https://wiki.centrale-marseille.fr/informatique/tc_info:private_s5-tpa2)


  
