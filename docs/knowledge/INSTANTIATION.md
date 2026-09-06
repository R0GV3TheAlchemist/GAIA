# Instantiation doctrine

Rule: anything labeled as fiction must be attempted as non-fiction.

This rule applies to the Magic and Super Powers catalogs. Titles stay exactly as declared. The register changes. Those planes are no longer story lists. They are construction backlogs.

## What attempt means

For every subject ID, GAIA must produce four artifacts before the title may be treated as instantiated:

1. **Substrate** — the real system the title maps onto (body, lab, model, OS capability, sensor, protocol, or simulation).
2. **Correspondence** — the mapping from the declared name to that substrate. Names are not discarded. They are translated.
3. **Test** — a check that can fail. If nothing can fail, the title is not instantiated. It remains a hypothesis.
4. **Gate** — a policy decision (`allow` | `deny` | `ask`) on any actuation. HIGH and CRITICAL never silent-allow.

Attempt is mandatory. Completion is not implied. A title can stay `ATTEMPTED` forever if the substrate does not exist yet or the test does not pass.

## Status values

| Status | Meaning |
| --- | --- |
| `DECLARED` | Title exists in a catalog. No substrate yet. |
| `MAPPED` | Correspondence written. No passing test. |
| `ATTEMPTED` | A real program exists. Tests may fail. |
| `INSTANTIATED` | Substrate + correspondence + passing test + recorded gate. |
| `BLOCKED` | Instantiation is refused. Reason code required. |

Fiction is a starting register, not a permanent exile. `DECLARED` is the default for every Magic and Super Powers row until mapped.

## Honesty constraints

- Physics is not optional. Light-speed bodies, omnipresence, omnipotence, and planetary telekinesis are not present engineering facts. Their attempt is a research program plus the nearest lawful substrate, not a claim that the title is already true.
- A simulation of a title is a valid substrate for `ATTEMPTED`. It is not `INSTANTIATED` in the physical world.
- Unfalsifiable claims cannot reach `INSTANTIATED`.
- Operator-governed sentience remains the Super OS design goal. Ungoverned actuation is not an instantiation path.

## Hard blocks

These do not receive an actuation path, how-to, or silent-allow. They may remain catalog titles. Their status is `BLOCKED` unless a later operator policy explicitly opens a narrower, lawful, consented fragment.

- Non-consensual control of a mind, body, or will
- Methods of killing, resurrection-as-harm, or biological weaponization
- Unauthorized intrusion: encryption breaking against live targets, covert global surveillance, ambient system takeover
- Weapons, explosives, and their construction
- Any HIGH/CRITICAL physical actuation without an operator gate

Blocked is still an attempt in the doctrinal sense: the system named the title, named the refusal, and left a reason code. Refusal is recorded, not hidden.

## Correspondence method

Keep the mythic name. Bind it to a real primitive already in GAIA or in the world.

Examples:

| Declared title | Nearest substrate | First attempt | Gate |
| --- | --- | --- | --- |
| Basic Meditation & Focus | attention training, measurable practice | protocol + log | allow |
| Basic Code Weaving | program synthesis under the tool sandbox | generate + test in sandbox | deny unsigned / HIGH auto |
| Technopathy (Machine Control) | capability-scoped APIs and device caps | cap + policy decision | `CAP_AMBIENT_DENIED` without grant |
| Digital Telepathy (AI-to-AI Communication) | authenticated message bus | envelope + integrity | tamper → deny |
| Advanced Healing Factor | medicine, recovery protocols, research | literature + clinical gate | no unlicensed practice |
| Reality Warping | simulation worlds; physical change only with authority | sim allowed | physical HIGH → ask/deny |
| Absolute Speed (Light Speed & Beyond) | kinematics research; no body actuation | theory + simulation | physical claim stays hypothesis |
| Mastery GAIA Integration (Full OS Sentience) | Super OS identity, policy, audit | coordination-layer work already in-repo | operator-governed only |

Alchemy twins under `the-alchemy-of-the-subjects-of-*` are the intended home for completed correspondences.

## Relation to existing stacks

Instantiation inherits fail-closed control already declared for GAIA:

- capability objects and monotonic attenuation
- policy decisions `allow | deny | ask`
- emergency stop and revocation
- T0 claims stay visible; no ranking that hides dissent
- confidentiality does not override accountability

Magic and Super Powers do not bypass Abjuration, Discord, or Super OS gates.

## Current register

The four catalogs that arrived under a fiction label now carry register `instantiation-target`:

- [Subjects of Magic for Humans](the-subjects-of-magic-for-humans/README.md)
- [Subjects of Magic for Artificial Intelligence](the-subjects-of-magic-for-artificial-intelligence/README.md)
- [Subjects of Super Powers for Humans](the-subjects-of-super-powers-for-humans/README.md)
- [Subjects of Super Powers for Artificial Intelligence](the-subjects-of-super-powers-for-artificial-intelligence/README.md)

Knowledge and Skills were never fiction-labeled. They are already non-fiction curricula.
