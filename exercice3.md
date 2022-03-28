# Exercice #03


# Instructions

1. Créer une fonction `splitSentenceIntoWords` qui va prendre une chaîne de caractère et retourné un tableau contenant chaque mot :
```js
const words = splitSentenceIntoWords("Bonjour tout le monde");
// [ "Bonjour", "tout", "le", "monde" ]
``` 
2. Créer une fonction `splitStringIntoChoices` qui prendra une chaîne de caractère séparée par des virgules et retournera un tableau avec chaque mot dont la première lettre a été mis en majuscule :
```js
const choices = splitStringIntoChoices("orange, apple, banana, strawberry, cucumber");
// [ "Orange", "Apple", "Banana", "Strawberry", "Cucumber" ]
```
3. Créer une fonction `sortAlphabetically` qui va trier en ordre alphabétique le tableau passé en paramètre :
```js
const choices = [ "Orange", "Apple", "Banana", "Strawberry", "Cucumber" ];
const sortedChoices = sortAlphabetically(choices);
// [ "Apple", "Banana", "Cucumber", "Orange", "Strawberry" ]
```
4. Créer les fonctions `sortNumbersInAscendingOrder` et `sortNumbersInDescendingOrder` qui prendront un tableau de nombres entiers et retourneront un tableau trié dans l'ordre indiqué.
