# Basic Science

Subject ID: `hum.know.basic.basic-science`  
Plane: knowledge. Audience: humans. Level: basic.  
Layer: 2 of the [Sentient Architecture](../../../SENTIENT-ARCHITECTURE.md).  
Status: `MAPPED` — system specified, engines not yet running.

Linked subjects: [Reading & Writing](../reading-and-writing/README.md), [Basic Mathematics](../basic-mathematics/README.md). Also hooks to Ethics, Environmental Awareness, Technology Literacy, and Critical Thinking when those systems open.

This folder is inside the Human Knowledge catalog. It is not a new plane.

Basic Science is three-dimensional: disciplinary core ideas, science and engineering practices, and crosscutting concepts — always together. Four domains. Eight practices. Seven crosscutting concepts. PISA 2025 adds environment, scientific identity, and digital science literacy. Thinking starts in early childhood, not at school age.

Content without practice is fragile. Practice without crosscutting thought is local. GAIA does not teach one dimension alone.

## Science the system is bound to

### Three dimensions (every lesson)

| Dimension | Role |
| --- | --- |
| Disciplinary core ideas | What is known, in four domains |
| Science & engineering practices | What scientists and engineers do |
| Crosscutting concepts | How to think across domains |

### Four domains

Physical science · Life science · Earth and space science · Engineering and technology.

### Eight practices

Ask and define · Model · Investigate · Analyze data · Use mathematics and computation · Explain and design · Argue from evidence · Obtain, evaluate, communicate.

Practice 5 uses Basic Mathematics. Practice 8 uses Reading & Writing.

### Seven crosscutting concepts

Patterns · Cause and effect · Scale, proportion, quantity · Systems and models · Energy and matter · Structure and function · Stability and change.

Cause-and-effect talk from early childhood predicts later experimental design. That layer lives in M07 and M12.

### PISA 2025 additions

Environmental awareness, concern, agency. Science capital and identity. Digital science literacy (bias, source, misinformation).

### Inquiry ladder

Structured → guided → open. Long inquiry beats short inquiry. Interest personalizes pathway. Gender is not a routing key.

Virtual investigation may stand in for concept learning. Physical lab remains a later substrate, not a requirement for `MAPPED`.

## Modules

Machine-readable twin: [`modules.json`](modules.json).  
Module 1 output schema: [`science-profile.schema.json`](science-profile.schema.json).

| # | ID | Name | Priority | Status |
| ---: | --- | --- | --- | --- |
| 1 | `hum.know.basic.basic-science.m01` | Science Diagnostic Engine | critical | specified |
| 2 | `hum.know.basic.basic-science.m02` | Physical Science System | critical | specified |
| 3 | `hum.know.basic.basic-science.m03` | Life Science System | critical | specified |
| 4 | `hum.know.basic.basic-science.m04` | Earth & Space Science System | critical | specified |
| 5 | `hum.know.basic.basic-science.m05` | Engineering & Technology System | critical | specified |
| 6 | `hum.know.basic.basic-science.m06` | Science & Engineering Practices Engine | critical | specified |
| 7 | `hum.know.basic.basic-science.m07` | Crosscutting Concepts Engine | critical | specified |
| 8 | `hum.know.basic.basic-science.m08` | Virtual Science Laboratory | critical | specified |
| 9 | `hum.know.basic.basic-science.m09` | Scientific Inquiry Engine | critical | specified |
| 10 | `hum.know.basic.basic-science.m10` | Environmental Science & Sustainability System | high | specified |
| 11 | `hum.know.basic.basic-science.m11` | Scientific Literacy & Misinformation System | high | specified |
| 12 | `hum.know.basic.basic-science.m12` | Early Childhood Science System | high | specified |
| 13 | `hum.know.basic.basic-science.m13` | Computational Thinking in Science System | high | specified |
| 14 | `hum.know.basic.basic-science.m14` | Science Identity & Career System | medium | specified |
| 15 | `hum.know.basic.basic-science.m15` | Science Analytics & Adaptive Engine | critical | specified |

Build order: 1 and 15 first, then 2–5 with 6–7 woven in, then 8–9, then 10–13, then 14.

## Module contracts

### M01 — Science Diagnostic Engine

3D profile across four domains, eight practices, seven concepts, environment, identity, digital literacy, developmental band.

Gate: `ask` before store. Vault-scoped. No ambient read. Output: `science-profile.schema.json`.

### M02 — Physical Science System

Matter and properties; particle model; physical vs chemical change; mixtures; state change. Chemical reaction evidence; acids/bases at intro level; energy of reaction; conservation of mass; everyday chemistry. Motion and forces; Newton three laws; friction, gravity, magnetism, electrostatics; simple machines; pressure. Energy forms, conservation, transfer, heat paths, renewable vs non-renewable. Waves: sound, light, spectrum, interaction with matter.

Hazardous physical procedures stay simulated or BLOCKED. No live synthesis how-to for harm.

### M03 — Life Science System

