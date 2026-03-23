# Hydra One: Green Hydrogen Catalyst Candidates 🌱⚡

Welcome to the **Hydra One** computational reproducibility and review packet. This repository serves as a bounded, advisory-only computational lane for green-hydrogen catalyst discovery. It contains a rigorously reviewed set of four top catalyst candidates, surrogate structure artifacts, and verifiable proof of existence (Prior Art) anchored on the blockchain.

## 🎯 Objective & Target Framing

The objective of this project is to screen bounded alkaline/AEM-adjacent oxygen-evolution catalyst candidates for green hydrogen production. Candidates were ranked based on a multi-factor score including activity, durability, cost efficiency, corrosion resistance, and manufacturability. 

**Target Parameters:**

* **Electrolyzer family:** AEM
* **Catalyst focus:** Anode oxygen evolution
* **Electrolyte environment:** Alkaline
* **Current density target:** 0.88 A/cm²
* **Maximum overpotential:** 395 mV
* **Durability target:** 1850 h
* **Max. critical mineral intensity:** 0.30

## 🏆 Top Four Candidates

After screening 24 initial candidates down to 13 review-grade candidates, the following four emerged as the strongest computational candidates. Below are their specific target parameters and surrogate formulas based on our multi-factor scoring:

### 1. Variant 15: `mn_fe_oxyhydroxide`

* **Candidate ID:** `hydra-one-candidate:d81b09a7-d630-42bc-ba32-87c2b7d69e74`
* **Surrogate Formula:** `MnFeO2H`
* **Simulated Metrics (per Variant):**
  * Current density achieved: `0.94 A/cm²`
  * Overpotential: `382 mV`
  * Durability projection: `1950 h`
  * Critical mineral intensity: `0.24`
* **Normalized Performance Scores:**
  * Activity: `0.91` | Durability: `0.88` | Cost Efficiency: `0.74` | Corrosion Resistance: `0.90` | Manufacturability: `0.75`

### 2. Variant 14: `co_free_spinel_oxide`

* **Candidate ID:** `hydra-one-candidate:19d4cfe8-e774-4604-96ce-76b58b6143c1`
* **Surrogate Formula:** `Fe3O4`
* **Simulated Metrics (per Variant):**
  * Current density achieved: `0.91 A/cm²`
  * Overpotential: `387 mV`
  * Durability projection: `2010 h`
  * Critical mineral intensity: `0.27`
* **Normalized Performance Scores:**
  * Activity: `0.89` | Durability: `0.90` | Cost Efficiency: `0.72` | Corrosion Resistance: `0.91` | Manufacturability: `0.74`

### 3. Variant 13: `ni_fe_layered_hydroxide`

* **Candidate ID:** `hydra-one-candidate:6214a8e7-3d9a-416d-8a9e-5eaa3028f2ae`
* **Surrogate Formula:** `Ni2FeO6H6`
* **Simulated Metrics (per Variant):**
  * Current density achieved: `0.92 A/cm²`
  * Overpotential: `385 mV`
  * Durability projection: `1940 h`
  * Critical mineral intensity: `0.28`
* **Normalized Performance Scores:**
  * Activity: `0.90` | Durability: `0.88` | Cost Efficiency: `0.71` | Corrosion Resistance: `0.89` | Manufacturability: `0.76`

### 4. Variant 3: `ni_mo_nitride`

* **Candidate ID:** `hydra-one-candidate:a5939696-2103-4254-a688-305c7747cc39`
* **Surrogate Formula:** `Ni2Mo3N`
* **Simulated Metrics (per Variant):**
  * Current density achieved: `0.99 A/cm²`
  * Overpotential: `368 mV`
  * Durability projection: `1720 h`
  * Critical mineral intensity: `0.15`
* **Normalized Performance Scores:**
  * Activity: `0.94` | Durability: `0.78` | Cost Efficiency: `0.76` | Corrosion Resistance: `0.79` | Manufacturability: `0.74`

> **Note:** This packet represents a strong computational basis for follow-on scientific discussion. It does not yet claim physical synthesis readiness or experimentally confirmed crystal truth.

## 🔬 How To Use This Packet

This packet is designed as a **computational discovery accelerator and peer-review mechanism**. Researchers and reviewers can leverage this repository in five distinct ways:

* **1. Crystallographic Analysis (3D Visualization):** The `.cif` files inside the `evidence_bundle` contain the exact atomic 3D structures and lattices. These can be opened directly in visualization software (e.g., VESTA, Avogadro, or PyMOL) for visual inspection.
* **2. Advanced Simulation & DFT Routing:** Researchers can bypass early trial-and-error by feeding these `.cif` structures into high-fidelity physical simulators (e.g., VASP, Quantum ESPRESSO). This allows independent teams to conduct their own deep Density Functional Theory (DFT) analyses on the Gibbs Free Energy profiles of the oxygen evolution reaction (OER).
* **3. Wet-Lab Synthesis Guidance:** If theoretical experts validate these calculations, the specific stoichiometries, binder fractions, and support combinations provide explicit starting points for a chemist to synthesize the materials in a real wet-lab (e.g., via co-precipitation) for physical AEM testing.
* **4. AI Decision Logic Auditing:** Reviewers can inspect the JSON files (such as `hydra-one-campaign.json`) to audit *why* the Hydra One system selected these top 4 candidates out of the initial 24, examining the algorithmic trade-offs made between durability, cost, and efficiency. The entire pipeline can be cryptographically reproduced using `scripts/reproduce_bundle_outputs.mjs`.
* **5. Intellectual Property & Prior Art:** The Base L2 blockchain anchor serves as an immutable mathematical timestamp (Proof of Existence). This protects the public domain by acting as verifiable open Prior Art, preventing external entities from inappropriately patenting these specific simulated architectural designs.

## 📂 Repository Structure

* `briefing/`: Human-readable executive summaries, candidate details, and review guidelines.
* `evidence_bundle/computational_repro_bundle_2026-03-23/`: Machine-readable evidence, surrogate relaxations, and final CIF files for the top candidates.
* `attachments/`: Ready-to-send ZIP archives (if applicable).

### 🚀 Recommended Review Path

If you are a reviewer, please start by inspecting:

1. `00_START_HERE.md`
2. `briefing/01_EXECUTIVE_SUMMARY.md`
3. `briefing/02_CANDIDATE_SUMMARY.md`
4. `briefing/03_HOW_TO_REVIEW.md`

## ⛓️ Blockchain Anchoring (Prior Art)

To establish verifiable prior art and proof of existence, the exact state of this public release has been hashed and anchored to the **Base L2 Blockchain (Ethereum)**. 

* **Archive Name:** `hydra_one_professor_github_packet_2026-03-23.zip`
* **SHA256 Hash:** `070ad1f7505f5390f926d29154597f5781509f4a613fc081efb28a3d03b7f992`
* **Base L2 TX ID:** [`0x6dc3013d2ed76da1cdd66731e70d0aad40710d8622e8835ee7a7e4241d7f299d`](https://basescan.org/tx/0x6dc3013d2ed76da1cdd66731e70d0aad40710d8622e8835ee7a7e4241d7f299d)
* **Block Number:** `43734327`

By verifying the SHA-256 integrity of the release against the blockchain transaction, experts can mathematically prove that this technical teaching was publicly available and enabling at the time of the block timestamp.

## 📜 License

This repository uses a **Dual License** approach for Open Science:

* All source code and scripts are licensed under the **MIT License**.
* All scientific data, structures, and CIF files are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Please see the `LICENSE.md` file for full details.
