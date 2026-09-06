# Basic Mathematics

Subject ID: `hum.know.basic.basic-mathematics`  
Plane: knowledge. Audience: humans. Level: basic.  
Layer: 2 of the [Sentient Architecture](../../../SENTIENT-ARCHITECTURE.md).  
Status: `MAPPED` — system specified, engines not yet running.

Linked subject: [Reading & Writing](../reading-and-writing/README.md). Mathematics and reading share cognitive-control networks. These two systems are not separate databases.

This folder is inside the Human Knowledge catalog. It is not a new plane.

Basic Mathematics is four cognitive systems, three pathways, four proficiency strands, and five number-sense stages. GAIA treats it as one subject ID and fourteen modules.

## Science the system is bound to

### Four cognitive systems

| System | Function | Predicts |
| --- | --- | --- |
| Symbolic number skills | Numerals, number words, relations | Arithmetic and word problems — strongest predictor |
| Language comprehension | Verbal reasoning, vocabulary, listening | Word problems |
| Spatial ability | Mental rotation, visualization, number line | Arithmetic and word problems over time |
| Nonverbal IQ | Abstract pattern reasoning | Word problems |

Nonsymbolic number sense (ANS) is a weak achievement predictor. Symbolic number skill is the dominant one. GAIA still assesses ANS because the ANS → SNS transition is the developmental leap.

### Two number systems

| Code | Name | Work | Design note |
| --- | --- | --- | --- |
| ANS | Approximate Number System | Estimate without counting | Present early; not the main achievement driver |
| SNS | Symbolic Number System | Exact numerals, arithmetic, place value | Must be built explicitly |

### Four proficiency strands (simultaneous)

Understanding · Fluency · Problem-solving · Reasoning.

Fluency without understanding is brittle. Understanding without fluency is slow. Both without problem-solving cannot leave the page.

### Five number-sense stages

| Stage | Marker |
| --- | --- |
| Pre-numerical | Subitizing 1–3, object permanence |
| Early counting | One-to-one, stable order, cardinality |
| Cardinal knowledge | Last count word = quantity |
| Symbolic mapping | Numeral ↔ quantity; number line |
| Arithmetic fluency | Fact retrieval, multi-digit, place value |

Number talk is itself an intervention. Caregiver prompts belong in M02 and M11.

### Three pathways

Quantitative (symbolic + ANS → arithmetic) · Linguistic (language → word problems) · Spatial (space + number line → both).

Number-line estimation is a core tool: it bridges space and magnitude, approximate and exact, arithmetic and later mathematics.

### Dyscalculia (design bounds)

Population estimates around 3–6% of school-age children; high overlap with reading difficulty. Affects numeral mapping, patterns, money, time, space. Intervention may use a dynamic student model. Screening here is support, not a silent clinical diagnosis.

## Modules

Machine-readable twin: [`modules.json`](modules.json).  
Module 1 output schema: [`math-cognition-profile.schema.json`](math-cognition-profile.schema.json).

| # | ID | Name | Priority | Status |
| ---: | --- | --- | --- | --- |
| 1 | `hum.know.basic.basic-mathematics.m01` | Mathematics Diagnostic Engine | critical | specified |
| 2 | `hum.know.basic.basic-mathematics.m02` | Number Sense Foundation System | critical | specified |
| 3 | `hum.know.basic.basic-mathematics.m03` | Symbolic Number System Engine | critical | specified |
| 4 | `hum.know.basic.basic-mathematics.m04` | Number Line Training System | critical | specified |
| 5 | `hum.know.basic.basic-mathematics.m05` | Arithmetic Fluency System | critical | specified |
| 6 | `hum.know.basic.basic-mathematics.m06` | Conceptual Understanding Engine | critical | specified |
| 7 | `hum.know.basic.basic-mathematics.m07` | Problem-Solving Engine | critical | specified |
| 8 | `hum.know.basic.basic-mathematics.m08` | Mathematical Reasoning System | high | specified |
| 9 | `hum.know.basic.basic-mathematics.m09` | Spatial Mathematics System | high | specified |
| 10 | `hum.know.basic.basic-mathematics.m10` | Word Problem Language System | high | specified |
| 11 | `hum.know.basic.basic-mathematics.m11` | Early Childhood Mathematics System | high | specified |
| 12 | `hum.know.basic.basic-mathematics.m12` | Dyscalculia Intervention System | high | specified |
| 13 | `hum.know.basic.basic-mathematics.m13` | Financial Mathematics System | medium | specified |
| 14 | `hum.know.basic.basic-mathematics.m14` | Mathematics Analytics & Adaptive Engine | critical | specified |

Build order: 1 and 14 first, then 2 → 3 → 4 → 5 → 6 → 7, then 8–12, then 13.

## Module contracts

### M01 — Mathematics Diagnostic Engine

Maps the four systems, three pathways, five stages, and four strands.

Build: ANS (dot comparison, estimation); symbolic skills (recognition, order, magnitude); number-line estimation (0–10 / 0–100 / 0–1000); fact retrieval speed and accuracy; working memory (digit and spatial span); spatial screen (rotation, pattern); language screen for the word-problem path; procedural multi-step fluency; conceptual why; novel problem-solving; generalization; dyscalculia *screening support*. Output: profile per `math-cognition-profile.schema.json`.

Gate: `ask` before store. Vault-scoped. No ambient read.

