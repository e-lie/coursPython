
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

# 8. Structures de données

---

# 8. Listes, dictionnaires

Les listes et dictionnaires permettent de stocker des séries
d'information...

## 8.1 Les listes

```python
favourite_pokemons = [ "Bulbizarre", "Roucoups", "Insecateur" ]
fibonnaci = [ 1, 1, 2, 3, 5, 8 ]
stuff = [ 3.14, 42, "bidule", ["a", "b", "c"] ]
```

### Accès à un élément particulier

```python
favourite_pokemons[1]    ->  "Roucoups"
```

### Longueur

```python
len(favourite_pokemons)    -> 3
```

---

# 8. Structure de données

```python
favourite_pokemons = [ "Bulbizarre", "Roucoups", "Insecateur" ]
```

### Iteration

```python
for pokemon in favourite_pokemons:
    print(pokemon + " est un de mes pokemons préférés !")
```

### Iteration avec index

```python
for i, pokemon in enumerate(favourite_pokemons):
    print(pokemon + " est mon "+ str(i) +"ème pokemon préféré !")
```

---

# 8. Structure de données

```python
favourite_pokemons = [ "Bulbizarre", "Roucoups", "Insecateur" ]
```

### Modification d'un élément

```python
favourite_pokemons[1] = "Roucarnage"
```

### Ajout à la suite

```python
favourite_pokemons.append("Mewtwo")
```

### Insertion

```python
favourite_pokemons.insert(1, "Papillusion")
```

---

# 8. Structure de données

### Transformation de string en liste

```python
"Hello World".split()    -> ["Hello", "World"]
```

### Transformation de liste en string

```python
' | '.join(["a", "b", "c"])      -> "a | b | c"
```

---

# 8. Structure de données

## 8.2 Les dictionnaires

```python
ages = { "Alice": 20, "Bob": 24, "Charlie": 19 }
```

N.B. : dans les dictionnaires, l'ordre des éléments est sans importance !

### Accès à une valeur

```python
ages["Charlie"]    ->   19
```

### Modification d'une entrée, ajout d'une nouvelle entrée

```python
ages["Charlie"] += 1
ages["Deborah"] = 21
```

---

```python
ages = { "Alice": 20, "Bob": 24, "Charlie": 19 }
```

### Iteration sur les clefs

```python
for prenom in ages:
    print("Je connais l'age de "+prenom)
```

### Iteration sur les valeurs

```python
for age in ages.values():
    print("Quelqu'un a "+str(age)+" ans")
```

### Iterations sur les clefs et valeurs

```python
for prenom, age in ages.items():
    print(prenom + " a " + str(age) + " ans !")
```

---

# 8. Structure de données

## 8.3 Les sets

Les `set`s stockent des éléments de manière unique et désordonnée.

```python
chat = set("chat")     # -> {'h', 'c', 'a', 't'}
chien = set("chien")   # -> {'c', 'e', 'i', 'n', 'h'}
chat - chien           # -> {'a', 't'}
chien - chat           # -> {'i', 'n', 'e'}
chat & chien           # -> {'h', 'c'}
chat | chien           # -> {'c', 't', 'e', 'a', 'i', 'n', 'h'}
chat.add("z")          # ajoute `z` à `chat`
```

---

# 8. Structure de données

## 8.4 Les tuples

Les tuples permettent de stocker des données de manière similaire à une liste, mais de manière non-mutable. Typiquement : des coordonnées de point.

```python
P = (2,3)
P[0]        # -> 2
P[1]        # -> 3
P[0] = 5    # -> Erreur!
```

---

# 8. Structure de données

## 8.5 List/dict comprehensions

Les "list/dict comprehensions" sont des syntaxes particulière permettant de rapidement construire des listes (ou dictionnaires) à partir d'autres structures.

### Syntaxe (list comprehension)

```python
[ new_e for e in liste if condition(e) ]
```

### Exemple (list comprehension)

Carré des entiers impairs d'une liste

```python
[ e**2 for e in liste if e % 2 == 1 ]
```

---

# 8. Structure de données

## 8.5 List/dict comprehensions

Les "list/dict comprehensions" sont des syntaxes particulière permettant de rapidement construire des listes (ou dictionnaires) à partir d'autres structures.

### Syntaxe (dict comprehension)

```python
{ new_k:new_v for k, v in d.items() if condition(k, v) }
```

### Exemple (dict comprehension)

Carré des entiers impairs d'une liste

```python
{ nom: age-20 for nom, age in ages.items() if age >= 20 }
```

---