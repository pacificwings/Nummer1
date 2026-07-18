---
name: roman-schreibstil-eng
description: >
  Activate this skill for any task involving the English translation of the Dobneun Son
  manuscript's prose style: translating chapters, style-checking translated text, dialogue.
  English-calibrated counterpart to roman-schreibstil.
---

# English Style Skill: "Dobneun Son – The Helping Hands" (English pipeline)

This is the English-calibrated counterpart to `roman-schreibstil` (the German style skill for
this project, derived independently from the source prose in
`buecher/roman/recherche/quellenmaterial/`). It is **not a literal translation of the German
rules** — it defines what the same stylistic effects should look like in natural English prose,
for use by `roman-uebersetzer`, `roman-lektor-eng`, `roman-korrektor-eng`, and
`roman-schriftsteller-eng`.

---

## 1. Sentence structure

The German source favors medium-to-long, information-dense sentences that fold background facts
directly into the narrative (geography, history, technology) rather than breaking them into short
fragments. **Do not translate this as staccato English.** Instead:

- Keep sentences full and grammatically complete; one main idea per sentence, with subordinate
  clauses carrying supporting detail (dates, distances, technical facts).
- English naturally runs shorter than German on average — when a German sentence with three
  nested clauses becomes unwieldy in English, split it into two clean English sentences rather
  than one long comma-spliced one. The goal is the *same density of information*, not the same
  sentence count.
- Reserve short, clipped sentences for radio/command exchanges and high-tension action beats —
  never as a general narrative rhythm.

**Example (style target, not a literal translation):**
> The Royal Netherlands Marechaussee is a gendarmerie force with broad domestic and international
> duties. Since 1998 it has operated as an independent branch of the armed forces, alongside the
> army, navy, and air force.

**Avoid:** chopping this into "Marechaussee. Dutch gendarmerie. Independent since 1998." — that
staccato rhythm does not exist in the source style.

---

## 2. Dialogue

Two clearly distinct registers, matching the German source:

**a) Extended, conversational dialogue** (framing story, investigations, political/intelligence
scenes): natural back-and-forth, tangents, deflection, teasing, characters circling the real topic
before addressing it directly. In English this should read like real adult conversation —
contractions, interruptions, understatement — not stilted or over-explained.

**b) Clipped operational/radio dialogue** (military, Special Branch, field operations): terse,
codified, no pleasantries, call signs and short imperatives.

> "K1 to K2. Satria. Suggestions?" [...] "Fire," Satria ordered, and within seconds all four
> attackers were down. "All clear," she said into the comms.

**Character voice in English (equivalents, not translations):**
- **McAllan:** dry, understated British wit — raised-eyebrow irony rendered through word choice
  and rhythm ("Did you, now.") rather than exclamation or explanation. Use classic English
  understatement patterns (litotes, deadpan tags) instead of literal renderings of German irony
  markers.
- **Corinna:** blunt, quick, occasionally sharper than intended — short, declarative questions
  that push the scene forward.
- **Bibi/Satria in the field:** clipped, rank-and-code-driven, no hedging; off-duty, playful and
  needling among colleagues.
- **Anique/Thomas in private:** warm, teasing, a little flustered — English equivalent should lean
  into gentle banter and self-deprecating humor rather than direct translation of German
  endearments.
- **North Korean officials:** formal, hierarchy-aware, minimal irony, clear chain-of-command
  phrasing — avoid making this sound stiffly "foreign"; it should read as natural formal register
  in English, not broken English.
- **Tech/hacker characters (Duke Cloud, Flim):** casual, jargon-heavy, short status updates.