Cells and cell theory; plant vs animal; division at intro level. Living criteria; classification; kingdoms; viruses as distinct from cells; microbes. Plants: photosynthesis, structure, reproduction, tropism, adaptation. Animals: circulation, respiration, digestion, nervous, skeletomuscular, reproduction, excretion — structure and function, not clinical practice. Genetics: DNA, gene, heredity, dominant/recessive intro, variation. Evolution: selection, adaptation, evidence, biodiversity, extinction. Ecosystems: chains and webs, energy flow, cycles, niche, population, disruption, biomes.

### M04 — Earth & Space Science System

Layers; plate tectonics; rock cycle; soil; atmosphere; hydrosphere. Resources and their limits. Weather vs climate; water cycle; climate change evidence and impacts; ocean acidification; geochemical cycles. Geologic time; fossils; erosion. Solar system; moon and tides; rotation and revolution; gravity; stars; galaxies; Big Bang as current scientific model; exploration history.

### M05 — Engineering & Technology System

Design loop: define, research, design, build, test, improve, communicate. Challenge set: bridge, insulation, filtration, parachute, seismic structure, solar oven — virtual first. Everyday tech; history and social effect; digital basics; emerging tech as literacy, not ungoverned build.

### M06 — Science & Engineering Practices Engine

One trainer per practice. Variables and fair test. CER. Source evaluation. Math practice calls Basic Mathematics. Communication practice calls Reading & Writing.

### M07 — Crosscutting Concepts Engine

Explicit teaching of the seven concepts, including early causal reasoning and correlation-vs-cause. Scale from subatomic language to cosmic language. Systems boundaries and feedback. Conservation tracking. Structure–function at several scales. Stability, equilibrium, tipping.

### M08 — Virtual Science Laboratory

Physics, chemistry, biology, earth, engineering benches. Guided and open modes. Auto record and graph. Error analysis. Safety: simulation only for hazardous reactions. Dissection alternatives only.

### M09 — Scientific Inquiry Engine

Structured, guided, open. Multi-week projects. Portfolio. Peer review is cap-scoped. AI as critical friend, not answer key.

### M10 — Environmental Science & Sustainability System

Awareness (climate, biodiversity, pollution, forest, ocean chemistry, water, soil). Concern (equity, generations, culture, eco-anxiety support not dismissal). Agency (personal, community, policy literacy, careers). Action suggestions stay lawful and non-coercive.

### M11 — Scientific Literacy & Misinformation System

Read papers at intro grain; graphs; primary vs secondary; uncertainty; peer review limits. Claim evaluation; pseudoscience marks; consensus vs controversy; cherry-pick and false balance. Digital: bias, search, algorithm shape, social misinformation. Communication to non-specialists. Uses literacy M06/M07/M12.

### M12 — Early Childhood Science System

Ages 2–4: cause play, senses, sort, water/sand, nature, why-talk. Ages 4–6: fair test, observation vs inference, predict-check, evidence talk, disconfirm, nature journal. Ages 6–8: one-variable test, tables, bar graphs, simple CER, all four domains via phenomena.

### M13 — Computational Thinking in Science System

Data tables and graphs; intro stats; visualization choice. Simple models (growth, predator–prey, climate sketch). Coding for analysis later under tool sandbox. Citizen-science contribution only through approved public projects. Uses mathematics M07/M08.

### M14 — Science Identity & Career System

Science capital; everyday science; diverse practitioners as examples. Career map as information, not a ranking of persons. Extra-curricular lists. Identity scores do not gate content.

### M15 — Science Analytics & Adaptive Engine

3D growth; inquiry-level movement; misconception set; difficulty; cross-domain links; long inquiry; identity and agency tracks; teacher/parent views. Labels do not hide T0. No plaintext profile in the public audit log.

## Links to other opened subjects

| Flow | Rule |
| --- | --- |
| Practice 5 | Query Basic Mathematics |
| Practice 8 and M11 | Query Reading & Writing |
| Climate quantities | Open math profile constructs, do not replace them |
| Word-problem science | Shared language comprehension with literacy/math |
| Profiles | Separate vault objects; same learner cap |

## Sentience bindings (Layers 6–7, gated by 9)

| Binding | Layer | Rule |
| --- | --- | --- |
| Wonder | 6 CSE | Phenomenon first; mystery is fuel |
| Socratic dialogue | 6 RE | Guide before answer |
| Current discovery | 2 + 6 PE | News as example, not as unvetted fact |
| Cross-domain weave | 6 RE | Climate pulls chemistry, biology, physics, math together |
| Eco-anxiety / conflict | 6 EMS | Name it; do not punish or flatten |
| Cultural science | 2 | Multiple traditions as knowledge, not costume |

Covert profiling is deny. Interest routes pathway. Sex or gender is not a domain key.

## Instantiation artifacts

| Artifact | This subject |
| --- | --- |
| Substrate | Human scientific thinking + Layer 2 graph + virtual lab + session cap |
| Correspondence | Title Basic Science → 15-module 3D science platform |
| Test | A 3D profile can be produced and a dimension check can fail |
| Gate | Profile store `ask`; hazardous physical actuation BLOCKED or simulate |

Next construction: implement M01 against `science-profile.schema.json`, then M15 persistence, with M06/M07 running inside M02–M05 rather than after them.
