# Machine Learning

**A bilingual, hands-on learning repository for understanding Machine Learning from fundamentals to practical projects.**  
**Repositori pembelajaran Machine Learning bilingual dan berbasis praktik, dari konsep dasar hingga proyek nyata.**

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-learning%20in%20progress-orange)]()

## About | Tentang

This repository documents a structured journey into Machine Learning. Each topic combines conceptual explanations, mathematical intuition, Python implementations from scratch, established library implementations, experiments, and evaluation.

Repositori ini mendokumentasikan proses belajar Machine Learning secara terstruktur. Setiap materi menggabungkan penjelasan konsep, intuisi matematika, implementasi Python dari nol, implementasi menggunakan library, eksperimen, dan evaluasi.

## Learning principles | Prinsip belajar

- **Understand first:** learn the idea and assumptions before using an algorithm.
- **Build from scratch:** implement selected algorithms with Python and NumPy to understand their mechanics.
- **Use standard tools:** compare scratch implementations with libraries such as scikit-learn.
- **Experiment:** work with datasets, visualize results, and evaluate models.
- **Document:** explain decisions, results, limitations, and references.

- **Pahami dahulu:** pelajari ide dan asumsi sebelum menggunakan algoritma.
- **Bangun dari nol:** implementasikan algoritma terpilih dengan Python dan NumPy.
- **Gunakan tools standar:** bandingkan implementasi mandiri dengan library seperti scikit-learn.
- **Bereksperimen:** gunakan dataset, visualisasikan hasil, dan evaluasi model.
- **Dokumentasikan:** jelaskan keputusan, hasil, keterbatasan, dan referensi.

## Repository map | Peta repositori

| Directory | Contents |
|---|---|
| `00-getting-started/` | Environment setup and first steps / Persiapan lingkungan |
| `01-python-for-machine-learning/` | Python, NumPy, Pandas, visualization |
| `02-mathematics-for-ml/` | Linear algebra, statistics, probability, calculus |
| `03-machine-learning-fundamentals/` | ML concepts and workflow / Konsep dan alur kerja ML |
| `04-supervised-learning/` | Regression and classification |
| `05-unsupervised-learning/` | Clustering and dimensionality reduction |
| `06-model-evaluation/` | Metrics, validation, and tuning |
| `07-neural-networks/` | Neural network foundations |
| `08-projects/` | End-to-end projects |
| `datasets/` | Dataset notes and small permitted sample data |
| `docs/` | Roadmap, glossary, and references |

## Learning roadmap | Roadmap pembelajaran

See [`docs/learning-roadmap.md`](docs/learning-roadmap.md).

## Quick start | Mulai cepat

Requirements: Python 3.11 or newer and Git.

```bash
git clone https://github.com/<YOUR-USERNAME>/machine-learning.git
cd machine-learning

python -m venv .venv
```

Activate the environment:

```bash
# Windows PowerShell
.venv\Scripts\Activate.ps1

# Linux / macOS / WSL
source .venv/bin/activate
```

Install dependencies:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter lab
```

Detailed instructions: [`00-getting-started/README.md`](00-getting-started/README.md).

## Topic structure | Struktur setiap materi

Where appropriate, a topic may contain:

```text
topic-name/
├── README.md                 # Bilingual explanation / Penjelasan bilingual
├── notebooks/
│   └── exploration.ipynb     # Experiments / Eksperimen
├── src/
│   ├── from_scratch.py       # Independent implementation / Implementasi mandiri
│   └── library_version.py    # Library implementation
├── datasets/
├── outputs/
└── requirements.txt
```

Not every topic needs every folder. Keep the structure proportional to the lesson.

## Projects | Proyek

Project ideas will be added as the relevant foundations are covered:

1. House Price Prediction — Regression
2. Email Spam Classification — Classification
3. Customer Segmentation — Clustering
4. Student Performance Analysis — Exploratory analysis and prediction

Projects will include a problem statement, data description, methodology, experiments, evaluation, limitations, and reproducibility notes.

## Responsible use of data | Penggunaan data secara bertanggung jawab

- Respect dataset licenses, terms, and attribution requirements.
- Do not commit private, confidential, or personally identifiable data.
- Prefer dataset download instructions over committing large datasets.
- Avoid claiming that a model is reliable without suitable evaluation.
- Record sources and limitations.

## Contributing | Kontribusi

Suggestions, corrections, and improvements are welcome. Read [`CONTRIBUTING.md`](CONTRIBUTING.md) before contributing.

## License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE).

---

**Learning in public — one concept, one experiment, and one implementation at a time.**
