# 🧬 GenomePipe Pro v4.0

> **Professional Clinical Genomics Platform** — A fully browser-based bioinformatics application for variant analysis, clinical interpretation, and report generation.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://shashwat-sahuu.github.io/genomepipe-pro/)
[![Version](https://img.shields.io/badge/Version-4.0-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()
[![No Server Required](https://img.shields.io/badge/Server-Not%20Required-orange)]()

---

## 🖼 Screenshot

> Open `genomepipe-pro-v4.html` in any modern browser — no installation needed.

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 🏥 **ClinVar Search** | Live NCBI ClinVar database search with batch workbench add |
| 🔬 **dbSNP Lookup** | rs ID search with population frequency tables |
| 🏷 **Variant Annotator** | Ensembl VEP REST API + NCBI fallback (ClinVar, Gene, PubMed) |
| 🌍 **Population Frequency** | gnomAD v4 GraphQL API with per-population breakdown |
| ⚡ **Pathogenicity Prediction** | SIFT · PolyPhen-2 · CADD · SpliceAI + composite scoring |
| 📊 **ACMG/AMP 2015 Classifier** | 28-criteria interactive classifier with auto-suggest |
| 🔧 **Variant Workbench** | Curate, enrich, annotate, compare and export variants |
| 🗺 **Genome Browser** | Integrated IGV.js (GRCh38/hg38) |
| 🧬 **Pathway Analysis** | KEGG, Reactome, GO term enrichment |
| 📄 **Clinical Reports** | Full clinical-grade PDF/HTML reports with NCBI enrichment |
| 🤖 **AI Clinical Assistant** | Claude-powered genomic interpretation chat |
| ⚙ **NGS Pipeline Monitor** | FASTQ → VCF pipeline simulation (BWA + GATK) |

---

## 🚀 Quick Start

### Option 1 — Run directly (easiest)
```bash
# Just download and open in your browser
# No server, no installation, no dependencies
```
1. Download `genomepipe-pro-v4.html`
2. Double-click to open in Chrome / Firefox / Edge
3. Start analyzing variants immediately

### Option 2 — Clone and run locally
```bash
git clone https://github.com/shashwat-sahuu/genomepipe-pro.git
cd genomepipe-pro
# Open genomepipe-pro-v4.html in your browser
```

### Option 3 — GitHub Pages (live URL)
Enable GitHub Pages in repo Settings → Pages → Deploy from branch `main`

---

## 🔑 Optional API Keys

The app works without any API keys, but adding them unlocks higher rate limits:

| Key | Where to get | What it unlocks |
|-----|-------------|-----------------|
| `NCBI API Key` | [ncbi.nlm.nih.gov/account](https://www.ncbi.nlm.nih.gov/account/) | 10 req/s instead of 3 req/s |
| `Claude AI Key` | [console.anthropic.com](https://console.anthropic.com) | AI Clinical Assistant |

Enter keys in the app under **⚙ Settings → API Keys**.

---

## 🌐 External Databases Used

- **Ensembl VEP 110** — Variant consequence prediction (GRCh38)
- **NCBI ClinVar** — Clinical variant classifications (live API)
- **gnomAD v4** — Population allele frequencies (GraphQL API)
- **NCBI Gene** — Gene function and summaries
- **PubMed** — Literature evidence
- **dbSNP 156** — Variant identifiers
- **CADD v1.7** — Pathogenicity scoring
- **SpliceAI** — Splice site prediction

---

## 📁 Repository Structure

```
genomepipe-pro/
├── genomepipe-pro-v4.html   # Complete application (single file)
├── README.md                # This file
├── LICENSE                  # MIT License
└── .gitignore               # Git ignore rules
```

---

## 🔬 ACMG Classification

The ACMG/AMP 2015 classifier implements all 28 evidence criteria:

- **Pathogenic evidence:** PVS1, PS1-4, PM1-6, PP1-5
- **Benign evidence:** BA1, BS1-4, BP1-7
- Weighted scoring with automatic classification

---

## 📋 Clinical Report Contents

Generated reports include:
1. Patient & sample metadata
2. Results summary with classification breakdown
3. Full variant details table (chromosome, position, zygosity, HGVS)
4. Per-variant clinical interpretation (pathogenic/LP variants)
5. VUS monitoring recommendations
6. NCBI enrichment data (gene summaries, ClinVar records, PubMed)
7. ACMG methodology & database versions
8. References
9. Clinical disclaimer

---

## 👨‍💻 Developer

**Shashwat Sahu**  
Bioinformatics Lead  
GitHub: [@shashwat-sahuu](https://github.com/shashwat-sahuu)

---

## 📄 License

MIT License — free for research and educational use.

> **Clinical Disclaimer:** This tool is for research and educational purposes only. It does not constitute a formal clinical laboratory report. Variant classifications should be confirmed by a CLIA-certified laboratory before clinical use.
