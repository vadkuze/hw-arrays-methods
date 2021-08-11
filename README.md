# hw-arrays-methods

## Темы на повторения 
[Методы массива](https://learn.javascript.ru/array-methods)

[Функции](https://learn.javascript.ru/function-basics)

[Function Expression](https://learn.javascript.ru/function-expressions)

[Функции-стрелки, основы](https://learn.javascript.ru/arrow-functions-basics)


## Задачи

Задача 1. Напишите ф-цию `transformString(string)` которая должна работать так:
  - `transformString('ForEsT') // output: [true, false, false, true, false, true]` (`true` соответствует верхнему регистру). 
  - еще пример `transformString('ABC') // output: [true, true, true]`.


Задача 2. Напишите ф-цию `filterWordCase(string, actionFn)` которая должна работать так:

 - `filterWordCase('ForEsT', (letter) => letter === letter.toUpperCase())  // output "FET!"`
 - или так `filterWordCase('ForEsT', (letter) => letter === letter.toLowerCase())  // output "ors!"`


Задача 3. Напишите ф-цию `sumAllLengths(stringsArray)` которая будет суммировать длину каждого слова в массиве. Работать должно так:
  - `sumAllLengths(["I'm", "a", "JavaScript", "Developer"]) // output 23`
  - `sumAllLengths([]) // output 0`

**P.S Вместо `for` используйте методы массива!**




### Необязательное дополнительное задание 

Напишите функцию sortFn(array, callback) , которая работает подобно классической sort. Метод `sort` использовать нельзя. 

Код для проверки
 ```
let arr = [1, 2, 3, 1, 0, 10, 7];
console.log( sortFn(arr, (a,b) => a - b) ); // [0,1,1,2,3,7,10]

// классическая sort
console.log( arr.sort((a,b) => a - b) ); // [0,1,1,2,3,7,10]
```



