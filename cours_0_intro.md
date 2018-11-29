title: Introduction Python et Git
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
<!--
.bottom-bar[
  {{title}}
]
-->

---

class: impact

# {{title}}
## *From start to autonomy in development*

---

class: impact

(Première chose qu'on dit avec un langage informatique)

# Hello, world!

---

# À propos de moi

.center[

## Elie Gavoty

]

.col-4[
Développeur Python, DevOps
.col-2[</br>]
.col-8[
![](img/python.png)
![](img/devops.png)
.col-2[</br>]
]]

.col-4[.center[
Doctorant en philosophie

![](img/platon.png)
]]

.col-4[.center[
Formateur: Python, Ansible, Elasticsearch

![](img/formation.png)
]]

---

# À propos de vous

## Parlez moi des épisodes précédents.

---

# Enseigner et apprendre la programmation

## (Mauvaises nouvelles)

- Abstract and Sometimes booooring exercices.
    - *Mais c'est les fondamentaux !*
- Disparité de vitesses d'apprentissage
- Rien ne remplace l'expérience... En fait ça prend des mois d'être à l'aise.
- Finalement assez éloigné du "vrai" travail d'entreprise (mais absolument nécessaire) :
    - != Analyse, architecture, UX, debugging, refactoring, tests, VCS, ...
    - la programmation est la source de l'automatisation et de l'autonomie dans votre carrière informatique.

---

# Enseigner et apprendre la programmation

## (Bonnes nouvelles)

- Je suis payé pour répondre à vos questions \o/
- J'ai essayé de faire des exercices plutôt ludiques ..?
- Je vais m'adapter aux différentes vitesses.
- On va se mettre dans une ambiance d'entreprise en utilisant gitlab pour les 3 derniers jours.
- DevOps = Devenir architecte du cyberespace

---

# Objectifs

## - Des bases solides de programmation et une vue globale
## - De l'enthousiasme et des bonnes pratiques ?
## - Une méthodologie réaliste avec gitlab.

---

# Fonctionnement du cours

Alternances entre explications théoriques sur une notion donnée...

... et mise en application sur des exercices.

---

# Python **ET** Git ensemble.

- C'est super pour apprendre **Git en contexte**.
- On va apprendre à coder du **Python** dans **Gitlab**, qui est très **utilisé en entreprise** pour **collaborer**.

## Doublement pratique !

---

# Logistique ?

- Les cours sont mis à dispositions chaque soir sur : **https://ptych.net/documents**
- Vous allez sauvegarder vos exercices sur votre dépot git en ligne... qu'on va créer dans deux jours.
- Machines virtuelles linux ? Partage Réseau ?
- Évaluation ?

---

class: impact

# La programmation

---

class: impact

## L'ordinateur comme outil universel

---

class: impact

# « Informatique »

---

# Informatique

<br>
<br>
<br>
.center[![](img/programmer_job.png)]


---

class: impact

# Machines ain't smart.

# You are !

---

# La programmation : cuisiner de l'information

* Préparer **des outils** et **des ingrédients**
* Donner **des instructions**
* ... parfois en utilisant **des "fonctions"**
    * _« monter des oeufs en neige »_
    * _« cuire à thermostat 6 pendant 20 minutes »_

---

# *Langage* de programmation

## Comme un vrai langage !

0. **Concepts** (mots, verbes, phrases ...)
1. **Grammaire et syntaxe**
2. **Vocabulaire**
3. **Organiser** sa rédaction et ses idées : **structurer** correctement son code et ses données

---

# Python 

.col-3[.col-10[![](img/python2.png)]]
--

- **Versatile !!! ** = un des langages les plus généralistes
--

- "Moyen-niveau"
--

- Syntaxe légère, lisible, facile à prendre en main
--

- Interprété, "scripting" = rapide à mettre en oeuvre mais dépendant d'un logiciel.
--

- Prototypage rapide = la glue du logiciel.
--

- Grande communauté
--

- De plus en plus répandu ! c'est la **mega hype**
--

- DevOps oriented

---

# Python dans la vraie vie

.center[Dropbox]

.center[![](img/dropbox.png)]

---

# Python dans la vraie vie

.center[Atom]

.center[![](img/atom.png)]

---

# Python dans la vraie vie

.center[Eve online]

.center[![](img/eveonline.jpg)]

---

# Python dans la vraie vie

.center[Matplotlib]

.center[![](img/matplotlib.png)]

---

# Python dans la vraie vie

.center[Blender]

.center[![](img/blender.jpg)]

---

# Python dans la vraie vie

.center[OpenERP / Odoo]

.center[![](img/odoo.jpg)]

---

# Python dans la vraie vie

.center[Tartiflette]

.center[![](img/tartiflette.png)]

---

# Python history

.col-8[
   « ... In December 1989, I was looking for a **"hobby" programming project that would keep me occupied during the week around Christmas**. My office ... would be closed, but I had a home computer, and not much else on my hands.
   <br>
   <br>
   I decided to write an interpreter for the new scripting language I had been thinking about lately: a descendant of ABC that would appeal to Unix/C hackers.
   <br>
   <br>
   I chose Python as a working title for the project, being in a slightly irreverent mood (and a big fan of Monty Python's Flying Circus). »
.right[— Guido van Rossum  .]
]

.col-4[
![](img/guido.jpg)
]


---

class: impact


*Programming mindset*

---

.center[![](img/brainMelting.jpg)]

---

## .center[La programmation est une pratique *compliquée*]
.col-3[</br>].col-6[![](img/clouds.jpg)].col-3[</br>]

.col-12[.center[

## <br>
## Il n'y a rien de génant si vous ne comprenez pas les exercices dès le départ.

]]

---

.center[![](img/suckingAtSomething.jpg)]

---

# Cassez des trucs !

.center[![](img/yodaMistakes.jpg)]

---

# Explorez !

.center[![](img/changingThings.jpg)]

---

# Nos outils

- Machine virtuelle (VM) Ubuntu
- Python (3.x)

## Pour coder durant cette formation

- **Thonny** : pour débutants, il montre comment s'exécute le code
- **VSCode** : un éditeur puissant et assez simple d'accès qui intègre facilement git

---

# Autres éditeur...

- **Vim** éditeur en console pour ninjas
- **Pycharm** IDE très gros qui fait même le café
- **Emacs** un éditeur de libristes et chercheurs
- **Eclipse** un gros IDE multilanguages
- ... plein d'autres

---

# 0. Hello world !

Dans Thonny :

```python
print("Hello, world!")
```
