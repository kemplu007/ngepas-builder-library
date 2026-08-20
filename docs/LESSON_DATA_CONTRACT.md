# Lesson Data Contract — Ngepas Builder Library

## Tujuan
Satu lesson harus cukup lengkap untuk menjelaskan konsep dengan analogi, contoh kode, kesalahan umum, dan latihan.

## Data lesson
| Field | Fungsi |
|---|---|
| id | Identitas unik lesson |
| title | Judul lesson |
| slug | URL ramah baca, contoh `javascript-variable` |
| level | `fundamental`, `intermediate`, atau `expert` |
| language | Bahasa pemrograman, contoh `javascript` |
| summary | Ringkasan singkat lesson |
| problem | Masalah nyata yang dipecahkan |
| analogy | Analogi kehidupan sehari-hari |
| mentalModel | Gambaran mental inti |
| contentMarkdown | Penjelasan konsep utama |
| codeExample | Contoh kode kecil |
| commonError | Kesalahan umum dan penjelasannya |
| exercise | Latihan kecil untuk learner |
| projectApplication | Hubungan konsep dengan project nyata |
| status | `draft`, `published`, atau `archived` |
| createdAt | Waktu lesson dibuat |
| updatedAt | Waktu lesson terakhir diubah |
| publishedAt | Waktu lesson dipublikasikan |

## Aturan publikasi
- Learner hanya dapat melihat lesson dengan status `published`.
- Admin dapat membuat, mengubah, dan mengarsipkan lesson.
- Slug harus unik dan menggunakan huruf kecil, angka, serta strip.

## Data belajar lokal
- `completed`: daftar slug lesson yang selesai.
- `bookmarked`: daftar slug lesson yang disimpan.
- `notes`: catatan explain-back berdasarkan slug lesson.
- `lastLesson`: slug lesson terakhir yang dibuka.

## Batas V0
Data belajar learner disimpan lokal di perangkat. Tidak ada login learner dan tidak ada sinkronisasi antarperangkat.
