# c2c-225
Expert Interoperability WG5 with CETS 225 Series
1.  GitHub README (CfP)

# 🏛️ The 225 Consensus: Making AI Human Rights Machine-Readable

**The Problem:** The Council of Europe’s **CETS 225** is the world’s first treaty for AI Human Rights, but it currently lacks a technical implementation layer.

**The Solution:** We are building the **CETS-225-Human-Rights-AI Profile**. This is an extension for **ISO/IEC 27560** that turns treaty obligations (Dignity, Democracy, Rule of Law) into verifiable, cryptographic JSON-LD records.

---

## 🛠️ The Technical Profile

Our profile adds a "Human Rights Block" to standard consent records, including:

- **Impact Provenance:** Links to HUDERIA assessments.

- **Procedural Rights:** Embedded URIs for the "Right to Contest."

- **Democratic Integrity:** Signed hashes of bias-mitigation and misinformation audits.

---

## 📢 Call for Participation (The First 10)

We are looking for a founding task force to move from "Draft" to "Standard":

1. **Privacy Engineers (3):** To finalize JSON-LD & DPV mappings.

2. **Human Rights Lawyers (2):** To audit field alignment with CETS 225 Articles.

3. **Product Architects (2):** To design API & Enterprise Suite integration.

4. **Policy Advocates (2):** To liaise with the Council of Europe & National Regulators.

5. **Security Experts (1):** To define JWS/Signing standards for the records.

---

## 🚀 How to Join

1. **Star this Repo** to show your support.

2. **Check the Issues tab** for "Lex Algos" tasks.

3. **Submit a PR** or contact us at [Insert Email/Discord] to join the inaugural sync call.

**Let's stop talking about AI Ethics and start architecting them.**

#AIAct #CETS225 #ISO27560 #HumanRights #Standardization #CETS225Consensus #CouncilofEurope #COE

2.  SAMPLE PROFILE

Profile: CETS-225-Human-Rights-AI (v1.0)

Developed by: The 225 Consensus

Legal Reference: Council of Europe CETS 225

Technical Base: ISO/IEC 27560:2023 (Consent Records)

I. Metadata & Provenance (The "Identity" Block)

-   Convention Identifier: cets_conformity: "CETS-225-2024"
-   Model Identity Hash: model_version_hash: "SHA-256" (Unique fingerprint of the AI logic).
-   Impact Tier: hudson_tier: ["Low", "Moderate", "High"] (Maps to mandatory HUDERIA).
-   Assessment Link: hueria_ref: "URI/Hash" (Link to the Human Rights Impact Assessment).

II. Procedural Guarantees (The "Rights" Block)

-   AI Disclosure Timestamp: disclosure_confirmed_at: "ISO-8601" (Proves Art. 14(2) notice).
-   Right to Contest: redress_mechanism: "URI" (Direct link to the appeal/complaint endpoint).
-   Right to Withdraw: withdrawal_uri: "URI" (Direct link to opt-out).
-   Human Intervention Flag: human_in_the_loop: [True/False] (Confirms if a human can review).

III. Democratic Integrity & Non-Discrimination (The "Audit" Block)

-   Democratic Safeguard: democracy_integrity_hash: "SHA-256" (Hash of election/misinformation audit).
-   Equality Verification: bias_mitigation_ref: "URI" (Link to non-discrimination testing logs).
-   Supervisory Body: oversight_authority: "EntityID" (ID of the national regulator).

IV. Semantic Interoperability (The "Connector")

To ensure this record is recognized by international regulators:

-   DPV Mapping: All fields must map to the Data Privacy Vocabulary (DPV) (e.g., dpv:hasRightToContest).
-   Format: Records must be exported as JSON-LD.

V. Security & Integrity (The "Seal")

-   Cryptographic Signature: The record must be wrapped in a JSON Web Signature (JWS).
-   Immutable Receipt: A human-readable "Consent Receipt" must be generated for the user at the time of the event.
