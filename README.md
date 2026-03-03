# Website Memo & Border Toolbox

Chrome Extension（Manifest V3）

## 功能

- 為網站新增可拖曳 Memo（可關閉，重新進入頁面會再顯示）
- 為網站加上四邊 Border（可關閉，重新進入頁面會再顯示）
- Border 可設定上下左右四個位置的說明文字
- 作用域支援：
  - domain 下所有頁面
  - 同父目錄下所有頁面（可自行編輯路徑）
  - 僅該頁面
- 提供完整設定頁：
  - 顯示該網域下所有設定
  - 使用頁籤切換 Memo / Border
  - 單筆編輯與刪除

## 安裝方式（開發模式）

1. 開啟 Chrome，前往 `chrome://extensions`
2. 啟用右上角「開發人員模式」
3. 點選「載入未封裝項目」
4. 選擇本專案資料夾

## 使用方式

1. 打開任一網站
2. 點擊擴充功能圖示開啟小視窗
3. 切換 `Memo` 或 `Border`
4. 選擇作用域
5. 填入內容並新增
6. 如需管理既有設定，點「開啟完整設定視窗」

## 資料儲存

- 使用 `chrome.storage.local`
- 所有設定儲存在 `entries` 陣列
