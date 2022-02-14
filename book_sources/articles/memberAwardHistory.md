# 會員獎項記錄查詢

## 查詢每日任務及龍虎榜中獎資訊

1. 會員資訊頁面，點擊獎項紀錄
2. 系統呼叫查詢每日任務及龍虎榜中獎資訊 API
3. 顯示資訊在頁面上

## URL

  /member/history/award/:memberID

## Method

  `GET`
  
## URL Params

   **Required:**

   `memberID=[integer]`

## Data Params

  None

## Success Response

* **Code:** 200
 **Content:** `{ id : 12, name : "Michael Bloom" }`

## Error Response

* **Code:** 404 NOT FOUND
  **Content:** `{ error : "User doesn't exist" }`

OR

* **Code:** 401 UNAUTHORIZED
  **Content:** `{ error : "You are unauthorized to make this request." }`
