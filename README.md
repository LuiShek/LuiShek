# Abishek Luitel

**Machine learning and agentic systems.** I build the whole thing — the model,
the measurement, and the written-down limits.

Lalitpur, Nepal · Kantipur Engineering College · [LinkedIn](https://www.linkedin.com/in/abishek-luitel-53573220b/)

---

## What I work on

- **Verification systems** — speaker and face pipelines where every decision is
  inspectable: GMM-UBM, LBPH, calibrated thresholds, speaker-clustered
  confidence intervals.
- **Agentic AI** — autonomous agent harnesses, tool-use loops, and the
  engineering discipline that keeps them reliable.
- **Evaluation** — reproducible splits, honest baselines, and results that
  survive their own error bars.

## Selected projects

### [classical-face-authentication](https://github.com/LuiShek/classical-face-authentication)

Face authentication built on LBPH — no neural embedding anywhere in the identity
decision. Active head-turn liveness, per-user conservative calibration,
DPAPI-encrypted biometric storage, 15 test modules, and CI on every push.

`5.83% EER` on ORL at 7 enrolment images · `94.17%` TAR at FAR = 1% ·
three-frame median pooling takes LFW from `26.83%` to `18.74%` EER, reported
with identity-clustered 95% intervals.

### [gmm-ubm-speaker-verification](https://github.com/LuiShek/gmm-ubm-speaker-verification)

Text-independent speaker verification with a GMM-UBM, MAP adaptation, and
T-norm.

`0.98% EER` (95% CI `0.58–1.26%`) over 13,315 trials from 50 speakers held out
of UBM training · `minDCF 0.219` · every ablation reproducible from committed
score artifacts.

The repository also documents a withdrawn `5.42%` figure and the normalisation
cohort bug that produced it, rather than quietly deleting the number.

### [neetcode-submissions](https://github.com/LuiShek/neetcode-submissions)

Ongoing data-structures and algorithms practice, synced from NeetCode — arrays,
two pointers, sliding window, stacks, binary search, trees, heaps, graphs.

## Private work

Agent harnesses I build and run, kept private: **DeepDragon**, **T-HEAD**,
**G-HEAD**, and **Dyros** — browser-first agent architectures with capability
gating, role specialisation, and a discipline layer that constrains what the
agent is permitted to do.

## Tooling

`Python` · `NumPy` · `SciPy` · `scikit-learn` · `OpenCV` · `C++` ·
`TypeScript` / `Next.js` · `pytest` · `GitHub Actions`
