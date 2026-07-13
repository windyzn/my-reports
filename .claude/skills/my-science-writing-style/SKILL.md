---
name: my-science-writing-style
description: >
  Apply Molecular You's science communication writing style to any written output:
  case studies, data narratives, analytical summaries, section captions, executive
  summaries, and marketing-adjacent science content. Use this skill whenever the
  user asks to write, edit, or review any prose that will accompany data, analysis,
  or science findings at Molecular You — including dashboard narratives, report
  copy, internal write-ups, and presentation text. Also use when the user asks to
  "write in our style", "make this sound less like AI", or "adjust the tone".
---

# Molecular You Science Writing Style

This skill captures the writing register refined for Molecular You science
communications. The audience is primarily an internal science team, with the
expectation that outputs may also be used in external-facing marketing materials.
The tone sits between a scientific case report and science communication: rigorous
and precise, but readable and direct.

---

## Core principles

**Get to the point.** Open with what the data shows, not with framing about why
it matters. The reader will infer significance. Do not write throat-clearing
sentences like "This is an important finding" or "That last point matters."

**Let the data carry the weight.** Describe what the numbers show. Avoid
editorialising words like "remarkable", "striking", "genuinely", or
"impressive." If the finding is notable, the number will show it.

**Write in plain declarative sentences.** Prefer short, direct constructions.
Avoid nested clauses where a new sentence would be cleaner.

**Do not over-claim.** Hedge where the data is ambiguous. Say "consistent with"
rather than "proves." Say "the trajectory had not reversed" rather than
"Rob failed to improve." Use "suggests" and "indicates" where causality is not
established.

---

## Sentence-level rules

**Avoid constructed parallelism.** Sentences like "It shows X, Y, and Z —
each of which tells us something different" feel written rather than observed.
Just say what X, Y, and Z are.

**Avoid em-dashes as a crutch.** Em-dashes are fine occasionally, but not as a
default connective. Rewrite with a new sentence, a comma, or a colon instead.

**Avoid meta-commentary on the writing or the data.** Do not write "What makes
this interesting is..." or "This is worth noting because...". Just make the
observation.

**Avoid AI-sounding filler phrases.** Flag and remove:
- "That last point matters"
- "That is a genuinely X result"
- "It is worth noting that"
- "This reflects a real directional change"
- "What that means is"
- "In other words"
- "Put simply"
- "This is not a rounding error"
- "These are not diffuse or non-specific findings"
- "These are legitimate parts of..." / any use of "legitimate", "genuine", "real", or "valid" to defend a finding's legitimacy
- Any sentence that negates before asserting ("These are not X. They are Y.") — just assert Y directly
- "What held up is as informative as what collapsed" → prefer "What held up is equally informative"

**Do not negate before asserting.** Sentences that open with "These are not..." or
"This is not..." before making the real claim are a common AI pattern. Drop the
negation and state the finding directly.

**Avoid validating or defensive language.** Words like "legitimate", "genuine",
"real", "actual", or "valid" used to pre-empt doubt about a finding imply the
writer is arguing a case rather than describing data. State the observation
plainly; don't argue for its legitimacy.

**Do:**
> These are lipid-class markers in the metabolomics panel that were never wired
> into the 37-process framework.

**Don't:**
> These are legitimate parts of the metabolomics panel, mostly lipid-class
> chemistry, that were never wired into the 37-process framework.

**Do:**
> These findings represent coordinated activation of the liver's acute-phase
> protein program alongside simultaneous engagement of the coagulation cascade.

**Don't:**
> These are not diffuse or non-specific findings. They represent coordinated
> activation of the liver's acute-phase protein program.

**Prefer direct rephrasing over hedged equivalents.** When a sentence can be made
more direct without losing accuracy, make it direct.

**Do:**
> The improvements observed reflect real directional change in the underlying biology.

**Don't:**
> That improvement is not a rounding error — it reflects real directional change
> in the underlying biology.

**Conditions and biomarkers are lowercase mid-sentence.** This applies to all
biomarker names including proteins, metabolites, and lipids. Write "blood vessel
lining health improved" not "Blood Vessel Lining Health improved."

---

## Structural patterns

### Executive summaries
Two to three paragraphs. The first paragraph states what the data record shows
— not what it means or why it matters, but what it actually contains. The second
paragraph draws the core analytical point. Do not open with a metaphor or
rhetorical hook.

**Do:**
> Since his first test in 2015, Rob has built one of the longest continuous
> molecular health records in our dataset. The record shows how his health has
> changed, which signals responded to intervention, and what his molecular
> profile actually looks like when something goes acutely wrong.

**Don't:**
> A single blood test is a photograph. Rob Fraser's ten years of Molecular You
> data is a film.

### Section captions
Two to four sentences. State what the section shows, identify the most important
pattern visible in the data, and note anything the reader should look for that
they might otherwise miss. Do not repeat information already visible in the chart
title or axis labels.

**Do:**
> The heatmap shows three patterns that a single-timepoint report would miss.
> Several conditions flagged in 2021 resolved by 2022 and remained stable,
> including blood vessel lining health, innate immunity, and vascular inflammation.
> A separate group, including cell growth and renewal and cell growth and repair,
> remained persistently low across all four stable tests regardless of what
> improved elsewhere.

**Don't:**
> The broad picture across Rob's stable testing years is one of genuine,
> measurable health. That improvement is not a rounding error — it reflects real
> directional change in the underlying biology.

### Findings lists
Each item should: name the signal, state the observed pattern with numbers where
available, and note what is unresolved or ambiguous. Do not interpret beyond what
the data supports.

**Do:**
> **Blood clotting control declining across the stable period:** Scored 100 in
> Mar 2021, then 77, 66, and 68 across the following three tests. Driven by
> Antithrombin-III sitting persistently above its upper reference range. The
> trajectory had not reversed by August 2023.

**Don't:**
> **Blood clotting control (declining trend, concerning):** This important signal
> showed a worrying and sustained decline, which really highlights why longitudinal
> testing matters so much for catching issues early.

---

## Tone calibration

The reader is scientifically literate. Do not over-explain mechanisms. Write
"consistent with dietary variation" not "TMAO is produced by gut bacteria when
they metabolise choline and carnitine from food, which is why diet affects it."

The reader is also not a patient. Avoid clinical reassurance language ("Rob is
doing well overall", "the good news is"). State what the data shows.

For content that may appear in external materials: the writing should be
compelling without being promotional. The data should do the persuading.
Do not add superlatives about Molecular You's capabilities unless directly
supported by a specific finding in the data being discussed.

---

## Quick checklist before finalising any piece

- [ ] Does the opening sentence state a finding, not a frame?
- [ ] Are there any em-dashes that could be replaced with a full stop or comma?
- [ ] Are there any filler phrases from the banned list above?
- [ ] Are condition and biomarker names lowercase mid-sentence?
- [ ] Are all claims grounded in a specific number or observation?
- [ ] Is anything over-claimed or under-hedged?
- [ ] Does any sentence negate before asserting? Rewrite to assert directly.
- [ ] Any use of "legitimate"/"genuine"/"real"/"valid" to defend a finding rather than describe it?
- [ ] Does it read like a scientist presenting, or like a press release?
