# Stardew Valley 攻略網站

## 網站結構
```
├── index.html          # 首頁
├── styles.css          # 全局樣式表
├── guides.json         # 遊戲數據
├── images/            # 圖片資源目錄
│   ├── hero-bg.jpg    # 首頁背景圖
│   └── logo.png       # 網站 logo
└── guides/           # 攻略指南目錄
    ├── artisan.html   # 工匠物品指南
    ├── festival.html  # 節日活動指南
    ├── crops.html     # 作物種植指南
    └── barn.html      # 農舍建築指南
```

## 頁面功能說明

### 首頁 (index.html)
- 網站主頁面
- 提供快速導航到各個攻略指南
- 展示遊戲主要特色
- 包含最新資訊和熱門指南

### 工匠物品指南 (guides/artisan.html)
- 詳細介紹各種工匠機器的使用方法
- 提供加工物品的收益計算
- 每分鐘收益分析
- 加工建議和注意事項

### 節日活動指南 (guides/festival.html)
- 四季節日活動時間表
- 活動參與方式說明
- 獎勵物品清單
- 攻略建議

### 作物種植指南 (guides/crops.html)
- 季節性作物列表
- 種植時間和收穫週期
- 收益計算和分析
- 種植策略建議

### 農舍建築指南 (guides/barn.html)
- 農舍升級資訊
- 動物飼養指南
- 動物產品說明
- 效率最大化建議

## 數據文件

### guides.json
- 儲存遊戲相關數據
- 工匠物品製作資訊
- 收益計算公式
- 遊戲機制數據

### styles.css
- 定義網站整體視覺風格
- 響應式設計樣式
- 組件樣式
- 動畫效果

## 開發注意事項
1. 所有頁面都使用響應式設計，支援各種設備訪問
2. 使用 Font Awesome 圖標增強視覺效果
3. 保持數據和展示分離，便於維護和更新
4. 統一使用繁體中文
5. 收益計算需要標註單位和計算方式 