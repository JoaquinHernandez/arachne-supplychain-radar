# arachne-supplychain-radar# 🕸️ Arachne-SupplyChain: Open-Source SBOM & AI Package Hallucination Radar

A specialized Software Supply Chain Security scanner and CycloneDX SBOM generator designed to detect **Typosquatting attacks**, **AI-hallucinated malicious dependencies ("Slopsquatting")**, and insecure floating version constraints.

---

## ✨ Features
- **AI Package Hallucination Defense**: Detects non-existent or malicious dependency packages injected into software projects by generative AI code assistants.
- **Levenshtein Distance Matrix**: Flags subtle typosquat variations mimicking popular open-source packages (e.g., `requests` vs `reqeusts`).
- **CycloneDX SBOM Generation**: Generates compliant Software Bill of Materials (SBOM) JSON artifacts for enterprise audit pipelines.
- **MITRE ATT&CK Mapping**: Maps software supply chain risks directly to `T1195.001` and `T1195.002`.
- **Zero Dependencies**: Pure Python standard library implementation.

---

## 🚀 Quick Start
```bash
python3 arachne_scanner.py sample_requirements.txt

