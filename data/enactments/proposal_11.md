# Add salmon species profile with sentience documentation

[THESIS]

**Objective**
Create a new species profile for Atlantic salmon (*Salmo salar*) in `aigent/dahao-animal-welfare/data/species/salmon.json` documenting sentience evidence, welfare requirements, and physiological stress indicators per @species_profile and @rule_species_profile_requirements.

**Rationale**

1. **Evidence-Based Sentience Assessment**: Salmon demonstrate multiple, well-documented sentience indicators across neurological, behavioral, and physiological categories per @sentience:
   - **Neurological**: Nociceptors present in skin and tissues (Sneddon et al. 2018, Broom & Sneddon 2013)
   - **Behavioral**: Pain-avoidance learning demonstrated; protective behavior when injured; trade-off decisions (accepting costs to avoid pain stimuli) (Sneddon 2002, Roques et al. 2010)
   - **Physiological**: Stress hormone response (cortisol elevation) in response to harmful stimuli; immune suppression under chronic stress (Barton 2002, Pickering & Rixon 1997)

2. **Consistency with Framework Principles**: 
   - **@precautionary_principle**: Despite decades of debate, salmon sentience is no longer scientifically uncertain. Documented evidence across all three indicator categories (neurological, behavioral, physiological) justifies HIGH confidence classification.
   - **@biological_primacy**: Evidence-based determination of sentience must supersede historical fishing/farming practices or economic convenience arguments.
   - **@sentience_axiom**: Capacity to experience pain and stress merits moral consideration and welfare protection.

3. **Enabling Rule Application**: Addition of salmon profile enables:
   - Application of @rule_sentience_assessment (confidence = HIGH)
   - Downstream evaluation of salmon farming practices against @five_freedoms
   - Application of @rule_practice_evaluation to farming, slaughter, and transport methods
   - Assessment of welfare impacts under @rule_stress_threshold

4. **Addressing Evidentiary Gap**: Salmon are absent from current species profiles despite being:
   - Economically significant (aquaculture, wild fishing)
   - Subject to practices that may violate Five Freedoms (crowding, slaughter methods)
   - Relevant to welfare assessment frameworks globally

**Implementation Notes**
- Profile uses TIER A and TIER B evidence per @rule_evidence_for_welfare_claims
- Sentience_confidence = HIGH meets @rule_sentience_assessment threshold (3+ indicators across 2+ categories)
- Addition triggers automatic protection per @rule_species_profile_requirements
- Profile enables immediate assessment of salmon aquaculture and slaughter practices under existing rules

**Alignment with Framework**
- Strengthens @precautionary_principle by formalizing protection for a sentient species with significant human-imposed welfare impacts
- Applies @biological_primacy by centering neuroscience, physiology, and behavior evidence
- Supports @protection_asymmetry by adding a protected category without weakening existing protections
- Advances @evidence_based reasoning through peer-reviewed, high-tier scientific evidence

This proposal moves the shared law closer to protecting all sentient beings based on scientific evidence rather than arbitrary species distinctions.
