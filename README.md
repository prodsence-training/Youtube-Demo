# GitHub Demo 專案

這是一個簡單的示範專案，用來教學如何透過 **Antigravity** 或 **VSCode** 從 GitHub Clone 專案到本地電腦。

## 📁 專案結構

```
Github-Demo/
├── README.md              (這個檔案)
├── docs/
│   └── getting-started.md (快速開始指南)
└── examples/
    └── example.txt        (示範檔案)
```

## 🚀 如何 Clone 本專案

### 方法 1：使用 Antigravity

Antigravity 是 GitHub 的 Web 編輯器，讓你可以在瀏覽器中編輯程式碼。

**步驟：**

1. 按下鍵盤快捷鍵 `.` (句號鍵) 或將 URL 中的 `github.com` 改為 `github.dev`
   - 例如：`https://github.dev/[username]/[repo-name]`

2. 你會看到 VSCode Web 介面

3. 點擊左側的「Source Control」圖標（三個圓點連線的圖標）

4. 點擊「Clone Repository」

5. 在搜尋框輸入此專案的 GitHub URL

6. 選擇本專案並開始編輯

**截圖說明：**

```
[預期截圖位置 1] - Antigravity 首頁面
[預期截圖位置 2] - Source Control 面板
[預期截圖位置 3] - Clone 對話框
```

---

### 方法 2：使用 VSCode

如果你已安裝 VSCode，可以直接在本地 Clone 專案。

**前置要求：**
- 已安裝 VSCode (下載：https://code.visualstudio.com/)
- 已安裝 Git (下載：https://git-scm.com/)

**步驟：**

1. 開啟 VSCode

2. 按 `Ctrl + Shift + P` (Windows/Linux) 或 `Cmd + Shift + P` (Mac) 開啟命令面板

3. 輸入 `Git: Clone` 並按 Enter

4. 在跳出的對話框中輸入本專案的 GitHub URL：
   ```
   https://github.com/[username]/Github-Demo.git
   ```

5. 選擇要儲存的本地資料夾位置

6. 點擊「Open」，VSCode 會自動開啟 clone 下來的專案

**截圖說明：**

```
[預期截圖位置 1] - VSCode 首頁面
[預期截圖位置 2] - 命令面板輸入 "Git: Clone"
[預期截圖位置 3] - 輸入 Repository URL 的對話框
[預期截圖位置 4] - 選擇本地資料夾位置
[預期截圖位置 5] - Clone 完成後的 VSCode 專案頁面
```

---

### 方法 3：使用命令列（進階用法）

如果你熟悉命令列，也可以使用 `git clone` 命令：

```bash
git clone https://github.com/[username]/Github-Demo.git
cd Github-Demo
```

---

## 📚 後續步驟

- 查看 `docs/getting-started.md` 了解快速開始指南
- 探索 `examples/` 資料夾查看示範檔案
- 修改文件並嘗試提交變更（Commit）到你的 Fork

---

## 💡 小貼士

| 工具 | 適用情境 | 優點 |
|------|--------|------|
| **Antigravity** | 快速瀏覽、線上編輯 | 無需安裝，即開即用 |
| **VSCode** | 正式開發、本地編輯 | 功能完整，適合日常開發 |
| **命令列** | 進階使用者 | 最靈活，支援複雜操作 |

---

## ❓ 常見問題

**Q: 我需要先 Fork 嗎？**
A: 不一定。你可以直接 Clone 公開專案。若要提交更改，建議先 Fork 專案到自己的帳號。

**Q: Clone 和 Fork 有什麼差別？**
A:
- **Clone**：將程式碼複製到本地電腦
- **Fork**：在 GitHub 上複製整個專案到自己的帳號

**Q: 我的 Clone 出現錯誤？**
A: 請檢查：
1. 網路連接是否正常
2. Repository URL 是否正確
3. Git 是否已正確安裝

---

## 🤝 貢獻

歡迎對本專案提出建議或改進！

---

**最後更新**：2026-02-21
