# Контрольная работа по JavaScript (Пересдача)

## 1. Определение типа данных  
**Задание:**  
Напишите функцию `checkType(value)`, которая принимает аргумент и возвращает его тип данных.  

**Пример работы:**
```js
console.log(checkType(42));        // "number"
console.log(checkType("hello"));   // "string"
console.log(checkType(true));      // "boolean"
console.log(checkType(null));      // "object"
console.log(checkType(undefined)); // "undefined"
console.log(checkType({}));        // "object"
console.log(checkType([]));        // "object"
console.log(checkType(function() {})); // "function"
```

---

## 2. Разворот строки  
**Задание:**  
Напишите функцию `reverseString(str)`, которая принимает строку и возвращает её задом наперёд.  

**Пример работы:**  
```js
console.log(reverseString("hello")); // "olleh"
console.log(reverseString("JavaScript")); // "tpircSavaJ"
```

---

## 3. Проверить, содержит ли массив заданный элемент (без includes)  
**Задание:**  
Напишите функцию `includesElement(arr, element)`, которая принимает массив и значение, а затем проверяет, есть ли элемент в массиве.  
**Важно:** использовать `includes()` нельзя!  

**Пример работы:**  
```js
console.log(includesElement([1, 2, 3, 4], 3)); // true
console.log(includesElement(["apple", "banana", "cherry"], "grape")); // false
```

---

## 4. Разворот массива (без reverse)  
**Задание:**  
Напишите функцию `reverseArray(arr)`, которая принимает массив и возвращает новый массив, в котором элементы идут в обратном порядке.  
**Важно:** использовать `reverse()` нельзя!  

**Пример работы:**  
```js
console.log(reverseArray([1, 2, 3, 4])); // [4, 3, 2, 1]
console.log(reverseArray(["a", "b", "c"])); // ["c", "b", "a"]
```

---

## 5. Найти два наибольших числа в массиве  
**Задание:**  
Напишите функцию `findTwoMax(arr)`, которая принимает массив чисел и возвращает два самых больших числа в виде массива `[max1, max2]`, где `max1` — самое большое число, а `max2` — второе по величине.  

**Пример работы:**  
```js
console.log(findTwoMax([3, 7, 2, 9, 5])); // [9, 7]
console.log(findTwoMax([-10, -3, -20, -5])); // [-3, -5]
```

---

**Удачи на пересдаче!** 😎