**Punctuation:** Use standard English double quotation marks for dialogue (not German „…").
Render internal monologue with quotation marks or unmarked free indirect style as appropriate to
English convention — no italics needed to signal it (see §7).

---

## 3. Narratorial stance

Largely omniscient-but-restrained, following one character's viewpoint per scene without
explanation of the switch (a new scene marker signals a new vantage point). The narrator stays
mostly factual, but — matching the actual source material, not an idealized "fully neutral"
narrator — **occasionally allows a light editorializing adverb**:

> "Curiously, no one knew that this unit did not belong to the regular forces..."
> "Unfortunately, there was no decent café nearby..."
> "As expected, the residents were afraid..."

**Rule:** such words ("unfortunately," "curiously," "as expected," "fortunately") are permitted
sparingly (at most one or two per scene) as a light authorial touch — never as a substitute for a
full editorializing sentence, and never paired with an exclamation point.

---

## 4. Humor

Situational and dialogue-driven, never through narratorial comment. It typically lands
**immediately after a tense or dangerous moment** as a tonal release — a deliberate shift, not an
undercutting of the tension:

> Right after a shootout that leaves three men dead: "Where were we? Right. Background. Shall we
> sit?"

**Rule:** the joke comes after the information, not before. No exclamation points to signal humor,
no narratorial explanation of the joke.

---

## 5. Pacing and tension

Alternates deliberately between extended background/world-building passages and very short, dense
action sequences (radio traffic, gunfire, second-by-second timing). In English, preserve this
alternation rather than smoothing it into a uniform pace. Maintain:
- Precise timestamps in action scenes (exact minutes: "08:15," "01:18 a.m.").
- Cliffhangers at scene ends ("What had happened in the meantime?").
- Cross-cutting between simultaneous plot threads (e.g., the MH370 night intercut with a Moscow
  scene).

---

## 6. Scene breaks and time jumps

Keep the source format for scene headers: `>>> Location, Date <<<` (with time of day where the
source specifies one, e.g., `>>> Saturday, 8 March 2014, 00:45–01:15: MH370 Cargo Hold <<<`).
Within the same location/thread, use `***` for a smaller time jump. Do not translate location
names unless there is an established English convention (e.g., keep "Den Haag" as "The Hague" only
if the project's canon already does so — check `recherche/welt.md` first).

**Rule:** every change of location or point-of-view gets its own `>>> ... <<<` marker — never a
silent shift mid-paragraph. Dates should be as complete as in the source (weekday + date + time
where available); do not invent precision the German original lacks, and do not drop precision
the original has.

---

## 7. Flashbacks and POV breaks

Historical/flashback material (e.g., the 650 AD Korea thread) is treated as a normal scene with
its own `>>> ... <<<` marker in the source — **not** set in italics or otherwise typographically
marked (confirmed by checking the actual converted source files; no italics markup for flashbacks
or internal monologue was found there). Follow the same convention in English: use the scene
marker and a short framing sentence (especially where `welt.md` flags a transition as still
"concept only, not yet written") rather than introducing italics as a new device not present in
the source.

---

## 8. Language and register

- Standard, slightly formal contemporary English; no slang-heavy modernization, no purple prose.
- Technical/military jargon (call signs, weapons/aircraft systems, intelligence terminology) is
  used but briefly glossed on first use, matching the source's approach.
- Keep the source's precision with numbers, times, and distances (convert units sensibly for an
  English-reading audience only where the project explicitly calls for it — otherwise preserve the
  original units, e.g. km, as the source does, per `recherche/welt.md`).
- Character and place names: use exactly the current canon spellings from
  `recherche/figuren.md`/`recherche/welt.md` (e.g., "Satria," not "Tia"; "Bae/Jil/Dol/Gaun" for the
  four merchants, not the superseded "Hyeop/Mok/Baek/Kim") — do not silently anglicize or respell
  names.

---

## 9. Known source weaknesses to correct in translation, not reproduce

1. **Inconsistent capitalization of "Sie"/"sie" in German** (formal address vs. third-person
   pronoun) does not carry over to English and needs no special handling — but translators should
   double-check pronoun antecedents in ambiguous German sentences before rendering them, since the
   German error sometimes obscures who "she" refers to.
2. **Verbatim-repeated paragraphs** across chapter/book boundaries in the source (e.g., the Ajwad
   Boussafa death paragraph appears almost identically at the end of Book 1 and the start of Book
   2) — translate once, reuse the same English wording only if the repetition is intentional per
   `recherche/zeitleiste.md`; flag to `roman-lektor-eng` if unsure.
3. **Name-spelling inconsistencies** in the source (Boussafa/Boufassar, Tia/Satria) — always
   resolve to the single current-canon spelling per `recherche/figuren.md`, never carry both
   spellings into English.
4. **Missing dates on some scene markers** in the source — do not silently invent a date in
   translation; carry the ambiguity over and flag it, per the known logic issues in
   `recherche/zeitleiste.md`.
5. **Dialogue-as-info-dump**, where characters explain facts to each other that both would already
   know, purely for the reader's benefit — where natural, prefer moving such information into
   narration in the English version (see §1), but do not silently cut plot-relevant content;
   flag substantial restructuring to `roman-lektor-eng`.

---

## 10. Forbidden

- Staccato sentence chains outside radio/command dialogue.
- Narratorial commentary carrying strong emotional judgment ("How awful!", "Thank goodness!") —
  light adverbs (§3) are fine, full editorializing sentences are not.
- Signaling humor with exclamation points or narratorial explanation ("which was, of course, a
  joke").
- A POV switch or time jump without a `>>> ... <<<` marker.
- Anglicizing or renaming established character/place names without checking
  `recherche/figuren.md`/`recherche/welt.md` first.
- Reproducing the German "Sie"/"sie" capitalization confusion as an English pronoun error.
- Vague, invented time references ("sometime that spring") on new scene markers where the source
  convention is precise dating.
- Duplicating whole paragraphs verbatim between chapters unless the repetition is confirmed
  intentional.

---

## 11. Quick-reference checklist

| Question | Standard |
|---|---|
| Is the sentence complete and information-dense but grammatically clean in English? | Yes — brevity reserved for radio/commands |
| Does the dialogue register match the scene (conversational vs. radio code)? | Yes |
| Does each character keep their recognizable English voice (see §2)? | Yes |
| Does humor land after the factual beat, not before? | Always |
| Does the narrator stay mostly factual, with at most a light editorial adverb here and there? | Yes |
| Is every location/POV change marked with `>>> Location, Date <<<` (date as complete as source)? | Yes |
| Are numbers/times/distances kept precise? | Yes |
| Do names match current canon in `recherche/figuren.md` exactly? | Yes |
| Is no whole paragraph silently duplicated from another chapter? | Yes |
| Are known source ambiguities (missing dates, name variants) flagged rather than silently resolved? | Yes |

---

## Relationship to `roman-schreibstil` (German) and the global skill `roman-mcallan`

This skill translates the *effects* identified in `roman-schreibstil` into English-appropriate
technique — it does not translate the German wording of the rules. Where `roman-schreibstil`
notes a divergence from the global German skill `roman-mcallan` (narrator restraint, italics for
flashbacks, the "Tia"/"Satria" naming question), the same divergence applies here in the English
pipeline: this skill treats the narrator as mostly-but-not-fully neutral, uses scene markers rather
than italics for flashbacks, and uses "Satria" as the current canon name.
