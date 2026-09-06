# Reading & Writing

Subject ID: `hum.know.basic.reading-and-writing`  
Plane: knowledge. Audience: humans. Level: basic.  
Layer: 2 of the [Sentient Architecture](../../../SENTIENT-ARCHITECTURE.md).  
Status: `MAPPED` — system specified, engines not yet running.

Reading & Writing is not one lesson. It is eleven-plus cognitive subsystems with distinct pathways, stages, and failure modes. GAIA treats it as one subject ID and thirteen modules.

This folder is inside the Human Knowledge catalog. It is not a new plane.

## Science the system is bound to

### Six reading constructs

| # | Construct | Function |
| ---: | --- | --- |
| 1 | Oral language | Spoken vocabulary, grammar, listening comprehension |
| 2 | Phonological awareness | Hearing and manipulating sounds in spoken words |
| 3 | Phonics | Letters ↔ sounds (decode and encode) |
| 4 | Fluency | Accuracy, rate, expression |
| 5 | Vocabulary | Word meaning, oral and written |
| 6 | Reading comprehension | Understand, infer, reason from text |

### Five literacy phases (orthographic mapping)

| Phase | Name | Marker |
| ---: | --- | --- |
| 1 | Pre-alphabetic | Visual cues, no letter-sound map |
| 2 | Partial alphabetic | Some letter-sound knowledge; context guessing |
| 3 | Full alphabetic | Systematic decoding of all letters |
| 4 | Consolidated alphabetic | Chunks, patterns, morphemes automatic |
| 5 | Automatic / orthographic | Instant recognition of stored brain words |

### Writing process (Hayes & Flower)

Planning → Translating (drafting) → Reviewing, under a Monitor, drawing Long-Term Memory (topic, audience, stored plans). Reading and writing share process. Weak transcription in early years predicts later failure. Instruction is integrated.

### Reading network (design map, not a clinical claim)

Visual word form area, phonological mapping, semantic extraction, executive control of inference and working memory.

## Modules

Machine-readable twin: [`modules.json`](modules.json).  
Module 1 output schema: [`literacy-profile.schema.json`](literacy-profile.schema.json).

| # | ID | Name | Priority | Status |
| ---: | --- | --- | --- | --- |
| 1 | `hum.know.basic.reading-and-writing.m01` | Literacy Diagnostic Engine | critical | specified |
| 2 | `hum.know.basic.reading-and-writing.m02` | Phonological Awareness Training | critical | specified |
| 3 | `hum.know.basic.reading-and-writing.m03` | Phonics & Decoding Engine | critical | specified |
| 4 | `hum.know.basic.reading-and-writing.m04` | Reading Fluency System | critical | specified |
| 5 | `hum.know.basic.reading-and-writing.m05` | Vocabulary Architecture | critical | specified |
| 6 | `hum.know.basic.reading-and-writing.m06` | Reading Comprehension Engine | critical | specified |
| 7 | `hum.know.basic.reading-and-writing.m07` | Writing Process Engine | critical | specified |
| 8 | `hum.know.basic.reading-and-writing.m08` | Transcription Skills System | high | specified |
| 9 | `hum.know.basic.reading-and-writing.m09` | Integrated Literacy System | high | specified |
| 10 | `hum.know.basic.reading-and-writing.m10` | Multilingual Literacy System | high | specified |
| 11 | `hum.know.basic.reading-and-writing.m11` | Literacy Intervention System | high | specified |
| 12 | `hum.know.basic.reading-and-writing.m12` | Advanced Literacy System | medium | specified |
| 13 | `hum.know.basic.reading-and-writing.m13` | Literacy Data & Analytics Engine | critical | specified |

Build order: 1 and 13 first (profile + record), then 2 → 3 → 4 → 5 → 6 → 7, then 8, 9, 10, 11, then 12.

## Module contracts

### M01 — Literacy Diagnostic Engine

Assesses all six constructs and places the learner on the five phases.

Build: phonological awareness (rhyme, segmentation, blending, manipulation); phonics (real + nonsense words); oral fluency (WCPM, accuracy, prosody); vocabulary depth (breadth, depth, morphology); comprehension (literal, inferential, critical); transcription (handwriting fluency, spelling); composition (plan, draft, revise). Output: literacy profile per `literacy-profile.schema.json`.

Gate: `ask` before storing a profile. Personal literacy data is vault-scoped. No ambient read.

### M02 — Phonological Awareness Training

