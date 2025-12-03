# 📘 Altium Designer：

這份文件的目標是：

> **讓第一次使用 Altium 的初學者，也能獨立完成一塊屬於自己的 PCB。**

但由於我也是第一次使用 Altium 畫自己的 PCB ，因此可能不是太專業，就當作留個紀錄。

本檔案會從最基本的 Schematics 開始，到 Footprint 建立、PCB Layout、Routing、DRC、鋪銅以及最後檔案輸出。

也謝謝 **陳泰鴻** 學長以及 **游富翔** 學長的耐心指導。

---

## 🎯 適用對象

- 第一次使用 Altium 的初學者  
- 想要畫自己晶片的 PCB  

---

## 🧭 使用方式
[在第一章節中](01_intro.md)，會介紹大致的設計流程，內部有連結可以快速找到需要使用的章節。

依序閱讀每個章節，最終應該就可以完成一個 PCB！

---

## 📂 章節導覽（Table of Contents）

### **1. 基礎概念與環境準備**
1. [概述（PCB 設計流程）](01_intro.md)    

---

### **2. 原理圖設計（Schematic）**
2. [建立 Project 與 Schematic Sheet](02_schematic.md)  
3. 如何開啟新專案
4. 如何繪製原理圖(Schematics)
5. 如何打開 library 並放置元件
6. 一些常用的快捷鍵

---

### **3. 元件庫（Library）建立**

7. [Symbol Library（原理圖元件）](03_create_library.md)  
8. **如何新增元件(Add library)**
9. **如何封裝(Add footprint)**
10. **如何叫出新增的原件**
   

---

### **4. PCB Layout 設置**
11. [從 Schematic 轉到 PCB](05_pcb_setup.md)  
12. Layer Stack 設置  
13. Design Rules（線寬、間距、過孔等）  
14. Polygon Plane 與電源配置  

---

### **5. 元件擺放（Placement）與走線（Routing）**
15. [元件 Placement 原則](06_component_placement.md)  
16. Routing 熱鍵與技巧  
17. 差動線、長度匹配（選用）  
18. 去耦電容佈局最佳實務  

---

### **6. 完成設計與檢查**
19. [DRC / ERC 錯誤檢查](09_drc.md)  
20. 丝印、板框、Logo、方向標示  

---

### **7. 製造輸出（Output）**
21. [Gerber 與 Drill File 輸出](10_output.md)  
22. OutJob 設定  
23. 3D View 檢查  

---

### **8. 常見錯誤與 Debug**
24. [PCB 初學者最容易犯的錯誤](11_common_mistakes.md)  
25. Polygon 不連接怎麼辦  
26. USB、MCU、電源常見問題  

---

