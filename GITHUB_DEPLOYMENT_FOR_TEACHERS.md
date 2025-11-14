# 🚀 給國中老師的GitHub Pages部署完整指南

## 📋 目標
將「幸福教育SEL Prompt生成系統」部署到GitHub Pages，獲得永久免費線上連結。

**成果**：你將擁有一個線上工具，GitHub不倒就永遠可以用！

---

## ⏱️ 預估時間
**首次設定**：10-15分鐘  
**以後使用**：點開連結就能用

---

## 📝 前置準備

### 你需要
- ✅ 一個GitHub帳戶（免費）
- ✅ 全部13個檔案（已準備好）
- ✅ 5分鐘的時間

### 取得GitHub帳戶（如果還沒有）
1. 訪問 https://github.com
2. 點右上「Sign up」
3. 輸入email、密碼、帳戶名稱
4. 完成驗證
5. ✅ 完成！

---

## 🎯 部署步驟（5步）

### 第1步：建立新Repository

#### 步驟 1.1
訪問 https://github.com/new
（或登入後，點右上 **+** → **New repository**）

#### 步驟 1.2
填寫資訊：

| 欄位 | 填寫內容 |
|------|---------|
| **Repository name** | `sel-prompt-generator` |
| **Description** | `教育部幸福教育SEL Prompt生成系統` |
| **Public/Private** | 選 **Public**（重要！） |
| **Add a README file** | ✓ 勾選 |
| **Add .gitignore** | 不用選 |
| **Choose a license** | 選 **MIT License** |

#### 步驟 1.3
點下方綠色按鈕 **「Create repository」**

✅ **第1步完成！**

---

### 第2步：上傳所有檔案

#### 步驟 2.1
你會看到一個空的Repository頁面，點擊 **「Add file」** → **「Upload files」**

（或者直接拖拉檔案到頁面上）

#### 步驟 2.2
選擇要上傳的所有13個檔案：

**必須上傳的5個HTML工具：**
- index-official.html
- sel-gov-official.html
- sdg-complete.html
- index.html
- sel-complete.html

**建議上傳的7份文檔：**
- README-OFFICIAL.md
- COMPLETE_SYSTEM_GUIDE.md
- GOV_SEL_OFFICIAL_GUIDE.md
- THREE_TOOLS_GUIDE.md
- SEL_SDG_Agent_Prompts_for_Taiwan_JHS.md
- DEPLOYMENT_GUIDE.md
- README.md

**其他：**
- LICENSE

#### 步驟 2.3
全部選好後，在底部找到 **「Commit changes」** 區塊

填寫：
- **Commit message**：`Initial commit: Add SEL Prompt Generator Tools`

點 **「Commit changes」** 綠色按鈕

✅ **第2步完成！**

---

### 第3步：啟用GitHub Pages

#### 步驟 3.1
進入Repository的 **Settings**（在上方選單）

#### 步驟 3.2
左側菜單找到 **「Pages」**

#### 步驟 3.3
在「Source」選擇：
- **Branch**：`main`
- **Folder**：`/ (root)`

點 **「Save」**

#### 步驟 3.4
頁面會出現訊息：
```
Your site is live at https://你的帳戶名.github.io/sel-prompt-generator/
```

✅ **第3步完成！**

---

### 第4步：測試連結

#### 步驟 4.1
複製你的線上連結：
```
https://你的帳戶名.github.io/sel-prompt-generator/
```

#### 步驟 4.2
在瀏覽器打開，應該看到 **index-official.html** 的內容

✅ **第4步完成！**

---

### 第5步：分享給老師們

#### 直接分享連結
```
https://你的帳戶名.github.io/sel-prompt-generator/
```

#### 或分享三個主工具的直接連結

**SEL官方版**：
```
https://你的帳戶名.github.io/sel-prompt-generator/sel-gov-official.html
```

**SDG完整版**：
```
https://你的帳戶名.github.io/sel-prompt-generator/sdg-complete.html
```

**整合快速版**：
```
https://你的帳戶名.github.io/sel-prompt-generator/index.html
```

✅ **第5步完成！**

---

## 🎉 大功告成！

你現在擁有一個**永遠免費的線上工具**！

### 老師可以：
✅ 點開連結，無需安裝任何東西  
✅ 填寫表單，30秒生成Prompt  
✅ 複製到ChatGPT或Claude  
✅ 下載為.txt檔案  
✅ 完全免費使用

### 你可以：
✅ 隨時分享連結給同事  
✅ GitHub不倒就永遠可用  
✅ 需要更新時，重新上傳檔案即可  
✅ 零維護成本  

---

## 🔄 如何更新工具

假如未來要修改或新增功能：

### 方法1：GitHub網頁介面（最簡單）
1. 進入你的Repository
2. 點 **「Add file」** 或點現有檔案的 **編輯圖示**
3. 修改或上傳新檔案
4. 點 **「Commit changes」**
5. 等待1-2分鐘，GitHub會自動更新

### 方法2：用Git命令（給進階使用者）
```bash
# 複製Repository到本地
git clone https://github.com/你的帳戶名/sel-prompt-generator.git

# 進入資料夾
cd sel-prompt-generator

# 修改檔案或新增檔案

# 上傳更新
git add .
git commit -m "Update: 你的修改說明"
git push
```

---

## 📞 如何分享給老師

### 分享方式1：直接貼連結
```
點這個連結就能用：
https://你的帳戶名.github.io/sel-prompt-generator/
```

