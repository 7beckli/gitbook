# 會員錢包資訊

## 查詢會員各種遊戲內錢包資訊

1. 從會員
2. 系統呼叫查詢會員錢包資訊 API
3. 查詢 CM 內 GC 及 CMD 的數量

## URL

  /member/wallet/:memberID

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
