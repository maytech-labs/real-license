# Reciprocal Ethical AI License (REAL 1.0)
[![License: REAL 1.0](https://img.shields.io/badge/License-REAL_1.0-blue.svg)](LICENSE.md)
[![Category: Source-Available](https://img.shields.io/badge/Category-Source--Available-orange.svg)](#classification-note)
[![Ethics: RAIL--Inspired](https://img.shields.io/badge/Ethics-RAIL--Inspired-green.svg)](#key-features)

**REAL** (Reciprocal Ethical AI License) is a source-available, ethical reciprocal license designed for modern software projects. It allows developers to freely share, modify, and distribute their code while protecting it from closed-source AI ingestion.

---

## Key Features

1. **Reciprocal AI Copyleft:** If anyone ingests or trains a machine learning model on software under this license, they are contractually obligated to release the resulting model weights, training scripts, and datasets under the same terms.
2. **Network Copyleft (AGPL-Style):** Interacting with or exposing a trained model over a network (e.g., hosted inference APIs) constitutes distribution, triggering open-weight obligations.
3. **Ethical Usage Bounds:** Prohibits use in mass surveillance, lethal autonomous weaponry, unlawful discrimination, or unmonitored critical infrastructure (modeled after RAIL principles).
4. **Contractual Fair Use Waiver:** Enforces restrictions via contract terms to ensure compliance regardless of statutory data-mining exceptions.

---

## How to Apply REAL 1.0 to Your Repository

To license your codebase under REAL 1.0:

1. Copy the contents of [`LICENSE.md`](./LICENSE.md) into the root directory of your repository.
2. Update the copyright header at the top of the file:
```text
   Copyright (c) [Year] [Your Name or Organization]
   Licensed under the Reciprocal Ethical AI License (REAL) 1.0.
