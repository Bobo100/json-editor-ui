# Front-End-Modify-JSON

在瀏覽器裡篩選 JSON 欄位的小工具：上傳一份 JSON 陣列，勾選要保留的欄位，再匯出只剩這些欄位的 JSON。

## 狀態

2023 年的練習作品(從明日方舟抽卡專案拆出來),已不再加新功能，目前沒有線上 demo。

## 使用方式

1. 選擇一個 JSON 檔(內容是物件陣列)
2. 勾選每個物件要保留的欄位
3. 按「Export json」,下載 `filteredData.json`

`src/json/` 裡是明日方舟幹員資料的範例檔，可以拿來試。

## 本機執行

```bash
npm install
npm start   # http://localhost:3000
```

技術:Vite、React 19、TypeScript。樣式的 `.scss` 是手動編譯成旁邊的 `.css` 再 import(專案沒有裝 sass)。
