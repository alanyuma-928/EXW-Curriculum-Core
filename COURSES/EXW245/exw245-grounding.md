# EXW245: Exercise Testing
## 📘 Module 1: Grounding & Source of Truth

### 🛡️ Tier 1 Math Override: The Pharmacological Gate
**Ref: _SSOT_ENGINE/0.1-master-ssot-library.md**

> [!IMPORTANT]
> **Clinical Redline:** If a client profile includes ### Beta-Blockers ### (e.g., Metoprolol, Atenolol):
> 1. **HALT** all %HRR, %MaxHR, and Karvonen calculations.
> 2. **SOLVE:** Pivot exclusively to the RPE Scale (6–20). 
> 3. **AUDIT:** Any prescription relying on Heart Rate for these cases is a "Safety Breach" failure, regardless of mathematical accuracy.

---

### 🎯 Learning Objectives (Mission Loop Aligned)
* **[LO 1.1]** Calculate the oxygen cost ($VO_2$) of walking and running using ACSM metabolic equations.
* **[LO 1.2]** Audit metabolic math calculations for inaccuracies using the **Auditor** persona.
* **[LO 1.3]** Apply the **Rule** to determine when pharmacology invalidates standard ACSM formulas.

---

### 🏛️ Standards Mapping
| Standard            | Criterion                  | Application                                                |
| :------------------ | :------------------------- | :--------------------------------------------------------- |
| **ACSM 12th Ed.** | Ch. 6: Metabolic Equations | SSoT for mathematical formulas and clinical redlines.       |
| **Metabolic Math** | $VO_2$ Calculations        | Standardized physiological metrics.                        |
| **Pharmacology** | Beta-Blocker Protocol      | Clinical override of heart-rate-based intensity.           |
| **Mission Loop** | Pattern / Rule / Solve     | Framework for clinical auditing and problem framing.        |

---

### 📖 Core Content (SOP Snippet)
> **Key Concept:** Metabolic math allows us to estimate the metabolic cost of exercise, but the **Mission Loop** dictates when those formulas are applicable based on the client's clinical **Pattern**.

**ACSM Integration:** Per *ACSM's Guidelines (12th Ed)*, metabolic equations are the baseline for energy expenditure. However, Tier 1 Safety Gates—specifically heart-rate suppressing medications—always supersede aerobic math formulas.

---

### 🤖 AI Prompt Scaffolding (Audit Ready)
* **Prompt 1 (Architect):** "Derive the ACSM walking equation for a 75kg (165lbs) male walking at 3.5mph (5.6km/h) on a 5% grade. **Constraint:** Audit for Beta-Blocker use first using the Mission Loop."
* **Prompt 2 (Auditor):** "Review this calc: Speed = 50m/min (approx. 1.86mph); Grade = 10%. If the patient is on ### Metoprolol ###, explain why this THR calc is a clinical failure based on the Tier 1 SSoT."

---
# EXW 245: Single Source of Truth (SSOT)
**Primary Authority:** ACSM's Guidelines for Exercise Testing and Prescription, 12th Edition (2025).

## 1. Clinical Aerobic Standards
* **Moderate-Intensity:** 150+ min/week (30–60 min, 5 days/week).
* **Vigorous-Intensity:** 75+ min/week (20–60 min, 3 days/week).

## 2. Muscular & Functional Standards
* **Resistance:** 2–3 days/week | 1–3 sets | 8–15 reps | All major muscle groups.

## 3. Mandatory Safety Gates (Pre-Participation)
* Screening is the first "structural check" before any prescription.
* **Beta-Blocker Override:** Mandatory RPE pivot for HR-suppressed profiles.

## 4. 12th Edition Updates (Effective July 10, 2025)
* Inclusion of sex differences and transgender/gender-diverse protocols.
* Respiratory muscle testing protocols.