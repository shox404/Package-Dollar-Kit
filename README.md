<code>$filter(array, searchText, key)</code>

```js
let items = ["laptop", "to year", "pen"];

console.log($filter(items, "to"));
// [ "laptop", "to year" ]
```

```js
let items = [
  { name: "laptop", key: "property" },
  { name: "to year", key: "property" },
  { name: "pen", key: "property" },
];

console.log($filter(items, "to", "name"));
// [{ name: "laptop" }, { name: "to year" }]
```

---

<code>$abc()</code>

```js
console.log($abc());
// [a, .., z]
```

---

<code>$number(from, to)</code>

```js
console.log($number(-3, 5));
// [-3, -2, -1, 0, 1, 2, 3, 4, 5]
```

---

<code>$getId(length)</code>

```js
console.log($getId(6));
// RlqQta
```

---

<code>$percentage(number, mainNumber)</code>

```js
console.log($percentage(2, 4));
// 50
```

---

<code>$capitalize(text)</code>

```js
console.log($capitalize("hello world"));
// Hello world
```

---

<code>$randomInt(minNumber, maxNumber)</code>

```js
console.log($randomInt(5, 10));
// random number: 7
```

---

<code>$total(array, number)</code>

```js
let array = [4, 3];

console.log($total(array));
// 7
```

```js
let array = [{ count: 4 }, { count: 3 }];

console.log($total(array, "count"));
// 7
```

---

<code>$formatNumber(number)</code>

```js
console.log($formatNumber(4000000));
// 4 000 000
```

---

<code>$shuffleArray(array)</code>

```js
let array = ["first", "second", "third"];

console.log($shuffleArray(array));
// [ "third", "first", "second" ]
```

---

<code>$truncateString(text, length)</code>

```js
console.log($truncateString("Hello world", 3));
// Hel...
```

---

<code>$is</code>

```js
console.log($is.odd(3));
// true
```

```js
console.log($is.even(3));
// false
```

```js
console.log($is.null(null));
// true
```

```js
console.log($is.undefined(undefined));
// true
```

---

<code>$uniqueArray(array)</code>

```js
let array = [1, 2, 3, 3, 4, 5, 5, 5];

console.log($uniqueArray(array));
// [1, 2, 3, 4, 5]
```

---

<code>$reverseText()</code>

```js
console.log($reverseText("Hello"));
// olleH
```

---

<code>$padStart(text, length, char)</code>

```js
console.log($padStart("Hello", 10, "-"));
// --Hello
```

---

<code>$padEnd(text, length, char)</code>

```js
console.log($padEnd("Hello", 10, "*"));
// Hello*****
```

---

<code>$randomItem(array)</code>

```js
let array = [1, 2, 3, 4, 5, 6];

console.log($randomItem(array));
// 3
```

---

<code>$formatDate(date)</code>

```js
console.log($formatDate("2008-04-30"));
// Wed Apr 30 2008
```
