# 會員資訊

## 顯示會員基本資訊

1. 登入或註冊後，進入會員資訊頁面
2. 系統呼叫查詢會員資訊 API
3. 顯示會員資訊

## URL

  /member/:memberID

## Method

  `GET`
  
## URL Params

   **Required:**

   `id=[integer]`

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
