# Android 相容版本 APK

收錄五個軟體、兩種 Android 版本，共 **10 個 APK**。本次整理既有安裝檔，沒有重新編譯或更改授權程式。

## 下載

| 軟體 | Android 5／P01Z | Android 16 相容版 |
|---|---|---|
| 電子詩歌 | [下載 10.1 MB](apks/android5/Hymns-P01Z-Android5.apk?raw=true) | [下載 10.1 MB](apks/android16/Hymns-Classic-Compat-3.apk?raw=true) |
| 恢復本聖經 | [下載 18.1 MB](apks/android5/RecoveryBible-P01Z-Android5.apk?raw=true) | [下載 18.1 MB](apks/android16/RecoveryBible-Compat.apk?raw=true) |
| 新舊約生命讀經 | [下載 24.6 MB](apks/android5/LifeStudy-P01Z-Android5.apk?raw=true) | [下載 24.6 MB](apks/android16/LifeStudy-Compat.apk?raw=true) |
| 生命讀經有聲 | [下載 3.8 MB](apks/android5/LifeStudyAudio-P01Z-Android5.apk?raw=true) | [下載 2.5 MB](apks/android16/LifeStudyAudio-Compat.apk?raw=true) |
| 倪柝聲文集 | [下載 24.4 MB](apks/android5/WatchmanNee-Android5.apk?raw=true) | [下載 24.4 MB](apks/android16/WatchmanNee-Android16.apk?raw=true) |

Android 5 目錄為最低 Android 5.0（API 21）版本，供 ASUS P01Z／Android 5.0.2 使用；Android 16 目錄沿用最低 Android 8（API 26）的既有相容版。兩類 APK 的 targetSdk 都是 28；「Android 16 相容版」並不表示 targetSdk 36 或符合 Google Play 最新發行要求。

## 安裝

1. 依裝置系統選擇上表對應的 APK，下載完成後用檔案管理員開啟。
2. 若系統要求，允許目前瀏覽器／檔案管理員安裝不明來源應用程式；Android 5 可在安全性設定允許不明來源。
3. 先保留既有 App 與資料，再確認能否覆蓋更新。同一軟體兩版套件名稱相同，每台裝置只需安裝適合的一版；跨版本切換可能受版本碼或簽章限制。

原有註冊與授權仍由既有程式、原服務處理。本儲存庫不新增自動授權；原廠 App 與相容版之間的私人授權、設定、書籤及下載內容不會因放入此儲存庫而自動搬移。有聲版的遠端音訊仍取決於原伺服器。

## 已知狀態

- **倪柝聲文集 Android 16：第二修正版 `1.2.2-android16.2`／版本碼 40003。** 已針對設定頁背景、選單光暈及切頁生命週期進行加固；實機曾回報設定頁閃退，尚未確認全部排除。先前 API 36 模擬器安裝成功，但完整操作回歸被模擬器系統介面的 ANR 阻擋，請視為待實機確認的候選版。
- Android 5 五個相容版本的既有紀錄為 Android 5.0.2 模擬器驗證，不等於 ASUS P01Z 實機驗證。
- 本次匯入核對 ZIP 完整性、套件名稱、版本、最低 SDK 及 SHA-256；沒有重新進行啟動、閱讀、音訊或選單操作測試。其餘 Android 16 APK 沿用既有相容檔案，不新增通過測試的聲明。

## 檔案核對

- [版本與套件清單](docs/versions.md)
- [機器可讀清單](catalog.json)
- [SHA-256 校驗碼](SHA256SUMS.txt)

檔名沿用先前交付名稱，因此 Android 16 目錄中的部分檔名仍以 `Compat` 命名。僅收錄 APK 與下載說明，不包含簽署私鑰或來源備份包。
