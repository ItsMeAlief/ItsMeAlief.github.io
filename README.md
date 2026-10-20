# Panduan Deployment GitHub Pages untuk Ahmad Alief Maulana Putra

Website portofolio profesional bergaya **Neo-Brutalism Sharp** ini siap di-host langsung ke **GitHub Pages** di bawah akun GitHub Anda: **[@ItsMeAlief](https://github.com/ItsMeAlief)**.

Domain website Anda:
👉 **`https://itsmealief.github.io`**

---

## 📁 Berkas di Folder Website:
1. [`index.html`](./index.html) *(Halaman website portofolio utama)*
2. [`cv.html`](./cv.html) *(Halaman Curriculum Vitae resmi versi Web/Print)*
3. [`CV_Ahmad_Alief_Maulana_Putra.pdf`](./CV_Ahmad_Alief_Maulana_Putra.pdf) *(Berkas resmi PDF Curriculum Vitae standar ATS, siap unduh)*
4. [`Me.jpg`](./Me.jpg) *(Foto profil Anda)*
5. [`README.md`](./README.md) *(Dokumen panduan deployment)*

---

## 🛠️ Tech Stack & Software yang Ditampilkan di Website:
- **Civil Engineering & BIM:** Autodesk AutoCAD, Autodesk Revit, SAP2000 / Etabs
- **Mechanical 3D & Prototyping:** Fusion 360 / SolidWorks, 3D Printing (FDM) & Slicers
- **Electronics & Embedded:** KiCAD, STM32CubeIDE, ESP-IDF & Arduino C++
- **UAV, Drones & Autonomous Robotics:** Betaflight, ArduPilot / PX4, Telemetry Radio & ESCs
- **Programming & Automation:** Python (Data/Automation scripts), Embedded C/C++
- **Technical Documentation & Computation:** Microsoft Word, Microsoft Excel

---

## 🚀 Langkah Deploy Cepat (2 Menit)

### Opsi A: Lewat Web Browser (Paling Mudah)
1. Buka [github.com/new](https://github.com/new).
2. Di kolom **Repository name**, isi persis:
   ```text
   ItsMeAlief.github.io
   ```
3. Pilih **Public**.
4. Klik **Create repository**.
5. Di halaman repository yang baru saja dibuat, klik link **"uploading an existing file"**.
6. Seret berkas ini: [`index.html`](./index.html), [`Me.jpg`](./Me.jpg), dan `CV_Ahmad_Alief_Maulana_Putra.pdf` (jika sudah ada) ke browser.
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
git add index.html Me.jpg README.md
# Jika ada file CV: git add CV_Ahmad_Alief_Maulana_Putra.pdf
git commit -m "feat: neo-brutalism portfolio with tech stack, cv download & spotify player"
git branch -M main
git remote add origin https://github.com/ItsMeAlief/ItsMeAlief.github.io.git
git push -u origin main
```

---

## 📇 Data, Musik & Kontak di Website:
- **Nama:** Ahmad Alief Maulana Putra
- **Foto Profil:** `Me.jpg`
- **Fokus Interdisipliner:** Civil Infrastructure & Structural Mechanics + Embedded Hardware, IoT & UAV/Drone Engineering
- **Genre Musik Favorit:** **Rap / Hip-Hop**
- **Life & Engineering Anthem:** *"If God got us then we gon' be alright"* — Kendrick Lamar (*Alright*, 2015)
- **Official Spotify Player:** *Kendrick Lamar - Alright* (ID: `3iVcZ5G6tvkXZkZKlMpIUs`)
- **Alamat:** Jl. N.J.Dt.Mangkuto Ameh No.65, RT.2/RW.2, Koto Selayan, Kec. Mandiangin Koto Selayan, Kota Bukittinggi, Sumatera Barat 26117
- **Kampus:** Universitas Andalas
- **WhatsApp / Phone:** `+62 857-8953-9506`
- **Primary Email:** `aaliefmp@gmail.com`
- **Formal Email:** `ahmadaliefmaulanaputra@gmail.com`
- **Instagram:** `@a.alief_`
- **GitHub:** `ItsMeAlief`
