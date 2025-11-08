# UTS-Temu-Kembali-Informasi
---

# 📘 Dataset Putusan Pengadilan Negeri Bandung – Kasus Narkotika & Psikotropika

## 🗂️ Struktur Direktori

```
Dataset/
│
├── Narkotika.zip
│
└── Overview/
    └── Overview.xlsx
```

---

## 📄 Deskripsi Dataset

Dataset ini berisi kumpulan **putusan pengadilan** yang berkaitan dengan **kasus narkotika dan psikotropika** di **Pengadilan Negeri Bandung**.
Dataset dikumpulkan untuk keperluan **analisis dokumen hukum**, seperti *information retrieval*, *text classification*, dan *case-based reasoning*.

---

## 📁 1. Narkotika.zip

* Berisi kumpulan **dokumen mentah** putusan pengadilan dalam **format PDF**.
* Setiap file PDF merepresentasikan satu kasus hukum yang berbeda.
* Dokumen-dokumen ini memuat elemen seperti:

  * Identitas perkara
  * Ringkasan fakta hukum
  * Barang bukti
  * Pasal yang dilanggar
  * Amar putusan

**Contoh isi file PDF:**

* No. Putusan: 123/Pid.Sus/2020/PN.Bdg
* Jenis Perkara: Narkotika Golongan I
* Barang Bukti: Sabu 0.5 gram
* Amar Putusan: Terdakwa dijatuhi pidana penjara 4 tahun

---

## 📊 2. Overview.xlsx

* Merupakan file ringkasan yang berisi metadata setiap dokumen putusan.
* Dapat digunakan sebagai *index table* untuk memudahkan pencarian, analisis, atau pemetaan dokumen.

### Struktur Kolom:

| Kolom                 | Deskripsi                                                    |
| --------------------- | ------------------------------------------------------------ |
| **No**                | Nomor urut data                                              |
| **No Putusan**        | Nomor perkara sesuai dokumen resmi                           |
| **Lembaga Peradilan** | Nama pengadilan yang memutuskan perkara (contoh: PN Bandung) |
| **Barang Bukti**      | Jenis dan jumlah barang bukti yang disebutkan dalam putusan  |
| **Amar Putusan**      | Ringkasan keputusan akhir hakim terhadap terdakwa            |

---

## 🧠 Tujuan Penggunaan

Dataset ini disiapkan untuk berbagai kegiatan analisis seperti:

* **Text Mining & NLP** pada dokumen hukum
* **Klasifikasi Putusan** berdasarkan amar atau barang bukti
* **Information Retrieval (IR)** kasus serupa
* **Case-Based Reasoning (CBR)** untuk sistem rekomendasi putusan hukum

---

## ⚠️ Catatan Penting

* Semua dokumen diambil dari sumber publik yang tersedia di laman resmi **Mahkamah Agung Republik Indonesia**.
* Dataset ini **tidak dimodifikasi secara substantif**, hanya diorganisasi untuk keperluan penelitian akademik.
* Penggunaan dataset ini **hanya untuk tujuan penelitian dan pendidikan**, bukan untuk kepentingan hukum atau komersial.

---

## 👤 Penyusun

**Nama:** [Diemas Andung Prayoga] [Lalu Muhammad Wisnu Yusuf]
**Tahun:** 2025

---
