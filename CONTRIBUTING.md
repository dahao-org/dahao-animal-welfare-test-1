# Contributing to DAHAO Animal Welfare

This domain extends [DAHAO Core](https://github.com/dahao-org/core) for animal welfare ethics.

---

## Ways to Contribute

### 1. Add Species Profiles

Document sentience evidence and welfare requirements for species.

### 2. Add Practice Assessments

Evaluate practices against welfare principles.

### 3. Improve Terms/Principles/Rules

Propose changes to the framework itself.

### 4. Participate in Discussions

Comment on proposals, raise concerns, help synthesize.

---

## Adding a Species

### Step 1: Research

Gather evidence for sentience indicators:
- Nociceptors / pain receptors
- Stress responses (cortisol, behavior)
- Avoidance learning
- Cognitive abilities

**Minimum:** 1 source, Tier C or higher

### Step 2: Create Discussion

**Title:**
```
[SPECIES] Add @{species_name} profile
```

**Body:**
```markdown
## [THESIS]

### Species Information
- Common name: 
- Scientific name: 

### Sentience Evidence
1. [Evidence with source]
2. [Evidence with source]

### Sentience Confidence
HIGH / MEDIUM / LOW / UNKNOWN

### Welfare Requirements
- Requirement 1
- Requirement 2

### Sources
- [Author (Year)] Title. Journal. URL
```

### Step 3: Discussion & Vote

- Wait for community review (minimum 5 days)
- Address concerns in [SYNTHESIS]
- Vote (66% threshold)

### Step 4: Merge

Once accepted, species profile is added to `data/species/`

---

## Adding a Practice Assessment

### Step 1: Research

Document:
- Target species
- Biological impacts (with evidence)
- Five Freedoms assessment

### Step 2: Create Discussion

**Title:**
```
[PRACTICE] Add @{practice_name} assessment
```

**Body:**
```markdown
## [THESIS]

### Practice
- Name: 
- Description: 
- Target species: 

### Biological Impacts
1. [Impact with evidence]
2. [Impact with evidence]

### Five Freedoms Check
- [ ] Freedom from hunger/thirst
- [ ] Freedom from discomfort
- [ ] Freedom from pain/injury
- [ ] Freedom to express normal behavior
- [ ] Freedom from fear/distress

### Proposed Verdict
ETHICAL / UNETHICAL / COMPLEX / UNKNOWN

### Justification
[Why this verdict based on evidence]

### Sources
- [Author (Year)] Title. Source. URL
```

### Step 3: Discussion & Vote

- Wait for community review (minimum 7 days)
- Address concerns
- Vote (66% threshold, or 75% if changing existing verdict)

---

## Evidence Tiers

| Tier | Type | Examples |
|------|------|----------|
| S | Meta-analysis | Cochrane reviews, systematic reviews |
| A | Peer-reviewed research | Journal articles with original data |
| B | Institutional reports | FAO, WHO, academic institutions |
| C | Expert opinion | Preprints, grey literature, expert statements |
| D | Anecdotal | Personal observation, news articles |

**Minimum for proposals:** Tier C

**For removing protection:** Tier A required

---

## Locked Principles

These cannot be violated by any proposal:

**From Core:**
- `@purpose_primacy`
- `@democratic_evolution`
- `@transparency`
- `@precautionary_default`
- `@protection_asymmetry`
- `@inheritance_integrity`

**Domain-specific:**
- `@precautionary_principle`
- `@biological_primacy`
- `@sentience_axiom`

---

## Protection Ratchet

Adding species/protection: **66% consensus**

Removing species/protection: **99% consensus** (66% × 1.5)

This ensures the framework evolves toward more protection, not less.

---

## Code of Conduct

- Focus on evidence, not emotion
- Assume good faith
- Disagree with arguments, not people
- Tradition/economics don't override biology
- When uncertain, protect

---

## Questions?

Open a Discussion with `[QUESTION]` tag.
