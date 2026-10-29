# alfin.zone.id — pengalih ke alfindigital.com

Sejak 28 Okt 2026 (KO-14, ACC owner 27 Okt 2026) domain ini **bukan lagi hub/portofolio**. Semua alamat dialihkan permanen (301) ke `https://alfindigital.com/` lewat `_redirects`. Portofolio aktif ada di `https://porto.alfindigital.com` (repo `Apps/Alfindigital`).

`index.html` hanya sisa versi hub lama dan tidak tampil ke pengunjung selama `_redirects` aktif.

## Infrastruktur
* **Folder lokal:** `C:\Users\GEEKOM A8\Documents\Apps\alfin-zone-id`
* **Hosting:** Cloudflare Pages (project `alfin-zone`), default `https://alfin-zone.pages.dev`
* **DNS:** [Zone.ID](https://my.zone.id), CNAME `@` -> `alfin-zone.pages.dev`

## Ubah tujuan pengalihan
1. Edit `_redirects`.
2. `npx wrangler pages deploy . --project-name alfin-zone`
3. Cek: `curl -sI https://alfin.zone.id/` harus `301` dengan `location` yang baru.
