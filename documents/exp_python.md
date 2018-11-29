
```python

def surface_rectangle(largeur, hauteur):
    surface = longueur * margeur
    return surface


def dessiner_rectangle(largeur, hauteur, caractere='@'):
    dessus_rectangle = largeur * caractere +'\n'

    ligne_rectangle = caractere + (largeur-2) * caractere + caractere + "\n"
    cotes_rectangle = (hauteur - 2) * ligne_rectangle

    dessous_rectangle = largeur * caractere

    rectangle = dessus_rectangle + cotes_rectangle + dessous_rectangle


rectangle = dessiner_rectangle(5, 3, '*')
print(rectangle)



```