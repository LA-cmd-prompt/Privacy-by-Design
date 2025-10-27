# Privacy-by-Design

# Why is PbD important
PbD is now a legal requirement in many jurisdictions (including under GDPR and anticipated Canadian reforms like Bill C-27), making it a foundational compliance skill.

---

## What’s Inside
-  → 7 principles of PbD with practical applications in Canadian compliance (e.g., PIPEDA) and global contexts (e.g., GDPR).
- → A scenario showing PbD could be applied in practice 

# Privacy by Design – HealthTrack App

## Introduction
 **Privacy by Design (PbD)** is applied to the fictional **HealthTrack App**, a Canadian mobile fitness and diet tracker.  Since HealthTrack processes **personal health information** (sensitive data under PIPEDA), PbD principles must be embedded at every stage of the product lifecycle.

---

## ⚙️ The 7 Foundational Principles of PbD Applied

### 1. Proactive, not Reactive
- Privacy risks identified **before launch** through a [Privacy Impact Assessment (PIA)](https://github.com/LA-cmd-prompt/Privacy-Impact-Assessment)
  
- Regular privacy reviews scheduled at each product sprint.  
  *Outcome:* Issues like over-collection of data flagged early, saving redesign costs.

---

### 2. Privacy as the Default
- HealthTrack collects only what’s strictly necessary (steps, calories).  
- Extra features (GPS location, photo uploads) are **OFF by default** until the user opts in.  
  *Outcome:* Users are protected even if they take no action.

---

### 3. Privacy Embedded into Design
- Privacy team sits in on product design sprints.  
- Data minimization and retention policies are documented alongside technical specs.  
  *Outcome:* Privacy becomes a design decision, not an afterthought.

---

### 4. Full Functionality — Positive-Sum, not Zero-Sum
- Users who decline optional features (like GPS tracking) can still enjoy full app functionality.  
- Privacy choices enhance trust without limiting usability.  
  *Outcome:* Business value and privacy coexist.

---

### 5. End-to-End Security — Lifecycle Protection
- All personal data encrypted at rest and in transit.  
- Data auto-deletes after 12 months of inactivity.  
- Access controls ensure only authorized staff see anonymized datasets.  
  *Outcome:* Data protected from collection to disposal.

---

### 6. Visibility and Transparency
- In-app prompts explain why data is collected at the moment it’s needed.  
- Privacy policy written in **plain language** (no legal jargon).  
  *Outcome:* Users know what’s happening with their data — no surprises.

---

### 7. Respect for User Privacy
- Users can **export, correct, or delete their data** at any time.  
- “Download My Data” and “Delete Account” options built into the app.  
  *Outcome:* Aligns with PIPEDA’s access and correction rights.

---

## Supporting Deliverables
This guide is supported by additional artifacts in this repo:
- **`pia-template.docx`** → Privacy Impact Assessment conducted before launch.  
- **`data-flow-diagram.png`** → Map of how HealthTrack data moves and where it’s stored
- ![System Data Flow Diagram](https://github.com/LA-cmd-prompt/images-.gitkeep/blob/main/privacy-data-flow-diagram.jpeg)
- **`mock-screenshots/`** → Settings, consent prompts, and risk matrix for visual demonstration.

---
### When to Conduct a PIA

 **PIA must be conducted for:**
- New systems that process personal data
- Significant changes to existing systems
- High-risk data processing activities
- Processing of sensitive data (health, financial, biometric)
- Large-scale data processing operations
- Use of new technologies (AI, facial recognition)
- Cross-border data transfers

## 📚 Additional Resources

- [PIPEDA Overview](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/)
- [GDPR DPIA Guidelines](https://gdpr.eu/data-protection-impact-assessment-template/)
- [ISO 27001 Standards](https://www.iso.org/isoiec-27001-information-security.html)
- [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

---

⚡ *Built as part of the Privacy by Design case study by [LA-cmd-prompt](https://github.com/LA-cmd-prompt).*

---

## Skills Demonstrated
- Translating privacy principles into **operational strategies**  
- Applying PbD to **Canadian compliance frameworks (PIPEDA, CASL)**  
- Designing processes that integrate privacy risk management into day-to-day operations  

---

## Next Steps
This PbD example ties into my **DPIA** and **PIA** projects, which show how I operationalize privacy through structured risk assessments.  
