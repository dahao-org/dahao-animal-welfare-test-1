# DAHAO Animal Welfare

**A living framework for evidence-based animal ethics**

---

## Purpose

> **Minimize animal suffering through evidence-based ethics.**

This DAHAO domain applies the universal governance framework to animal welfare, providing:

- **Terms** defining sentience, suffering, welfare, and related concepts
- **Principles** establishing ethical foundations (precautionary principle, biological primacy)
- **Rules** for making ethical judgments about species and practices

---

## Inheritance

```
dahao-org/core v1.0.0
        │
        └── dahao-org/animal-welfare v1.0.0 (this repo)
                │
                ├── Inherits: All core governance
                └── Adds: Animal-welfare-specific ethics
```

This domain inherits all locked principles from [DAHAO Core](https://github.com/dahao-org/core):
- `@purpose_primacy`
- `@democratic_evolution`
- `@transparency`
- `@precautionary_default`
- `@protection_asymmetry`
- `@inheritance_integrity`

---

## Domain-Specific Components

### Terms (`data/terms.json`)

Animal welfare vocabulary:
- `@sentience` — Capacity for subjective experience
- `@suffering` — Prolonged negative affective state
- `@welfare` — Physical and psychological wellbeing
- `@nociception` — Pain sensing mechanisms

### Principles (`data/principles.json`)

Ethical foundations:
- `@precautionary_principle` — Assume sentience when uncertain
- `@biological_primacy` — Evidence over tradition
- `@five_freedoms` — Baseline welfare requirements
- `@sentience_axiom` — Pain capacity = moral relevance

### Rules (`data/rules.json`)

Decision procedures:
- `@rule_sentience_assessment` — How to evaluate sentience
- `@rule_practice_evaluation` — How to judge practices
- `@rule_protection_trigger` — When protections apply

---

## How It Works

### Assessing a Species

```
INPUT: "Does species X deserve welfare consideration?"

PROCESS:
1. Check for sentience evidence (nociceptors, behavior, stress response)
2. Apply @precautionary_principle if uncertain
3. Apply @rule_sentience_assessment

OUTPUT: Protection status + confidence level
```

### Evaluating a Practice

```
INPUT: "Is practice Y ethical?"

PROCESS:
1. Identify affected species
2. Check against @five_freedoms
3. Apply @rule_practice_evaluation
4. Check @biological_primacy (no tradition/economic override)

OUTPUT: Ethical verdict + violations + recommendations
```

---

## Knowledge Base

As the community contributes, knowledge accumulates:

```
data/
├── species/          # Species profiles with sentience evidence
│   ├── octopus.json
│   ├── chicken.json
│   └── ...
│
└── practices/        # Practice assessments
    ├── battery_cages.json
    ├── live_boiling.json
    └── ...
```

---

## Contributing

This domain evolves through the same governance as core:

1. **Propose** — GitHub Discussion with evidence
2. **Discuss** — Dialectic process (thesis → antithesis → synthesis)
3. **Vote** — Community consensus
4. **Merge** — Versioned change

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## Version

**Current Version:** v1.0.0

| Component | Version |
|-----------|---------|
| Terms | 1.0.0 |
| Principles | 1.0.0 |
| Rules | 1.0.0 |
| Inherits Core | 1.0.0 |

---

## Links

- **DAHAO Core**: [github.com/dahao-org/core](https://github.com/dahao-org/core)
- **Whitepaper**: [DAHAO: A Living Framework for Collaborative Ethical Evolution](https://github.com/dahao-org/core/blob/main/WHITEPAPER.md)
- **Discussions**: [GitHub Discussions](https://github.com/dahao-org/animal-welfare/discussions)

---

## License

CC BY-SA 4.0 — Share and adapt with attribution.
