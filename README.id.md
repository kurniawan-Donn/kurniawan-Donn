<!--
  Terjemahan Bahasa Indonesia dari README.md. Jaga agar isi kedua file tetap sama.
-->

<div align="center">

[English](./README.md) · **Bahasa Indonesia**

# Dony Kurniawan

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&repeat=true&width=640&height=40&lines=%3E+Audit+TI+%26+Tata+Kelola+TI;%3E+Keamanan+Siber+%26+Penilaian+Risiko;%3E+Pengembangan+Software+%26+Otomasi+Python;%3E+Secure+by+design%2C+auditable+by+default." alt="Teks animasi bergantian: Audit TI dan Tata Kelola TI, Keamanan Siber dan Penilaian Risiko, Pengembangan Software dan Otomasi Python, Secure by design, auditable by default" />

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-11151B?style=for-the-badge&logo=vercel&logoColor=00D9FF)](https://portofoli-dony.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-11151B?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/dony-kurniawan-7b04bb291)
[![Email](https://img.shields.io/badge/EMAIL-11151B?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:donykurniawan1298@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-11151B?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/kurniawan-Donn)

[Tentang](#about) · [Proyek](#projects) · [Tech Stack](#tech-stack) · [Belajar](#learning) · [Aktivitas](#activity) · [Kontak](#contact)

</div>

---

<a id="about"></a>

## ⌨️ whoami

```yaml
# ~/profile.yml
nama: Dony Kurniawan
pendidikan: D3 Teknologi Informasi @ Politeknik Negeri Madiun (tingkat akhir)
lokasi: Indonesia 🇮🇩

fokus:
  utama:      [audit TI, tata kelola TI]
  pendukung:  [keamanan siber, penilaian risiko, pengembangan software, otomasi Python]

sedang_dipelajari: [ISO 27001, COBIT 2019, threat modeling, Next.js, TypeScript, Supabase]
terbuka_untuk:     [magang, posisi IT entry-level, kolaborasi teknis]

prinsip:
  - "Secure by design, auditable by default."
  - "Build to understand. Create to solve."
```

Saya suka memahami cara kerja sistem, di mana risiko muncul, dan bagaimana kontrol yang praktis membuat teknologi lebih aman dan andal. Minat karier utama saya adalah **audit TI**: memeriksa apakah sistem memiliki kontrol yang tepat dan apakah kontrol itu bekerja sebagaimana mestinya. Saya mendekatinya lewat tiga bidang yang saling terhubung:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#11151B', 'primaryTextColor': '#F2F0E9', 'primaryBorderColor': '#00D9FF', 'lineColor': '#9299A5', 'fontFamily': 'monospace'}}}%%
flowchart LR
    DEV["BUILD<br/>Pengembangan software<br/>bagaimana sistem dibuat"] --> SEC["PROTECT<br/>Keamanan siber<br/>bagaimana sistem diserang dan dilindungi"] --> AUD["VERIFY<br/>Audit dan tata kelola TI<br/>apakah kontrol berjalan"]
```

---

<a id="projects"></a>

## 🚀 Proyek Unggulan

<table>
<tr>
<td width="50%" valign="top">

### 📝 DocxLint

![Live](https://img.shields.io/badge/status-demo_live-70E1A1?style=flat-square&labelColor=11151B)
![Tests](https://img.shields.io/badge/test-218_lulus-00D9FF?style=flat-square&labelColor=11151B)

Memeriksa dokumen Word berbahasa Indonesia: salah eja, istilah asing yang belum di-*italic*, dan format yang tidak sesuai profil. Berjalan lokal dengan kamus berbasis aturan, tanpa AI generatif, dan hanya menerapkan perbaikan yang Anda setujui ke salinan dokumen.

`Python` `Streamlit` `.docx`

[**Demo live**](https://docxlint-id.streamlit.app) · [Repository](https://github.com/kurniawan-Donn/docxlint-app)

</td>
<td width="50%" valign="top">

### 🛡️ Regulation Audit Assistant

![Beta](https://img.shields.io/badge/status-beta-00D9FF?style=flat-square&labelColor=11151B)
![Focus](https://img.shields.io/badge/fokus-audit_TI-9299A5?style=flat-square&labelColor=11151B)

Mengubah regulasi perbankan Indonesia (POJK, SEOJK, PBI, PADK) menjadi kertas kerja audit TI dan checklist gap analysis. Dibantu AI, dengan setiap referensi pasal divalidasi terhadap teks sumber untuk mencegah halusinasi. Keputusan tetap di tangan auditor.

`Python` `FastAPI` `Gemini API` `Ekspor Excel / PDF`

[Repository](https://github.com/kurniawan-Donn/regulation-audit-assistant)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🥷 Metadata Remover

![Live](https://img.shields.io/badge/status-demo_live-70E1A1?style=flat-square&labelColor=11151B)
![Focus](https://img.shields.io/badge/fokus-privasi-9299A5?style=flat-square&labelColor=11151B)

Menganalisis, mengklasifikasikan, dan menghapus metadata sensitif (lokasi GPS, nama pembuat, info perangkat) dari file sebelum dibagikan ke publik.

`Python` `Streamlit`

[**Demo live**](https://metadata-remover-app-dk.streamlit.app) · [Repository](https://github.com/kurniawan-Donn/metadata-remover-streamlit)

</td>
<td width="50%" valign="top">

### 💎 Xuping Afa

![Live](https://img.shields.io/badge/status-situs_live-70E1A1?style=flat-square&labelColor=11151B)
![Platform](https://img.shields.io/badge/platform-web-9299A5?style=flat-square&labelColor=11151B)

Toko web untuk pembelian dan pemasaran perhiasan xuping, dengan katalog produk untuk pelanggan dan akses berbasis peran untuk mengelola toko.

`Laravel` `PHP` `Blade`

[**Kunjungi situs**](https://xuping-afa.my.id/) · [Repository](https://github.com/kurniawan-Donn/Xuping-Afa)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📒 LumiNote

![Complete](https://img.shields.io/badge/status-selesai-70E1A1?style=flat-square&labelColor=11151B)
![Platform](https://img.shields.io/badge/platform-android-9299A5?style=flat-square&labelColor=11151B)

Catatan, tugas, pengingat, kalender, dan statistik produktivitas dalam satu aplikasi Android. Data tersimpan di perangkat, jadi tetap bisa dipakai tanpa koneksi internet.

`Kotlin` `MVVM` `Room` `Material Design`

[Repository](https://github.com/kurniawan-Donn/LumiNote)

</td>
<td width="50%" valign="top">

### 🎲 Spinly

![Beta](https://img.shields.io/badge/status-beta-00D9FF?style=flat-square&labelColor=11151B)
![Platform](https://img.shields.io/badge/platform-android-9299A5?style=flat-square&labelColor=11151B)

Spinner acak multiplayer. Pemain bergabung ke room dengan kode room dan melihat hasil yang sama pada saat yang sama, tersinkron secara real-time.

`Kotlin` `Firebase Auth` `Cloud Firestore`

[Repository](https://github.com/kurniawan-Donn/Spinly-Android-Beta)

</td>
</tr>
</table>

<sub>Juga di GitHub: <a href="https://github.com/kurniawan-Donn/FItQuest_Android-Beta"><b>FitQuest</b></a>, aplikasi fitness Android versi beta (Kotlin, Jetpack Compose, Firebase), dan <a href="https://github.com/kurniawan-Donn/Porto_dnyy"><b>situs portofolio saya</b></a> (Next.js, TypeScript).</sub>

<div align="center">

<br />

[![Lihat semua repository](https://img.shields.io/badge/LIHAT_SEMUA_REPOSITORY-11151B?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/kurniawan-Donn?tab=repositories)

</div>

---

<a id="tech-stack"></a>

## 🧰 Tech Stack

<div align="center">

**Bahasa pemrograman**
<br /><br />
<img src="https://skillicons.dev/icons?i=python,php,kotlin,js,ts,html,css&theme=dark" alt="Python, PHP, Kotlin, JavaScript, TypeScript, HTML, CSS" />

**Framework dan tools**
<br /><br />
<img src="https://skillicons.dev/icons?i=laravel,fastapi,nextjs,tailwind,androidstudio,git,github,figma,vscode&theme=dark" alt="Laravel, FastAPI, Next.js, Tailwind CSS, Android Studio, Git, GitHub, Figma, VS Code" />
<br />
<img src="https://img.shields.io/badge/Streamlit-11151B?style=flat-square&logo=streamlit&logoColor=00D9FF" alt="Streamlit" />

**Database dan layanan backend**
<br /><br />
<img src="https://skillicons.dev/icons?i=mysql,sqlite,postgres,firebase,supabase&theme=dark" alt="MySQL, SQLite, PostgreSQL, Firebase, Supabase" />

**Audit, tata kelola, dan keamanan**
<br /><br />
`Audit TI` `Tata kelola TI` `Penilaian risiko` `Analisis sistem` `Privasi`

<sub>Dipakai di proyek: Python, PHP, Kotlin, Laravel, FastAPI, Streamlit, MySQL, Firebase, Room di atas SQLite. Sedang dipelajari: Next.js, TypeScript, Supabase.<br />Daftar ini gabungan pengalaman proyek dan pembelajaran yang sedang berjalan, bukan tingkat kemahiran yang sama di setiap tool.</sub>

</div>

---

<a id="learning"></a>

## 📚 Peta Belajar

| Bidang | Fokus saat ini | Mengapa penting untuk jalur saya |
|:--|:--|:--|
| **Framework audit TI** | ISO 27001, COBIT 2019 | Acuan umum untuk manajemen keamanan informasi dan tata kelola TI |
| **Keamanan siber** | Analisis jaringan, threat modeling | Menunjukkan bagaimana sistem bisa diserang dan di mana pengamanan dibutuhkan |
| **Otomasi Python** | Skrip audit dan pemrosesan dokumen | Mengurangi pekerjaan manual berulang saat meninjau dokumen dan bukti |
| **AI yang bertanggung jawab** | Alur kerja berbantuan AI dengan tinjauan manusia | Output AI perlu diverifikasi sebelum dipakai dalam pekerjaan audit |
| **Web stack modern** | Next.js, TypeScript, Supabase | Memperluas cara saya membangun dan memahami aplikasi modern |

---

<a id="activity"></a>

## 📈 Aktivitas GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kurniawan-Donn/kurniawan-Donn/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kurniawan-Donn/kurniawan-Donn/output/github-snake.svg" />
  <img alt="Animasi ular yang memakan kotak-kotak grafik kontribusi GitHub saya" src="https://raw.githubusercontent.com/kurniawan-Donn/kurniawan-Donn/output/github-snake-dark.svg" width="100%" />
</picture>

<br /><br />

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=kurniawan-Donn&show_icons=true&hide_border=true&border_radius=8&bg_color=11151B&title_color=00D9FF&icon_color=00D9FF&text_color=F2F0E9" alt="Statistik profil GitHub kurniawan-Donn" />
<img width="49%" src="https://streak-stats.demolab.com?user=kurniawan-Donn&hide_border=true&border_radius=8&background=11151B&ring=00D9FF&fire=00D9FF&currStreakNum=F2F0E9&currStreakLabel=00D9FF&sideNums=F2F0E9&sideLabels=F2F0E9&dates=9299A5&stroke=9299A5&locale=id" alt="Streak kontribusi GitHub kurniawan-Donn" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kurniawan-Donn&layout=compact&langs_count=6&hide_border=true&border_radius=8&bg_color=11151B&title_color=00D9FF&text_color=F2F0E9&locale=id" alt="Bahasa yang paling sering dipakai di repository publik" />

<sub>Kartu-kartu ini berasal dari layanan pihak ketiga dan sesekali bisa tidak tersedia. Statistik bahasa menggambarkan isi repository, bukan tingkat keahlian secara keseluruhan.</sub>

</div>

---

<a id="contact"></a>

## 📫 Hubungi Saya

Saya terbuka untuk **magang, posisi IT entry-level, dan kolaborasi teknis**, terutama di bidang audit TI, tata kelola, keamanan siber, dan pekerjaan terkait risiko. Jika Anda sedang mengerjakan sesuatu di bidang tersebut, saya senang mendengarnya.

- **Portfolio:** [portofoli-dony.vercel.app](https://portofoli-dony.vercel.app)
- **LinkedIn:** [Dony Kurniawan](https://www.linkedin.com/in/dony-kurniawan-7b04bb291)
- **Email:** [donykurniawan1298@gmail.com](mailto:donykurniawan1298@gmail.com)
- **GitHub:** [@kurniawan-Donn](https://github.com/kurniawan-Donn)

<div align="center">

<br />

<img src="https://komarev.com/ghpvc/?username=kurniawan-Donn&label=PROFILE%20VIEWS&color=00D9FF&style=flat-square" alt="Penghitung kunjungan profil" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080A0D,100:00D9FF&height=110&section=footer" alt="" width="100%" />

</div>