### 分享方式2：製作簡單說明
```
【新工具】幸福教育SEL Prompt生成系統

教育部有推出「幸福教育、健康臺灣 幸福學校、師生共好」計畫
我用它做了一套線上工具，可以快速生成AI教學Prompt

✨ 完全免費
✨ 無需安裝
✨ 5分鐘快速規劃課程

👉 點這裡試用：https://你的帳戶名.github.io/sel-prompt-generator/

有任何問題可以聯絡我！
```

### 分享方式3：製作QR Code
用 https://qr-code-generator.com 將連結轉成QR Code
貼在教室或學校公告欄，老師掃就能用

---

## ❓ 常見問題

### Q: GitHub會收費嗎？
A: 不會！GitHub Pages對公開Repository完全免費，GitHub本身也免費。

### Q: 如果GitHub倒了怎麼辦？
A: 極不可能。GitHub是Microsoft旗下全球最大代碼托管平台，已運作15年+。

### Q: 如何讓Google搜尋到這個工具？
A: 在GitHub的Settings → About 中填寫描述，會自動被搜尋引擎索引。

### Q: 可以改成自訂網域嗎？
A: 可以，但需要購買網域。在Settings → Pages中設定。

### Q: 其他老師能編輯嗎？
A: 不能。只有你能編輯。其他老師只能使用。

### Q: 可以看到誰在用嗎？
A: 不行。GitHub不提供使用者統計。但你可以在Insights看到repository被view的次數。

---

## 🎯 WIX網站整合（選擇方案）

如果你想把工具掛在WIX老師網站上：

### 方法1：直接嵌入連結（最簡單）
在WIX中新增「嵌入代碼」元件：

```html
<iframe 
  src="https://你的帳戶名.github.io/sel-prompt-generator/index-official.html"
  width="100%"
  height="800px"
  frameborder="0">
</iframe>
```

### 方法2：WIX頁面中嵌入工具
1. 在WIX編輯頁面
2. 點 **「+」** → **「更多」** → **「HTML iFrame」**
3. 貼上上面的代碼
4. 完成！

### 方法3：直接連結（推薦）
在WIX中添加按鈕或連結，指向：
```
https://你的帳戶名.github.io/sel-prompt-generator/
```

---

## 📊 架構示意

```
你的GitHub
    ↓
sel-prompt-generator (Repository)
    ├─ index-official.html      ← 主頁
    ├─ sel-gov-official.html    ← SEL官方版
    ├─ sdg-complete.html        ← SDG版
    ├─ index.html               ← 整合版
    ├─ sel-complete.html        ← SEL完整版
    ├─ README-OFFICIAL.md
    ├─ 其他文檔...
    └─ LICENSE
        ↓
啟用GitHub Pages
    ↓
獲得線上連結
    ↓
https://你的帳戶名.github.io/sel-prompt-generator/
    ↓
老師們可以使用了！ 🎉
```

---

## ✅ 完成檢查清單

- [ ] 建立GitHub帳戶
- [ ] 建立新Repository
- [ ] 上傳13個檔案
- [ ] 啟用GitHub Pages
- [ ] 測試線上連結
- [ ] 複製連結
- [ ] 分享給老師們
- [ ] （可選）整合到WIX網站

---

## 🎓 額外提示

### 保護Repository內容
雖然設成Public是必要的（讓GitHub Pages運作），但：
- 老師看不到你的源代碼細節
- 他們只看得到運行後的介面
- 其他人也無法輕易複製或修改你的代碼

### 追蹤使用情況
在GitHub Repository頁面點 **Insights** → **Traffic**
可以看到：
- 過去14天有多少人訪問
- 來自哪些地方的流量

### 創意擴展
未來可以：
1. 新增更多Prompt模板
2. 添加其他年級版本
3. 支援其他科目（國文、數學等）
4. 加上中英雙語版本

---

## 📞 需要幫助？

如果部署時遇到問題：

### 檢查清單
- [ ] Repository設定為Public嗎？
- [ ] 在Settings → Pages中啟用了嗎？
- [ ] 等待了5分鐘嗎？（GitHub需要時間建構）
- [ ] 檔案名稱有沒有打錯？
- [ ] .html副檔名完整嗎？

### 常見錯誤與解決

**404 Not Found**
→ 檢查URL拼寫、檔案名稱是否正確

**頁面樣式亂掉**
→ 清空瀏覽器快取（Ctrl+Shift+Delete）

**無法看到最新版本**
→ 強制重新整理（Ctrl+F5）

**GitHub Pages未啟用**
→ 進Settings → Pages，確認Branch是main且Folder是root

---

## 🎉 恭喜！

你已經完成部署了！現在：

✨ **你是一名EdTech倡導者**  
✨ **你為同事節省了寶貴時間**  
✨ **你在推廣教育部的幸福教育政策**  
✨ **你創造了一個永遠免費的教學工具**

分享這個連結給你的同事吧！

```
https://你的帳戶名.github.io/sel-prompt-generator/
```

---

## 📝 快速參考卡

保存這張卡，以後查詢時方便：

```
【我的SEL Prompt生成系統】

線上連結：
https://你的帳戶名.github.io/sel-prompt-generator/

三個主工具：
1. SEL官方版：.../sel-gov-official.html
2. SDG版本：.../sdg-complete.html  
3. 快速整合版：.../index.html

GitHub Repository：
https://github.com/你的帳戶名/sel-prompt-generator

更新方式：
進Repository → Add file → Upload files → Commit

分享給老師時說：
「點這個連結，30秒生成教案Prompt」
```

---

**祝你部署順利！GitHub不倒，工具永遠可用！🚀**

Made with ❤️ for Taiwan Teachers  
Aligned with MOE Social Emotional Learning Initiative 🏛️

---

**最後更新**：2025年11月  
**版本**：1.0 教師友善版
