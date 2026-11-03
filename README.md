# 班級儀表板：香港天氣版

- 導師版：https://hcl-fcms.github.io/classdashboard-hk/
- 多班科任版：https://hcl-fcms.github.io/classdashboard-hk/subject/

香港十八區天氣、香港時區，預設深水埗。天氣由 Open-Meteo 提供，並非天文台警告系統。

班級資料存於瀏覽器 localStorage，沒有伺服器同步。轉用新網址前，請先在舊版本匯出備份；不同網址的本機資料不會自動轉移。勿把學生資料或備份上傳此公開倉庫。

## 來源

原作：https://github.com/ckj1022-art/classdashboard

本倉庫為香港天氣修改版，保留原作內容。原始倉庫未附授權條款，本倉庫不另行授予原作的重用或再分發授權。

## 部署與回退

GitHub Pages 從 main 分支根目錄發布。更新後 push main 即重新部署。出現問題時以 git revert 回退相關提交，並確認 Pages build 通過。
