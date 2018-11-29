
#### Prenom : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Nom : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

# Initiation à Python : questionnaire



### Question 1

Si `mot` est une chaîne de caractère, que renvoie `len(mot)`:

- A. Les trois première lettres de `mot`
- B. Le mot en majuscule.
- C. Le nombre de caractères de `mot`.


### Question 2

Que renvoie `int("42")` ?

- A. `42.0`
- B. `'42'`
- C. `42`

### Question 3

Un programme contient cette instruction :

```python
age = input("Quel est ton âge ?")
```
Pendant une execution du programme, un utilisateur répond 28 à la question.
Que contient la variable `age` ?

- A. `28`
- B. `"28"`
- C. `None`



### Question 4

Pour concaténer un entier `n` à une chaîne de caractère, j'écris :

- A. `"une chaîne" + str(n)`
- B. `"une chaîne" + int(n)`
- C. `"une chaîne" + "n"`


### Question 5

Pour vérifier qu'une variable `n` est un entier, j'utilise :

- A. `isinstance(n, int)` 
- B. `type(n) == "int"`
- C. `int(n) == True`

### Question 6

Quelle valeur de retour renvoie la fonction `print()` ?

- A. None
- B. Une chaîne de caractère
- C. un entier


### Question 7

Que renvoie `7 / 2`:

- A. `3`
- B. `3.5`
- C. `4`

Donc que produit programme suivant: `print( "#" * (7/2) )`

- A. `"#######"`
- B. `"###"`
- C. `"####"`
- D. une erreur

### Question 8

A quoi sert le bouton insecte dans Thonny ?

- A. Lancer le programme pas à pas pour contrôler son execution et trouver les bugs
- B. Accélérer l'exécution
- C. Afficher précisément les erreurs de syntaxe

### Question 9

Quelles commandes Python créent un bloc (avec indentation) ?

- A. `print(), int() et str()`
- B. `if` et les conditions, `for` et les boucles, `def` pour les fonctions.
- C. Les deux.


### Question 10

À la fin de l'execution de ce programme, que contiendra la variable `x` ?

```python
def dire_bonjour():
    print("Bonjour !")

x = dire_bonjour()
```

- A. `"Bonjour !"`
- B. `""`
- C. `None`


### Question 11

Dans le programme de la question précédente, pour que la fonction
`dire_bonjour()` renvoie `"Bonjour !"`,  j'aurais dû remplacer la deuxième ligne
par :

- A. `return "Bonjour !"`
- B. `return print("Bonjour !")`
- C. Rien du tout, c'était déjà bon !


### Question 12

Pour savoir si une variable `n` contient l'entier 20, j'écris :

- A. `n = 20`
- B. `n = "20"`
- C. `n == 20`
- D. `n == "20"`


### Question 13

Qu'affiche le programme suivant ?

```python
for i in range(0,10):
    if i % 2 == 0:
        continue
    print("La variable i vaut " + str(i))
```

- A. Un message pour chaque entier impair entre 0 et 9 compris
- B. Rien du tout
- C. Il y a une erreur de syntaxe


### Question 14

Qu'affiche le programme suivant ?

```python
for i in range(0,10):
    if i % 2 == 0:
    continue
    print("La variable i vaut " + str(i))
```

- A. Un message pour chaque entier impair entre 0 et 9 compris
- B. Rien du tout
- C. Il y a une erreur de syntaxe

### Question 15

Vous désirer exécuter une boucle un nombre indéfini de fois. Quel type de boucle utiliser ?

- A. Une boucle `for`.
- B. Une boucle `dowhile`.
- C. Une boucle `while`.

### Question 16

Dans quel contexte la commande `break` est-elle utile ?

- A. Dans tous les `if` ou `elif`.
- B. Dans toutes les fonctions.
- C. Dans toutes les boucles `while` et `for`.

