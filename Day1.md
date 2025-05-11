
## ✅ Day 1 - JS 起手式與 Console 工具介紹

### 📌 主題涵蓋：
- JavaScript 起源與應用場景
- 如何在瀏覽器使用 console
- `alert`, `prompt`, `confirm` 差異
- `console.log()` 的基礎用法
- 如何開啟 Chrome DevTools

### ✅ 關鍵概念：
```js
alert("Hello");
console.log("This is JS");
let name = prompt("What's your name?");
let isOk = confirm("Do you want to continue?");
```

### 💡 小提醒：
- `prompt()` 會回傳字串
- `confirm()` 回傳布林值（true/false）

### 🌍 JavaScript 是什麼？
JavaScript 是一種 **腳本語言**，專門為了網頁設計，能讓靜態 HTML 頁面變得 **互動且動態**。它能控制：
- 頁面元素變化（DOM）
- 使用者互動（滑鼠、鍵盤事件）
- 資料存取（API 請求、表單）
- 動畫、音效、遊戲邏輯等

### 📜 歷史由來
- 1995 年由 Netscape 的 Brendan Eich 開發，最初名為 LiveScript
- 因為當時 Java 熱門，為了行銷改名為 JavaScript（與 Java 語言實際無直接關聯）
- 目前由 ECMA（標準組織）維護，稱為 ECMAScript

### 🧪 怎麼執行 JavaScript？
1. **HTML 中插入 `<script>`**
```html
<script>
  alert('Hello JS');
</script>
```
2. **引入外部檔案**
```html
<script src="main.js"></script>
```
3. **瀏覽器開發者工具（DevTools）Console 模式**
- 在 Chrome 按 F12 > Console 標籤即可輸入程式碼互動

### 💬 互動彈窗函式：
```js
alert("純顯示訊息");
prompt("請輸入年齡"); // 回傳字串
confirm("確定刪除嗎？"); // 回傳 true / false
```

### 🧰 Console 開發技巧
```js
console.log("資訊");
console.warn("警告");
console.error("錯誤");
console.table([{ name: "Amy" }, { name: "Bob" }]);
```

### 📎 面試可能提問：
- JS 與 Java 有什麼關聯？（幾乎無）
- 如何在瀏覽器中執行 JS？（三種方式）
- DevTools 中有哪些 console 方法？（log/warn/error/table...）

---
