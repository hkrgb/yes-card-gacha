# 香港扭卡機

獨立 HTML 小遊戲。玩家預設有 200 分，每次扭卡消耗 200 分；卡片固定使用直向 2:3。

- 遊戲：`index.html`
- 管理後台：`admin.html`
- Firebase：`yes-card-gacha-rgb`
- 完成／返回故事時送出：`window.parent.postMessage({complete:true, score:credits}, '*')`

後台只允許已驗證的 `info@rgb-workshop.com` 登入，可修改卡機封面、起始分數、抽卡費用、所有前台文字，以及新增或刪除卡片款式、圖片、稀有度和抽中權重。
