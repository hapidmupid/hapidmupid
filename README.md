# 🎉 Selamat Datang di Proyek Konyol Ini! 🎉

![Meme Konyol](https://i.pinimg.com/originals/3e/5c/4e/3e5c4e1c1c1b1c1b1c1b1c1b1c1b1c1.jpg)

## 🤔 Apa Ini?

Ini adalah proyek yang tidak terlalu serius, di mana saya mencoba membuat sesuatu yang konyol dan menyenangkan. Jika Anda mencari sesuatu yang berguna, mungkin Anda harus pergi ke tempat lain. 😜

## 🕹️ Mini Game: Tebak Angka!

Cobalah mini game sederhana ini! Tebak angka antara 1 dan 10. Jika Anda berhasil, Anda adalah jenius! Jika tidak, ya... setidaknya Anda mencoba! 😅

```python
import random

angka_rahasia = random.randint(1, 10)
tebakan = None

while tebakan != angka_rahasia:
    tebakan = int(input("Tebak angka antara 1 dan 10: "))
    if tebakan < angka_rahasia:
        print("Terlalu rendah! Coba lagi.")
    elif tebakan > angka_rahasia:
        print("Terlalu tinggi! Coba lagi.")
    else:
        print("Selamat! Anda berhasil menebak angka yang benar! 🎉")
