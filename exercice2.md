# Exercice #02

Vous allez faire une petite page HTML dans le but de faire des opérations sur les chaînes de caractères et faire découvrir les méthodes des `String`.

# Références

* ASCII Table: https://www.alpharithms.com/ascii-table-512119/
* JavaScript String: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String

# Instructions

1. Créer une fonction `displayEachLetterAsciiCode` qui prendra une chaîne de caractères en paramètre et affichera chaque `caractère` ainsi que son code ASCII associé grâce à un `console.log`.
```js
displayEachLetterAsciiCode("Hello");
// H = 72
// e = 101
// l = 108
// l = 108
// o = 111
```
2. Créer une fonction `capitalize` qui met la première lettre d'une chaîne de caractères en majuscule.
  * `const capitalizedString = capitalize("hello"); // "Hello" `
3. Créer une fonction `uncapitalize` qui fait l'inverse de la fonction précédente.
3. Créer une fonction `reverseString` qui prend une chaîne de caractères et l'inverse.
  * `const reversedString = reverseString("Hello"); // "olleH"`

4. Créer une fonction `isPalindrome` qui vérifiera si une chaîne de caractères est un palindrome ou non (la fonction doit être `case insensitive`).
```js
isPalindrome("Hello"); // false
isPalindrome("laval"); // true
isPalindrome("Laval"); // true
```

5. Créer une fonction `isInteger` qui vérifiera si la chaîne de caractère est un nombre entier ou non.
6. Créer une fonction `isNumber` qui vérifiera si la chaîne de caractère est un nombre ou non.
7. Créer une fonction qui prend une chaîne de caractères et qui retourne cette `String` en tant que `Number` si la chaîne de caractères est un nombre sinon retourné `null`.
9. Créer une fonction `isAlpha` qui vérifiera si la chaîne de caractère contient seulement des lettres ou non.
10. Créer une fonction `isZipCode` qui vérifiera si la chaîne de caractère est un code postal canadien valide ou non (e.g. J3R3L3).
11. Créer une fonction `contains` qui vérifiera si une chaîne de caractère contient une autre chaîne de caractère.
  * `contains("Hello World", "World"); // true`

10. Faites une page HTML permettant d'appeler certains fonctions pour vous pratiquer (e.g. un champs de texte et un bouton pour valider le code postal, etc.).

