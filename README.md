# Nummer1

Roman-Projekt "Dobneun Son" mit spezialisierten Claude-Code-Agenten für Recherche, Schreiben, Stil und Lektorat.

> Dieses Repo ist ausschließlich dem Roman-Projekt gewidmet. Ein früher hier angelegtes Sachbuch-Projekt (ESG-Thema) wurde entfernt — es wird nicht in Nummer1 geführt.

## Projekt

- [`buecher/roman/`](buecher/roman/README.md) — Roman "Dobneun Son"

## Agenten

Neun Subagenten (definiert in `.claude/agents/`), aufgeteilt in eine deutsche und eine englische Pipeline — siehe `buecher/roman/README.md` für den vollständigen Workflow:

| Phase | Deutsch | Englisch |
|-------|---------|----------|
| Recherche/Konsistenz | `roman-rechercheur` | _(gemeinsam genutzt, keine Übersetzung nötig)_ |
| Verfassen / Übersetzen | `roman-schriftsteller` (Inhalt + Stil) | `roman-uebersetzer` |
| Logik-Lektorat | `roman-lektor` | `roman-lektor-eng` |
| Grammatik/Orthografie | `roman-korrektor` | `roman-korrektor-eng` |
| Stil-/Textfluss-Rückprüfung | `roman-schriftsteller` (2. Durchlauf) | `roman-schriftsteller-eng` |

Lektorat und Korrektur sind bewusst getrennt: `roman-lektor`/`roman-lektor-eng` prüfen nur Handlungslogik und listen Rückfragen (ändern den Text nicht selbst); `roman-korrektor`/`roman-korrektor-eng` korrigieren Rechtschreibung automatisch und fragen nur bei zweifelhaften Grammatik-Korrekturen nach. Die Schriftsteller-Agenten nutzen dafür die projekteigenen Skills `roman-schreibstil` (Deutsch) bzw. `roman-schreibstil-eng` (Englisch) — sie ändern keine Fakten/Handlung, nur Sprache und Form.

Aufruf z.B. in Claude Code: *"Nutze den Agenten roman-rechercheur, um X zu recherchieren"* oder direkt über das Agent-Tool mit dem jeweiligen `subagent_type`.

`buecher/roman/recherche/` enthält Figuren/Welt/Zeitleiste sowie das importierte Quellenmaterial; `buecher/roman/manuskript/` die deutschen Kapiteltexte, `buecher/roman/manuskript/en/` die englischen Übersetzungen. Details siehe die README im Projektordner.
