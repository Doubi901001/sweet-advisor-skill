# Local Flavor Finder Skill

## Goal

協助使用者在不同縣市快速找到當地有名或有特色的咖啡廳、甜點店，並透過 Google Maps 與 Instagram 搜尋即時地點與照片資訊，減少一個一個慢慢查找的搜尋時間。

---

## Semantic Trigger

當使用者提到以下內容時啟動：

- 推薦咖啡廳
- 推薦甜點店
- 附近咖啡廳
- 附近甜點店
- 在地特色店家
- 不知道去哪裡
- 想找拍照咖啡廳
- 想找特色甜點
- Google Maps 搜尋店家
- Instagram 打卡店家

---

## Required Input

1. 所在縣市  
   - 例如：嘉義市、南投縣、台南市

2. 搜尋關鍵詞  
   - 例如：特色咖啡廳、甜點店、老宅咖啡、千層蛋糕、布丁、檸檬塔

---

## Workflow

### Step 1

確認使用者輸入的縣市。

### Step 2

確認使用者想搜尋的關鍵詞。

### Step 3

組合搜尋語句：

```text
縣市 + 關鍵詞
