# Azra Bano

Empirical ML researcher and engineer. SWE @ Google Ads, ex-NASA, Goldman Sachs. Bi-coaster (SF & NJ). 10x Hackathon Winner. ECE (Electrical & Computer Engineering) + Math at Rutgers-New Brunswick. I work on safe, interpretable AI: LLM evaluation infrastructure, quantum-inspired learning, and multimodal medical imaging.

Currently at **Google** (Ads AI/ML), **NASA** (swarm robotics for lunar infrastructure), and **Columbia Center for AI** (quantum ML research). Founder of the **Grey Matter Society** at Yale School of Medicine — 150+ chapters worldwide.

**$5.5M raised** across projects with NEC, Nokia, Google, Qualcomm, Robert Wood Johnson Hospital.

---

### Currently

- **Google Ads · YouTube AI/ML** — Simulation-based forecasting in Python and C++ across 20K+ advertising entities, on distributed infrastructure scaling toward 50M+ simulated user-query scenarios.
- **Swarm Robotics Intelligence Project · NASA-funded, Rutgers** — Decentralized, fault-tolerant multi-agent software for a heterogeneous robotic swarm; autonomous coordination and self-assembly for lunar infrastructure. Delivering technical reviews directly to NASA stakeholders.
- **Columbia Center for AI · IEEE · INNS** — First-author empirical ML research benchmarking quantum-inspired and classical optimization methods on noisy medical-imaging data.
- **Founder & President · Grey Matter Society** — Yale School of Medicine. 150+ chapters globally.

### Earlier this year

- **NASA SpaceTech · L'Space Academy** — Led systems architecture for *InnerSolace*, an AI circadian-rhythm modeling platform simulating 100+ mission-day scenarios across orbital and polar environments. **1st nationally**.
- **Goldman Sachs · SWE Emerging Leader** — Selected first-year cohort. Backend prototyping for low-latency, high-throughput data pipelines; performance and reliability tradeoffs in production-grade systems.
- **WINLAB (Wireless Information Network Lab)** — Real-time simulation and telemetry infrastructure for XR systems. Asynchronous data pipelines, structured logging, distributed tracing.
- **National Science Foundation · Princeton** — Cross-platform backend translating insights from 40+ user interviews into measurable reliability improvements for financial systems.

---

### Selected work

**[cross-sae](https://github.com/azrabano23/cross-sae)** — Interpretability: do vision transformers and the human visual cortex share the *same* features? Trains sparse autoencoders on both a ViT and human brain responses to the same images, then matches features across domains under **false-discovery-rate control** (Model-X knockoffs). The cross-domain feature match is an honest null at current SAE capacity — with a diagnostic (RSA ρ = 0.155, p = 0.0005) showing the shared structure is real and recoverable. Error-controlled, self-correcting empirical interpretability.

**Quantum ML for AML detection** · [arXiv:2601.18710](https://arxiv.org/abs/2601.18710) · [code](https://github.com/azrabano23/quantum-blood-cell-classification)
First-author publication, January 2026. Equilibrium Propagation reached **86.4% accuracy without backpropagation**; a 4-qubit Variational Quantum Circuit held its accuracy with **5× less training data**. Established reproducible QML baselines on the 18,365-image AML-Cytomorphology dataset. Rutgers + Columbia.

**[Aurelis](https://github.com/azrabano23/aurelis)** — Reproducible LLM-as-judge evaluation infrastructure: it grades clinical notes against a rubric and *validates the AI grader against human reference scores* (quadratic-weighted kappa, Pearson) on real ACI-Bench clinical notes — applied scalable oversight, with a content-addressed cache for byte-identical reruns.

**[Thaakat](https://github.com/azrabano23/thaakat)** (EndoDetect) — Multimodal radiomics decision-support for endometriosis: an EfficientNet + XGBoost ensemble on pelvic MRI with Grad-CAM explanations, behind a strict non-diagnostic boundary.

**[Circa](https://github.com/azrabano23/circa)** — *InnerSolace*, productized: a chronotype-aware scheduler built on a tested two-process alertness model that places demanding work at your biological peak (recovers up to +203% modelled throughput for evening types vs. clock-blind scheduling).

**[Robrick](https://github.com/azrabano23/robrick-selfassembly-algorithm)** — The NASA swarm self-assembly work as runnable, tested code: identical units build and self-heal a target structure from one neighbour-only local rule (decentralized gradient assembly, Kilobot-style).

**Fitra** · [repo](https://github.com/azrabano23/alifsideprojectsnight)
Circadian-optimization app for Muslims. The five prayers are treated as immovable anchors; everything else — sleep, nap, caffeine cutoff, peak focus — is optimized around them. Two-process sleep model, live recompute, present mode.

**[AeroBin](https://github.com/azrabano23/AeroBin)** + **[routing engine](https://github.com/azrabano23/aerobin-routing)** — Multi-sensor, edge-compute smart-waste system; the prediction + optimization engine cuts wasteful pickups from **87% → 0.5%** and servicing events **−70%**. **1st Place, national Verizon Smart Campus Competition** (NEC · Nokia · Google · Qualcomm).

---

### Open-source & AI-safety contributions

- **[TransformerLens #1369](https://github.com/TransformerLensOrg/TransformerLens/pull/1369)** — a Direct Logit Attribution tool for mechanistic interpretability.
- **[SAELens #697](https://github.com/decoderesearch/SAELens/pull/697)** — covariance-whitening normalization for training sparse autoencoders.
- **[Inspect Evals #1765](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1765)** — registering the **MedCalc-Bench** medical-reasoning benchmark in the UK AI Safety Institute's evaluation framework.

---

### Recognition

- 1st nationally — NASA SpaceTech Competition
- 1st Place national — Verizon Smart Campus Competition (AeroBin)
- Rutgers Innovation Award · Outstanding Student Leader (20 of 60K+)
- Elected Representative to 40K+ students — Rutgers School of Engineering · RUSA

---

[portfolio](https://azra-bano.com) · [linkedin](https://linkedin.com/in/meetazrabano) · [arxiv](https://arxiv.org/abs/2601.18710) · [gitlab](https://gitlab.orbit-lab.org/azrabano) · [email](mailto:azra.bano@rutgers.edu)
