EECS + Math @ Rutgers. Previously @ Google (Ads Infra, AI/ML), NASA Swarm Robotics, Goldman Sachs, Columbia AI. First author of [arXiv:2601.18710](https://arxiv.org/abs/2601.18710). 

Founder of the [Grey Matter Society](https://medicine.yale.edu/neurology/education/grey-matter-project/) at Yale School of Medicine, 150+ Global Chapters.

### now

- **interpretability & evals** — [interp](https://github.com/azrabano23/interp) asks *why* a model made a prediction (logit lens, activation patching, SAE features) from inside your coding agent · [evalkit](https://github.com/azrabano23/evalkit) is evals done right — bootstrap CIs, unbiased pass@k, judge-bias controls · [steering-audit](https://github.com/azrabano23/steering-audit) found that only 31–50% of "successful" activation steers stay coherent — the classifier can't tell degenerate text from a steered one · [cross-sae](https://github.com/azrabano23/cross-sae) matches sparse-autoencoder features between vision models and human visual cortex, with the false-discovery rate actually controlled
- **ML for medicine** — [thaakat](https://github.com/azrabano23/thaakat): endometriosis detection from pelvic MRI, AUC 0.961 on a patient-level split (the honest kind) · [vigil](https://github.com/azrabano23/vigil): pilot cognitive state from EEG/ECG, where fixing the leaky eval cost 0.19 AUROC — I kept the honest number · [aurelis](https://github.com/azrabano23/aurelis): an LLM judge for clinical notes, validated against human graders · [neuroloop](https://github.com/azrabano23/neuroloop): closed-loop neuromodulation graphs that prove their safety envelope before they run
- **biological time** — the niche I keep coming back to: [circa](https://github.com/azrabano23/circa) · [rhythmrx](https://github.com/azrabano23/rhythmrx) · [fitra](https://github.com/azrabano23/alifsideprojectsnight) — the right intervention at the right circadian phase
- **carbonium** — with [@RyanRana](https://github.com/RyanRana), exploring whether an abductive engine over fleet-maintenance data can name a failure *and* its evidence chain — and be evaluated with confounder traps so it can't bluff

### upstream

PRs to the tools researchers actually run —

- **merged** · [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens/pull/1369) — direct logit attribution · [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1765) (UK AI Security Institute) — MedCalc-Bench · [nnsight](https://github.com/ndif-team/nnsight/pull/671) — multi-invoker `.backward()` fix
- **in review** · [MOABB](https://github.com/NeuroTechX/moabb/pull/1140) — Nadeau–Bengio corrected t-test, so EEG benchmarks stop reporting optimistic p-values · [braindecode](https://github.com/braindecode/braindecode/pull/1128) — spec-compliant zarr JSON · [Medplum](https://github.com/medplum/medplum/pull/10293) — GraphQL error semantics · [MONAI](https://github.com/Project-MONAI/MONAI/pull/8905) — invertible `NormalizeIntensity` · [SAELens](https://github.com/decoderesearch/SAELens/pull/697) — covariance whitening · [garak](https://github.com/NVIDIA/garak/pull/1852) — NonEngagement detector · [pyvene](https://github.com/stanfordnlp/pyvene/pull/239) — ELECTRA support · [dynamo](https://github.com/ai-dynamo/dynamo/pull/13326) ×[2](https://github.com/ai-dynamo/dynamo/pull/13318) · [SkyPilot](https://github.com/skypilot-org/skypilot/pull/10484) · [FlashInfer](https://github.com/flashinfer-ai/flashinfer/pull/4548)
- **in discussion** · [lm-evaluation-harness #3080](https://github.com/EleutherAI/lm-evaluation-harness/issues/3080#issuecomment-5306101152) — design for per-instance repeats aggregation with unbiased pass@k

### elsewhere

[azra-bano.com](https://azra-bano.com) · [linkedin](https://linkedin.com/in/meetazrabano) · [arxiv](https://arxiv.org/abs/2601.18710) · [email](mailto:azra.bano@rutgers.edu)
