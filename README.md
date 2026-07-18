# Nummer1

Buch-Projekte mit spezialisierten Claude-Code-Agenten für Recherche, Schreiben und Lektorat.

## Projekte

- [`buecher/sachbuch/`](buecher/sachbuch/README.md) — Sachbuch
- [`buecher/roman/`](buecher/roman/README.md) — Roman

## Agenten

Für jedes Buch gibt es vier Subagenten (definiert in `.claude/agents/`), die nacheinander im Workflow **Recherche → Schreiben → Schriftsteller (Stil) → Lektorat** eingesetzt werden:

| Buch     | Recherche              | Schreiben            | Schriftsteller (Stil)      | Lektorat            |
|----------|-------------------------|----------------------|-----------------------------|----------------------|
| Sachbuch | `sachbuch-rechercheur`  | `sachbuch-schreiber` | `sachbuch-schriftsteller`   | `sachbuch-lektor`    |
| Roman    | `roman-rechercheur`     | `roman-schreiber`    | `roman-schriftsteller`      | `roman-lektor`       |

Der Schriftsteller-Agent bringt einen Text in den für das jeweilige Projekt geltenden Schreibstil (beim Roman verbindlich definiert im Skill `roman-mcallan`) — er ändert keine Fakten/Handlung, nur Sprache und Form.

Aufruf z.B. in Claude Code: *"Nutze den Agenten sachbuch-rechercheur, um Kapitel 1 zu recherchieren"* oder direkt über das Agent-Tool mit dem jeweiligen `subagent_type`.

Jedes Buch hat sein eigenes `recherche/`-Verzeichnis (Fakten-Dossiers bzw. Figuren/Welt/Zeitleiste) und `manuskript/`-Verzeichnis (Kapiteltexte). Details siehe die jeweilige README im Projektordner.