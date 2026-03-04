## SCRIPT BORNEO SSH & XRAY ( UBUNTU 18 & 20 / DEBIAN 9 & 10 )

## Cara Install

### 1. Daftarkan terlebih dahulu IP VPS Yang ingin di install di link berikut ini :

>>> https://github.com/lapakheru/ijin/blob/main/vip

### 2. Pastikan Domain Sudah di pointing di cloudflare 

![Contoh Pointing Domain](https://github.com/lapakheru/borneo/blob/main/CONTOH.png?raw=true)

### 3. Install Script Borneo dengan copy paste Link di bawah ini ke VPS Yang ingin di install :
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://github.com/lapakheru/install/raw/refs/heads/main/install-borneo && chmod +x install-borneo && ./install-borneo
```
### 4. Panduan Video Lengkap

Untuk lebih jelasnya, silakan tonton video panduan instalasi di bawah ini:

<table>
  <tr>
    <td align="center">
      <a href="https://youtu.be/hW1-10tr25I">
        <img src="https://i9.ytimg.com/vi/hW1-10tr25I/mqdefault.jpg?v=68298bf9&sqp=CNCtns0G&rs=AOn4CLCTRJpq4OTkdzROGpg-bsu0phmdmg" alt="Panduan Part 1" width="400">
      </a>
      <br>
      <b>Part 1: Persiapan VPS & Domain</b>
    </td>
    <td align="center">
      <a href="https://youtu.be/v0tvwGXiW0c">
        <img src="https://i9.ytimg.com/vi_webp/v0tvwGXiW0c/mqdefault.webp?v=67b1a7b3&sqp=CNCtns0G&rs=AOn4CLCVVgDyNW2L1Gfo-ONrJGQTzmTMoQ" alt="Panduan Part 2" width="400">
      </a>
      <br>
      <b>Part 2: Pointing Domain Cloudflare</b>
    </td>
  </tr>
</table>

### 5. Selesai

================================= JIKA VPS UBUNTU LEBIH DARI UBUNTU 20.0.4 WAJIB DOWNGRADE KE UBUNTU 20.0.4========================
###  COPY PASTE LINK BERIKUT UNTUK DOWNGRADE VPS KE UBUNTU 20


```
wget https://raw.githubusercontent.com/lapakheru/borneo/refs/heads/main/install-ulang
chmod +x install-ulang
./install-ulang
```

- PILIH NOMOR 2.UBUNTU
- PILIH VERSI NOMOR 1 . 20.04
- krtika di minta masukan atau ketikan huruf Y ( lalu ENTER )
- TUNGGU PROSSES NYA KURANG LEBIH 10 MENIT
- SELESAI MASUK SUDAH BERUBAH MENJADI UBUNTU 20.04
