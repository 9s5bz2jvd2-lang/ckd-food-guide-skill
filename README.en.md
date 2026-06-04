# Nutrition Science | CKD Food Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Chronic Kidney Disease (2024 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Chronic Kidney Disease (2024 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Stage-specific dietary guidance**: CKD stages 1–2 (normal protein for prevention) → stages 3–5 non-dialysis (low protein, 0.6 g/kg/day) → dialysis stage (higher protein, 1.0–1.2 g/kg/day)
- Dietary-nutrition principles covering all CKD stages, emphasizing integrated management of protein, sodium, potassium, and phosphorus
- **TCM dietary support**: 7 syndrome patterns (qi deficiency / blood deficiency / yin deficiency / yang deficiency / dampness / heat / stasis) plus symptom-oriented dietary formulas
- **Regional menus**: 7 regions × 3 stages × 4 seasons = 84 complete meal plans with sodium, potassium, and phosphorus data
- **Nutrition-data annotations**: each menu includes energy, protein, fat, carbohydrate, sodium, potassium, and phosphorus
- **Quick nutrient tables for common foods**: sodium, potassium, phosphorus, protein, and phosphorus/protein ratio
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Protein (CKD stages 3–5, non-dialysis) | 0.6 g/kg/day | For 60 kg, about 36 g; roughly the amount in half a jin of tofu |
| Protein (dialysis stage) | 1.0–1.2 g/kg/day | For 60 kg, about 60–72 g; more high-quality protein is needed |
| Sodium | <2 g/day (<5 g salt) | About one beer-bottle cap of salt |
| Potassium (stages 3–5) | Adjust according to blood potassium | High-potassium fruits and vegetables may need restriction |
| Phosphorus (stages 3–5) | <800 mg/day | Avoid animal organs, nuts, and cola |
| Salt | <5 g/day | About one beer-bottle cap |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~10 | Ten dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-11~12 | Appendix knowledge: food nutrient quick-reference tables and exchange tables | Appendices 1–2 |
| KPK-13 | Disease background and TCM understanding | Preface + disease characteristics |

## File Structure

```text
- ckd-SKILL.md: Main skill entry file
- ckd-skill.yaml: Metadata configuration
- ckd-system_prompt.md: System prompt
- ckd-knowledge_base.md: Merged knowledge base
- ckd-kpk_principles.md: KPK-01~10 dietary-nutrition principles
- ckd-kpk_appendix.md: Appendices 1–2 data tables
- ckd-kpk_disease_qa.md: Disease background + TCM + Q&A
- ckd-recipes_all.md: Collection of 84 menus
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medical diagnosis or medication treatment.
2. The intended population is adults with CKD stages 1–5; it is not intended for children, pregnant women, or patients with acute kidney injury.
3. Patients with CKD stage 3 or above should consider blood potassium, phosphorus, uric acid, and other indicators, and select dietary formulas under medical guidance.
4. Food-medicine substances should be used under professional guidance and not taken in excessive amounts.
5. CKD patients with diabetes, hypertension, cardiovascular disease, or other conditions should receive integrated management under relevant specialists.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
