
## ✅ Day 2 - 變數、型別、typeof 與動態語言特性

### 📌 主題涵蓋：
- `let` / `const` / `var` 差異
- 動態型別語言：變數可以變型別
- 七種 Primitive Type：string, number, boolean, null, undefined, bigint, symbol
- Object 是非 primitive 型別

### ✅ 關鍵範例：
```js
let a = 123;
a = "hello"; // 合法！因為 JS 是動態型別

const PI = 3.14;
// PI = 3.15; ❌ 錯誤：const 不能重新賦值

let user = { name: "Amy" };
user.name = "Bob"; // ✅ OK
```

### 🔍 `typeof` 特例：
```js
typeof null        // 'object' (歷史遺留 bug)
typeof NaN         // 'number'
typeof function()  // 'function'
```

### 🧠 小測驗：
1. `typeof []` 是什麼？
2. const 宣告的物件能不能改內容？
3. let 宣告的變數，在使用前是否會 Hoisting？
