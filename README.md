# Pulmo-M: Micro-capillary respiratory gas chromotography manifold
An OSHWA-Compliant, open-source microfluidic manifold engineered for non-invasive point-of-care lung disease screening and diagnostic differentiation of common and rare lung pathologies.

---

## Engineering & Clinical Thesis
Pulmo-M targets the critical clinical challenge of diagnostic overlapping. Common respiratory conditions (Asthma and COPD) share almost identical physical symptoms with rare, life-threatening pulmonary pathologies.

Traditional point-of-care diagnostics measure airflow volume rather than chemical composition. Pulmo-M isolates unique **Volatile Organic Compound (VOC) biomarker fingerprints** directly from human breath to differentiate these conditions instantly at the bedside.

---

## Hardware Architecture & Design Specs

### 1. Fluid Dynamic Path
* **Sample Chamber:** A 12 mm internal low-backpressure chamber optimized for sorbent trapping materials to concentrate ultra-trace VOCs from single exhalations.
* **Transfer Vias:** Micro-capillary routing channels engineered with strict boundary controls to prevent gas-cloud peak broadening during sample migration.

### 2. Mechanical Assembly & Tolerance Strategy
* **Airtight Sealing:** Uses a 0.5 mm recessed structural pocket to perfectly seat non-outgassing Teflon face gaskets, preventing atmospheric contamination or VOC leaking.
* **Fastener Pattern:** Uniform pressure distribution across the fluidic path is maintained using high tolerance M2.5 machine fasteners.
* **Thermal Efficiency:** Engineered using a lightweight lug flange geometry to minimize total thermal mass, allowing rapid temperature cycling for high throughput clinic deployments.

---

## Open Source Hardware Distribution
* **CAD Formats:** Fully Editable '.Step' and '.STL' geometric configurations are located in the '/Hardware' directory.
* **Production BOM:** Full hardware components, including exact fastener classifications and material requirements, are indexed in '/Documentation/Bill_of_Materials.csv'.
* **Hardware Licensing:** Distributed under the **CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S-2.0)**
* **Documentation Licensing:** Creative Common Attribution 4.0 International (CC BY 4.0) 
