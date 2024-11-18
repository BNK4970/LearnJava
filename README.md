# Prendre java
Dans ce repository, nous allons apprendre java en passant par différents niveaux :
 - **Facile** :
   - Variables
   - Tableaux
 - **Moyen**
 - **Difficile**

# Facile

## Variables
- **Boolean**:
2 valeurs possibles uniquement : `true` ou `false`
```java
boolean myVar = true;
```
- **byte**:
Valeur numérique pouvant aller de `-128` à `127` inclus.
```java
byte myVar = 10;
```
- **char**:
Un simple caractère

```java
char myVar = 'a';
```
- **double**:
Valeur flottante à double précision allant de `2.22507e-308` à `1.79769e+308`
```java
double myVar = 10.0;
```
- **float**:
Valeur flottante à simple précision allant de `1.401e-045` à `3.40282e+038`
```java
float myVar = 10.0f;
```
- **int**:
Valeur numérique entière pouvant aller de `231` à  `231-1` inclus.
```java
int myVar = 10;
```
- **long**:
Valeur numérique entière pouvant aller de `264` à  `264-1` inclus.
```java
long myVar = 10;
```
- **short**:
Valeur numérique entière pouvant aller de `-32,768` à `32,767` inclus.
```java
short myVar = 10;
```

## Tableaux
Pour gérer un ensemble de données d’un même type, le langage Java comme de nombreux autres langages de programmation implémente les **tableaux** (array en anglais). <br> <br>
Un tableau possède un nombre défini d’éléments. Chaque case du tableau peut contenir un élément. Chaque élément est du même type.

**Par exemple**:
```java
int[] unTableauDEntier = {5, 10, 15, 20};
```
- J'ai déclaré un tableau nommé unTableauDEntier contenant des entiers.
- J'ai affecté 4 valeurs de type int, à savoir 5, 10, 15 et 20.

Je peux accéder à une case du tableau en indiquant l’indice de cette dernière grâce à la notation suivante :  `unTableauDentier[0];`

**La première case a pour indice 0, la deuxième l’indice 1, etc.**

