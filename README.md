# Nummer1

Roman-Projekt "Dobneun Son" mit spezialisierten Claude-Code-Agenten für Recherche, Schreiben, Stil und Lektorat.

> Dieses Repo ist ausschließlich dem Roman-Projekt gewidmet. Ein früher hier angelegtes Sachbuch-Projekt (ESG-Thema) wurde entfernt — es wird nicht in Nummer1 geführt.

## Projekt

- [`buecher/roman/`](buecher/roman/README.md) — Roman "Dobneun Son"

## Agenten

Vier Subagenten (definiert in `.claude/agents/`), die nacheinander im Workflow **Recherche → Schreiben → Schriftsteller (Stil) → Lektorat** eingesetzt werden:

| Recherche           | Schreiben         | Schriftsteller (Stil)  | Lektorat        |
|----------------------|-------------------|--------------------------|------------------|
| `roman-rechercheur`  | `roman-schreiber` | `roman-schriftsteller`   | `roman-lektor`   |

Der Schriftsteller-Agent bringt einen Text in den für das Projekt verbindlichen Schreibstil (definiert im Skill `roman-mcallan`) — er ändert keine Fakten/Handlung, nur Sprache und Form.

Aufruf z.B. in Claude Code: *"Nutze den Agenten roman-rechercheur, um X zu recherchieren"* oder direkt über das Agent-Tool mit dem jeweiligen `subagent_type`.

`buecher/roman/recherche/` enthält Figuren/Welt/Zeitleiste sowie das importierte Quellenmaterial; `buecher/roman/manuskript/` die eigentlichen Kapiteltexte. Details siehe die README im Projektordner.
