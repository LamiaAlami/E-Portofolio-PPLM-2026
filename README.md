# E-Portofolio PPLM 2026

Static, dependency-free portfolio site for the 2026 PPLM Informatika teaching practicum.

## Preview locally

Open `index.html` in a browser, or run a small local server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Structure

- `DESIGN.md` — editorial visual direction and interaction principles for the portfolio.
- `INVENTAR-EPORTOFOLIO.md` — current requirement inventory, evidence status, and remaining work.
- `index.html` — shared profile and portfolio landing page.
- `portfolio-1.html` — E-Portfolio 1, guided-teaching context and independent-teaching Cycle 1.
- `portfolio-2.html` — E-Portfolio 2, Cycles 2–4.
- `assets/` — shared styles and the small mobile-navigation script.
- `dokumen/modul/` — lesson modules for Meetings 1–9.
- `dokumen/refleksi/` — signed Cycle 1–4 reflection documents (LK4S1–LK4S4).
- `dokumen/instrumen/` — completed and scored Lampiran 7 (lesson-plan design reviews P1–P9) and Lampiran 8 (independent-teaching reviews Cycles 1–4).
- `dokumentasi-terkurasi/` — selected portfolio media, including five rendered MP4 compilations and 24 optimized still photographs grouped by meeting and non-teaching duty. Raw classroom footage and student-identifiable working files remain outside the site.

## Evidence and privacy notes

- Raw classroom footage, named student gradebooks, student roster/identity lists, and individual assessment response exports are intentionally not included.
- A root-level `Dokumentasi/` folder is ignored by Git. Add only selected, permission-checked media to `dokumentasi-terkurasi/`; files there are not displayed by the site until their links are added to the HTML.
- The LK3 reflection is summarized on the site; its source PDF contains a personal student number and blank approval fields, so the original is not published.
- Assessment descriptions distinguish the written rubrics from the flexible progress-monitoring approach used in practice.
- Five rendered video compilations are embedded in the relevant portfolio sections. The Cycle 2 P7 compilation has nine timestamp anchors based on the meeting observation notes. Do not add the raw source clips to this repository.
- Selected still photos are embedded at P2, P3, P4, P7, and P9. The non-teaching section includes the 17 August school activities, Piket Menyapa Pagi, Piket Literasi (18 August 2026), and Piket UKS. No still photo is used for Cycle 4.
- Curated photos are orientation-corrected, resized/compressed, and saved without EXIF metadata; still confirm school/community permissions before public deployment.
- The teaching-philosophy notes in `INVENTAR-EPORTOFOLIO.md` draw on a separate Seminar PPG reflection as context only; Seminar PPG's 4C framework is not a requirement for this PPL Mandiri portfolio.
- Before public deployment, check permissions for any later-added photos, student work, faces, names, or account links.

## Publish with GitHub Pages

Create a separate repository for this project, upload the contents of this folder to its root, then enable GitHub Pages from the repository's Pages settings using the `main` branch and `/ (root)` directory. Do not add the original evidence folder or raw video collection to the repository.

## Updating the site

Edit the HTML directly. Keep file links relative so the site works both from a local folder and from a GitHub Pages project site. No build step or external package is required.
