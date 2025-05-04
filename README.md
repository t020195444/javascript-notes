# JavaScript.info 精讀計畫 Day 1：變數與資料型別

## 📘 主題：變數與資料型別（Variables and Data Types）

### ✅ 你需要掌握的重點：
1. 變數宣告方式：`let` / `const` / `var` 差異
2. 資料型別：Primitive（基本型） vs Object（物件型）
3. 動態型別（JavaScript 是 dynamically typed）
4. `typeof` 操作與特殊案例

### `let` vs `const` vs `var`
- `let`: 可重新賦值，不可重複宣告，區塊作用域（block scope）
- `const`: 必須初始化、不可重新賦值，區塊作用域
- `var`: 可以重複宣告、函式作用域（function scope），有 hoisting 行為（提升）

### 資料型別分類
- **Primitive**: string, number, boolean, null, undefined, symbol, bigint
- **Object**: object, array, function（函式也是物件）

### `typeof` 特例
```js
typeof null // "object"
typeof NaN // "number"
typeof function(){} // "function"
```

### 練習題
1. `console.log(a); var a = 5;` → `undefined`
2. `const name; name = 'Herry';` → ❌ 錯誤：const 必須初始化
3. `typeof` 題：
```js
typeof undefined // "undefined"
typeof null      // "object"
typeof NaN       // "number"
typeof [1,2,3]   // "object"
```
