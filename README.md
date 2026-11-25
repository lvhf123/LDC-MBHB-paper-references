# LDC-MBHB paper references

Literature collection for our analysis of the **massive black hole binary (MBHB)** data set of the **LISA Data Challenge 1 (LDC1-1, "Radler")**, with a focus on simulation-based inference.

> **Private repository.** It contains LISA Consortium internal documents (the LDC manual, the sensitivity technical note and the Mojito CD1 description) whose terms forbid redistribution, plus copyrighted journal PDFs. Please do not make it public or share the files outside the group.

## Layout

```
reference/
├── paper_about_MBHB/                        # core MBHB literature
│   ├── 01_LDC_MLDC_challenges_and_search_pipelines/
│   ├── 02_parameter_estimation/
│   ├── 03_machine_learning_and_SBI/
│   ├── 04_global_fit/
│   ├── 05_waveforms_response_likelihood/
│   └── 06_mission_and_MBHB_science_overview/
├── LISA_mission_LDC_and_official_docs/
├── LISA_instrument_noise_and_data_gaps/
├── other_LISA_sources/                      # SGWB, galactic binaries, stellar-origin BBH
├── SBI_and_statistical_methods/
└── GW_inference_tutorials_and_reviews/
paper_about_matching_flow/                   # flow-matching background
```

The full annotated index (year, authors, title, arXiv link for every paper) is in [`reference/README.md`](reference/README.md).

## Where to start for LDC1-1 (Radler) MBHB

| Paper | Why it matters |
|---|---|
| [arXiv:2204.12142](https://arxiv.org/abs/2204.12142) — Baghi et al., *The LISA Data Challenges* | Overview of the LDC program and the Radler data sets |
| [arXiv:2005.03610](https://arxiv.org/abs/2005.03610) — Cornish & Shuman, *Black Hole Hunting with LISA* | Analysis of the LDC1 MBHB data |
| [arXiv:2111.01064](https://arxiv.org/abs/2111.01064) — Katz, *Fully automated end-to-end MBHB pipeline* | Search and parameter estimation on Radler MBHB data |
| [arXiv:1806.10734](https://arxiv.org/abs/1806.10734) — Marsat & Baker, *Fourier-domain modulations and delays* | The Fourier-domain LISA response of the kind used to simulate the Radler MBHB signal |
| [arXiv:2003.00357](https://arxiv.org/abs/2003.00357) — Marsat et al., *Bayesian PE of BBHs with LISA* | MBHB posterior structure and sky/inclination degeneracies |
| [arXiv:2005.01827](https://arxiv.org/abs/2005.01827) — Katz et al., *GPU-accelerated MBHB PE* (BBHx) | Fast MBHB likelihood and waveform code |
| [arXiv:2406.00565](https://arxiv.org/abs/2406.00565), [arXiv:2603.20431](https://arxiv.org/abs/2603.20431) | Neural likelihood and SBI for LISA MBHBs, the closest to our approach |

## Flow matching background
Flow matching, rectified flows and stochastic interpolants (generative-model background for flow-matching posterior estimation).

| File | Year | Authors | Title |
|---|---|---|---|
| [PDF](paper_about_matching_flow/2209.03003v1.pdf) · [arXiv:2209.03003](https://arxiv.org/abs/2209.03003) | 2022 | Xingchao Liu et al. | Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow |
| [PDF](paper_about_matching_flow/2210.02747v2.pdf) · [arXiv:2210.02747](https://arxiv.org/abs/2210.02747) | 2022 | Yaron Lipman et al. | Flow Matching for Generative Modeling |
| [PDF](paper_about_matching_flow/2302.00482v4.pdf) · [arXiv:2302.00482](https://arxiv.org/abs/2302.00482) | 2023 | Alexander Tong et al. | Improving and generalizing flow-based generative models with minibatch optimal transport |
| [PDF](paper_about_matching_flow/2303.08797v4.pdf) · [arXiv:2303.08797](https://arxiv.org/abs/2303.08797) | 2023 | Michael S. Albergo et al. | Stochastic Interpolants: A Unifying Framework for Flows and Diffusions |
| [PDF](paper_about_matching_flow/2412.06264v1.pdf) · [arXiv:2412.06264](https://arxiv.org/abs/2412.06264) | 2024 | Yaron Lipman et al. | Flow Matching Guide and Code |
| [PDF](paper_about_matching_flow/2506.02070v3.pdf) · [arXiv:2506.02070](https://arxiv.org/abs/2506.02070) | 2025 | Peter Holderrieth et al. | An Introduction to Flow Matching and Diffusion Models |
