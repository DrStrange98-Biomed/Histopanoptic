## Why HistoPanoptic

Commercial digital pathology tools (HALO, Visiopharm, Definiens) cost $30k–$100k+ per seat per year, putting them out of reach for many academic labs and smaller biotech teams. HistoPanoptic is an open-source alternative built on modern transformer-based foundation models, designed to be reproducible, extensible, and accessible to anyone with a Colab account.

# HistoPanoptic

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DrStrange98-Biomed/Histopanoptic/blob/main/Histopanotic.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.12.13](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/release/python-3110/)

> Open-source toolkit for IHC quantification and tumor microenvironment profiling from whole-slide histopathology images.

## Status

🚧 **Under active development** — Week 1 of build (Setup & PyTorch foundations)

## What this project does

HistoPanoptic provides an end-to-end pipeline for:
- Tumor / stroma / necrosis segmentation in whole-slide images
- IHC marker quantification (H-score, Allred, % positivity)
- Cell-level feature extraction and spatial statistics
- Reproducible analysis with foundation model backbones (UNI, Virchow)

## Quick start

All notebooks run on free Colab GPUs — click the "Open in Colab" badge on any notebook.

## Roadmap

- [x] **Week 1:** Environment setup, PyTorch foundations, first CNN
- [ ] **Week 2:** Histology image basics, PatchCamelyon classification
- [ ] **Week 3:** Whole-slide image handling, stain normalization
- [ ] **Week 4:** U-Net baseline for tumor/stroma segmentation
- [ ] **Week 5–7:** Vision Transformers, SegFormer
- [ ] **Week 8–9:** Foundation model fine-tuning (UNI, Virchow)
- [ ] **Week 10–11:** Cell segmentation (HoVer-Net, CellViT)
- [ ] **Week 12–13:** IHC quantification + spatial statistics
- [ ] **Week 14–15:** Uncertainty estimation & explainability
- [ ] **Week 16–17:** Streamlit demo + Power BI dashboard
- [ ] **Week 18:** Documentation, benchmarks, writeup

## Project structure

- 📓 **`notebooks/`** — Jupyter notebooks, all Colab-ready with one-click badges
- 🐍 **`src/`** — Core Python modules 
- 📊 **`data/`** — Local datasets 
- 📖 **`docs/`** — Project documentation and learning notes
- 📚 **`papers/`** — Reference papers and reading notes
- ⚙️ **`configs/`** — Experiment configurations 

## License

MIT — see [LICENSE](LICENSE)

## Acknowledgments

This project uses models and datasets from:
- UNI, Virchow, CellViT (foundation models for pathology)
- BCSS, PanNuke, NuCLS, PatchCamelyon (public datasets)
- HuggingFace, Weights & Biases, Google Colab (infrastructure)

Each component retains its original license; see individual references in the relevant notebooks.