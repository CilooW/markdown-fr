# Les titres

A l'ouverture d'un nouveau document markdown, il faut ajouter un titre et des sous-titres.

Le markdown supporte deux styles de titrage: Setext and atx.

Les titres stylisés en Setext sont “soulignés” en utilisant le signe égal plusieurs fois (pour des titres de premier niveau) et le tiret (pour des titres de second niveau). Par exemple:

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Cette méthode fonctionnera peu importe le nombre de "=" ou de "-" utilisés.

Le style de titrage Atx utilise de 1 à 6 dièse au début de la ligne, correspondant aux titres de niveau 1 à 6. Par exemple:

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```


Vous pouvez éventuellement "fermer" les titres en atx-style. Ce n'est que purement esthétique — vous pouvez l'utiliser si vous trouvez que c'est plus joli. Le nombre de dièses fermant le titre n'a donc même pas besoin d'être identique au nombre utilisé à l'ouverture du titre. (Le nombre de dièse détermine le niveau du titre.) :

```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######  
```



---  



Vous trouverez ci-dessous un quizz concernant les titrages markdown.

Sélectionnez le bon titrage:
- [x] `# hello`
- [ ] `#hello`

> Les titres ont besoin d'au moins un espace entre le premier dièse et le texte du titre.

Sélectionnez le bon titrage:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seuls les signes '=' et '-' sont acceptés pour souligner un titre.

---

