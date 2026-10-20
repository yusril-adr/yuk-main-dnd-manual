# Manual YukMainDnD

Buku panduan pengguna YukMainDnD (Bahasa Indonesia) untuk pengunjung, pemain, dan Dungeon Master, dibuat dengan [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

**Baca online:** https://yusril-adr.github.io/yuk-main-dnd-manual/

Isi panduan ada di folder `docs/`. Setiap push ke branch `main` otomatis membangun dan menerbitkan situs ke GitHub Pages.

## Menjalankan di komputer sendiri

### Dengan Docker

```bash
docker compose up
```

Lalu buka http://localhost:8000.

### Dengan Python

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Lalu buka http://127.0.0.1:8000.

Untuk memeriksa build seperti di GitHub Actions:

```bash
mkdocs build --strict
```
