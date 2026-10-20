# AthDGC Laboratory, Erasmus+ Internships

Public site and application materials for **research internships at the AthDGC Laboratory**, hosted by the Faculty of English Language and Literature at the National and Kapodistrian University of Athens (NKUA, Erasmus code **G ATHINE01**), supervised by Prof. Nikolaos Lavidas.

Live site (after Pages is enabled): **https://athdgc.github.io/athdgclab-erasmus-internship/**

## What's in this repo

| Path | What it is |
|---|---|
| [`index.html`](./index.html) | Single-page site: about the lab, internship overview, how to apply, embedded welcome video, downloads, contact |
| [`documents/AthDGC_Info_Brochure.pdf`](./documents/AthDGC_Info_Brochure.pdf) | 2-page call for applications |
| [`documents/AthDGC_Application_Form.docx`](./documents/AthDGC_Application_Form.docx) | Editable Word application form |
| [`documents/AthDGC_FAQ.pdf`](./documents/AthDGC_FAQ.pdf) | Frequently Asked Questions |
| [`documents/AthDGC_Video_Script.pdf`](./documents/AthDGC_Video_Script.pdf) | Welcome-video script & storyboard (production document) |

The welcome video is hosted externally and embedded via `<iframe>` in `index.html`.

## Hosting

The site is fully static — `index.html` plus a `documents/` folder. To publish, drop the contents anywhere:

- **GitHub Pages** — *Settings → Pages*, set Source to `main` / `/ (root)`, save. The site will be served at `https://athdgc.github.io/athdgclab-erasmus-internship/`.
- **University web space / Netlify / any static host** — upload the folder as-is.

All document links in `index.html` are relative, so the structure must be preserved when uploading.

## Updating the welcome video

To swap in a different video (e.g. a YouTube or Vimeo embed, or a self-hosted `.mp4`), open `index.html` and replace the `<iframe>` inside `<div class="video-wrap">` with your preferred embed code. Keep the wrapper div for responsive sizing.

## How to apply

See the [Information Brochure](./documents/AthDGC_Info_Brochure.pdf) and the on-site "How to Apply" section. Applications are reviewed on a rolling basis; submit at least three months before your intended start date.

## Contact

- **Supervisor:** [Prof. Nikolaos Lavidas](https://en.enl.uoa.gr/staff/tomeas_glossas_glossologias_eng/nikolaos_lavidas_eng/) — Faculty of English Language & Literature, NKUA
- **NKUA Erasmus office:** [en.interel.uoa.gr/erasmus](https://en.interel.uoa.gr/erasmus)
- **Erasmus code:** G ATHINE01

## License

© AthDGC Laboratory. Documents and copy may be adapted for academic use with attribution.
