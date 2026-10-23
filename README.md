# Plant Spatial Multi-omics Analysis

**A practical guide to spatial multi-omics data analysis in plants** — companion site to our review in *Trends in Plant Science*.

📖 **Read the guide:** https://yaoj-bioin.github.io/plant-spatial-multiomics-analysis/

> 植物空间多组学数据分析实践指南（*Trends in Plant Science* 综述配套教程）：从预处理到基础分析、多组学整合与下游分析，附成熟种子空间多组学示例数据。

## Contents

| Chapter | Status |
|---|---|
| [Welcome](docs/index.md) — scope, dataset, publication | ✅ |
| [Preprocessing](docs/1_preprocess.md) — image/spot QC, binning, segmentation | ✅ |
| Basic analysis — normalisation, clustering, spatial domains | 🚧 in preparation |
| Multi-omics integration — ST × sc/snRNA-seq × scATAC-seq × metabolomics | 🚧 in preparation |
| Downstream analysis — cell–cell communication, trajectories, cross-species | 🚧 in preparation |

## Build locally

```bash
pip install mkdocs-material mkdocs-jupyter
mkdocs serve        # http://127.0.0.1:8000
```

The site is deployed automatically to GitHub Pages on every push to `main` (`.github/workflows/deploy.yml`).

## Citation

Yao J, Marand AP, Bai Y, Schmitz RJ, Fan L\*. **Advances in plant spatial multi-omics data analysis.** *Trends in Plant Science* (2025). [doi:10.1016/j.tplants.2025.10.005](https://doi.org/10.1016/j.tplants.2025.10.005)

## Contact

Jie Yao · JieYao@uga.edu · Schmitz Lab, University of Georgia
