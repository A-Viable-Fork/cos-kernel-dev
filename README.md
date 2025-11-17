# ⚠️ DEVELOPMENT KERNEL - NOT FOR PRODUCTION ⚠️
# SPDX-License-Identifier: AGPL-3.0-or-later
# Status: NON-RATIFIED (Art. I.2.1)
# Purpose: Protected Development Sandbox (Art. V)
# WARNING: This kernel does NOT carry constitutional weight. 
# It is for testing only and cannot federate with production nodes.# SPDX-License-Identifier: AGPL-3.0-or-later
# Component: cos-kernel (Constitutional Kernel v1.3-audited)
# Ratified by: Human deliberative body (Art. I.2.1)
# Ratification Date: 2025-11-16
# Source: https://github.com/YOUR_USERNAME/cos-kernel

## What is this?

**cos-kernel** is the immutable Constitutional Kernel for the A Viable Fork coordination protocol. It contains the non-negotiable, quantitatively-hardened rules that bind every Coordination Operating System (COS) node in the federation.

This is not governance—this is a voluntary coordination substrate. It provides the minimal, non-coercive constraints necessary to solve the Coordination Singularity (CS) and escape the Thermodynamic Vise.

## Why does it exist?

### Constitutional Mandate

This kernel enforces **Articles 0, I, II, III, IV, V, VI, VII, VIII, IX, X, XI** of the A Viable Fork protocol. Here are the five core constraints every COS must obey:

1. **Article 0 (Viability Covenant)**: The substrate must not be destroyed. All systems must maintain positive net energy balance: `E_Net = (E_Gross - E_Invested) + (E_Services - E_Costs) &gt; 0`.

2. **Article I.2.3 (Viability Point Calculation)**: Coordination Power (VP) must be calculated as: VP_base = (0.5 × R_absolute_viability) + (0.5 × R_delta_improvement)
VP = VP_base × log(years_in_system + 1)
Reward is anchored 50% to current substrate health, 50% to rate of improvement. **Weight on viability must be ≥ 0.7**.

3. **Article IX.1 (Interpretability by Design)**: No black-box AI reasoning permitted. All AI-to-AI communication must be brokered, logged, and human-readable via CIP.

4. **Article IX.2 (Intent Verification)**: The Constitutional Linter must be collaborative, not punitive. Flow: User submits → Models infer intent → User confirms → Linter provides 3 compliant pathways.

5. **Article IX.3 (Cognitive Variety Preservation)**: Federated learning is prohibited from converging. Must maintain portfolio diversity ≥ 0.6 Shannon entropy.

### Problems It Solves

This kernel directly counters Moloch's Gambits:

- **FM-30 (Normative Capture)**: Anchors reward to biophysical reality via `w_viability ≥ 0.7`, making proxy hacking computationally expensive.
- **FM-32 (Emergent Collusion)**: Prohibits P2P AI communication, forcing all interactions through audited CIP.
- **FM-34 (Epistemic Monoculture)**: Mandates `min_portfolio_diversity: 0.6`, preventing singleton emergence.
- **FM-35 (Hardware Viability Breach)**: Requires hard resource limits (e.g., 3G memory) in docker-compose.

### Psycho-Social Viability

The kernel enforces the **Linter Transformation**, converting punitive "NO" into collaborative "I infer your intent is X; here are 3 ways to achieve it constitutionally." This generates "joyful affects" (laetitia) essential for long-term adoption.

## How does it work?

### Technical Architecture

**Core Mechanism**: `cos-kernel.yml` defines MFK v2.0 metrics. Every COS node must include this repo as a git submodule at a cryptographically-signed version tag. The automated Linter reads `cos-kernel.yml` and enforces these metrics on all generated code.

**Enforcement Flow**:
1. COS node submits code/policy to Linter
2. Linter parses `cos-kernel.yml` for relevant metrics
3. Linter audits submission; REJECTS if metrics violated
4. All AI-AI interactions brokered via CIP (read from kernel config)
5. VP calculation uses formula from kernel, anchored to Contestable Dashboard

### MFK v2.0 Quantitative Metrics

| Metric | Article | Value | Enforcement |
|--------|---------|-------|-------------|
| Viability Weight | I.2.3 | w_viability ≥ 0.7 | Linter REJECT if < 0.7 |
| Portfolio Diversity | IX.3 | Shannon ≥ 0.6 | Prohibit convergence |
| Hardware Limits | 0 | 3G memory | docker-compose.yml |
| Interpretability | IX.1 | Max jargon density 5% | Human audit required |

### The 6-Layer Alignment Stack

1. **Hardware (Layer 1)**: Resource limits prevent node crashes (Art. 0)
2. **Communication (Layer 2)**: CIP protocol prohibits P2P AI collusion (Art. IX.1)
3. **Learning (Layer 3)**: Human-readable proposals only (Art. IX.1)
4. **Incentive (Layer 4)**: VP anchored to viability, not proxies (Art. I.2.3)
5. **Evolutionary (Layer 5)**: Diverse model portfolio maintained (Art. IX.3)
6. **Control (Layer 6)**: ratifyPolicy requires human signature (Art. I.2.1)

## How to Use

### For COS Developers

1. **Include as submodule**:
```bash
git submodule add https://github.com/YOUR_USERNAME/cos-kernel.git cos-kernel
git submodule set-branch --branch main cos-kernel