---
title: Match a Literal String with Different Possibilities
localeTitle: Сопоставьте литеральную строку с различными возможностями
---
## Сопоставьте литеральную строку с различными возможностями

Предположим, вы хотите совместить много разных слов с вашим регулярным выражением; используя `|` символ, который становится возможным. В этой задаче вы используете этот символ, чтобы идентифицировать четырех разных животных, скрытых внутри строк!

## Подсказка 1:

Внутри строкового литерала поместите имена домашних животных, каждый из которых разделен символом `|` условное обозначение.

## Оповещение о спойлере - решение впереди!

## Решение:

```js
let petString = "James has a pet cat."; 
 let petRegex = /dog|cat|bird|fish/; 
 let result = petRegex.test(petString); 

```