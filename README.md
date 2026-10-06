<div align="center">

# Hi, I'm Srijan Roy 👋

### AI/ML Engineer • Researcher • Open-Source Contributor

[![GitHub followers](https://img.shields.io/github/followers/SrijanRoy123-github?label=Followers&style=for-the-badge&logo=github)](https://github.com/SrijanRoy123-github?tab=followers)
[![GitHub stars](https://img.shields.io/github/stars/SrijanRoy123-github?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge&logo=github&label=Stars)](https://github.com/SrijanRoy123-github?tab=repositories)
[![Profile views](https://komarev.com/ghpvc/?username=SrijanRoy123-github&style=for-the-badge)](https://github.com/SrijanRoy123-github)

</div>

---

## About Me

- 🎓 Electronics & Telecommunication Engineering, Jadavpur University
- 🤖 Interested in **Machine Learning, Deep Learning, Computer Vision, LLM Systems, Scientific ML, and AI Infrastructure**
- 🧠 I enjoy working across the stack: from numerical correctness and ML frameworks to distributed systems, compilers, inference, and research
- 🛠️ Active in open source across the **JAX, PyTorch, Google DeepMind, Hugging Face, Zulip, and compiler ecosystems**
- 📍 Kolkata, India

---

## GitHub Statistics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=SrijanRoy123-github&show_icons=true&include_all_commits=true&count_private=true&theme=github_dark&hide_border=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SrijanRoy123-github&layout=compact&langs_count=10&theme=github_dark&hide_border=true" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=SrijanRoy123-github&theme=github-dark-blue&hide_border=true" />

</div>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SrijanRoy123-github&theme=github_dark" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=SrijanRoy123-github&theme=onestar&no-frame=true&no-bg=true&margin-w=8&column=7" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SrijanRoy123-github&theme=github-compact&hide_border=true&area=true" />

</div>

---

# Open-Source Contributions

## ✅ Merged Upstream Contributions

### JAX — `jax-ml/jax`

**PR #41247 — Fix `reduceat` accumulator dtype**  
[View merged PR](https://github.com/jax-ml/jax/pull/41247)

- Fixed `jnp.add.reduceat` / `jnp.multiply.reduceat` ignoring an explicitly requested accumulator dtype.
- Prevented accumulation in the original narrow dtype, which could cause silent overflow.
- Added NumPy-parity regression coverage with explicit dtype checking.
- Merged into `jax-ml:main`.

---

### Google DeepMind — `formal-conjectures`

**PR #1349 — Erdős Problem 822: positive density of `n + φ(n)`**  
[View merged PR](https://github.com/google-deepmind/formal-conjectures/pull/1349)

**PR #1351 — Erdős Problem 881: minimal additive basis of order `k`**  
[View merged PR](https://github.com/google-deepmind/formal-conjectures/pull/1351)

- Contributed formal mathematical problem statements and research-status metadata.
- Worked with Lean-based formal conjecture infrastructure.

---

## 🚧 Active Upstream Contributions

### PyTorch — `pytorch/pytorch`

**PR #192502 — Support integer dtypes in safetensors consolidation**  
[View PR](https://github.com/pytorch/pytorch/pull/192502)

- Replaced floating-point-only dtype-size logic with `Tensor.element_size()`.
- Adds support for integer/bool dtypes in distributed-checkpoint safetensors consolidation.
- Includes targeted regression testing.

---

### Google DeepMind — `torax`

**PR #2551 — Fix TGLF ExB normalization**  
[View PR](https://github.com/google-deepmind/torax/pull/2551)

- Corrects the TGLF-specific ExB normalization path to use the poloidal magnetic field.
- Keeps shared rotation behavior unchanged for other TORAX components.

---

### Google DeepMind — `formal-conjectures`

**PR #6783 — Mark TxGraffiti Conjecture 2 as false**  
[View PR](https://github.com/google-deepmind/formal-conjectures/pull/6783)

**PR #6788 — Mark Erdős Problem 1212 as solved**  
[View PR](https://github.com/google-deepmind/formal-conjectures/pull/6788)

- Research-status updates grounded in published counterexamples / constructions.
- Added references to external mathematical and Lean formalization results.

---

## 🧩 Other Contribution Work

### Hugging Face Transformers — `huggingface/transformers`

**PR #49201 — Fix Trainer metrics after checkpoint resume**  
[View PR](https://github.com/huggingface/transformers/pull/49201)

- Investigated incorrect loss and throughput metrics after resuming training.
- Added regression coverage around resumed-step accounting.

---

### Clad — `vgvassilev/clad`

**PR #1704 — Fix lambda-local globals leaking into outer derivative function**  
[View PR](https://github.com/vgvassilev/clad/pull/1704)

- Worked on automatic-differentiation compiler behavior around lambda scoping.
- Added regression testing for lambda-local derivative state.

---

### Zulip — `zulip/zulip`

**PR #36017 — Realm URL port handling**  
[View PR](https://github.com/zulip/zulip/pull/36017)

**PR #36093 — Slack sender display-name handling / URL-related work**  
[View PR](https://github.com/zulip/zulip/pull/36093)

---

### Canonical Multipass — `canonical/multipass`

**PR #4347 — Improve quit-dialog UX**  
[View PR](https://github.com/canonical/multipass/pull/4347)

---

### Sugar Labs Music Blocks — `sugarlabs/musicblocks-v4`

**PR #454 — Update PWA assets configuration**  
[View PR](https://github.com/sugarlabs/musicblocks-v4/pull/454)

---

## Technology & Research Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,pytorch,tensorflow,git,github,linux,docker,vscode&perline=10" />
</p>

**ML / AI:** PyTorch • JAX • Transformers • Computer Vision • Deep Learning • LLM Systems  
**Systems:** Distributed Training • Inference • GPU/Accelerator Computing • Scientific Computing  
**Languages:** Python • C++ • C • Lean  
**Tools:** Git • GitHub • Linux • Docker • VS Code

---

## Contribution Portfolio

| Ecosystem | Repository | Area | Status |
|---|---|---|---|
| JAX | [`jax-ml/jax`](https://github.com/jax-ml/jax) | NumPy API / numerical correctness | ✅ Merged |
| Google DeepMind | [`formal-conjectures`](https://github.com/google-deepmind/formal-conjectures) | Lean / formal mathematics | ✅ Merged + 🚧 Active |
| PyTorch | [`pytorch/pytorch`](https://github.com/pytorch/pytorch) | Distributed checkpoint / safetensors | 🚧 Active |
| Google DeepMind | [`torax`](https://github.com/google-deepmind/torax) | Scientific ML / plasma simulation | 🚧 Active |
| Hugging Face | [`transformers`](https://github.com/huggingface/transformers) | Trainer / checkpoint-resume metrics | Contribution history |
| Clad | [`vgvassilev/clad`](https://github.com/vgvassilev/clad) | Automatic differentiation compiler | Contribution history |
| Zulip | [`zulip/zulip`](https://github.com/zulip/zulip) | Backend / integrations | Contribution history |
| Canonical | [`canonical/multipass`](https://github.com/canonical/multipass) | Desktop / VM tooling | Contribution history |
| Sugar Labs | [`musicblocks-v4`](https://github.com/sugarlabs/musicblocks-v4) | Web / PWA | Contribution history |

---

## Current Focus

```text
ML Frameworks        ████████████████████
Open Source          ████████████████████
AI Systems           ██████████████████░░
Research             ██████████████████░░
Compilers / Kernels  ███████████████░░░░░
Scientific ML        ███████████████░░░░░
```

---

<div align="center">

### Building reliable AI systems, contributing upstream, and learning from production-grade codebases.

[![GitHub](https://img.shields.io/badge/GitHub-SrijanRoy123--github-181717?style=for-the-badge&logo=github)](https://github.com/SrijanRoy123-github)

</div>
