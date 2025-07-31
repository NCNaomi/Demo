# WanderTales | 漫遊傳說

> **說故事 x 智慧旅遊導覽**  
> 一款將文化傳說與地圖導覽結合的旅遊 App Prototype

---

## ✨ 功能特色

- **地圖導覽**：`MapKit + CoreLocation` 顯示景點與使用者位置
- **雙語切換**：即時切換中英文顯示
- **故事卡片**：橫向滑動卡片顯示附近文化故事
- **背景音樂**：旅遊氛圍音樂播放 / 暫停切換
- **UI 設計**：溫暖色調、文化圖騰背景，沉浸式體驗

---

## 🛠 技術堆疊

- **UIKit**：客製化 Header / Card / 按鈕 UI
- **MapKit & CoreLocation**：地圖標註與 GPS 導覽
- **AVFoundation**：背景音樂播放控制
- **Auto Layout**：程式化版面設計

---

## 📂 專案架構

```plaintext
WanderTales/
├── ViewController.swift       # 主畫面控制器 (地圖、故事卡片、音樂控制)
├── StoryCardCell.swift        # 自訂 UICollectionViewCell (故事卡片)
├── Assets.xcassets/           # 圖片資源 (背景圖、App Icon、色彩)
├── journey.mp3                # 旅遊背景音樂
├── Info.plist                 # App 權限設定 (定位 / 語言)
└── README.md                  # 專案說明文件
