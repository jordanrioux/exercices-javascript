# Exercice #01

Vous allez faire une petite page HTML dans le but de faire des calculs mathématiques simples. Comme premier exercice, chaque étape est clairement identifié pour vous guider et vous amener à réfléchir à ce qui doit être fait.

# Instructions

1. Créer une fonction `add` qui prend deux entiers en paramètres et qui retourne la valeur additionnées de ces deux entiers :
    * __Exemple:__ `const total = add(25, 22);`
2. Tester que la fonction fonctionne correctement à l'aide de `console.log` (penser aux différents cas de tests avec des nombres négatifs, décimals, etc.):
      * __Exemple:__ `console.log(add(25, 22));`
3. Répéter les étapes précédentes pour créer les fonctions `subtract`, `multiply` et `divide`.
4. Créer une fonction `calculate` : 
  * La fonction devra prendre deux nombres en paramètres, l'opération désirée et effectuer l'opération pour retourner le résultat.
  * L'opération sera '+', '-', '*' ou '/'. 
  * __Exemple:__ `const total = calculate(25, '+', 22);`
  * Votre fonction doit faire une vérification (if, switch) de l'opération et appelé la fonction correspondante précédemment créée (add, substract, etc.).
5. Créer les éléments HTML suivants : 
  * Un champs de texte pour le nombre #1
  * Un champs de texte pour le nombre #2
  * Un bouton pour chaque opération (Ajouter, Soustraire, Multiplier, Diviser)
  * Une division (div) pour écrire la sortie du calcul
6. Ajouter les informations nécessaires pour pouvoir cibler les éléments à partir du JavaScript (id, class, etc.)
7. Faire fonctionner le bouton "Ajouter" :
  * Ajouter un écouteur d'événement sur le clic du bouton "Ajouter"
  * Lors du clic, vous allez récupérer les `value` du champs de texte du nombre #01 et du nombre #02.
  * Vous allez appeler la méthode `calculate` avec les valeurs des nombres récupérés et avec l'opération '+'. (e.g. `calculate(number1, '+', number2)`)
  * Avec le résultat retourné par la méthode `calculate`, vous allez récupérer la division pour y écrire dans le HTML le résultat du calcul.
8. Répéter pour les boutons "Soustraire", "Multiplier" et "Diviser".
