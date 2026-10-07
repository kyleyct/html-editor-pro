# HTML Editor Pro

線上 HTML 編輯器：貼上或編寫 HTML、即時預覽、於預覽區直接改字，並可匯出 PDF。

**示範：** https://kyleyct.github.io/html-editor-pro/  
（純靜態前端；請以實際開啟結果為準。）

## 功能

- HTML 原始碼編輯 + iframe 即時預覽
- 預覽區直接點擊標題／段落修改文字，再同步回 HTML
- 複製 HTML、匯出 PDF
- 深色／淺色模式
- 以 lz-string 等前端庫輔助（見 `index.html`）

## 使用

1. 開啟 [GitHub Pages](https://kyleyct.github.io/html-editor-pro/)，或
2. Clone 後用本機靜態伺服器開啟 `index.html`：

```bash
git clone https://github.com/kyleyct/html-editor-pro.git
cd html-editor-pro
python3 -m http.server 8080
# 瀏覽器開啟 http://localhost:8080/
```

## 技術

- 單頁 `index.html`（繁中介面）
- 瀏覽器端處理，無後端上傳

## 授權

未於 repo 宣告授權時，使用前請先向作者確認，或自行補上 MIT／合適授權。
