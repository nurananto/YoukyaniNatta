# Youkya ni Natta Ore no Seishun Shijou Shugi

> Di dunia ini, secara garis besar ada dua jenis manusia: ekstrovert dan introvert. Untuk menikmati masa muda yang terbatas ini, hanya ada satu jalan yang harus dipilih. Dengan kata lain — kalau mau populer dan disukai, jadilah seorang ekstrovert. Ueda Kyouta, mantan introvert, berhasil “debut” di SMA berkat usaha dan tekad, dan menjalani kehidupan sekolah yang mulus bersama anak-anak populer. Tinggal punya pacar gyaru dan hidupnya akan sempurna — tapi kenapa justru tanda-tanda asmara yang muncul hanya dengan cewek-cewek introvert…!?

---

## Info

| | |
|---|---|
| Judul | Youkya ni Natta Ore no Seishun Shijou Shugi |
| Judul Alternatif | 陽キャになった俺の青春至上主義 |
| Author | Mochizaki Yuba |
| Artist | Koa |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Drama · Shounen · Comedy · Romance · School Life · Slice of Life |
| Chapter | 10 chapter |

## Link

- [MangaDex](https://mangadex.org/title/cfcb65ff-cf9b-4628-a666-76d1b06553dc/youkya-ni-natta-ore-no-seishun-shijou-shugi)
- [Raw](https://www.manga-up.com/titles/1388)

---

## Struktur

```
YoukyaniNatta/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)