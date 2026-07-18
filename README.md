# Nummer1

Buch-Projekte mit spezialisierten Claude-Code-Agenten für Recherche, Schreiben und Lektorat.

## Projekte

- [`buecher/sachbuch/`](buecher/sachbuch/README.md) — Sachbuch
- [`buecher/roman/`](buecher/roman/README.md) — Roman

## Agenten

Für jedes Buch gibt es drei Subagenten (definiert in `.claude/agents/`), die nacheinander im Workflow **Recherche → Schreiben → Lektorat** eingesetzt werden:

| Buch     | Recherche              | Schreiben            | Lektorat            |
|----------|-------------------------|----------------------|----------------------|
| Sachbuch | `sachbuch-rechercheur`  | `sachbuch-schreiber` | `sachbuch-lektor`    |
| Roman    | `roman-rechercheur`     | `roman-schreiber`    | `roman-lektor`       |

Aufruf z.B. in Claude Code: *"Nutze den Agenten sachbuch-rechercheur, um Kapitel 1 zu recherchieren"* oder direkt über das Agent-Tool mit dem jeweiligen `subagent_type`.

Jedes Buch hat sein eigenes `recherche/`-Verzeichnis (Fakten-Dossiers bzw. Figuren/Welt/Zeitleiste) und `manuskript/`-Verzeichnis (Kapiteltexte). Details siehe die jeweilige README im Projektordner.