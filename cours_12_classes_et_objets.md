
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

## 12. Les classes

```python
class Monstre:

    def attaque(self, cible):
        cible.hp -= self.force

class Troll(Monstre):

    def __init__(self):
        self.hp = 20
        self.force = 4

    def vomir(self):
        print("Bleuarg!")

class Gobelin(Monstre):

    def __init__(self):
        self.hp = 5
        self.force = 1
```

---

## 12. Les classes

```python
# Initialiser des créatures

troll = Troll()
gob_army = [ Gobelin() for i in range(0,4) ]

# Faire une bataille !

print("Le troll a {n} hp".format(n=troll.hp))

troll.attaque(gob_army[0])
for gob in gob_army:
    gob.attaque(troll)

print("Le troll a {n} hp".format(n=troll.hp))
```

---

## 12. Les classes

### Elements syntaxiques importants : 

- L'indentation
- Le mot clef `class`
- `self` corresponds à l'instance / l'object (similaire à `this` dans d'autres
  langages)
- `__init__` corresponds au constructeur
- J'instancie un objet avec `NomDeClasse()` (eventuellement des arguments)

---


## 12. Les classes

### Appeler le constructeur de la classe mère...

```python
class Mere():
    
    def __init__(self):
        print("Je suis dans le constructeur de la classe mere !")

class Fille(Mere):

    def __init__(self):
        super().__init__()

```

---