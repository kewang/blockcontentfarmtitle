# 內容農場標題退散

貼到粉絲頁上面必須要有 access token，所以使用 https://developers.facebook.com/tools/explorer，應用程式及 access token 都選擇"內容農場標題退散"

## 流程

### 第一種

用戶傳訊息給 bot，bot 收到後確認是否為文字+圖片，若為文字+圖片則貼到粉絲頁上面，其他則不處理

### 第二種

用戶傳訊息給 bot，bot 收到後如果只有文字或圖片，就使用 dialog 的方式處理。

可以試看看 serverless，先把文字存起來，同個使用者若上傳圖片就把前一個文字加上去後貼到粉絲頁上
