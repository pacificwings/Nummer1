# Roman-Projekt

## Projektdaten

- **Reihentitel/Autor:** H.S. "Daily" McAllan
- **Buch 1:** "Das Geheimnis der »Dobson Neun«"
- **Buch 2:** "Dobneun Son – Die Helfenden Hände"
- **Genre:** Politthriller/Spionage-Roman, angelehnt an reale Ereignisse (u.a. MH370, MH17) mit historischer Rückblende (Korea, 650 AD)
- **Perspektive/Erzählform:** siehe Analysenotizen in `recherche/quellenmaterial/gesamtdokument_20261224.md` (TEIL A) — Empfehlung dort: Ich-Erzähler McAllan mit auktorialem Rückblick. **Das ist eine Analyse-Empfehlung, kein feststehender Kanon** — im Manuskripttext selbst (TEIL B/C) wird bisher wechselnd auktorial/personal erzählt, McAllan tritt aber ab der Rahmenhandlung 2018 (`kap3_korrigiert_20260707.md`) bereits als handelnde Figur auf.
- **Zielumfang:** _(noch offen)_

Bestehendes Quellenmaterial (vorhandene Manuskript-Entwürfe) ist bereits eingepflegt, siehe `recherche/quellen.md` und `recherche/quellenmaterial/`. Figuren-, Welt- und Zeitleisten-Dateien sind daraus vom `roman-rechercheur` befüllt (Stand: erste vollständige Durchsicht aller drei Quelldateien).

## Struktur

```
buecher/roman/
├── README.md          diese Datei — Projektsteckbrief
├── recherche/         Figuren-Bibel, Welt, Zeitleiste, Weltenbau-Recherche
└── manuskript/         die eigentlichen Kapitel/Szenen
```

Wichtige Dateien in `recherche/` (werden vom `roman-rechercheur` gepflegt):
- `quellen.md` — zentrale, manuell gepflegte Quellensammlung (Grundlagen)
- `figuren.md` — Steckbriefe der Hauptfiguren (Rahmenhandlung 2018, Nordkorea-Strang, NL/AIVD-Strang, Malaysia Special Branch, Buch-2-London-Strang, historische Ebene 650 AD, Organisationen)
- `welt.md` — Setting, Zeitebenen, wichtige Orte, Organisationsregeln
- `zeitleiste.md` — chronologischer Ablauf über beide Bücher, inkl. bekannter Logikfehler/Datumsprobleme aus der Ghostwriter-Analyse

## Workflow

1. **Recherche/Konsistenz** — `roman-rechercheur` pflegt Figuren/Welt/Zeitleiste und prüft neue Kapitel auf Widersprüche.
2. **Schreiben** — `roman-schreiber` verfasst Kapitel/Szenen in `manuskript/` passend zum bestehenden Kanon.
3. **Lektorat** — `roman-lektor` prüft das fertige Kapitel auf Stil, Spannungsbogen und Konsistenz.

## Kapitelübersicht

Buch 1 ("Das Geheimnis der »Dobson Neun«") ist im Quellenmaterial
(`gesamtdokument_20261224.md`, TEIL B) tatsächlich in Kapitel mit
Sun-Tzu-Zitat als Motto gegliedert. Diese Tabelle spiegelt den
**vorgefundenen Manuskript-Stand** (Rohmaterial), nicht bereits final
lektorierte/neu geschriebene Kapitel dieses Projekts — Status ist daher
grundsätzlich "vorhandener Entwurf" statt "geplant". Details und
Fundstellen: siehe `recherche/zeitleiste.md`.

| Nr. | Titel/Inhalt | Quelle | Status |
|-----|-------|--------|--------|
| 01  | New York 2011 – April 2013 ("Teil 1: Eruptionen", kein Kapitel-Header) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 02  | Dobneun-Son-Zentrale ("weinender Berg"), New-York-Nachbereitung | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 03  | Projekt Mujigage: Pyeongyang/Falkennest/Sinpo-Werft (Okt.–Nov. 2013) — **⚠️ Konflikt mit `kap3_korrigiert`, siehe unten** | gesamtdokument TEIL B | Entwurf (Rohmaterial), klärungsbedürftig |
| 04  | Brisbane/Glashouse Mountains, Australien (Jan. 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 05  | Sepang Race Circuit, MH370-Vorbereitung (Feb.–März 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 06  | Flughafen Kuala Lumpur, Boarding MH370 (März 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 07  | Cargo-City/weitere MH370-Szenen | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 08  | Raketen-/Artillerie-Hauptverwaltung, Tonghae, Sinpo-Nachbereitung | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 09  | Assen, Niederlande (Anique-Strang, März 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 10  | Isala Klinik Zwolle, weitere NL-Szenen (April 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 11  | Groningen, MH17-Vorbereitung (Juli 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 12  | Ottensen, Hamburg — Rahmenkapitel Corinna Brandenburg (16. Jan. 2018) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 13  | Malaysia, Royal Belum National Park (Feb. 2015) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| 14  | Libyen/Afrika-Strang (März 2015) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| —   | Le Touquet, Westsahara, London Juni 2015 (Buch-1-Ende, unnummeriert) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| —   | "Kapitel 3: Wie alles begann" — Corinna/McAllan, Dubai/Wüste (Okt. 2018) | `kap3_korrigiert_20260707.md` | Korrigierter Entwurf, **Nummerierungskonflikt mit Kapitel 03 oben — Klärung nötig** |
| B2-1 | Buch 2, Kapitel 1 "Spurensuche, Korea" (5 Szenen) | gesamtdokument TEIL C | nur Platzhalter |
| B2-2 | Buch 2, Kapitel 2 "Feinde" (3 Szenen) | gesamtdokument TEIL C | nur Platzhalter |
| B2-3 | Buch 2, Kapitel 3 "Afrika, UnMaCo" (8 Szenen) | gesamtdokument TEIL C | nur Platzhalter |
| B2-4 | Buch 2, Kapitel 4 "Recherche, Geld" (4 Szenen) | gesamtdokument TEIL C | nur Platzhalter |
| B2-0 | Buch 2, London Juni 2015 (vollständig ausgearbeitete Eröffnungsszene) | gesamtdokument TEIL C | Entwurf (Rohmaterial) |

Status-Werte für neu zu schreibende/lektorierte Kapitel dieses Projekts
bleiben: geplant → Entwurf → lektoriert → final. Die obige Tabelle
beschreibt den Stand des vorgefundenen Rohmaterials, nicht den
Bearbeitungsstand dieses Repos.
