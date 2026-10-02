外賣計次 安卓 App 打包說明

1. 到 github.com 註冊（免費），按右上角「+」→ New repository，名稱隨意（例如 waimai），選 Public，建立。
2. 在新倉庫頁面點「uploading an existing file」，把這個資料夾裡的所有檔案和資料夾
   （www、.github、package.json、capacitor.config.json）拖進去，按 Commit changes。
   ※ .github 是隱藏資料夾，請直接上傳解壓縮後的整個資料夾內容。
3. 點上方「Actions」分頁，如果看到 Build APK 沒有自動執行，點它 → Run workflow。
4. 等約 5～8 分鐘，完成後點進該次執行，最下方「Artifacts」下載 waimai-counter-apk。
5. 解壓縮得到 app-debug.apk，傳到安卓手機，點它安裝。
   第一次安裝會問「允許安裝未知來源的應用程式」，請允許。
