# Numerology Database Repository

Repo ini menyimpan **database statis** untuk aplikasi Android [Numerologi Masana Bangun](https://github.com/numerologynumber0-hue/numerologi).

Tujuan: memisahkan data besar (kata, terjemahan, tabel lookup) dari source code Android agar:
- Source code `.kt` lebih ringan
- Data bisa di-update **tanpa release APK baru**
- Mudah dikolaborasikan (kontribusi terjemahan, tambah kata, dsb.)

---

## 📦 Struktur Data

| File | Isi | Ukuran (estimasi) |
|------|-----|-------------------|
| `version.json` | Metadata versi + checksum | ~1 KB |
| `data/available_languages.json` | Daftar bahasa yang didukung | ~1 KB |
| `data/language_databases.json` | Seed DB `id` & `en` + generated `ar/fr/es/zh/hi` | ~200 KB |
| `data/extended_word_database.json` | 9 bucket Exp1..Exp9 untuk Name Generator | ~400 KB |
| `data/vlookup_table.json` | Deskripsi G1..G1390 (Grafologi) × 7 bahasa | ~80 KB |
| `data/translations.json` | UI translations 7 bahasa | ~120 KB |
| `data/name_dictionary.json` | Kamus nama + artinya | ~15 KB |
| `data/parameter_descriptions.json` | Deskripsi parameter numerologi | ~10 KB |

---

## 🌐 Cara Akses

### Opsi 1 — jsDelivr CDN (Recommended)
