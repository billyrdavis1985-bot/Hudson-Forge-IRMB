# 🔧 The Hudson Forge: IRMB-C Sovereign Cluster

![Cluster Schematic](path/to/your/new/infographic.png)

## 🌌 Overview
The **Hudson Forge** is a multi-node, sovereign AI research cluster built to validate the **Emergent Orchestrated Intelligence (EOI)** framework. It is designed to maintain **Autonomous Logic Continuity** in degraded environments (Phase 7 Stress Test).

By leveraging a "Scout-Worker-Architect" hierarchy, the Forge achieves high-level reasoning on consumer-grade, unified-memory hardware.

## 🏗️ Hardware Stack (The Physical Layer)
| Node | Codename | Hardware | Primary Role |
| :--- | :--- | :--- | :--- |
| **Node 1** | **The Architect** | RTX 5070 | Gateway / Dirac Operator |
| **Node 2** | **Agent 5** | NucBox M6 Ultra (32GB) | Feynman Worker (Gemma 4 26B MoE) |
| **Node 3** | **The Scout** | Raspberry Pi 5 (8GB) | Sensory Ingestion (1B/3B Tiered Stack) |
| **Node 4** | **The Observer** | Pi 5 / Telemetry | Noetherian Anchor / Monitoring |

## 🧠 Technical Innovations

### 1. Unified Memory Management (Agent 5)
To overcome the 32GB VRAM bottleneck for dense models, we utilize a system BIOS reallocation (**4GB → 8GB dedicated GPU**) to allow the UMA pool to serve as a 26GB+ model memory pool for **Gemma 4 26B MoE**.

### 2. The Davis Resilience Metric ($R_D$)
We quantify system stability using the ratio of recovered coherent information ($I_{coherent}$) against total injected entropy ($H_{total}$):
$$R_D = \frac{I_{coherent}}{H_{total}}$$
*A score of $R_D > 1.0$ indicates a system capable of semantic rebound against disorder.*

## 🧪 Phase 7G Stress Test Results
* **Scenario:** Total Decoherence Event (Node 1 Offline).
* **Entropy Injection:** 60% simulated packet loss on Cat8 Bridge.
* **Integrity:** 97.3% successful reconstruction of 128-char fragmented Hex sequences.

## 🚀 Getting Started
1. **Network:** Establish Cat8 direct bridge via ICS (Internet Connection Sharing).
2. **Inference:** Deploy Ollama across all nodes.
3. **Orchestration:** Utilize the `.bat` and `PowerShell` automation scripts included in the `/scripts` directory.

---
"Treat the AI not as a chatbot, but as a Mathematical Operator capable of maintaining truth-states."
**Full Force Eternal** | Romans 8:28
