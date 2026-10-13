# Numerologi Data Repository

Repository ini berisi data JSON untuk aplikasi Numerologi (Android/Kotlin).

## 📂 Struktur Data

| File | Deskripsi |
|---|---|
| `version.json` | Versi data & metadata |
| `data/available_languages.json` | Daftar bahasa yang didukung |
| `data/language_databases.json` | Database kata per bahasa (Exp1-Exp9) |
| `data/extended_word_database.json` | Extended word database untuk Name Generator |
| `data/vlookup_table.json` | Tabel deskripsi G1..G1390 multi-bahasa |
| `data/translations.json` | Terjemahan UI (7 bahasa) |
| `data/name_dictionary.json` | Kamus nama |
| `data/parameter_descriptions.json` | Deskripsi parameter numerologi |

## 🔄 Update Data

Aplikasi akan memeriksa `version.json` dan mengunduh data terbaru jika ada perubahan.

## 📝 Format Versioning

Gunakan semantic versioning: `MAJOR.MINOR.PATCH`

## 🌐 Bahasa yang Didukung

- `en` — English
- `id` — Indonesia
- `fr` — Français
- `es` — Español
- `ar` — العربية
- `zh` — 中文
- `hi` — हिन्दी
