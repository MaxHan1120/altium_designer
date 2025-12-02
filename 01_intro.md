# 01｜快速導覽：完成一片 PCB 需要什麼？

這一章只講兩件事：

1. **做出一片 PCB 的完整流程**
2. **一些常用的 Altium hot key**

---

## 🛠️ PCB 設計完整流程

要完成一塊 PCB，需要以下步驟：

1. [建立 Project（專案）& 畫原理圖 Schematic](02_schematic.md)

2. [製作 Symbol / Footprint → 連結 Symbol ↔ Footprint](03_create_library)

3. 製作 PCB（Design → Update to PCB）(複製學長姐的檔案來修改)

4. 連結 PCB 與 Schematics 的元件

5. 設定 Design Rules（線寬、間距、過孔…

6. 鋪銅 → DRC 檢查 → 鋪 Via → DRC 檢查 

7. 輸出 Gerber 檔案

只要把上述步驟做完，就能做出第一塊 PCB。

而要製作給晶片的 PCB 板，需要製作大板與小板。(要開兩個專案做 一個專案做一個PCB)
小板是讓晶片可以連接到 PCB 上，而大板是再將小板接到大板上來給電源供應。

小板上原則上只會有 Chip(要自己做屬於自己的 chip 元件，詳細見 [03_create_library.md](03_create_library.md))、Pad、穩壓電容(視需求給 SMA )

而大板上要有連接大小板的 Pad， LDO 、穩壓電容、JUMPER等等，後續會再說明

---

## ⌨️ Altium 必備熱鍵（最常用）

### 📌 **Schematic（原理圖）**
- 放元件：`P` → `P`
- 放線 Wire：`P` → `W`
- 放 Net Label：`P` → `N`
- 放 Power：`P` → `V`
- 移動：`M` → `M`
- 旋轉：`Space`
- 選取區塊：拖曳滑鼠（右到左是包含）

---

### 📌 **PCB Layout（佈局 + 走線）**
- 移動元件：`M` → `M`
- 旋轉元件：`Space`
- 開始走線：點 Net → `Space`
- 推擠路徑（推線）：`Shift` + `R`
- 改變線寬：`Tab`（進入屬性修改）
- 倒角/彎角切換：`Space`
- 查看層：`+` / `-`
- 增加過孔（vias）：走線中按 `2`

---

## 🎯 對初學者最重要的觀念

- 原理圖決定邏輯  
- PCB 決定能不能正常運作  
- Design Rules 一定要一開始就設好  
- 電源與地線絕對要乾淨  
- 3D View 一定要檢查 footprint 對不對  

---

## 👉 下一章：建立第一份原理圖  
前往：**[02_schematic.md](02_schematic.md)**

---
