# 拾知 · Knowledge Hub Android

這個公開儲存庫只放 Android 安裝檔與更新資訊。個人收藏、資料庫、帳號、密碼與私人伺服器網址皆保留在使用者自己的電腦。

[下載最新 APK](https://github.com/blizzard-new/knowledge-hub-android-releases/releases/latest/download/KnowledgeHub.apk) · [查看版本與更新說明](https://github.com/blizzard-new/knowledge-hub-android-releases/releases/latest)

## 第一次使用

1. 手機與 Windows 電腦都開啟 Tailscale，登入同一個私人網路。
2. 在電腦啟動 Knowledge Hub。電腦需要保持清醒並執行服務。
3. 安裝 APK，開啟「拾知」。Android 可能會要求允許瀏覽器安裝此來源的 App。
4. 從電腦知識庫「偏好設定 → 手機連回這台電腦」複製私人 HTTPS 網址，貼到 App。
5. 使用自己的知識庫管理員帳號登入。

需要 Android 8.0 以上。這個 App 連到你自己的知識庫；不提供公開知識庫服務，也不會喚醒關機或睡眠中的電腦。

## 從其他 App 分享收藏

在 Threads、Instagram 或 YouTube 選擇分享，再選「拾知／收藏到拾知」，確認網址後按「確認收藏」。
電腦離線或未登入時，連結會保留在手機「待收藏」，登入並連線後可手動補存；重新開啟 App 仍會保留。
每次最多 20 個連結。分享文字與媒體附件不會被上傳，收藏不會自動送交 AI。

## 版本更新

在 App 選「更多 → 檢查 App 更新」，或重新下載最新 APK。更新會保留手機的連線設定。
App 會驗證下載大小、SHA-256、套件名稱與簽章，再交由 Android 顯示安裝確認。
每個版本均附 `SHA256SUMS.txt`，可從 Release 頁面核對檔案。

套件名稱：`tw.shizhi.knowledgehub`。App 使用私人 HTTPS 連線，登入密碼與 Session 不會包含在公開安裝檔中。
