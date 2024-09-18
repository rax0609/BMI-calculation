# 🏋️‍♂️ **BMI 計算器** 🧮

## 📑 **目錄**

- [🔍 簡介](#🔍-簡介)
- [✨ 功能](#✨-功能)
- [🖼️ 截圖](#🖼️-截圖)
- [🛠️ 技術棧](#🛠️-技術棧)
- [📥 安裝](#📥-安裝)
- [🚀 使用方式](#🚀-使用方式)
- [⬇️ 下載可執行文件](#%EF%B8%8F-下載可執行文件)
- [🤝 貢獻](#🤝-貢獻)
- [📄 許可證](#📄-許可證)
- [📫 聯繫方式](#📫-聯繫方式)

## 🔍 **簡介**

BMI 計算器是一款使用 **C#** 和 **WPF** (Windows Presentation Foundation) 開發的桌面應用程式，旨在幫助用戶快速計算並了解自己的身體質量指數（**BMI**）。此應用程式擁有現代化且具有科技感的用戶界面，提供簡潔且直觀的使用體驗。

## ✨ **功能**

- **📏 BMI 計算**：根據用戶輸入的身高（公分）和體重（公斤）計算 BMI 值。
- **📊 即時分類**：根據計算出的 BMI 值，提供體重狀況分類（體重過輕、正常範圍、過重、肥胖）。
- **🎨 現代化 UI**：採用漸變色背景、圓角按鈕和陰影效果，提升視覺效果和使用體驗。
- **⚠️ 錯誤處理**：對用戶輸入進行驗證，確保數據的有效性並提供相應的錯誤提示。

## 🖼️ **截圖**

![主界面](https://raw.githubusercontent.com/rax0609/botimg/main/BMI.png)

*主界面展示*

## 🛠️ **技術棧**

- **📝 語言**：C#
- **⚙️ 框架**：.NET 8.0 / .NET Core 3.1 / .NET Framework 4.8
- **🖥️ UI 框架**：WPF (Windows Presentation Foundation)
- **🛠️ 開發環境**：Visual Studio 2022

## 📥 **安裝**

### 🧩 前置條件

- **🔗 .NET 8.0 SDK** 或更新版本
- **💻 Visual Studio 2022** 或其他支援 WPF 的開發環境

### 📥 下載專案

1. **🔄 克隆儲存庫**：

   ```bash
   git clone https://github.com/rax0609/BMICalculator.git
   ```

2. **📂 進入專案目錄**：

   ```bash
   cd BMICalculator
   ```

3. **📂 打開專案**：

   使用 Visual Studio 打開 `BMICalculator.sln` 解決方案檔案。

4. **🔄 還原 NuGet 套件**：

   在 Visual Studio 中，右鍵點擊解決方案，選擇「還原 NuGet 套件」。

5. **🛠️ 編譯並運行**：

   按下 `F5` 鍵或點擊「啟動」按鈕來編譯並運行應用程式。

## 🚀 **使用方式**

1. **▶️ 啟動應用程式**：

   啟動後，應用程式將顯示主界面。

2. **✍️ 輸入數據**：

   - 在「身高 (公分)」輸入框中輸入你的身高。
   - 在「體重 (公斤)」輸入框中輸入你的體重。

3. **📊 計算 BMI**：

   點擊「計算 BMI」按鈕，系統將自動計算並顯示你的 BMI 值及相應的體重分類。

4. **📈 查看結果**：

   計算結果將顯示在界面下方，包括 BMI 值和體重狀況分類。

## ⬇️ **下載可執行文件**

如果你不想自行編譯專案，可以直接下載已打包的可執行文件 `BMICalculator_boxed.exe`。請前往 [Releases](https://github.com/rax0609/BMICalculator/releases) 頁面下載最新版本。

### 📥 下載步驟：

1. 前往 [Releases 頁面](https://github.com/rax0609/BMICalculator/releases)。
2. 找到最新的 Release 版本。
3. 下載 `BMICalculator_boxed.exe` 檔案。
4. 下載完成後，雙擊執行檔以啟動應用程式。

**⚠️ 注意**：下載和執行可執行文件時，請確保你的防毒軟體允許該檔案運行。如遇到安全提示，請根據需求允許該應用程式。

## 🤝 **貢獻**

歡迎各位開發者為此專案貢獻力量！請遵循以下步驟進行貢獻：

1. **🔗 Fork 此專案**
2. **🌿 建立新分支** (`git checkout -b feature/新功能`)
3. **✍️ 提交更改** (`git commit -m '新增某某功能'`)
4. **⬆️ 推送分支** (`git push origin feature/新功能`)
5. **🔀 創建 Pull Request**

請確保在提交 Pull Request 前進行充分的測試，並遵循專案的代碼風格。

## 📄 **許可證**

此專案採用 [MIT 許可證](LICENSE) 授權。詳情請參閱 [LICENSE](LICENSE) 文件。

## 📫 **聯繫方式**

- **👤 作者**：[rax0609](https://github.com/rax0609)
- **✉️ 電子郵件**：<support@futuracept.com>
- **🔗 專案網址**：[https://github.com/rax0609/BMICalculator](https://github.com/rax0609/BMICalculator)

---

## 🔧 **補充說明**

### 🚀 **如何改善專案**

- **📱 響應式設計**：目前應用程式使用固定寬度，未來可以考慮使用 `Grid` 和 `ViewBox` 等控件來實現響應式設計，適應不同解析度和視窗大小。
- **🎞️ 動畫效果**：添加按鈕點擊或輸入框聚焦時的動畫，提升用戶體驗。例如，使用 `Storyboard` 來實現漸變顏色或移動效果。
- **🖌️ 圖示和圖形**：添加相關圖示，如體重和身高的圖標，增強視覺效果。可以使用矢量圖形（如 SVG）或 FontAwesome 等圖標庫。
- **🌙 主題切換**：提供暗黑模式和亮色模式的切換，滿足不同用戶的喜好。
- **📈 數據保存與歷史記錄**：新增功能來保存用戶的歷史 BMI 計算記錄，並以圖表形式展示趨勢。

### ❓ **常見問題**

**Q1: 為什麼應用程式無法啟動？**

A1: 請確保已安裝正確版本的 .NET SDK，並已還原所有 NuGet 套件。如果問題持續存在，請檢查錯誤訊息並參閱 [問題追蹤](https://github.com/rax0609/BMICalculator/issues)。

**Q2: 如何更改應用程式的顏色主題？**

A2: 目前應用程式使用固定的顏色主題。你可以修改 `MainWindow.xaml` 中的 `LinearGradientBrush` 和其他顏色屬性來更改主題顏色。

---

感謝你使用 **BMI 計算器**！如果有任何建議或問題，歡迎透過 [📫 聯繫方式](#📫-聯繫方式) 與我取得聯繫。

---

## 🏷️ **版本歷史**

### v1.0.0

- 初始發布
- 完成所有核心功能，包括 BMI 計算、即時分類、現代化 UI 設計等。

---

## 📄 **授權信息**

此專案採用 [MIT 許可證](LICENSE) 授權。詳情請參閱 [LICENSE](LICENSE) 文件。

---

## 📂 **資料夾結構**

```
BMICalculator/
│
├── BMICalculator.sln
├── BMICalculator/
│   ├── MainWindow.xaml
│   ├── MainWindow.xaml.cs
│   ├── BMICalculator.csproj
│   └── Assets/
│       └── Logo.png
├── Releases/
│   └── BMICalculator_boxed.exe
├── LICENSE
└── README.md
```

---

## 🌟 **感謝**

感謝所有使用和支持 **BMI 計算器** 的用戶！你的反饋是我們不斷改進的動力。如果你喜歡這個專案，請考慮給我們一個 ⭐️。

---
