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
├── recherche/
│   ├── quellen.md    Zentrale, manuell gepflegte Quellensammlung (Grundlagen)
│   └── ...           Recherche-Dossiers pro Kapitel (Fakten, offene Fragen)
└── manuskript/        die eigentlichen Kapiteltexte
```

## Workflow

1. **Recherche** — `sachbuch-rechercheur` sammelt und prüft Fakten/Quellen zu einem Kapitel, Ergebnis landet in `recherche/<kapitel-slug>.md`.
2. **Schreiben** — `sachbuch-schreiber` verfasst das Kapitel in `manuskript/` auf Basis des Dossiers.
3. **Schriftsteller (Stil)** — `sachbuch-schriftsteller` bringt den Text in den für dieses Sachbuch geltenden Schreibstil (eigener Skill, falls vorhanden, sonst Vorgaben aus dieser README).
4. **Lektorat** — `sachbuch-lektor` prüft das fertige Kapitel auf Stil, Struktur und Beleglücken.

## Kapitelübersicht

| Nr. | Titel | Status |
|-----|-------|--------|
| 01  | _(offen)_ | geplant |

Status-Werte: geplant → recherchiert → Entwurf → lektoriert → final
