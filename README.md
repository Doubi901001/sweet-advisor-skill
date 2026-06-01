# Travel Choice Helper

## 專案名稱

Travel Choice Helper：AI旅行選擇困難救星

---

## 專案簡介

許多人在旅遊時經常面臨選擇困難，不知道該去哪裡、吃什麼、喝什麼咖啡或選擇哪一家甜點店。

Travel Choice Helper 是一個結合 AI 決策邏輯與 Google Maps 搜尋功能的旅遊輔助工具，使用者只需輸入所在地、同行對象、當下心情與預算，系統便會分析需求並提供最適合的探索方向。

本專案旨在協助旅客快速縮小選擇範圍，減少搜尋時間，讓選擇困難症的人不用提前做功課也能輕鬆旅遊。

---

## 專案特色

* AI旅行決策分析
* 支援任意縣市搜尋
* 根據心情推薦適合的探索方向
* 根據旅遊情境進行決策
* 提供 Google Maps 搜尋連結
* 提供 Instagram 打卡照片搜尋
* 提供「🎲 我選不出來，直接幫我決定」功能
* 協助選擇困難旅客快速做出決策
* 不虛構店家資訊

---

## 使用流程

### Step 1

輸入目前所在縣市

例如：

* 台南市
* 嘉義市
* 南投縣
* 屏東市

### Step 2

選擇同行對象

* 自己
* 情侶
* 朋友
* 家人

### Step 3

選擇目前心情

* 想放鬆
* 想拍照
* 想喝咖啡
* 想吃甜點
* 想冒險
* 不知道

### Step 4

選擇預算

* 300元以下
* 300~600元
* 600元以上

### Step 5

取得 AI 推薦結果

系統會根據輸入條件產生：

* 推薦方向
* 推薦原因
* Google Maps 搜尋連結
* Instagram 搜尋連結

---

## 🎲 我選不出來模式

當使用者完全不知道要去哪裡時，可以直接使用：

🎲 我選不出來，直接幫我決定

系統將從以下方向隨機推薦：

* 老宅咖啡廳
* 景觀咖啡廳
* 特色甜點店
* 千層蛋糕
* 布丁
* 提拉米蘇
* 檸檬塔
* 可麗露
* 巴斯克乳酪蛋糕
* 文青咖啡廳
* 巷弄咖啡廳
* 隱藏版甜點店

---

## Skill 說明

Skill 位於：

```text
skill/SKILL.md
```

內容包含：

* Goal
* Semantic Trigger
* Required Input
* Workflow
* Success Criteria
* Output Format

---

## 作品檔案

```text
index.html
```

功能包含：

* AI旅行分析
* Google Maps搜尋
* Instagram搜尋
* 隨機推薦系統

---

## Repository 結構

```text
travel-choice-helper
│
├── README.md
├── index.html
│
└── skill
    └── SKILL.md
```

---

## 使用工具

* ChatGPT
* GitHub
* HTML
* CSS
* JavaScript

---

## 注意事項

本系統不直接提供店家評分與營業資訊。

建議使用者透過 Google Maps 搜尋結果，優先選擇：

1. 評分 4.5 顆星以上店家
2. 距離目前位置最近的前三家店
3. Instagram 打卡數較高的熱門店家

實際店家資訊、營業時間、評價與距離，請以 Google Maps 顯示內容為準。
