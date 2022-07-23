# 2-3 A1 我的餐廳清單

一個可以在本地端運行的網頁，可以展示一系列的餐廳清單
網頁功能：
1. 使用者可以點擊感興趣的餐廳，觀看更詳細的資訊
2. 使用者可以搜尋餐廳名稱或餐廳類型，快速找到感興趣的餐廳

## Prerequisites - 環境建置與需求

這個專案使用 Node.js + express 作為 server 的運作環境，並使用 handlebars 作為模板引擎

- Node.js (專案開發時使用的版本為 v16.16.0）
- express (專案開發時使用的版本為 v4.16.4）
- express-handlebars (專案開發時使用的版本為 v3.0.0）

## Installation and execution - 安裝與執行步驟 

要在你的本地端運行此專案，請參考以下步驟

1. 下載專案
```
git clone https://github.com/kenkuo86/2-3_A1_restaurant_list.git
```

2. 打開終端機，移動到專案資料夾後，下載專案所需模組
```
npm install
```

3. 使用 nodemon 打開主程式 app.js
```
nodemon app.js
```

<span>此時 console 中應該會顯示 "server listen on http://localhost:3000"，代表專案已經正式開始運作囉！</span>

4. 瀏覽網頁
點開 http://localhost:3000，就可以看到「我的餐廳清單」
