ñ
# 🌊 Phenomenological Tokenizer

An experimental, context-aware NLP tokenizer that calculates structural prediction error and semantic drift at the token level. 

Instead of relying on massive, static lookup tables and expensive live web retrievals for every unknown string, this engine uses **non-linear multi-dimensional math** to detect when a token's meaning is physically deforming based on its surroundings. It operates on the philosophy of **"Inevitability under Emergence."**

---

## 🧠 Core Philosophy

Standard NLP models chase "relevance" by passing static IDs to heavy attention layers. This engine shifts the paradigm from relevance to **inevitability**.

It treats language not as a static dictionary, but as a reactive physical lattice. The engine does not ask *"What does this token mean?"* It asks, *"Is the meaning of this token structurally deforming based on its surroundings?"*

When a token repeatedly produces a structured prediction error against its baseline, its mutation becomes inevitable. **We observe first, and promote later.**

---

## ⚙️ Architecture: The 4-Tier Pipeline

To prevent runtime collapse from live internet noise, the system utilizes a tiered, cost-effective hybrid retrieval pipeline:

* **Tier 1: The Stable Substrate (Base Vocabulary)**
    * Assigns non-linear baseline axioms to known characters/tokens (Semantic: 1.1, Sentiment: 1.2, Connotation: 1.3). This represents historical, stable identity.
* **Tier 2: The Mutation Cache (The Floquet Pump)**
    * Computes the "Substrate Shift"—the Euclidean distance between the baseline axiom and the context-influenced projection. Tokens are scored and classified as `Stable`, `Plausible`, `Emergent`, or `Inevitable`.
* **Tier 3: Localized Memory (User Thread Context) - *In Development***
    * Checks localized user history to see if an "Inevitable" token has already been defined within a specific semantic frame.
* **Tier 4: Live Web Retrieval - *In Development***
    * Triggered *only* when a promoted anomaly remains unresolved by Tier 3, reaching out to the web to validate cultural trends.

---

## 🔭 The Physics Metaphor: Optomechanics & Floquet Theory

This engine mathematically simulates the interaction between light and mechanical vibrations:
* **The Token = A Photon** (The unperturbed vacuum state).
* **The Context = Phononic Lattice** (The vibrational waves of surrounding text).
* **The Substrate Shift = Phase Dispersion** (How far the photon is refracted from its baseline).

When a user repeatedly types an anomaly in the same structural context, they act as a periodic energy pump. Hitting the frequency threshold (3 observations) forces a **Floquet Topological Phase Shift**, proving that localized *Choice* acts as a physical, mechanical operator that re-folds the semantic space. The token permanently transitions to a `PROMOTED` state.

---

## 🚀 Quick Start & Usage

This project is currently optimized for Google Colab and Jupyter Notebook environments. 

### Prerequisites
* Python 3.8+
* `matplotlib` (for visual cache plotting)

### Running the Engine

1. Instantiate the Cache and the Tokenizer:
```python
from tokenizer_engine import MutationCache, AxiomaticTokenizer

global_cache = MutationCache()
tokenizer = AxiomaticTokenizer(global_cache)
