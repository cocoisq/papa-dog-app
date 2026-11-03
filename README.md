# 拍拍小狗 Android App

此專案將最新版「單聲狗叫版」HTML 遊戲包裝成離線 Android WebView App。

## 建置 APK
GitHub Actions 會在推送到 `main` 或手動執行時建置 APK：
1. 開啟 GitHub 專案的 **Actions**。
2. 選擇 **Build Android APK**。
3. 執行完成後，在該次工作流程頁面底部下載 `papa-dog-apk` artifact。
4. 解壓縮後安裝 `app-debug.apk`。

建置環境：JDK 17、Gradle 8.9、Android Gradle Plugin 8.7.3。
