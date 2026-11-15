# Documint Hub — Jawapan borang **Data Safety** (Play Console)

Salin-terus ke: **Play Console → App content → Data safety**.

## A. Adakah app kumpul data?
**Ya** (kerana iklan AdMob) — tapi **bukan oleh developer**.

## B. Data yang dikumpul

### 1. Device IDs — *Advertising ID*
| Soalan | Jawapan |
|---|---|
| Is it collected? | **Yes** |
| Is it shared? | **No** |
| Is it required, or optional? | **Optional** |
| Purposes | **Advertising** · **Fraud prevention, security, compliance** |
| Data is deleted when user requests | **Yes** (iklan personal boleh dimatikan dlm settings; AdMob mematuhi permintaan padam Google) |
| Collected by | **Third party (Google AdMob)** — developer sendiri tidak mengumpul |

### 2. Purchases — *In-app purchases*
| Soalan | Jawapan |
|---|---|
| Is it collected? | **Yes** (diproses **Google Play**, bukan server kami) |
| Is it shared? | **No** |
| Required / optional | **Required** (untuk langganan PRO pilihan pengguna) |
| Purposes | **App functionality** (unlock PRO) |
| Encrypted in transit | **Yes** |
| User can request deletion | **Yes** (Play urus; app pun ada Delete Account & Wipe Data) |

## C. TIADA kumpulan data lain
Sahkan **tidak** untuk: Name, Email, User IDs (akaun), Phone number, Physical address,
Contacts, Photos/videos, Audio files, Files/docs, Messages, In-app messages, Photos,
Location (precise/approximate), App activity, Web browsing, Search history,
Device/other IDs (selain Advertising ID), Health/fitness, Financial info, Car info,
Contacts/Address book, Call log, SMS.

Alasan: app **tiada backend**; semua data dokumen disimpan **pada peranti** dan tidak dihantar ke sesiapa.

## D. Security practices
- ✅ Data encrypted in transit: **Yes** (TLS — hanya trafik iklan/semakan kemas kini)
- ✅ User can request data deletion: **Yes**
- ✅ Independent security review: **Not applicable** (tiada pengumpulan data developer)

## E. Account deletion (Play: Account deletion)
- Tiada akaun server dibuat. Dalam app ada **Settings → Delete Account & Wipe Data**
  yang memadam SEMUA data lokal seketika.
- Pilihan dalam borang: **"N/A — app doesn't create accounts"** (atau jika perlu senaraikan
  ciri padam dalam app).

## F. Privacy policy URL
```
https://empirepixelspro.github.io/documint-hub-privacy-policy/
```

## G. Target audience
- **No** (app bukan khusus untuk kanak-kanak)
- Rating kandungan: **Everyone / Everyone 10+** (app perniagaan, tanpa tema sensitif)
