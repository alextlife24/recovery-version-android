# Android 相容版本 APK

收錄五個軟體、兩種 Android 版本，共 **10 個 APK**。倪柝聲文集 Android 16 已更新為第三修正版（40004）；其餘安裝檔維持既有版本，授權程式未變更。

## 下載

下方為完整的 APK 直接下載網址。也可開啟 [Android 5 目錄](https://github.com/alextlife24/recovery-version-android/tree/main/apks/android5) 或 [Android 16 目錄](https://github.com/alextlife24/recovery-version-android/tree/main/apks/android16) 選擇檔案。

| 軟體 | Android 5／P01Z | Android 16 相容版 |
|---|---|---|
| 電子詩歌 | [下載 10.1 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android5/Hymns-P01Z-Android5.apk) | [下載 10.1 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android16/Hymns-Classic-Compat-3.apk) |
| 恢復本聖經 | [下載 18.1 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android5/RecoveryBible-P01Z-Android5.apk) | [下載 18.1 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android16/RecoveryBible-Compat.apk) |
| 新舊約生命讀經 | [下載 24.6 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android5/LifeStudy-P01Z-Android5.apk) | [下載 24.6 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android16/LifeStudy-Compat.apk) |
| 生命讀經有聲 | [下載 3.8 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android5/LifeStudyAudio-P01Z-Android5.apk) | [下載 2.5 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android16/LifeStudyAudio-Compat.apk) |
| 倪柝聲文集 | [下載 24.4 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android5/WatchmanNee-Android5.apk) | [下載 24.4 MB](https://raw.githubusercontent.com/alextlife24/recovery-version-android/main/apks/android16/WatchmanNee-Android16.apk) |

Android 5 目錄為最低 Android 5.0（API 21）版本，供 ASUS P01Z／Android 5.0.2 使用；Android 16 目錄沿用最低 Android 8（API 26）的既有相容版。兩類 APK 的 targetSdk 都是 28；「Android 16 相容版」並不表示 targetSdk 36 或符合 Google Play 最新發行要求。

## 安裝

1. 依裝置系統選擇上表對應的 APK，下載完成後用檔案管理員開啟。
2. 若系統要求，允許目前瀏覽器／檔案管理員安裝不明來源應用程式；Android 5 可在安全性設定允許不明來源。
3. 先保留既有 App 與資料，再確認能否覆蓋更新。同一軟體兩版套件名稱相同，每台裝置只需安裝適合的一版；跨版本切換可能受版本碼或簽章限制。

原有註冊與授權仍由既有程式、原服務處理。本儲存庫不新增自動授權；原廠 App 與相容版之間的私人授權、設定、書籤及下載內容不會因放入此儲存庫而自動搬移。有聲版的遠端音訊仍取決於原伺服器。

## 已知狀態

- **倪柝聲文集 Android 16：第三修正版 `1.2.2-android16.3`／版本碼 40004。** 針對「顯示圖表」滑動後文字重疊、殘影，補上不透明背景、停用捲動快取，圖表清單改用軟體繪圖。**使用者於 2026-10-20 安裝後回報正常，確認本次圖表清單滑動問題已改善。** 原圖表資料、圖片、程式碼與註冊流程保留；這次實機回報不等於所有裝置與功能均已完整回歸。詳見 [第三版修正紀錄](https://github.com/alextlife24/recovery-version-android/blob/main/docs/map-list-fix-40004.md)。
- Android 5 五個相容版本的既有紀錄為 Android 5.0.2 模擬器驗證，不等於 ASUS P01Z 實機驗證。
- 第三修正版已核對編譯後的背景與清單繪圖設定、原圖片／資料庫、註冊程式、簽章及版本升級；使用者已回報本次更新正常。其餘 APK 沿用既有相容檔案，不新增完整回歸測試的聲明。

## 檔案核對

- [版本與套件清單](https://github.com/alextlife24/recovery-version-android/blob/main/docs/versions.md)
- [機器可讀清單](https://github.com/alextlife24/recovery-version-android/blob/main/catalog.json)
- [SHA-256 校驗碼](https://github.com/alextlife24/recovery-version-android/blob/main/SHA256SUMS.txt)

檔名沿用先前交付名稱，因此 Android 16 目錄中的部分檔名仍以 `Compat` 命名。僅收錄 APK 與下載說明，不包含簽署私鑰或來源備份包。
