# alfin.zone.id — Personal Ecosystem Hub

Website personal hub dan portfolio cepat untuk domain **https://alfin.zone.id**.

## 📍 Lokasi & Infrastruktur
* **Folder Lokal:** `C:\Users\GEEKOM A8\Documents\Apps\alfin-zone-id`
* **Hosting:** Cloudflare Pages (Project: `alfin-zone`)
* **Default URL:** [https://alfin-zone.pages.dev](https://alfin-zone.pages.dev)
* **Custom Domain:** [https://alfin.zone.id](https://alfin.zone.id)
* **DNS Provider:** [Zone.ID](https://my.zone.id) (Record CNAME `@` -> `alfin-zone.pages.dev`)
* **SSL:** Google Trust Services via Cloudflare Edge (Auto-renew)

## 🛠 Cara Edit & Deploy Ulang
1. Edit file `index.html` langsung di folder ini untuk mengubah teks, link, atau menambahkan kartu baru.
2. Buka terminal di folder ini dan jalankan:
   ```bash
   npm run deploy
   ```
   *(Atau `npx wrangler pages deploy . --project-name alfin-zone`)*
3. Perubahan akan langsung live dalam beberapa detik di `alfin.zone.id` dan `alfin-zone.pages.dev`.

## 💻 Testing Lokal (Preview)
```bash
npm run dev
```
Buka `http://localhost:8788` di browser.
