# SDM660 Kernel Builder (GitHub Actions)

Repositori ringan untuk mengompilasi kernel Snapdragon 660 (Whyred, Lavender, Clover, dll.) secara otomatis menggunakan GitHub Actions Runner (`ubuntu-latest`) tanpa perlu fork kernel besar.

## Sumber Upstream
Target kernel diambil langsung dari repositori resmi:
👉 **[sdm660-mainline/linux](https://github.com/sdm660-mainline/linux)**

## Cara Menggunakan
1. Masuk ke tab **[Actions](../../actions)**.
2. Klik workflow **Build SDM660 Kernel**.
3. Klik tombol **Run workflow**.
4. Pilih branch yang ingin di-build dari menu dropdown:
   - `setotau/qcom-sdm660-7.2.y-ipa2-lite` : Branch modem IPA & BAM terbaru.
   - `qcom-sdm660-7.2.y` : Branch mainline 7.2 default stabil.
   - `custom` : Untuk mengetik nama branch/tag lain.
5. Tunggu proses build selesai (~25-30 menit) lalu unduh artifact `.tar.gz`.
