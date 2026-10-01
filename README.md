# 𓃥 白六影子訊息 (White 6 Shadow Message)

> **𓃥 白六互動視覺系列作品**  
> 一款基於 WebGL / Three.js 與 ES6 模組化技術建構的動態訊息傳遞工具，將文字與光影美學結合，呈現獨特的影子訊息視覺效果。

👉 **[點此線上體驗 𓃥 白六影子訊息](https://kuochili-ops.github.io/Shadow-message/)**

---

## 🌟 專案簡介 (Overview)

**𓃥 白六影子訊息** 是白六（White 6）數位互動系列的作品之一。本專案透過純前端技術與動態視覺模組，提供使用者輸入自訂訊息並即時渲染為光影動態的效果。全套系統整合即時預覽（Live Preview）功能與獨立 Flip-board 模組，無需後端即可在瀏覽器端順暢運作。

---

## 🚀 核心功能與特色 (Key Features)

- **𓃥 影子光影視覺渲染**：結合靜態與動態視覺設計，創造出具有立體感與光影層次的文字訊息。
- **𓃥 獨立 Flip-board 翻牌模組**：採用獨立模組化封裝（Flip-board Module），實現流暢且自然的葉片翻轉與軸心動態。
- **𓃥 即時預覽系統 (Live Preview)**：具備完整的預覽模式與設定記憶，輸入文字或調整參數時即時呈現變化。
- **𓃥 全靜態極速載入**：基於 HTML5 / ES6 Modules 開發，支援 GitHub Pages 自動化託管，輕量且無縫跨平台。

---

## 🛠️ 技術架構 (Tech Stack)

- **Frontend**: HTML5, CSS3 (Custom Properties & Animations)
- **JavaScript**: ES6+ Native Modules (ESM)
- **Visual Effects**: 獨立 Flip-board 動態模組 / 視覺光影算子
- **Deployment**: GitHub Pages 靜態自動化部署

---

## 📂 專案結構 (Project Structure)

```text
Shadow-message/
├── index.html          # 主程式入口與頁面 DOM 配置
├── css/                # 視覺樣式與 3D/光影動畫定義
├── js/                 # 邏輯模組
│   ├── flipboard.js    # 獨立 Flip-board 翻牌組件模組
│   └── main.js         # 主控邏輯與 Live Preview 狀態控制
└── README.md           # 專案說明文件
