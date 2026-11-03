# RoadScope Beta

RoadScope Android **Beta** 版本的發布處。原始碼不在這裡，維持閉源。

此 repo 只放：

- Android Beta 的 APK（以 GitHub Release 附件發布，每個版本一個 Release，tag 為 `vX.Y.Z_beta`）
- App 自動檢查更新用的版本資訊檔 `latest.json`（附在每個 Release；App 讀取最新 Release 的這個檔案）

## 安裝

到 [Releases](../../releases) 下載最新的 APK 安裝。第一次安裝需要在 Android 允許「安裝未知應用程式」。

- 已經裝了 v1.2.0_beta 以後的版本：App 冷啟動時會自動檢查新版本（每天最多一次），也可以在「設定 › 關於 › 檢查更新」手動檢查。更新會保留手機上的紀錄，**不要先解除安裝**。
- 從 v1.1.0_beta 以前（或任何 alpha 版）換過來：簽章不同，必須先解除安裝，手機上的紀錄會被清掉。

## 注意

- 這是測試版。計時精度還沒有用參考設備驗證，目前只保證重播結果一致、邏輯正確。
- APK 使用正式金鑰簽署，憑證 SHA-256：`fdd871e19edf1a87030e663c4afa454e8a0b9f50e73f55063adf2fd4e4fc3b5c`。
- 本 repo 原名 `RoadScope-public`，舊網址會自動轉到這裡。
