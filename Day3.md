
## ✅ Day 3 - 型別轉換、比較與條件式

### 📌 主題涵蓋：
- 隱式與顯式型別轉換
- `==` 與 `===` 差異（== 有型別轉換）
- `Boolean()`、`Number()`、`String()` 明確轉型
- 假值（Falsy）與真值（Truthy）
- 條件式：`if`、`else if`、`else`、`三元運算子`

### ✅ 重點範例：
```js
Boolean(0)       // false
Boolean("hello") // true

Number("123")   // 123
Number("abc")   // NaN

"5" == 5   // true
"5" === 5  // false

let age = 18;
let status = age >= 18 ? "Adult" : "Minor";
```

### ❗ 常見陷阱：
```js
false == 0       // true
null == undefined // true
null === undefined // false

Number(null) => 0
Number(undefined) => NaN
```

### 🧠 小測驗：
1. `Number(" ")` 結果是什麼？為什麼？
2. `null == 0` 結果是什麼？
3. `!!"0"` 是 true 還是 false？為什麼？
