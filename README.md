# 1151VR-HW1-{學號}-{姓名}

輔仁大學 資工系｜Unity 3D 虛擬實境應用｜作業一

Unity 6000.0.83f1（Universal 3D 範本）

## 專案截圖

<!-- 把截圖存成 docs/screenshot-01.png，然後把下面這行的註解拿掉 -->
<!-- ![專案畫面](docs/screenshot-01.png) -->

## 連結

- GitHub：
- YouTube：

## 影片章節

| 時間 | 內容 |
|---|---|
| 0:14 | 新增立方體 |
| 0:18 | 匯入 3D 模型 |
| 0:20 | Scene 視角調整 |
| 0:37 | 改變物件形狀 |
| 1:00 | 執行遊戲 |
| 1:10 | 儲存場景、另存新檔 |

## 製作流程與操作說明

1. **建立專案** —— 用 Unity Hub 建立 Universal 3D 範本專案，Editor 版本 6000.0.83f1。

2. **新增立方體** —— `GameObject → 3D Object → Cube`，場景中原本就有 Directional Light（燈光）和 Main Camera（攝影機）。

3. **匯入 3D 模型** —— 把模型資料夾（含 `.meta` 檔）整個拖進 `Assets`，再將 prefab 拖入 Hierarchy 放到場景中。

4. **調整 Scene 視角** —— 滾輪縮放、中鍵平移、`Alt` + 左鍵旋轉。這裡改的是開發者視點，不是遊戲執行時的畫面。

5. **改變物件形狀** —— `W` 移動、`E` 旋轉、`R` 縮放，也可以直接在 Inspector 的 Transform 輸入數值。

6. **執行遊戲** —— 按 ▶ Play（`Ctrl+P`），畫面切到 Game 視窗看實際執行結果。

7. **儲存場景** —— `Ctrl+S` 儲存，另以 `File → Save As` 另存新檔。

## 備註

模型材質原本是 Built-in 管線的 Standard shader，在 URP 專案中會顯示為洋紅色，
已透過 `Window → Rendering → Render Pipeline Converter` 轉換為 URP Lit。
