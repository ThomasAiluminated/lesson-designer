# Lesson Designer

**Een Claude-skill die lessen ontwerpt die vertrekken van het leerdoel en eindigen met een check of het geleerd is.**

Je geeft het onderwerp, de klas en de lestijd, en je krijgt een lesverloop met realistische timing: een activerende start, expliciete instructie met een uitgewerkt voorbeeld, begeleide en zelfstandige oefening, differentiatie en een exit-check.

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

*English summary: a Claude skill that designs single lessons or short lesson series aligned from learning objective to activities to a check for understanding, with worked examples, differentiation and realistic timing. It works in Dutch, French and English.*

## Wat de skill doet

- **Ontwerpt terug vanuit het leerdoel.** Een vaag doel ("fotosynthese begrijpen") wordt een observeerbaar doel met een succescriterium dat leerlingen zelf kunnen nagaan.
- **Volgt een beproefd lesritme:** activeren → expliciete instructie met een uitgewerkt voorbeeld → begeleide inoefening met een klassikale check → zelfstandige inoefening → exit-check.
- **Benoemt het typische misconcept** en hoe je het aanpakt.
- **Kiest werkvormen die bij het doel passen**, niet groepswerk als standaard of bezigheidstherapie.
- **Differentieert praktisch:** per oefenfase een ondersteunende en een uitdagende optie.
- **Timing die klopt:** de minuten tellen exact op tot de lestijd.

## Wat je terugkrijgt

1. **Leerdoel en succescriteria** ("Ik kan …")
2. **Lesverloop** in een tabel: tijd, fase, leraar, leerlingen, materiaal
3. **Uitgewerkt voorbeeld en misconcept**
4. **Differentiatie** per oefenfase
5. **Exit-check** met antwoorden
6. **Volgende les**: wat je doet op basis van de exit-check

## Voor wie

Voor leerkrachten, docenten en trainers die snel een doordachte lesvoorbereiding willen, van basisonderwijs tot bedrijfsopleiding.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): prompts voor leerkrachten, met uitleg waarom ze werken
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): beoordelingsrubrics met observeerbare niveaus
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specifieke, haalbare feedback op leerlingenwerk
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): lesmateriaal toegankelijk maken met UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): opleidingen en leertrajecten ontwerpen
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (web, desktop of mobiel):**
1. Download [`lesson-designer.skill`](lesson-designer.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `lesson-designer/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"maak een les van 50 minuten over procenten voor het eerste middelbaar"*. De skill start vanzelf.

## Structuur

```
lesson-designer/
└── SKILL.md              # de volledige instructies van de skill
examples/                 # voorbeelden van input en output
lesson-designer.skill     # installeerbaar pakket
```

## Bijdragen

Ideeën en verbeteringen zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
