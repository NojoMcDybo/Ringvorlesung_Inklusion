# Klausur-Trainer — Ringvorlesung „Inklusion im Sport" (Uni Münster, SoSe 2026)

Interne Lernhilfe. Eine einzige statische Seite — kein Build, kein Server, keine Abhängigkeiten.

## Dateien
- `index.html` — die komplette Seite (HTML/CSS/JS in einer Datei)
- `hippo_*.webp`, `roll*.webp`, `hippo_cloud.webp`, `hoehle.png` — Sprites & Hintergrund des Maskottchens

Alle Dateien müssen im **selben Ordner** liegen — die Seite lädt die Assets über relative Pfade.

## Als GitHub Pages veröffentlichen
1. Den **Inhalt** dieses Ordners in den Repo-Root laden (oder nach `/docs`).
2. Repo → Settings → Pages → Branch `main`, Ordner `/ (root)` bzw. `/docs` → Save.
3. Nach ~1 Min erreichbar unter `https://<user>.github.io/<repo>/`.

## Wichtig — Sichtbarkeit
Die Seite ist eine **geschlossene Lernfassung** (`noindex`, „nicht zur öffentlichen Verbreitung").
`noindex` + kryptische URL ist **kein** echter Zugriffsschutz — wer die URL hat, kommt rein.
Bei geschützten/nicht paraphrasierten Inhalten: **privates Repo** oder Passwortschutz statt öffentlicher Pages.
