# 🧱 BALANCE CRAFT：超界限體感平衡總署
> **Gamified Neuromuscular & Balance Training Suite**  
> 一個結合前庭系統訓練、倒單擺物理學（Inverted Pendulum Physics）與像素方塊美學的一頁式網頁體感平衡訓練與線上競技平台。

![BALANCE CRAFT Theme](https://img.shields.io/badge/Physics-Inverted%20Pendulum-7bcc39?style=for-the-badge)
![HTML5 Canvas](https://img.shields.io/badge/Canvas-HTML5-orange?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Multiplayer-Firebase%20Realtime-ffca28?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 📌 專案緣由 (Background)

在許多運動競技項目中，**本體感覺（Proprioception）**與**前庭系統（Vestibular System）**的控制能力是決定對抗穩定度與敏捷反應的關鍵。傳統的平衡訓練（如單腳站立、平衡板、聽覺音訊反應）往往缺乏量化的即時數據回饋，且長期訓練容易感到枯燥。

為了提升訓練的持續性與趣味性，本專案致力於將**運動科學訓練機制**轉化為高度視覺化、具備雙重任務（Dual-Tasking）挑戰與線上連線互動的體感網頁遊戲平台。

---

## 💡 研發動機 (Motivation)

1. **遊戲化本體感覺訓練 (Gamified Proprioception)**：利用網頁遊戲的即時回饋與物理反饋，讓練習者在遊戲遊玩中不知不覺鍛鍊核心穩定度與神經肌肉反應。
2. **導入雙重任務機制 (Dual-Tasking)**：結合動態平衡控制與認知干擾（如數學快速反應、視覺轉向鎖定），模擬真實比賽場上高壓與多工處理環境。
3. **跨平台低門檻接入**：無需安裝額外硬體裝置，透過標準瀏覽器即可利用手機觸控、滑鼠拖曳或鍵盤進行即時微調訓練。
4. **社群連線競技 (Real-Time Multiplayer)**：引入多人線上房間與即時對戰系統，打造同場較勁的競爭感，激勵使用者突破自我穩定極限。

---

## ✨ 專案特色 (Features)

- 🧱 **倒單擺物理重力模擬 Engine**：真實計算高塔重心偏移、傾斜角速度、空氣阻尼與高度加成，考驗微感調節能力。
- 🧠 **認知雙重任務系統 (Dual-Task Cues)**：整合數字倍數判斷、反向視線轉動與視覺瞬時報數挑戰。
- ⚔️ **線上即時連線對戰 (Multiplayer Room System)**：基於 Firebase Firestore 的 6 位數房號即時連線匹配，支援雙人 side-by-side 房況與角速度同步對決。
- 🎨 **Minecraft 像素美學與 Web Audio API**：豐富的方塊掉落、爆破粒子與原生合成音效，無外部音訊資源相依性。
- 📱 **多端流暢控管 (Responsive Inputs)**：完整支援按鈕長按推力、螢幕全域拖曳與鍵盤 `A / D` / 方向鍵控制。

---

## 🚀 專案研發演進歷程 (Evolution Journey)

專案經歷了四個核心階段的迭代升級，從基礎實體動作模組演進至全方位的體感網頁遊戲：

```
Phase 1: 靜態與雙重任務起點 ➔ Phase 2: 星核重力連線對決 ➔ Phase 3: 量子矩陣超界限 ➔ Phase 4: BALANCE CRAFT 終極體感
```

| 階段 | 模組名稱 | 訓練核心與遊戲機制 |
| :--- | :--- | :--- |
| **Phase 1** | **靜態鎖定與雙重任務** | 單腳 90 度支撐，融入聽覺「逢 3 的倍數拍手」干擾；鐘點羅盤（12/3/6/9點）視線反向鎖定；0.5 秒閉眼聽覺突袭。 |
| **Phase 2** | **星核重力與保衛戰** | 導入 2D 向量重力物理場。包含線上 1v1 重力拉鋸戰與雙人協同引力罩彈開反物質隕石防禦戰。 |
| **Phase 3** | **超界限平方：量子矩陣** | 8x8 霓虹 Arcade 網格躍遷、同色平方脈衝連鎖爆破與 360 度四方向量護盾格擋。 |
| **Phase 4** | **BALANCE CRAFT 終極方塊塔** | 融合像素方塊風與倒單擺物理，實現多關卡切換、高塔動態平衡、TNT 碰撞衝擊與線上即時連線對戰。 |

---

## 🎮 遊戲玩法與操作指南 (How to Play)

### 🕹️ 操作方式
* **電腦鍵盤**：使用 `A` / `D` 或 `←` / `→` 方向鍵進行平滑位移。
* **螢幕按鈕**：按住畫面上方的【按住左移】與【按住右移】進行推力控制。
* **觸控/滑鼠拖曳**：在遊戲 Canvas 畫面上直接用手指/滑鼠拖曳，角色會跟隨游標精準修正重心。

### 🏆 通關與勝負規則
* **保持平衡**：將倒單擺高塔的傾斜角度維持在 $65^\circ$ 以內。
* **接取方塊**：接住空中掉落的鑽石、黃金與草方塊可獲得分數與高度，注意避開或抵禦 **TNT 炸藥** 帶來的強烈扭力衝擊！
* **雙重任務**：在 Phase 1 模式下，當畫面上出現 **3 的倍數** 數字時，需快速按下拍手按鈕擊退干擾。

---

## 📊 賽場競技能力評估表 (Stability Score Index)

遊戲根據得分與物理平衡穩定度提供專業的競技場表現評估：

| 總得分 | 成就稱號 | 賽場競技表現預測 |
| :--- | :--- | :--- |
| **180 - 200 分** | **SSS 級：重力掌控者** | 前庭覺與前饋神經肌肉反應極佳，能在激烈的體育對抗或快速變向中瞬時恢復重心。 |
| **140 - 179 分** | **S 級：領域專家** | 具備優異的動靜態平衡能力，在多重任務與高壓視覺干擾下依然維持高度穩定。 |
| **100 - 139 分** | **A 級：穩定戰士** | 基礎核心穩定度良好，但在快速視野移轉與大角度搖晃時修正時間較長。 |
| **100 分以下** | **B 級：體感修練者** | 本體感覺與視覺依賴性較強，建議先進行基礎單腳靜態支撐再挑戰關卡。 |

---

## 🛠️ 技術棧 (Tech Stack)

- **前端核心**：HTML5, CSS3, ES6+ JavaScript (Modules)
- **視覺與UI**：Tailwind CSS, HTML5 Canvas API, Google Web Fonts (Silkscreen, Press Start 2P)
- **音效處理**：Web Audio API Oscillator & Gain Synthesizer
- **即時連線與後端**：Firebase Firestore (Real-time DB), Firebase Authentication
- **物理數學引擎**：Custom Vector Physics, Torque & Angular Acceleration Simulation

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 授權開放。
