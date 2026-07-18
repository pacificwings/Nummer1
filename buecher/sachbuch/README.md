# Sachbuch-Projekt

## Projektdaten

- **Arbeitstitel:** _(noch offen)_
- **Thema:** _(noch offen)_
- **Zielgruppe:** _(noch offen)_
- **Zielumfang:** _(noch offen, z.B. Anzahl Kapitel/Wörter)_

## Struktur

```
buecher/sachbuch/
├── README.md         diese Datei — Projektsteckbrief
├── recherche/        Recherche-Dossiers pro Kapitel (Fakten, Quellen, offene Fragen)
└── manuskript/        die eigentlichen Kapiteltexte
```

## Workflow

1. **Recherche** — `sachbuch-rechercheur` sammelt und prüft Fakten/Quellen zu einem Kapitel, Ergebnis landet in `recherche/<kapitel-slug>.md`.
2. **Schreiben** — `sachbuch-schreiber` verfasst das Kapitel in `manuskript/` auf Basis des Dossiers.
3. **Lektorat** — `sachbuch-lektor` prüft das fertige Kapitel auf Stil, Struktur und Beleglücken.

## Kapitelübersicht

| Nr. | Titel | Status |
|-----|-------|--------|
| 01  | _(offen)_ | geplant |

Status-Werte: geplant → recherchiert → Entwurf → lektoriert → final
