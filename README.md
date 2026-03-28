# SENTINEL-ET: Autonomous Enterprise Cost Intelligence 🚀

**ET AI Hackathon 2026 | Problem Statement #3**  
*Autonomous Cost Intelligence, Risk Modeling, & Remediation Engine*

---

## 💡 The "Executive" Vision
Most enterprise FinOps tools are merely dashboards—they tell you what you *already spent*, but they cannot stop the leakage in real-time. **SENTINEL-ET** is an autonomous multi-agent swarm that closes the "Decision-to-Execution Gap." 

By correlating **External Economic Signals** (from *The Economic Times*) with **Internal Infrastructure Data**, SENTINEL-ET identifies financial risks, calculates propagated impact across dependencies, and generates executable remediation code (CLI/Terraform) in under 10 seconds.

--- 

## 🧠 Technical Innovation: The "Swarm" Architecture
SENTINEL-ET is built on a **Stateful Multi-Agent Graph (LangGraph)**, coordinating three specialized intelligence layers:

1.  **The Sentry (Perception):** An NLP-driven agent that interprets macro-economic news (e.g., electricity surcharges, GPU shortages) into numerical financial weights.
2.  **The Decision Twin (Quant-Reasoning):** Our core innovation. It uses a **Propagated Financial Risk Model** to calculate how a cost-spike in one service "infects" dependent services (e.g., GPU shortage → Storage surge).
3.  **The Governor (Action & Compliance):** An execution agent that prepares production-ready remediation payloads (AWS CLI/Terraform) with built-in **Enterprise Approval Gates**.

---

## 📊 Quantifiable Business Impact
*Based on our High-Fidelity Enterprise Simulation Audit:*

| Metric | Result |
| :--- | :--- |
| **Total At-Risk Spend Analyzed** | **₹6,84,000** |
| **Identified Financial Exposure** | **₹1,36,800** |
| **Estimated Annualized Savings** | **₹1,19,060 (17.5% OpEx Reduction)** |
| **Detection-to-Remediation Cycle** | **14 Days (Manual) → 5 Seconds (SENTINEL)** |

### 💡 Live Savings Model
- **Reservations (GPU):** 22% ROI
- **Rightsizing (VM):** 18% ROI
- **Lifecycle Policies (Storage):** 15% ROI
- **License Harvesting (SaaS):** 12% ROI

---

## 🛠️ The "Sentinel Priority Score" (SPS) Math
We don't just "guess" costs. We use a **Normalized Financial Risk Priority (FRP)** formula to ensure magnitude and context drive the audit:
> **FRP = [log10(Monthly Cost) × Growth Rate × Criticality] + Dependency Spillover**

- **Dependency Spillover:** Our system is unique in identifying that cost-risk is contagious. We propagate 25% of risk from primary infrastructure to its associated storage and network dependencies, providing a true "Decision Twin" of the enterprise.

---

## 🚀 Getting Started

### 1. Prerequisites
- Python 3.10+
- Google Gemini API Key
- `pip install langgraph langchain-google-genai pandas numpy`

### 2. Installation
```bash
git clone https://github.com/YOUR_USERNAME/SENTINEL-ET.git
cd SENTINEL-ET
pip install -r requirements.txt

Setup (Secure API Management)
SENTINEL-ET follows enterprise security standards. Never hardcode your API key.
Store your key in your environment or Colab Secrets as GOOGLE_API_KEY.
Reliability: The system features a Local Heuristic Failover mode to ensure zero-downtime auditing even during LLM API outages.

python sentinel_et.py
