
## ✅ Day 4 - 流程控制：if、switch、loop（流程控制）

### 🔁 條件分支：if / else if / else
```js
let score = 85;
if (score >= 90) {
  console.log("A");
} else if (score >= 80) {
  console.log("B");
} else {
  console.log("C");
}
```

📎 **面試常見問法：**
- if/else 是否可寫成三元運算？有何時機該使用？
- 巢狀過多的 if/else 如何改寫？（可以考慮 early return 或 switch）

### 🧠 三元運算子（Ternary Operator）
```js
let age = 18;
let access = age >= 18 ? "允許" : "拒絕";
```

### 🔀 switch 語法
```js
let fruit = "banana";
switch (fruit) {
  case "apple":
    console.log("蘋果");
    break;
  case "banana":
    console.log("香蕉");
    break;
  default:
    console.log("未知水果");
}
```
✅ `switch` 適合多條件分支，**記得加 `break`，否則會 fall-through**。

📎 **面試可能問：** switch 與 if 差異何在？

### 🔁 常見迴圈：for / while / do...while
```js
// for loop
for (let i = 0; i < 3; i++) {
  console.log(i);
}

// while loop
let count = 0;
while (count < 3) {
  console.log(count);
  count++;
}

// do...while loop
let num = 0;
do {
  console.log(num);
  num++;
} while (num < 3);
```

📎 **面試常見問法：**
- 哪個迴圈執行至少一次？（答：do...while）
- 怎麼中斷迴圈？（答：`break`）
- 怎麼跳過某次？（答：`continue`）

### 🔁 for...of / for...in
```js
let arr = ["a", "b", "c"];
for (let item of arr) {
  console.log(item); // 值
}

let obj = { x: 1, y: 2 };
for (let key in obj) {
  console.log(key, obj[key]); // 鍵與值
}
```

📎 **面試補充知識：**
- `for...of` 走陣列的值（可搭配 `Symbol.iterator`）
- `for...in` 走物件的 key（含 prototype）
