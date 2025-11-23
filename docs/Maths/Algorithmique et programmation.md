# I – Types de variables – Affectation

!!! notes "Définition - Un **algorithme**" 
    Un **algorithme** est un enchaînement d'étapes ou d'**instructions** à effectuer dans un certain ordre et dont la réalisation va permettre la résolution d'un problème donné. Un algorithme manipule des **variables**. Son intérêt, c'est d'**être codé** dans un langage informatique afin qu'une machine (ordinateur, calculatrice) puisse l'exécuter rapidement et efficacement.

!!! notes "Définition - Une **variable**" 
    Une **variable** est une « boîte » possédant un **nom** et dans laquelle est stockée une **valeur**. On utilise différents **types de valeurs** :
    - **entier** : nombre entier relatif
    - **flottant** : nombre réel (écriture décimale)
    - **booléen** : variable ne pouvant prendre que deux états notés Vrai et Faux
    - **chaîne de caractères** : suite ordonnée de caractères

!!! notes "Définition" 
    La **longueur** d’une chaîne de caractères est son nombre d’éléments.
    Le $k^e$ élément d’une chaîne de caractère $L$ est donné par $L [k - 1]$ (le 1er élément est l’élément de rang 0).

!!! Examples "Exemple" : 
    La variable A contient le mot « ALGORITHME ». A est une variable de type  « chaîne de caractères ». La longueur de la chaîne est 10. Le premier élément, noté $A[0]$, est A. Le 5e élément, noté $A[4]$, est $R$.

!!! notes "Définition - L’affectation d’une variable" : 
**L’affectation d’une variable** est l’instruction permettant de « remplir » la boîte correspondante. Affecter une donnée va permettre à l'algorithme d'attribuer une valeur à une variable.

Exemple et notation : On donne à X la valeur a. L’instruction correspondante est :
« X ← a » qui se lit « X prend la valeur a » ou « X reçoit la valeur a » ou « la valeur a est
affectée à X ».
Exemple :
Programme de calcul Algorithme
Choisir un nombre pair.
Calculer le carré de sa moitié.
Ajouter au résultat le nombre entier qui suit
le nombre choisi.
Calculer et afficher la racine carrée du
résultat.
Deux variables : N, entier (choisi par
l’utilisateur) et R, flottant (pour stocker le
résultat obtenu à chaque étape)
R ← (N/2)²
R ← R + (N + 1)
R ← √R
Afficher R