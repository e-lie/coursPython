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

(Première chose qu'on dit avec languange informatique)

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

---

# Enseigner et apprendre la programmation

#### (Mauvaises nouvelles)

- Abstrait
- Booooring exercices
- Disparité de vitesses d'apprentissage
- Rien ne remplace l'expérience..
- Eloigné du taf de "la vraie vie" :
    - Analyse, architecture, UX, debugging, refactoring, tests, VCS, ...

---

# Enseigner et apprendre la programmation

#### (Bonnes nouvelles)

- On a du temps
- Je suis payé pour répondre à vos questions \o/
- Vous montrer l'essentiel et l'utile
- Exercices ludiques ?
- Priorité aux moins rapides
- Devenir architecte du cyberespace

---

# Objectifs

Transmettre :

- Des bases solides et une vue globale
- De l'enthousiasme !
- Des bonnes pratiques ?
- Du "pragmatisme" et du fun ?

---

## Fonctionnement du cours

Alternances entre explications théoriques sur une notion donnée

et mise en application sur des exercices. 

## Évaluation

- QCM et bouts de programmes à compléter
- Basé sur des cas et erreurs "courantes" vues dans les exercices

---

# Logistique ?


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

.col-4[![](img/python.png)]

.col-8[
- Versatile
- "Moyen-niveau"
- Syntaxe légère, lisible, facile à prendre en main
- Interprété, "scripting"
- Prototypage rapide
- Grande communauté
- De plus en plus répandu (?)]

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

class: impact

# Machines ain't smart.

# You are !

---

.center[![](img/brainMelting.jpg)]

---

.center[![](img/clouds.jpg)]

---

class: impact

## Programming *is* complicated

## <br>
## Don't be ashamed
## of not understanding right away

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
