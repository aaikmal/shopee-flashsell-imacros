<div align="center">
<img src="https://github.com/aaikmal/shopee-flashsell-imacros/raw/main/img/s-min.png" width="128" height="128"/>
  
# shopee-flashsell-imacros

>Bot Shopee Flash Sell menggunakan iMacros.
>
  
<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/nur_ikmal19?label=Follow%20%40nur_ikmal19%20for%20updates&logo=twitter&style=social">
</div>

## Install iMacros di Browser

Silahkan install Extention iMacros di browser.
| Bowser                          | Extention |
| --------------------------------- | ----------- |
| Chrome                   | [iMacros for Chrome v10.1.1](https://chrome.google.com/webstore/detail/imacros-for-chrome/cplklnmnlbnpmjogncfgfijoopmnlemp)
| Firefox        | [iMacros for Firefox v10.1.0.1485](https://addons.mozilla.org/id/firefox/addon/imacros-for-firefox/)

Untuk browser lain tinggal menyesuaikan.

## Penjelasan Script

- Line 3
```
> WAIT SECONDS=60
```
Penjelasan : Script dijalankan 1 menit (60 Second) sebelum jam serbu di mulai.
Misal serbuan di mulai jam 00:00. Nah, kita jalankan script pas di jam 23:59:00. Harus pas di detik 00 nya. Bisa juga diganti dengan 120 secod (2 Menit). Tinggal sesuaikan dengan kebutuhan.

Untuk bisa melihat jam beserta detiknya bisa di lihat [Disini](https://www.timeanddate.com/worldclock/indonesia/jakarta). Kemudian tinggal klik "Full Screen, Kemudian klik "Popup Window". Hingga muncul seperti ini:
<div align="center">
<img src="https://github.com/aaikmal/shopee-flashsell-imacros/raw/main/img/popup.png" width="400" height="300"/>
</div>

- Line 5
```
> URL GOTO=LINK BARANG KALIAN
```
Penjelasan : Silahkan isi link barang yang mau kalian serbu, setelah samadengan (=).

-line 11 dan 12
```
> TAG POS=1 TYPE=BUTTON ATTR=TXT:Shopeepay
```
Penjelasan : Pilih metode pembayaran. Disini, sebagai contoh kita menggunakan Shopeepay untuk metode pembayaran yang kita pakai. Jika kita ingin menggunakan metode pembayaran lain, kita bisa mengubahnya.

Sebagai contoh kita menggunakan BNI VA, di bagian line 12. Tetapi line tersebut tidak diaktifkan, dengan di beri tanda "'". tanda tersebut di artikan <i>comment</i> di iMacros. Jika ingin menggantikan peembayaran Shopeepay dengan yang lain, tinggal mengganti dengan pembayaran yang kita mau.

<i>Catatan:
  Tidak semua barang Flash Sell di Shopee bisa menggunakan metode pembayaran Transfer Bank, Jadi silahkan sesuaikan dengan metode pembayaran yang mendukung barang Flash Sell. Sebagai contoh disini ada barang yang harus menggunakan ShopeePay sebagai metode pembayaran. Dengan di tandai dengan label seperti ini di foto barang nya.
<div align="center">
<img src="https://github.com/aaikmal/shopee-flashsell-imacros/raw/main/img/spay.png"
</div>

