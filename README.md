# LALA LAND 前台 v11：手機版 + 對話工具列

## 更新重點
- 手機開啟時會自動縮小成適合手機閱讀的聊天版面。
- 每則對話新增「重新生成／編輯／複製」按鈕。
- 設定中新增「狀態列格式」，玩家可自行修改，修改後會同步前台顯示，也會送入 Gemini 提示。
- PC 頭像仍使用「檔案」上傳；每個角色可以有多個 PC。
- 已加入現代小說式沉浸文筆包與古風文筆包，作為 Gemini 回覆時的底層風格指令。
- 不使用 Cloudflare Worker；玩家使用自己的 Gemini API Key 直接呼叫 Gemini。

## GitHub 使用方式
把本資料夾內所有檔案直接上傳到 GitHub repo 最外層：

- index.html
- chat.html
- style.css
- app.js
- chat.js
- characters.json
- strix_avatar.jpeg
- strix_cover.jpeg
- gu_yu_avatar.jpeg
- gu_yu_cover.jpeg
- README.md

不要只上傳 ZIP 檔本身。

## 注意
純前端版本只能做到「畫面上不顯示角色資料」。因為沒有後端，任何放在前端的資料都有可能被懂技術的人從原始碼看到。
