# 貓窩裏 到府寵物褓姆 系統說明

## 📁 檔案一覽

| 檔案 | 用途 |
|------|------|
| `index.html` | 客戶預約前台（公開分享） |
| `admin.html` | 管理員後台（內部使用） |
| `sitter.html` | 保母專區（保母個人登入） |

---

## 🔐 帳號密碼

**後台管理員**
- 密碼：`chch715715`

**保母個人密碼**（可自行修改 sitter.html 內的 pw 值）

| 保母 | 密碼 |
|------|------|
| May | may0001 |
| Ying | ying0002 |
| 小汶 | xiaowen0003 |
| 菓菓 | guoguo0004 |
| 小茹 | xiaoru0005 |
| 阿瑛 | aying0006 |

---

## 🚀 上架到 GitHub Pages（免費）

### 第一步：建立 GitHub 帳號
1. 前往 https://github.com
2. 點「Sign up」建立帳號並驗證 Email

### 第二步：建立新 Repository
1. 登入後點右上角「＋」→「New repository」
2. Repository name 填：`maowo`（或自訂）
3. 選擇「**Public**」（必須是 Public）
4. 點「Create repository」

### 第三步：上傳三個檔案
1. 進入剛建立的 Repository
2. 點「Add file」→「Upload files」
3. 把 `index.html`、`admin.html`、`sitter.html` 三個一起拖進去
4. 點底部「Commit changes」

### 第四步：開啟 GitHub Pages
1. 點 Repository 的「Settings」
2. 左側點「Pages」
3. Source 選「Deploy from a branch」
4. Branch 選「**main**」，資料夾選「**/ (root)**」
5. 點「Save」

### 第五步：等待（約 1-3 分鐘）
網址會出現：
```
✅ Your site is live at https://你的帳號.github.io/maowo/
```

---

## 🔗 分享網址

```
客戶預約頁：  https://你的帳號.github.io/maowo/
管理員後台：  https://你的帳號.github.io/maowo/admin.html
保母專區：    https://你的帳號.github.io/maowo/sitter.html
```

---

## ⚠️ 重要注意事項

1. **資料儲存**：訂單存在瀏覽器 localStorage，**建議固定使用同一台電腦**的後台
2. **後台網址**不要公開，自行收藏即可
3. **保母密碼**如需修改，直接編輯 `sitter.html` 中的 pw 欄位後重新上傳
4. LINE 帳號：`@099nuhen`（需已啟用 LINE 官方帳號）

---

## 📝 更新檔案

1. 修改本地端的 html 檔案
2. 進入 GitHub Repository
3. 點要更新的檔案 → 右上角鉛筆圖示 → 貼上新內容 → Commit
4. **或**點「Add file」→「Upload files」→ 重新上傳同名檔案（會自動覆蓋）
5. 約 1 分鐘後自動更新
