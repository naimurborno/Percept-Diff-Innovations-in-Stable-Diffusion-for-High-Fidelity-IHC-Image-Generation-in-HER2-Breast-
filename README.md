# PerceptDiff: Innovations in Stable Diffusion for High-Fidelity IHC Image Generation in HER2 Breast Cancer

This repository contains the implementation of **PerceptDiff**, a novel method built on top of **Stable Diffusion** for generating high-fidelity **Immunohistochemistry (IHC)** images focused on **HER2-positive breast cancer**. The approach introduces perceptual enhancements and domain-specific training strategies to improve the visual realism and biomedical accuracy of synthetic IHC images.

---

## 🔬 Motivation

IHC image generation in medical AI often suffers from:
- Lack of perceptual realism,
- Poor alignment with tissue morphology,
- Limited generalization across HER2 biomarker variations.

**PerceptDiff** addresses these challenges using a customized diffusion pipeline that integrates:
- Perceptual priors (via loss functions or guided attention),
- Domain-specific conditioning,
- Custom dataset curation from annotated HER2 slides.

---

## 🧠 Key Features

- 🔧 Fine-tuned Stable Diffusion backbone on HER2 IHC patches.
- 🖼️ Perceptual-aware training with high-frequency structure preservation.
- 🧬 Domain-guided latent conditioning based on tissue morphology.
- 📊 Evaluation metrics tailored to medical image quality (SSIM, PSNR, expert grading).

---
