---
title: Homework for Lesson 01
summary: Excercise for variables, strings and numbers
date: '2020-02-06'
tags:
  - homework
  - variables
  - strings
  - numbers
---
### Challenge 01: Variables & Strings

1. Choose your favorite character from movie, tv, book, game, etc..
2. Create and fill in following variables based on your character: first name, last name, alias, city, country and source (movie, tv, book, game, etc..)
3. Create variable with name "my favorite character" which will have all information created in last step, separated by comma and space. The first and last name will have only space in between.
4. Output the last variable to console.

__Solution:__
```javascript
let firstName = 'Tony'
let lastName = 'Stark'
let alias = 'Iron Man'
let city = 'New York'
let country = 'United States'
let origin = 'Avengers'
// put them all together
let myFavoriteCharacter = firstName + ' ' + lastName + ', ' + alias + ', ' + city + ', ' + country + ', ' + origin
console.log(myFavoriteCharacter)
// output
Tony Stark, Iron Man, New York, United States, Avengers
```

- - -

### Challenge 02: Numbers

1. Create variables named doggo age and hooman age
2. Calculate dog age in human years inside hooman age variable using this formula:<br> 1 Dog year is 7 Human years
3. Output the hooman age to the console.

__Solution (if dog is 4 years old):__
```javascript
let doggoAge = 4
let hoomanAge = doggoAge * 7
// show output
console.log(hoomanAge)
// result
28
```

- - -


[Back Home](/)