# Matematikavilágosán — statikus weboldal

Ez a repo a Matematikavilágosán statikus weboldalának alapverziója (HTML + CSS). A fájlokat helykitöltő tartalommal hoztam létre — cserélheted a szövegeket és a képeket a Google Sites-on lévő tartalomra.

Fájlok:
- index.html — Főoldal
- css/styles.css — Globális stílusok
- pages/ — Több oldal: tananyag, letöltések, kapcsolat
- pages/files/ — ide teheted a PDF-eket
- netlify.toml — Netlify konfiguráció

Deploy Netlify-re (ajánlott GitHub + Netlify):
1. Git init / add / commit, push a GitHub repo-dba.
2. Netlify web UI: New site → Import from Git → válaszd a repository-t → publish directory: "." → Deploy site.
3. Vagy Netlify CLI: `netlify deploy --prod --dir=.`
4. Ha szeretnéd, beállítok Netlify Forms űrlapot a kapcsolat oldalon és/vagy összekötöm a repo-dal (ha adsz hozzáférést).

További teendők:
- Cseréld ki a `images/hero-placeholder.jpg` fájlt a valós képedre.
- Töltsd fel a PDF-eket a `pages/files/` mappába.
- Küldd el a pontos Google Sites tartalmat (szöveg + képek), és beillesztem a végleges változatba.
