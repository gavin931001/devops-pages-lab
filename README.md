# 🚀 DevOps Pages Lab - 活動日誌專案

這是我的 GitHub Pages 專案，旨在透過 GitHub Actions 自動化活動日誌的生成與部署。

## 專案目標 (O 等級文件部分)

本專案滿足 DevOps 作業 E 級要求，並透過以下方式強化至 O 級：
1. **排程邏輯說明：** 活動日誌設定為每日 UTC 午夜（`cron: '0 0 * * *'`）執行，確保日誌能準確反映前一日的完整活動，避免在主要工作時間進行提交。
2. **客製化 Action 參數：** 使用 `COMMIT_MESSAGE` 和 `EVENT_LIMIT` 參數，優化了機器人提交訊息的描述性並限制了日誌長度，展現了對 Action 的客製化能力。

---

## 🤖 GitHub 專案活動記錄

以下區塊的內容將由 GitHub Actions 自動更新。
<!--START_SECION:activity-->

<!--END_SECION:activity-->
---

## 網站存取資訊

* **專案擁有者：** 羅云駿
* **課程：** DevOps
* **部署狀態：**  (可選，您可以新增一個 Status Badge 來顯示 Workflow 狀態)
