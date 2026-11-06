# Handbuch Digital Humanities im deutschsprachigen Raum

Projektseite und Dokumentation zum geplanten transdisziplinären DH-Handbuch. Die GitHub Pages-Site unter diesem Repository dient als öffentliche Informationsseite zum Projekt.

## Über das Handbuch

Das Handbuch Digital Humanities im deutschsprachigen Raum ist ein kollaboratives Referenzwerk für Forschende, Lehrende und Studierende der Geistes- und Kulturwissenschaften im DACH-Raum. Es verbindet:

- **Kapitel zu zentralen Praktiken** mit begleitenden Jupyter-Notebooks (Teil II)
- **20 disziplinäre Perspektiven** als kompakte Anwendungskapitel (Teil III)
- **Positionalitätserklärungen** aller Beitragenden als verbindendes Element
- **Deutschsprachigen Fokus** mit Bezug zu internationalen Debatten

## Struktur dieses Repositories

```
public/
├── index.md              # Startseite (Projektübersicht)
├── struktur.md           # Buchstruktur (Teil I–III)
├── handbuecher.md        # Übersicht gesichteter DH-Handbücher
├── arbeitsstand.md       # Aktueller Arbeitsstand & offene Punkte
├── beitragen.md          # Hinweise für Beitragende / Kontakt
├── _config.yml           # Jekyll-Konfiguration
├── .github/workflows/
│   └── pages.yml         # Build & Deploy nach GitHub Pages
├── _layouts/
│   └── default.html      # Seitenlayout
└── assets/
    ├── css/main.css       # Stylesheet
    └── images/            # Logos und Grafiken
```

## Deployment (GitHub Pages)

Die Site wird bei jedem Push auf `main` durch den Workflow `.github/workflows/pages.yml`
mit Jekyll gebaut und nach GitHub Pages deployt. Voraussetzung in den Repo-Einstellungen:
**Settings → Pages → Build and deployment → Source: „GitHub Actions“**.

Damit die Site unter der Wurzel **https://dh-handbuch.github.io/** erreichbar ist, muss das
Repository `dh-handbuch.github.io` heissen (GitHub-Konvention für Organisations-Sites).
Unter dem Namen `public` wird sie stattdessen unter https://dh-handbuch.github.io/public/
ausgeliefert; `url`/`baseurl` werden beim Build automatisch gesetzt, beide Varianten funktionieren.

Lokal bauen:

```bash
gem install jekyll
jekyll serve
```

## Herausgeber:innen

- **Evelyn Gius** (TU Darmstadt)
- **Aline Deicke** (Universität Marburg, Akademie der Wissenschaften und der Literatur Mainz)
- **Michael Schonhardt** (TU Darmstadt, Akademie der Wissenschaften und der Literatur Mainz)
- **Sarah-Mai Dang** (Universität Zürich)
- **Tobias Hodel** (Universität Bern)

## Konzeptuelle Arbeit

Dieses Repo ist work-in-progress und repräsentiert weder die abschliessende Meinung der Herausgeber:innen noch des Verlags. Aktuell (2026 bis März 2027) wird aktiv nach Ideen und Strukturen gesucht.

## Verbundene Projekte und Publikationen

Aktuell keine. Kooperationsvorschläge können gerne gemacht werden.

## Lizenz

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) (siehe Seite „Mitwirken“)

## Kontakt

Tobias Hodel, Universität Bern — [tobias.hodel@unibe.ch](mailto:tobias.hodel@unibe.ch)
