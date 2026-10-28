# Scientist’s Mission

**Who Stole TP53’s Superpower? Searching for the Key to Unlock Cancer**  
**Using AI to Uncover the Secrets of TP53–DNA Interactions**

姓名：待填　｜　學號：待填

依照 [paristzou/tp53abc 標準範例](https://github.com/paristzou/tp53abc) 整理以下五題作業架構。題目以中文摘要呈現；答案區待填。

## 1. The LEGO Assembly Line

胺基酸以哪種鍵連成蛋白質？請說明哪些胺基酸或主鏈基團之間可形成氫鍵。

**Answer:**

（待填）

## 2. The Double-Track Highway of Life’s Blueprint

請說明 DNA 雙股如何組成、核苷酸的基本成分、螺旋方向、四種鹼基，以及鹼基之間的氫鍵配對。

**Answer:**

（待填）

## 3. A 20-Base-Pair Love Code

以 **3KMD** 結構找出一組互相作用的 TP53 胺基酸與 DNA 鹼基，說明它們如何參與辨識。

**Answer:**

（待填；請記錄鏈、殘基編號與觀察到的作用。）

## 4. Return to the Crime Scene

為什麼單一胺基酸改變可能造成嚴重疾病？請舉一個具體疾病例子並解釋。

**Answer:**

（待填）

## 5. Return to the Crime Scene: Searching for Clues

在 **3KMD** 中選擇一個與癌症相關的 TP53 胺基酸突變，使用 ChimeraX 判斷該位置在蛋白質–DNA 接觸面或蛋白質其他區域。

**Answer:**

（待填；目前的工作階段尚未標示突變，亦未執行突變模擬。）

### a. ChimeraX 視覺化圖片

正式 ChimeraX 截圖待補。下方僅為使用者提供的 PDB 座標示意圖，不能代替指定突變位置的證據。

![TP53–DNA 結構座標示意圖](image/tp53_structure.png)

### b. ChimeraX 工作階段

已建立並驗證可開啟：[ChimeraX/TP53.cxs](ChimeraX/TP53.cxs)。提交前請依課程規定另存為自己的 `StudentID.cxs`。

---

# 結構檔與操作說明

## 檔案

| 路徑 | 說明 |
| --- | --- |
| [structures/tp53_tetramer.pdb](structures/tp53_tetramer.pdb) | 原始 3KMD 結構；蛋白質鏈 A–D、DNA 鏈 E–F，含水分子及鋅離子 |
| [structures/tp53.pdb](structures/tp53.pdb) | 使用者提供的蛋白質鏈 B 結構 |
| [structures/tp53_DNA.pdb](structures/tp53_DNA.pdb) | 使用者提供的 DNA 鏈 E、F 結構 |
| [ChimeraX/TP53.cxs](ChimeraX/TP53.cxs) | 用 ChimeraX 1.12 建立的工作階段；已驗證可重新開啟 |
| [ChimeraX/view_tp53.cxc](ChimeraX/view_tp53.cxc) | 可重新建立檢視樣式的 ChimeraX 指令 |

## 在 ChimeraX 開啟

1. 下載並解壓縮整個儲存庫。
2. 在 ChimeraX 使用 **File → Open** 開啟 `ChimeraX/TP53.cxs`。
3. 工作階段以 cartoon 顯示蛋白質，DNA 使用 stick；水分子已從工作階段移除，原始 PDB 檔完整保留。
4. 若課程要求學號檔名，使用 **File → Save** 另存為自己的 `學號.cxs`。
5. 調整角度後，可在 ChimeraX 命令列輸入 `save ~/Desktop/tp53_chimerax.png width 1600 height 1200 supersample 3` 輸出正式截圖。

## 結構來源

`tp53_tetramer.pdb` 的 HEADER 記載結構編號為 **3KMD**，TITLE 為 *Crystal structure of the P53 core domain bound to a full consensus site as a self-assembled tetramer*，檔案記載解析度為 **2.15 Å**。詳細來源請參閱 [RCSB PDB 3KMD](https://www.rcsb.org/structure/3KMD)。

上述結構資訊直接讀自使用者提供的 PDB；未將教學影片作者的圖片、作業答案或工作階段檔複製到此專案。
