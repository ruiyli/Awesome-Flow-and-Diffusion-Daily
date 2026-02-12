# Awesome Flow Matching & Diffusion Models

[![Daily Update](https://github.com/ruiyli/ArXiv_Paper_Fetcher/actions/workflows/daily_update.yml/badge.svg)](https://github.com/ruiyli/ArXiv_Paper_Fetcher/actions)
[![Paper Source](https://img.shields.io/badge/Source-ArXiv-B31B1B.svg)](https://arxiv.org)
[![Topic](https://img.shields.io/badge/Topic-Diffusion%20Flow-blue)](https://arxiv.org/search/?query=%22Diffusion+Flow%22&searchtype=all)
[![Topic](https://img.shields.io/badge/Topic-Flow%20Matching-green)](https://arxiv.org/search/?query=%22Flow+Matching%22&searchtype=all)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

> **Tracking the frontier of Generative AI: Diffusion and Flow Models.**

This repository is a curated, **daily-updated** collection of the latest research papers from ArXiv. It is designed for researchers, engineers, and enthusiasts who want to stay ahead in the rapidly evolving field of continuous-time generative models.

---

## 🚀 Why Follow This Repository?

The field of Generative AI is moving fast. New techniques like **Flow Matching** and **Rectified Flow** are challenging the dominance of standard Diffusion Models. Keeping up with the daily influx of papers is exhausting.

This repository solves that by:
1.  **Automating Discovery**: We fetch papers every 24 hours directly from ArXiv.
2.  **Focusing on Quality**: Filtering for the most relevant keywords in the domain.
3.  **Archiving History**: Maintaining a structured log of research progress over time.

---

## 🔥 Fresh off the Press (Daily Updates)
*Updated automatically at 01:00 UTC.*

> *(The automation script is running... New papers will appear here after the next update cycle.)*
---

## 🎯 Scope & Keywords

We track a specific set of high-impact topics. The automation script filters for papers containing the following keywords in their titles or abstracts:

| Category | Keywords |
| :--- | :--- |
| **Core Methods** | `Flow Matching`, `Diffusion Model`, `Diffusion Flow`, `Score-based Generative Model` |
| **Advanced Theory** | `Stochastic Interpolants`, `Rectified Flow`, `Schrödinger Bridge`, `Optimal Transport` |
| **Applications** | `Image Generation`, `3D Generation`, `Molecular Generation` |

**Target ArXiv Categories:**
* `cs.LG` (Machine Learning)
* `cs.CV` (Computer Vision)
* `cs.AI` (Artificial Intelligence)
* `stat.ML` (Machine Learning)
* `math.PR` (Probability)

---

## 🗄️ Paper Archives

Missed a day? Check the historical archives organized by date.

### [📂 Enter the Archives](./archives/)

* **2026**: [Jan](./archives/2026-01.md) | [Feb](./archives/2026-02.md) | ...

---

## 🛠️ How It Works

This repository is maintained by an automated pipeline:
1.  **Fetcher**: A Python script queries the ArXiv API for specific keywords.
2.  **Filter**: Papers are filtered by date (last 24h) and relevance.
3.  **Formatter**: Metadata (Title, Abstract, Authors, Code Links) is extracted and formatted into Markdown.
4.  **Publisher**: GitHub Actions pushes the update to this repository and archives the old data.

*Powered by [ArXiv_Paper_Fetcher](https://github.com/ruiyli/ArXiv_Paper_Fetcher).*

---

## 🤝 Contributing

While the paper list is automated, we welcome community contributions!

* **Feature Requests**: If you want to add new keywords (e.g., "Discrete Diffusion") or change the layout, please open an issue in the [Source Repo](https://github.com/ruiyli/ArXiv_Paper_Fetcher).
* **Bug Reports**: Found a broken link or a missed paper? Let us know.

---

<p align="center">
  <sub>Maintained by <a href="https://github.com/ruiyli">@ruiyli</a></sub>
</p>


## 2026-02-12
### [SurfPhase: 3D Interfacial Dynamics in Two-Phase Flows from Sparse Videos](https://arxiv.org/abs/2602.11154v1)
- **Date**: 2026-02-11
- **Code**: N/A
- **Abstract**:
  > Interfacial dynamics in two-phase flows govern momentum, heat, and mass transfer, yet remain difficult to measure experimentally. Classical techniques face intrinsic limitations near moving interfaces, while existing neural rendering methods target single-phase flows with diffuse boundaries and cannot handle sharp, deformable liquid-vapor interfaces. We propose SurfPhase, a novel model for reconstructing 3D interfacial dynamics from sparse camera views. Our approach integrates dynamic Gaussian surfels with a signed distance function formulation for geometric consistency, and leverages a video diffusion model to synthesize novel-view videos to refine reconstruction from sparse observations. We evaluate on a new dataset of high-speed pool boiling videos, demonstrating high-quality view synthesis and velocity estimation from only two camera views. Project website: https://yuegao.me/SurfPhase.

---
### [From Circuits to Dynamics: Understanding and Stabilizing Failure in 3D Diffusion Transformers](https://arxiv.org/abs/2602.11130v1)
- **Date**: 2026-02-11
- **Code**: N/A
- **Abstract**:
  > Reliable surface completion from sparse point clouds underpins many applications spanning content creation and robotics. While 3D diffusion transformers attain state-of-the-art results on this task, we uncover that they exhibit a catastrophic mode of failure: arbitrarily small on-surface perturbations to the input point cloud can fracture the output into multiple disconnected pieces -- a phenomenon we call Meltdown. Using activation-patching from mechanistic interpretability, we localize Meltdown to a single early denoising cross-attention activation. We find that the singular-value spectrum of this activation provides a scalar proxy: its spectral entropy rises when fragmentation occurs and returns to baseline when patched. Interpreted through diffusion dynamics, we show that this proxy tracks a symmetry-breaking bifurcation of the reverse process. Guided by this insight, we introduce PowerRemap, a test-time control that stabilizes sparse point-cloud conditioning. We demonstrate that Meltdown persists across state-of-the-art architectures (WaLa, Make-a-Shape), datasets (GSO, SimJEB) and denoising strategies (DDPM, DDIM), and that PowerRemap effectively counters this failure with stabilization rates of up to 98.3%. Overall, this work is a case study on how diffusion model behavior can be understood and guided based on mechanistic analysis, linking a circuit-level cross-attention mechanism to diffusion-dynamics accounts of trajectory bifurcations.

---
### [The Offline-Frontier Shift: Diagnosing Distributional Limits in Generative Multi-Objective Optimization](https://arxiv.org/abs/2602.11126v1)
- **Date**: 2026-02-11
- **Code**: N/A
- **Abstract**:
  > Offline multi-objective optimization (MOO) aims to recover Pareto-optimal designs given a finite, static dataset. Recent generative approaches, including diffusion models, show strong performance under hypervolume, yet their behavior under other established MOO metrics is less understood. We show that generative methods systematically underperform evolutionary alternatives with respect to other metrics, such as generational distance. We relate this failure mode to the offline-frontier shift, i.e., the displacement of the offline dataset from the Pareto front, which acts as a fundamental limitation in offline MOO. We argue that overcoming this limitation requires out-of-distribution sampling in objective space (via an integral probability metric) and empirically observe that generative methods remain conservatively close to the offline objective distribution. Our results position offline MOO as a distribution-shift--limited problem and provide a diagnostic lens for understanding when and why generative optimization methods fail.

---
### [FastFlow: Accelerating The Generative Flow Matching Models with Bandit Inference](https://arxiv.org/abs/2602.11105v1)
- **Date**: 2026-02-11
- **Code**: [GitHub](https://github.com/Div290/FastFlow.)
- **Abstract**:
  > Flow-matching models deliver state-of-the-art fidelity in image and video generation, but the inherent sequential denoising process renders them slower. Existing acceleration methods like distillation, trajectory truncation, and consistency approaches are static, require retraining, and often fail to generalize across tasks. We propose FastFlow, a plug-and-play adaptive inference framework that accelerates generation in flow matching models. FastFlow identifies denoising steps that produce only minor adjustments to the denoising path and approximates them without using the full neural network models used for velocity predictions. The approximation utilizes finite-difference velocity estimates from prior predictions to efficiently extrapolate future states, enabling faster advancements along the denoising path at zero compute cost. This enables skipping computation at intermediary steps. We model the decision of how many steps to safely skip before requiring a full model computation as a multi-armed bandit problem. The bandit learns the optimal skips to balance speed with performance. FastFlow integrates seamlessly with existing pipelines and generalizes across image generation, video generation, and editing tasks. Experiments demonstrate a speedup of over 2.6x while maintaining high-quality outputs. The source code for this work can be found at https://github.com/Div290/FastFlow.

---
### [A Gibbs posterior sampler for inverse problem based on prior diffusion model](https://arxiv.org/abs/2602.11059v1)
- **Date**: 2026-02-11
- **Code**: N/A
- **Abstract**:
  > This paper addresses the issue of inversion in cases where (1) the observation system is modeled by a linear transformation and additive noise, (2) the problem is ill-posed and regularization is introduced in a Bayesian framework by an a prior density, and (3) the latter is modeled by a diffusion process adjusted on an available large set of examples. In this context, it is known that the issue of posterior sampling is a thorny one. This paper introduces a Gibbs algorithm. It appears that this avenue has not been explored, and we show that this approach is particularly effective and remarkably simple. In addition, it offers a guarantee of convergence in a clearly identified situation. The results are clearly confirmed by numerical simulations.

---
