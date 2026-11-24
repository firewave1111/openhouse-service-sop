# 房務服務標準（全居資產房管處）

網站：https://firewave1111.github.io/openhouse-service-sop/

房管處服務標準化的共編手冊，分四層：遵守標準、執行細節、教育訓練、落地推動，另有待確認議題、交接清單、更新紀錄。

## 閱讀
房管師直接開網址就能看，不需要帳號。

## 編輯（主管）
1. 請 repo 擁有者把你的 GitHub 帳號加為協作者（Settings → Collaborators），並到信箱接受邀請。
2. 到 https://github.com/settings/personal-access-tokens/new 建立 Fine-grained token：
   - Resource owner：firewave1111
   - Repository access：Only select repositories → openhouse-service-sop
   - Repository permissions → Contents：Read and write
3. 在網站右上角按「編輯者登入」，貼上權杖。權杖只存在你自己的瀏覽器。

## 資料存在哪裡
所有內容都在 `data.json`。網站上每次儲存都會變成一筆 commit，可以在 GitHub 的 commit 紀錄看到誰改了什麼，需要時也能還原。

網站更新後，沒登入的閱讀者大約 1～2 分鐘後才會看到新內容（GitHub Pages 重新部署的時間）。
