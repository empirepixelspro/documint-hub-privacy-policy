# Documint Hub — Privacy Policy (GitHub Pages)

Tiruan struktur daripada `empirepixelspro/jagasolat-privacy-policy`, disesuaikan untuk
**Documint Hub** (app tempatan, tiada backend, tiada lokasi/kalendar/notifikasi).

## Cara publish (pilih satu)

### A) GitHub Pages (disaran — sama macam Jaga Solat)
```bash
cd "F:\Project\GooleAIStudio-APP Android\documint-hub-privacy-policy"
git init
git add index.html README.md
git commit -m "Documint Hub privacy policy"
gh repo create empirepixelspro/documint-hub-privacy-policy --public --source=. --push
# atau tanpa gh: buat repo kosong di github.com, kemudian
#   git remote add origin https://github.com/empirepixelspro/documint-hub-privacy-policy.git
#   git push -u origin main
```
Lepas tu aktifkan: **Repo → Settings → Pages → Source: main → /(root)**.

URL untuk Play Console:
```
https://empirepixelspro.github.io/documint-hub-privacy-policy/
```

> `gh` CLI belum dipasang pada mesin ini — pasang dulu (`winget install GitHub.cli`)
> atau guna cara B.

### B) Tanpa gh
1. Buka https://github.com/new → name: `documint-hub-privacy-policy` → Public → Create
2. Upload fail `index.html` (dan README.md)
3. Settings → Pages → Source: `main` → Save

## Nota kandungan
- Bahagian **2 (Israel exclusion)** ditiru daripada Jaga Solat. Kalau tak mahu sekatan serantau,
  padam seksyen itu.
- E-mel hubungan `empirepixelspro@gmail.com` — tukar jika perlu.
- Kemas kini tarikh "Last Updated" bila ubah kandungan.
