# AI-Identity-Fraud-Guardrails
The "Deepfake Guard" Identity Vault: This project implements a Defense-in-Depth protocol. If the AI detects a "low-confidence" liveness score or a high-value transaction, it automatically triggers an Out-of-Band (OOB) verification to a known physical device.
# 🛡️ AI-Identity-Fraud-Guardrails (KYC-Shield)
**Mitigating Deepfake Injection Attacks in Financial Onboarding**

### 📊 The Problem
Standard KYC "Selfie" checks are now vulnerable to high-fidelity deepfakes. Attackers use virtual cameras to inject synthetic video into banking apps, bypassing traditional biometric matching.

### 🎯 The Solution
This project implements a **Multi-Modal Identity Security Protocol** aligned with **NIST SP 800-63 (IAL3)**. It moves beyond simple face-matching by layering **Metadata Forensics** and **Out-of-Band (OOB)** verification.

### 🛠️ Key GRC Logic:
* **Liveness-to-Risk Mapping:** If the AI liveness score drops below 0.90, the system automatically escalates the case to a human auditor.
* **Out-of-Band (OOB) Verification:** Prevents "Man-in-the-Browser" deepfake attacks by requiring verification from a secondary, physical device.
* **Metadata Forensic Audit:** Uses LLM-based analysis to detect "Synthetic Markers" (missing EXIF data, software rendering signatures) in user-submitted IDs.

### 💼 Professional Context
Developed by a **Series 7 & 2-15 licensed professional**. This tool doesn't just "detect faces"; it protects **Institutional Integrity** and prevents **AML (Anti-Money Laundering)** violations caused by synthetic identities.
