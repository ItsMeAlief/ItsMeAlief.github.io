# Panduan Deployment GitHub Pages untuk Ahmad Alief Maulana Putra

Website portofolio teknik & pengenalan diri ini siap di-host langsung ke **GitHub Pages** di bawah akun GitHub Anda: **[@ItsMeAlief](https://github.com/ItsMeAlief)**.

Domain website Anda nantinya adalah:
👉 **`https://itsmealief.github.io`**

---

## 🚀 Langkah Deploy Cepat (3 Menit)

### Opsi A: Lewat Web Browser (Paling Mudah)
1. Buka [github.com/new](https://github.com/new).
2. Di kolom **Repository name**, isi persis:
   ```text
   ItsMeAlief.github.io
   ```
3. Pilih **Public**.
4. Klik **Create repository**.
5. Di halaman repository yang baru saja dibuat, klik link **"uploading an existing file"**.
6. Seret file [`index.html`](./index.html) dan [`README.md`](./README.md) ini ke browser.
7. Klik tombol hijau **Commit changes**.
8. Buka tab **Settings** > **Pages** (di sidebar kiri):
   - Pastikan **Source** adalah `Deploy from a branch`
   - **Branch** terpilih `main` dan folder `/(root)`
   - Klik **Save**.
9. Tunggu 1–2 menit, website Anda langsung online di **`https://itsmealief.github.io`**!

---

### Opsi B: Lewat Git Terminal / PowerShell
Jalankan perintah ini di PowerShell pada folder ini:
```powershell
cd "C:\Users\ahmad\.gemini\antigravity\scratch\portfolio-github-io"
git init
git add index.html README.md
git commit -m "feat: portfolio site for Ahmad Alief Maulana Putra"
git branch -M main
git remote add origin https://github.com/ItsMeAlief/ItsMeAlief.github.io.git
git push -u origin main
```

---

## 📇 Data & Kontak yang Terpasang di Website:
- **Nama:** Ahmad Alief Maulana Putra
- **Alamat:** Jl. N.J.Dt.Mangkuto Ameh No.65, RT.2/RW.2, Koto Selayan, Kec. Mandiangin Koto Selayan, Kota Bukittinggi, Sumatera Barat 26117
- **Kampus:** Universitas Andalas
- **WhatsApp / Phone:** `+62 857-8953-9506` (`https://wa.me/6285789539506`)
- **Primary Email:** `aaliefmp@gmail.com`
- **Formal Email:** `ahmadaliefmaulanaputra@gmail.com`
- **Instagram:** `@a.alief_` (`https://instagram.com/a.alief_`)
- **GitHub:** `ItsMeAlief` (`https://github.com/ItsMeAlief`)
