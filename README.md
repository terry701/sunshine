# sunshine — TP53 與 DNA 結構

本儲存庫整理使用者提供的三個 PDB 結構檔，並提供可重新開啟的 ChimeraX 工作階段。

## 結構預覽

![TP53–DNA 結構座標示意圖](image/tp53_structure.png)

此圖由 `tp53_tetramer.pdb` 的蛋白質 Cα 原子與 DNA 磷原子座標繪製，為骨架示意圖，**不是 ChimeraX 螢幕截圖**。鏈 A、B、C、D 分別使用藍、綠、黃、紫色，DNA 鏈 E、F 使用紅色系。

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

## 作業內容狀態

目前僅收到 PDB 結構檔，尚未收到影片中示範的 `TP53_English.docx` 或使用者自己的 Word 作業，因此未轉換、填寫或宣稱完成作業答案。尚未指定或標示任何突變，也未執行突變模擬。

## 結構來源

`tp53_tetramer.pdb` 的 HEADER 記載結構編號為 **3KMD**，TITLE 為 *Crystal structure of the P53 core domain bound to a full consensus site as a self-assembled tetramer*，檔案記載解析度為 **2.15 Å**。詳細來源請參閱 [RCSB PDB 3KMD](https://www.rcsb.org/structure/3KMD)。

上述結構資訊直接讀自使用者提供的 PDB；未將教學影片作者的圖片、作業答案或工作階段檔複製到此專案。
