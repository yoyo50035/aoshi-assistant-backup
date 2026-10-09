# 傲視小助手繁體版備份

版本：第二版（v2.0）。

備份日期：2026-10-09。這是現有 Windows 程式的執行檔備份，不是完整原始碼專案。

## 內容

- 傲視小助手.exe 與 .config 設定。
- 主程式所需 DLL，包括繁體化元件 TraditionalUiRuntime.dll 、日誌重繪元件 LogPageRepaint.dll 及 NianAutomation.dll。
- runtimes 內的 x86 WebView2 載入元件。
- Win10_Flash_ActiveX_移植到_Win11_操作過程.docx 操作文件。
- 原使用說明，以及 SHA256SUMS.txt 檔案校驗清單。

## 刻意排除

- 助手開發備份／repair-log-tab：修補程式、測試與舊版備份只保留在本機。
- account.ini、accounts：登入資訊、角色設定與歷史資料。
- cache、reports、日誌及臨時檔案。

## 還原

1. 下載此資料夾的全部內容，保持目錄結構。
2. 將 DLL、EXE、.config 與 runtimes 放在同一程式資料夾，不要只取出 EXE。
3. 本備份不包含帳號及掛機設定；需重新設定，或從自己的本機備份還原。
4. Windows／.NET／瀏覽器等系統環境仍需另行準備；此備份不包含系統安裝程式。

本次備份目前資料夾的執行版本，更新主程式與 astdcommon.dll，並納入 NianAutomation.dll。備份過程未執行遊戲登入或自動任務。
