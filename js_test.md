# 📌 Контрольная работа по основам JavaScript  

> **📅 Внимание:**  
> Это контрольная работа по основам JavaScript курса Hexlet. В ней 10 задач, расположенных по возрастанию сложности. 
> Не спешите. Внимательно читайте задания и подходить к решению постепенно. Если затрудняетесь в решении задачи, то перейдите к следующей, и вернитесь к заданию позже. 

## 🟢 1. Типы данных  

**Что выведет следующий код? Объясните почему.**  

```js
console.log(typeof 42);
console.log(typeof "42");
console.log(typeof true);
console.log(typeof null);
console.log(typeof undefined);
console.log(typeof {});
console.log(typeof []);
console.log(typeof function() {});
```

---

## 🟢 2. Работа со строками  

**Напишите функцию, которая переворачивает строку.**  

```js
function reverseString(str) {
  // Ваш код
}

console.log(reverseString("hello")); // "olleh"
```

---

## 🟡 3. Арифметические операции  

**Что выведет код? Объясните почему.**  

```js
console.log(5 + "5");  
console.log("10" - 2);  
console.log(6 * "3");  
console.log("4" / 2);  
console.log(10 % "3");  
console.log("5" - "2" + "1");
```

---

## 🟡 4. Неизменяемость и примитивные типы данных  

**Что выведет код и почему?**  

```js
let a = "hello";
let b = a;
b = "world";
console.log(a);  
console.log(b);
```

---

## 🟡 5. Функции и их параметры  

**Напишите функцию `sum(a, b, c)`, которая складывает три числа. Если одно из них не передано, оно считается равным `0`.**  

```js
function sum(a, b, c) {
  // Ваш код
}

console.log(sum(5, 10)); // 15  
console.log(sum(3)); // 3  
console.log(sum()); // 0  
```

---

## 🟠 6. Циклы и работа с массивами  

**Напишите функцию, которая находит максимальное число в массиве.**  

```js
function findMax(arr) {
  // Ваш код
}

console.log(findMax([1, 5, 2, 9, 3])); // 9
```

---

## 🟠 7. Условные операторы и switch  

**Напишите функцию `getSeason(month)`, которая принимает номер месяца и возвращает время года.**  

```js
function getSeason(month) {
  // Ваш код
}

console.log(getSeason(3));  // "Весна"
console.log(getSeason(12)); // "Зима"
```

---

## 🔵 8. Циклы for..of и обработка строк  

**Напишите функцию, которая считает количество гласных букв (a, e, i, o, u) в строке.**  

```js
function countVowels(str) {
  // Ваш код
}

console.log(countVowels("JavaScript")); // 3
console.log(countVowels("Hello World")); // 3
```

---

## 🔵 9. Продвинутая работа с числами и циклами  

**Напишите функцию, которая проверяет, является ли число простым.**  

```js
function isPrime(n) {
  // Ваш код
}

console.log(isPrime(7));  // true
console.log(isPrime(10)); // false
```

---

## 🔴 10. Функции высшего порядка и массивы  

**Напишите функцию `mapArray(arr, fn)`, которая применяет функцию `fn` к каждому элементу массива.**  

```js
function mapArray(arr, fn) {
  // Ваш код
}

function square(x) {
  return x * x;
}

console.log(mapArray([1, 2, 3, 4], square)); // [1, 4, 9, 16]
```

---

**📌 Удачи на контрольной! 🚀**