Adaptive auditory foundation. Rhyme, syllable segment/blend, phoneme isolation (initial/medial/final), blend, segment, manipulate (delete, substitute, add). Real-time feedback. Progress maps to phases 1–3.

### M03 — Phonics & Decoding Engine

Explicit, systematic. 44 English phonemes; grapheme–phoneme map simple → complex; decode CVC → CCVC → CVCC → multisyllabic; encode (dictation); orthographic patterns (digraphs, blends, diphthongs, silent letters); morphology (prefix, suffix, root); nonsense-word fluency; later hooks to M10 languages.

### M04 — Reading Fluency System

Automatic expressive reading. WCPM tracker; prosody; repeated reading with feedback; paired reading; reader's theater; grade fluency norms; RAN drills; high-frequency brain-words vault.

### M05 — Vocabulary Architecture

Tiers 1–3; relations (synonym, antonym, analogy, collocation); morphological families; contextual inference; depth checks; etymology (Latin, Greek, Germanic); spaced repetition; cross-language transfer via M10.

### M06 — Reading Comprehension Engine

Literal, inferential, critical; text structures (narrative, expository, persuasive, procedural); main idea and summary; inference generation; metacognitive fix-up; question generation; close reading; multi-text synthesis.

### M07 — Writing Process Engine

Hayes & Flower: planning (brainstorm, map, outline, goals); drafting (sentence, paragraph, transition); reviewing (clarity, argument, revision). Monitor tracks goals. Long-term memory draws Layer 2 subjects under cap. Genre templates. Audience shift. Sentence combining. Self-efficacy log.

### M08 — Transcription Skills System

Print → cursive → typing; stroke order; letters per minute; spelling path phonetic → orthographic → morphological → etymological; dictation; typing WPM; home-row curriculum. Handwriting is kept because it supports memory. This is instruction, not a medical device.

### M09 — Integrated Literacy System

Read-to-write and write-to-read; shared reading/writing; mentor-text imitation; comprehension-through-writing; integrated spelling–reading–writing lessons; cross-curricular texts from other Layer 2 subjects.

### M10 — Multilingual Literacy System

Phonics paths for English, Spanish, French, Mandarin, Arabic, Hindi, Portuguese, Russian, Japanese, Korean, German, Italian. Transfer map. Bilingual pathways. Scripts: Latin, Cyrillic, Arabic, Devanagari, CJK, Hangul. Orthographic depth (shallow vs deep) is an explicit parameter.

### M11 — Literacy Intervention System

Screening support and accommodation tools for dyslexia and dysgraphia — not a silent clinical diagnosis. Structured literacy protocols; TTS/STT; assistive tech hooks; multi-sensory activities; MTSS progress monitoring; IEP-aligned goal tracking when an operator supplies the plan. Medical claims stay outside GAIA.

### M12 — Advanced Literacy System

Academic, professional, and creative writing; critical literacy; digital/multimodal source evaluation; rhetorical analysis; speed practice; annotation; discipline reading (scientific, legal, literary) via Layer 2 links.

### M13 — Literacy Data & Analytics Engine

Growth dashboards; longitudinal record; early-warning signals; educator cohort tools; level scales (Lexile, DRA, guided reading) as labels, not as a single hidden rank that erases T0 dissent; writing rubrics with human-in-the-loop; age/grade/language benchmarks; parent/teacher reports. No plaintext profile in the public audit log.

## Sentience bindings (Layers 6–7, gated by 9)

| Binding | Layer | Rule |
| --- | --- | --- |
| Adaptive personalization | 6 AFS + MA | Pace, interest, and error pattern adjust the next item |
| Emotional awareness | 6 EMS | Frustration or withdrawal changes approach; it does not punish |
| Motivational intelligence | 6 CSE + 7 CIM | Goals and identity of the learner, not a generic streak |
| Cross-domain linking | 2 + 6 RE | Science text opens science subject IDs; history writing draws history IDs |
| Metacognitive coaching | 6 MCM | Learner watches their own reading and writing |

All five are `ask` or `allow` only with a session cap. HIGH auto-personalization that stores covert profiles is deny.

## Instantiation artifacts

| Artifact | This subject |
| --- | --- |
| Substrate | Human literacy cognition + GAIA Layer 2 graph + session cap |
| Correspondence | Title Reading & Writing → 13-module literacy platform |
| Test | A profile can be produced and can fail a construct check |
| Gate | Profile store `ask`; intervention labels `ask`; public audit no raw profile |

Next construction: implement M01 against `literacy-profile.schema.json`, then wire M13 to persist the profile in a vault cap.
