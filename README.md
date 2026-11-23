# Nusa Browser

Browser Android minimalis dengan banyak pilihan mesin pencari.

## Fitur
- Mesin pencari: Google, Bing, DuckDuckGo, Brave, Yahoo, Yandex, Ecosia, Startpage
- Banyak tab, tutup tab
- Back dan Next
- Mode baca
- DevTools (Eruda, butuh internet)
- Mode desktop
- Unduhan: lihat dan buka hasil download, termasuk APK
- Pintasan situs ke layar utama
- Bisa dijadikan browser default

## Cara build (dari HP, lewat GitHub)
1. Upload `NusaBrowser.zip` ke repo ini.
2. Buat file `.github/workflows/build.yml`, isi dengan workflow "Build APK dari ZIP".
3. Buka tab **Actions**, tunggu build selesai (atau Run workflow).
4. Unduh artifact `NusaBrowser-debug`, ekstrak, lalu install `app-debug.apk`.

## Catatan
- Android 8.0 (API 26) ke atas.
- Tab tidak tersimpan setelah app ditutup.
- Download dari link `blob:` belum didukung.
