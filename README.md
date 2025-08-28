# LINE 文案一鍵去(emoji) 清理器 · v15.1（GitHub Pages 版）

單一 `index.html`，無後端、純前端。直接丟到 GitHub，開啟 GitHub Pages 就能用。

## 部署步驟
1. 新建 GitHub Repo（例如 `line-cleaner`）。
2. 上傳 `index.html` 與 `README.md` 到 **根目錄**。
3. 進 Repo → **Settings → Pages**：
   - Source: **Deploy from a branch**
   - Branch: **main / root**（根目錄）
4. 等約 1 分鐘，會有網址，例如 `https://<你的帳號>.github.io/line-cleaner/`。

## 參數預填
可用 URL 參數預填：`?store=成功漢神店&name=邱偉綸&phone=0978658101&lineid=myline&emp=362102`

## 版本重點
- v15.1：修正 `sinyi.in` 短網址覆蓋員編（不會出現兩個員編），長網址 `sinyi.com.tw/buy/house/...` 仍在物件 ID 後補入員編；其餘規則沿用 v15。
