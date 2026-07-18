# Roman-Projekt

## Projektdaten

- **Reihentitel/Autor:** H.S. "Daily" McAllan
- **Buch 1:** "Das Geheimnis der »Dobson Neun«"
- **Buch 2:** "Dobneun Son – Die Helfenden Hände"
- **Genre:** Politthriller/Spionage-Roman, angelehnt an reale Ereignisse (u.a. MH370, MH17) mit historischer Rückblende (Korea, 650 AD)
- **Perspektive/Erzählform:** siehe Analysenotizen in `recherche/quellenmaterial/gesamtdokument_20261224.md` (TEIL A) — Empfehlung dort: Ich-Erzähler McAllan mit auktorialem Rückblick. **Das ist eine Analyse-Empfehlung, kein feststehender Kanon** — im Manuskripttext selbst (TEIL B/C) wird bisher wechselnd auktorial/personal erzählt, McAllan tritt aber ab der Rahmenhandlung 2018 (`kap3_korrigiert_20260707.md`) bereits als handelnde Figur auf.
- **Zielumfang:** _(noch offen)_

Bestehendes Quellenmaterial (vorhandene Manuskript-Entwürfe) ist bereits eingepflegt, siehe `recherche/quellen.md` und `recherche/quellenmaterial/`. Figuren-, Welt- und Zeitleisten-Dateien sind daraus vom `roman-rechercheur` befüllt (Stand: fortlaufende Durchsicht aller Quelldateien, zuletzt Quellen #1–#9).

**Ordnungsprinzip für dieses Projekt:** Handlungsstränge/Themenzusammenhänge werden durchgehend als Ordnungskriterium verwendet — nicht die im Rohmaterial vergebene Kapitelnummerierung ("Kapitel N"). Die Kapitelnummern im Quellenmaterial sind zwischen den Fassungen uneinheitlich (z.B. wird die Bezeichnung "Kapitel 3" im Rohmaterial für zwei inhaltlich komplett unterschiedliche Szenen verwendet, siehe `recherche/zeitleiste.md`) und eignen sich daher nicht als verlässliches Ordnungskriterium. Das gilt für `figuren.md`, `welt.md`, `zeitleiste.md` und die Kapitelübersicht unten gleichermaßen.

**Namensstand historische Ebene:** Die vier Kaufleute der 650-AD-Handlung heißen laut Nutzer-Entscheidung **Bae** (Reeder), **Jil** (Tonwarenhändler), **Dol** (Mineralienhändler) und **Gaun** (Zwischenhändler, königstreu — Gründer der Gegengesellschaft). Frühere Namensversionen (Hyeop, Mok, Baek, konzeptionell "Kim") sind damit verworfen — Details und Begründung der Zuordnung in `recherche/figuren.md`.

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
- `zeitleiste.md` — chronologischer Ablauf über beide Bücher, gegliedert nach Handlungssträngen, inkl. bekannter Logikfehler/Datumsprobleme aus der Ghostwriter-Analyse

## Workflow

1. **Recherche/Konsistenz** — `roman-rechercheur` pflegt Figuren/Welt/Zeitleiste und prüft neue Kapitel auf Widersprüche.
2. **Schreiben** — `roman-schreiber` verfasst Kapitel/Szenen in `manuskript/` passend zum bestehenden Kanon.
3. **Lektorat** — `roman-lektor` prüft das fertige Kapitel auf Stil, Spannungsbogen und Konsistenz.

## Kapitelübersicht (nach Handlungssträngen)

Diese Übersicht spiegelt den **vorgefundenen Manuskript-Stand**
(Rohmaterial) wieder, gruppiert nach thematischem Handlungsstrang statt
nach der (uneinheitlichen) Kapitelnummerierung im Quellenmaterial — siehe
`recherche/zeitleiste.md` für die vollständige, zeilengenaue Zuordnung.
Status ist grundsätzlich "vorhandener Entwurf" statt "geplant", solange
noch kein neu geschriebenes/lektoriertes Kapitel dieses Projekts
vorliegt. Die Strang-ID (S01, S02, …) ist eine neutrale, projektinterne
Kennung und kollidiert bewusst nicht mit Kapitelnummern aus dem
Originalmanuskript.

| Strang-ID | Handlungsstrang | Inhalt/Zeitraum | Quelle | Status |
|-----------|------------------|------------------|--------|--------|
| S01 | Historische Ebene (Baekje 650 AD) | Kaufleute **Bae, Jil, Dol** (Reeder/Tonwarenhändler/Mineralienhändler) — Ursprung des Konflikts; vierter Kaufmann **Gaun** (Verfolger, Gründer der Gegengesellschaft) bisher nur Konzeptfigur | gesamtdokument TEIL B / Band 1 (Manuskripttext verwendet technisch noch die alten Namen Hyeop/Mok/Baek, siehe `figuren.md`) | Entwurf (nur Einstiegsszene ausgeschrieben; vollständiger Handlungsbogen inzwischen als Konzept ausgearbeitet, Quelle #7) |
| S02 | Nordkorea/Geheimdienst-Strang | New York (Moon's JAM, 2011–2013), Projekt Mujigage (Planung, Okt.–Nov. 2013), Falkennest/Gutseoda/Haedongcheong | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S03 | Dobneun-Son/Helfende-Hände-Strang (Zentrale) | "Weinender Berg"-HQ Korea, Decknamen-System, Finanzierungsprogramm, UMACO-Konzept (Westsahara) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S04 | Russland/BUK-Strang | Moskau-Planung, Tonghae-Testgelände | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S05 | Australien-Strang | Brisbane/Glashouse Mountains (Jan. 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S06 | MH370-Operation | Sepang-Vorbereitung bis Bergung/Rückkehr (Feb.–März 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S07 | Niederlande/AIVD-Strang | Assen/Den Haag/Zwolle/Groningen — Anique Smits, Thomas Ganghofer, Joost van der Dijkstraat | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S08 | MH17-Operation | Amsterdam/Den Haag-Vorbereitung, Donbass-Abschuss (Juli 2014) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S09 | Rahmenhandlung 2018 (Hamburg) | Ottensen — Corinna Brandenburg erhält Joosts Akten (16. Jan. 2018) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S10 | Malaysia/Special-Branch-Strang | Royal Belum National Park (Feb. 2015) — Bibi Kaur, Satria Chow | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S11 | Libyen/Westsahara-Strang | Dr. Benjamin Dingakas Expedition, Bodenproben (März–Mai 2015) | gesamtdokument TEIL B | Entwurf (Rohmaterial) |
| S12 | Rahmenhandlung 2018 (Dubai/Wüste) | Corinna trifft McAllan, Wüsten-Hinterhalt (Okt. 2018) | `kap3_korrigiert_20260707.md` | Korrigierter Entwurf |
| S13 | Buch-2-London-Strang | Vereitelter Anschlag auf Dr. Dingakas Labor (Juni 2015, vollständig ausgeschrieben) | gesamtdokument TEIL C | Entwurf (Rohmaterial) |
| S14 | Buch-2-Platzhalter-Stränge | "Spurensuche, Korea" / "Feinde" / "Afrika, UMACO" (Bedeutung geklärt, siehe unten) / "Recherche, Geld" | gesamtdokument TEIL C | nur Platzhalter |

**Hinweis zu S02/S12:** Beide Textstellen waren im Rohmaterial zufällig
mit "Kapitel 3" überschrieben, behandeln aber völlig unterschiedliche
Themen (nordkoreanische Planung vs. Rahmenhandlung Dubai). Da die
Kapitelnummerierung des Originalmanuskripts hier nicht als
Ordnungskriterium verwendet wird, ist das kein Konflikt, sondern zwei
getrennte Handlungsstränge — siehe Details in `recherche/zeitleiste.md`.

**✅ UMACO/"UnMaCo" geklärt:** Das lange als "ungeklärt" markierte
Buch-2-Platzhalterkapitel "Afrika, UnMaCo" (S14) steht für **"United
Mankind Consultancy Organisation"** — laut Konzeptnotizen (Quelle #8)
ein von den Helfenden Händen selbst initiiertes, UNO-alternatives
Gremium mit Sitz in der Westsahara, ihr erster öffentlicher Auftritt in
1.400 Jahren. Details in `recherche/welt.md`. Die acht zugehörigen
Buch-2-Szenen selbst sind weiterhin nur Platzhalter ohne ausgeschriebenen
Text.

Status-Werte für neu zu schreibende/lektorierte Kapitel dieses Projekts
bleiben: geplant → Entwurf → lektoriert → final. Die obige Tabelle
beschreibt den Stand des vorgefundenen Rohmaterials, nicht den
Bearbeitungsstand dieses Repos.
