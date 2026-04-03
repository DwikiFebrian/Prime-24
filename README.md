# PRIME 24 🃏🔢

**PRIME 24** adalah game *math-based roguelike deck builder* di mana aritmatika bertemu dengan mekanik judi berisiko tinggi. Terinspirasi dari *Balatro*, game ini menantang pemain untuk mengombinasikan kartu bilangan prima dengan operator dasar untuk mencapai angka target, membangun pengganda skor (Mult) yang masif, dan memilih *passive buffs* yang bisa mengubah jalannya permainan.

Coba gamenya langsung di browser: [**Mainkan PRIME 24**](https://dwikifebrian.github.io/Prime-24/)

---

## ✨ Fitur Utama

- **Mekanik Bilangan Prima:** Menggunakan dek yang seluruhnya berisi bilangan prima (2, 3, 5, 7, 11, 13, 17, 19, 23).
- **Sistem Level:** Setiap level memiliki angka target komposit yang berbeda (misalnya: 24, 36, 77) dan target skor yang harus dicapai untuk lanjut ke level berikutnya.
- **Sistem Skor Chips × Mult:** Bangun skor dengan memainkan prima bernilai tinggi (Chips) dan manfaatkan operator perkalian/pembagian atau *Exact Hit* (Mult).
- **Drafting Joker:** Pilih satu dari 3 Joker acak di akhir setiap level. Joker ini akan menjadi bonus pasif permanen yang memperkuat strategi perhitungan lu.
- **Tanpa Dependency:** Dibangun sepenuhnya menggunakan satu file HTML dengan vanilla JavaScript dan CSS (Tailwind via CDN).

---

## 🎮 Cara Bermain

Pemain akan mendapatkan 5 kartu prima di setiap tangan. Tujuannya adalah menyusun persamaan matematika menggunakan kartu-kartu tersebut dan operator (`+`, `-`, `*`, `/`) agar hasilnya sedekat mungkin dengan **Angka Target**.

1. Klik/Tekan kartu untuk memasukkannya ke persamaan.
2. Masukkan operator di antara kartu-kartu tersebut.
3. Submit untuk menghitung skor.
4. Capai **Skor Target** sebelum jumlah tangan (Hands) habis.

### Perhitungan Skor
- **Chips:** Setiap kartu prima memberikan chips sebesar `Nilai × 10`.
- **Mult:** Meningkat jika menggunakan operator kali/bagi, menggunakan semua 5 kartu, atau memicu efek Joker.
- **Exact Hit:** Jika hasil persamaan tepat sama dengan angka target, lu dapat bonus tambahan +500 Chips!

### Kontrol Keyboard
Selain menggunakan mouse, lu bisa bermain lebih cepat dengan keyboard:
- `1` - `5`: Memilih kartu di tangan
- `+`, `-`, `*`, `/`: Menambahkan operator matematika
- `Enter`: Submit Hand
- `Backspace` / `Esc`: Menghapus Persamaan

---

## 🃏 Daftar Joker (Passive Buffs)

Setelah menyelesaikan level, lu bisa memilih satu Joker untuk masuk ke inventori:

* **🔮 The Diviner:** Pembagian dengan prima 3 → final Mult ×10
* **♊ Twin Paradox:** Menggunakan 2 prima dengan selisih 2 → Mult ×5
* **☮ The Pacifist:** Hanya menggunakan operator `+` → Mult ×15
* **⚡ The Titan:** Menggunakan prima ≥17 → +500 bonus chips
* **🪞 The Mirror:** Menggunakan kartu prima kembar/duplikat → Mult ×4

---

## 🛠️ Teknologi

- **HTML5 & CSS3** (Desain UI prosedural dengan Tailwind CSS)
- **Vanilla JavaScript** (ES6+)
- **GitHub Pages** untuk hosting.

## 🚀 Instalasi Lokal

Karena game ini bersifat *self-contained*, lu cukup:

1. Clone repository ini:
   ```bash
   git clone [https://github.com/dwikifebrian/Prime-24.git](https://github.com/dwikifebrian/Prime-24.git)
2. Buka file index.html di browser favorit lu.
