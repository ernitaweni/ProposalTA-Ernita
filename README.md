# Proposal Tugas Akhir

**Evaluasi Komparatif *Vision-Language Model* Terkuantisasi untuk Klasifikasi Pegawai dan Pelanggan dari Rekaman CCTV**

Proposal tugas akhir Departemen Teknik Komputer, Institut Teknologi Sepuluh Nopember (ITS), disusun dengan LaTeX menggunakan template proposal TA departemen.

## Struktur

| Lokasi | Isi |
|---|---|
| `TemplateProposalTATeknikKomputer.tex` | Berkas utama: identitas, judul, pembimbing, dan urutan bab |
| `Init/` | Konfigurasi template, sampul, lembar pengesahan, dan daftar pustaka |
| `abstrak/` | Abstrak Bahasa Indonesia dan Bahasa Inggris |
| `bab1/` – `bab5/` | Isi setiap bab beserta gambarnya (proposal memakai Bab I–III) |
| `KataPengantar/`, `BiografiPenulis/` | Halaman pelengkap |

Daftar pustaka ditulis langsung di `Init/DaftarPustaka.tex` (gaya IEEE, urut sesuai sitasi pertama). Berkas `pustaka/pustaka.bib` saat ini tidak dipakai.

## Kompilasi

Membutuhkan distribusi LaTeX seperti MiKTeX atau TeX Live.

```sh
latexmk -pdf TemplateProposalTATeknikKomputer.tex
```

Hasilnya adalah `TemplateProposalTATeknikKomputer.pdf`. Berkas hasil kompilasi (`.pdf`, `.aux`, `.log`, dan sejenisnya) tidak disimpan di repositori.
