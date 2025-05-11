# Day 5 - 流程控制（二）：函式定義、表達式與箭頭函式

## 🧠 目標整理
- 熟悉 JS 中各種函式定義方式
- 了解函式作用域與 hoisting 行為
- 熟練箭頭函式的語法與 this 特性

---

## ✅ 函式定義方式總覽

### 📌 傳統函式聲明（Function Declaration）

```js
function greet(name) {
  return `Hello, ${name}!`
}
```

- 可被 hoist（提升）至作用域頂部
- 適合一般函式定義

---

### 📌 函式表達式（Function Expression）

```js
const greet = function(name) {
  return `Hello, ${name}!`
}
```

- 不能被 hoist（變數提升但值為 undefined）
- 適用需要根據條件動態指定的情境

---

### 📌 箭頭函式（Arrow Function）

```js
const greet = (name) => `Hello, ${name}!`
```

- 語法簡潔
- 不會綁定自己的 `this`
- 不具備 `arguments`、不能用作 constructor

---

## 🆚 傳統函式 vs 箭頭函式

| 特性           | 傳統 function     | 箭頭函式              |
|----------------|-------------------|------------------------|
| `this` 綁定    | 根據呼叫方式      | 由外部作用域決定      |
| `arguments` 可用 | ✅ 可使用         | ❌ 無 `arguments`     |
| 可作 constructor | ✅               | ❌                   |
| 可被 hoist     | ✅               | ❌（表達式不能提升） |

---

## 📚 實作範例

### ✅ 使用箭頭函式搭配陣列迭代

```js
const numbers = [1, 2, 3]
const squared = numbers.map(n => n * n)
console.log(squared) // [1, 4, 9]
```

---

## 🧪 小挑戰練習

### 🔸 寫出一個 `sum` 函式，可以傳入任意數量參數並回傳總和。

```js
const sum = (...args) => args.reduce((a, b) => a + b, 0)
```

---

## 🧩 小測驗

1. 箭頭函式是否能作為 constructor？
2. `function greet() {}` 與 `const greet = function() {}` 的 hoisting 行為有何不同？
3. 箭頭函式內部的 `this` 是如何決定的？

---
