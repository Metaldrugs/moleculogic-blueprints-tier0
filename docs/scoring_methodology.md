# Moleculogic Scoring Methodology – SEI-lite Blueprint Metrics

This document outlines the logic and reproducibility protocol for interpreting SEI-lite scores associated with Moleculogic-generated compounds. All metrics are derived using deterministic structural logic overlays defined by SEI under Pillar I: Rational Constructivism.

## 🧠 Core Scoring Axes

### 1. Entropy Score
- Range: 0.00 (fully targeted logic) to 1.00 (chaotic, unstructured activity)
- Derived via Matryoshka logic mesh across compound action domains (e.g., intercalation, redox, scaffold topology)
- Formula:
  ```
  entropy_score = Σ (subsystem_logic_variance) / total_system_paths
  ```

### 2. ROS Generation Index
- Empirical metric from logic simulation using ROS-propagating motifs (quinones, Fe²⁺ chelates, etc.)
- Range: 0.00 (no ROS generation) to 1.00 (active ROS logic under basal conditions)
- SEI factors:
  - Redox pair stability
  - Metal coordination potential
  - Membrane-localized redox cycling risk

### 3. Topoisomerase Selectivity
- Reported as separate binding affinities to Topo IIα (therapeutic) and Topo IIβ (cardiotoxic)
- Binding estimates use quantum overlay from blueprint structure logic, not docking
- Expressed as affinity ratio or normalized 0–1

### 4. Cardiac Toxicity Risk
- Composite score combining:
  - Topo IIβ affinity
  - Mitochondrial penetration index
  - ROS Index × Lipid Affinity
- Normalized to match clinical correlation thresholds (0 = silent; 1 = high risk)

### 5. Tumor Selectivity Ratio
- Ratio of logic activation (e.g., linker cleavage, redox release) under tumor vs normal physiology
- ≥1.0 indicates tumor-preferring activation logic
- Tier 2 designs aim for ≥2.0

## 📌 SEI Overlay JSON Format
Each blueprint includes:
```json
"sei_overlay": {
  "entropy_class": "Targeted",
  "entropy_score": 0.38,
  "risk_flags": [],
  "explanation": "...",
  "activation_logic": "..."
}
```

## 📎 Validation
All SEI-lite simulations are conducted using deterministic, reproducible Moleculogic modules. Logic paths are hash-locked and archived in `sei_mdcfdc_20250520_logic_snapshot.sha256`.

For replication, use:
- Blueprint JSON
- Logic explanation fields
- This scoring document