### M02 — Number Sense Foundation System

Pre-symbolic and early symbolic bedrock. Subitizing 1–5; counting principles (one-to-one, stable order, cardinality, abstraction, order-irrelevance); cardinal how-many; number words in many languages; numeral–quantity map; magnitude comparison; conservation; early counting play; caregiver number-talk prompts.

### M03 — Symbolic Number System Engine

Strongest achievement predictor. Digit–quantity map through large scale; order and skip-count; place value; decomposition; expanded and standard form; rounding and estimation; negatives; rationals (fraction, decimal, percent) and conversion; properties (even/odd, prime/composite, factor, multiple, divisibility); scale intuition for large numbers.

### M04 — Number Line Training System

Linear 0–10 through 0–1000; fraction and decimal lines; negatives; estimation games; mental line; line as model of the four operations; benchmarks 0, 1/2, 1; ratio and rate on the line; range expands with mastery.

### M05 — Arithmetic Fluency System

Addition and subtraction facts; multiplication 0–12 and derived division; mental strategies (make ten, doubles, compensation, skip-count, partial products/quotients); multi-digit standard and alternative algorithms with estimate-first; fraction and decimal operations; percentages; spaced repetition; timed and untimed modes.

### M06 — Conceptual Understanding Engine

Four representations: concrete, pictorial, symbolic, verbal. CPA progression. Concept graph across this subject. Explain why an algorithm works. Documented misconception set with corrections. Equivalence 3/4 = 0.75 = 75%. Inverse operations. Commutative, associative, distributive. Modeling onto real situations.

### M07 — Problem-Solving Engine

Word-problem types (join, separate, compare, part-whole, rate, ratio, and the rest). Strategies: diagram, table, pattern, work backwards, guess-and-check, simpler numbers, act out, equation. Comprehend before compute. Multi-step. Real contexts. Difficulty ladder. Reasonableness check. Problem posing. Collaborative mode is cap-scoped.

### M08 — Mathematical Reasoning System

Patterns; conjecture and test; argument; generalization; counterexample; logic puzzles; early algebraic thinking; proportion; if-then; prove / explain / another way.

### M09 — Spatial Mathematics System

Mental rotation; visualization; 2D/3D geometry (class, area, perimeter, surface, volume); line, angle, symmetry, transform; measurement (length, mass, capacity, time, temperature, money) with unit conversion; coordinates; graphs; spatial–numerical integration; map scale.

### M10 — Word Problem Language System

Draws [Reading & Writing](../reading-and-writing/README.md) M01 and M06/M07. Math vocabulary; signal words; sentence parse; visualization from text; schema types (additive, multiplicative, proportional); multilingual problems; math-text reading strategies; written mathematical explanation.

### M11 — Early Childhood Mathematics System

Ages 2–7. Songs and rhymes; virtual manipulatives; sort and classify; pattern AB/ABC/AAB; comparison language; number stories; finger math; subitizing games; calendar; informal measurement.

### M12 — Dyscalculia Intervention System

Screening support, not silent diagnosis. Dynamic student model that may adapt item choice. Gamified targeted practice; symbol–verbal mapping; pattern work; multi-sensory routes; reduced load; TTS/STT; comorbidity hooks to literacy M11; caregiver/educator reports. Medical claims stay outside GAIA.

### M13 — Financial Mathematics System

Currency recognition; change; budget arithmetic; percent in commerce; simple interest explained; unit price; earn/spend scenarios; saving-goal math; basic tax as calculation, not legal advice; exchange-rate arithmetic.

### M14 — Mathematics Analytics & Adaptive Engine

Growth by module and strand; trajectory; early warning; live difficulty; error-pattern (not only wrong/right); load and engagement monitors; spaced review; links to science and financial-literacy subject IDs; educator/parent dashboards. Level labels do not hide T0 dissent. No plaintext profile in the public audit log.

## Shared cognitive control with Reading & Writing

Working memory, executive function, and language comprehension are shared.

| Flow | Rule |
| --- | --- |
| Word problem | May query literacy M01 / M06 |
| Mathematical explanation | May query literacy M07 |
| Weakness in one domain | Surface it in the other; do not rank it away |
| Profile store | Separate vault objects; same learner cap |

## Sentience bindings (Layers 6–7, gated by 9)

| Binding | Layer | Rule |
| --- | --- | --- |
| Math-anxiety response | 6 EMS | Avoidance or negative self-talk lowers pressure; it does not mock |
| Growth-mindset coaching | 6 MCM | Ability is trained, not a fixed trait claim |
| Personalized context | 6 CSE + 7 CIM | Sports, cooking, games, music — learner's world |
| Socratic questioning | 6 RE | Guide before answer |
| Cross-module intelligence | 2 + 6 RE | Science quantities open this subject |
| Cultural mathematics | 2 | Multiple traditions as representations, not decoration |

Covert profiling is deny. Session cap required.

## Instantiation artifacts

| Artifact | This subject |
| --- | --- |
| Substrate | Human numerical cognition + Layer 2 graph + session cap |
| Correspondence | Title Basic Mathematics → 14-module mathematics platform |
| Test | A profile can be produced and a construct check can fail |
| Gate | Profile store `ask`; intervention labels `ask`; public audit no raw profile |

Next construction: implement M01 against `math-cognition-profile.schema.json`, share control fields with the literacy profile, then persist via M14 in a vault cap.
