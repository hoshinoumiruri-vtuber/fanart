# 星ノ海琉璃 Fan art

收集大家送給星ノ海琉璃的圖。感謝每一位繪師。
A collection of fan art for Hoshinoumi Ruri. Thank you to every artist.
星ノ海琉璃へのファンアートを集めています。描いてくださったすべての方に感謝します。

這些圖的著作權屬於各位繪師，請不要轉載、加工或用於 AI 學習。
The copyright of each picture belongs to its artist. Please do not repost, edit or use them for AI training.
各イラストの著作権は描いてくださった方にあります。無断転載・加工・AI学習への利用はご遠慮ください。

網站：<https://hoshinoumiruri-vtuber.github.io/fanart/>

## 資料夾

| 資料夾 | 放什麼 |
|---|---|
| `general/` | 一般的 fan art，沒有特定主題（出道祝賀、生日快樂、紀念圖都放這裡） |
| `themes/<主題>/` | 有主題的企劃，一個主題一個資料夾，例如 `outfit-prediction-2026/` 是 2026 年新衣裝的預測圖 |
| `works.json` | 每張圖的作者、標題、主題。網站從這裡讀 |

## 檔名

`作者_內容.副檔名`，例如 `想貓_生日快樂.jpg`。不知道作者就寫 `作者不明_內容`。同一張圖有兩個版本（例如有字和無字）時，在 `works.json` 的 `alt` 指向第二個檔案，網站會做成可以切換。

## 新增一張圖

1. 把圖放進 `general/`（或某個主題的資料夾）。
2. 在 `works.json` 的 `works` 補一筆：`file`、`artist`、`zh`（中文標題，可空白）、`ja`（日文標題，可空白）。
3. 有新的主題企劃時，在 `themes` 加一個主題，並建同名資料夾。

直接把圖丟進資料夾、沒有補 `works.json` 也可以，網站仍會顯示（作者從檔名取），只是少了標題。
