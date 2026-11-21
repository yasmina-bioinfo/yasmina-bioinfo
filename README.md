<p align="center">
  <img src="https://raw.githubusercontent.com/yasmina-bioinfo/yasmina-bioinfo/main/banniere_immuno.png" width="100%">
</p>

<h1 align="center">Hi, I'm <b>Yasmina Soumahoro</b></h1>

<p align="center">
  <em>Immune cell states in human disease, read through single-cell transcriptomics</em>
</p>

---

## About Me

I am a biologist and biology educator with a background in molecular biology, microbiology and immunology, and hands-on training in experimental techniques, including immunohistochemistry and microscopy. My research orientation is computational cancer biology: how the intracellular programs of tumor microenvironment cells relate to their interactions and to the response to immune checkpoint blockade. My latest work is a single-cell study of non-small cell lung cancer under neoadjuvant PD-1 therapy, analysing transcription factor activity and inferred myeloid–CD8 signalling by pathological response in lung adenocarcinoma and lung squamous cell carcinoma.

---

## Featured Work

### Transcription factor activity and inferred myeloid-CD8 signaling by pathological response in lung adenocarcinoma and squamous cell carcinoma after neoadjuvant PD-1 therapy

Single-cell analysis of tumor-infiltrating CD45+ immune cells from patients with non-small cell lung cancer treated with neoadjuvant anti-PD-1 therapy (GSE243013). In lung adenocarcinoma and lung squamous cell carcinoma, analysed separately, the study examines transcription factor activity in CD8 T cells and macrophages, and inferred myeloid–CD8 communication, in relation to pathological response (major pathological response versus non-response).

**Preprint:** [https://doi.org/10.5281/zenodo.24423380](https://doi.org/10.5281/zenodo.24423380) ·
**Code:** [`LUAD_LUSC_CD8_TAM_antiPD1`](https://github.com/yasmina-bioinfo/LUAD_LUSC_CD8_TAM_antiPD1) ([DOI](https://doi.org/10.5281/zenodo.24407433))

- **Nine-block pipeline** (00 to 08), from raw matrix loading to cell–cell communication, each block documented with its parameters and the rationale behind them.
- **TME annotation** with CellTypist (`Immune_All_Low`; Domínguez Conde et al., 2022), validated against the authors' curated marker sets (Domínguez Conde et al., 2022; Mullan et al., 2023).
- **CD8 T cell compartment**: ProjecTILs subtyping, UCell signature scoring, and transcription factor activity via decoupleR/CollecTRI.
- **Tumor-associated macrophages**: scGate purification, and transcription factor activity via decoupleR/CollecTRI.
- **Cell–cell communication**: MultiNicheNet, both contrast directions declared explicitly, with the authors' geneset-to-background diagnostic run before interpretation.
- **Patient-level throughout.** Comparisons between response groups are run on patients, not cells (Wilcoxon with Benjamini–Hochberg correction), to avoid pseudoreplication.
  
---

## Applied Projects

Earlier projects, developed while building my methodology. The featured work above reflects my current standards: patient-level statistics, documented parameters and reproducible pipelines.

| Project | Dataset | Focus |
|---|---|---|
| **CD8_NSCLC_scRNAseq** | GSE131907 + GSE207422 | Cross-dataset synthesis of CD8 exhaustion in lung adenocarcinoma and its association with anti-PD-1 response, built on the two analyses below |
| **scRNA_LUAD_Immunotherapy** | GSE207422 | Integrated single-cell and bulk analysis of T cell functional programs associated with clinical response (PR vs SD) |
| **scRNA_Lung_Cancer_Tcells** | GSE131907 | T cell states across tumor and non-tumor compartments, and transcriptional programs of immune dysfunction |
| **scRNA_SjD_Tcells** | GSE253568 | PBMC T cell heterogeneity in Sjögren's disease: enriched and depleted subclusters, within-state differential expression |
| **scRNA_InfluenzaA** | GSE243629 | Peripheral immune cells in Influenza infection: annotation, T cell analyses, pseudobulk differential expression |
| **Tcell_Influenza_RNAseq** | GSE149689 | Human T cells during Influenza infection, including a critical assessment of dataset suitability and metadata limitations |
| **InfluenzaA_RNAseq** | GSE154596 | End-to-end host–virus bulk RNA-seq: interferon-driven antiviral response |
| **Dual RNA-seq (*H. pylori* – *H. sapiens*)** | GSE243405 | Host–pathogen dual transcriptomics, WT versus KO strains and temporal effects |

---

## Tools & Environment

| | |
|---|---|
| **Languages** | R 4.4.1, Python 3.14 |
| **Single-cell core** | Seurat v5, Harmony, BPCells, CellTypist, ProjecTILs, scGate |
| **Functional analysis** | UCell, decoupleR / CollecTRI, presto, pseudobulk differential expression (DESeq2, edgeR) |
| **Communication** | MultiNicheNet |
| **Reproducibility** | renv lockfiles, `here`-managed relative paths, versioned scripts and structured project documentation |

---

## Foundations in Computational Biology

Projects developed to build solid foundations in computational biology and reproducible analysis, using real biological datasets.

| Project | Description |
|---|---|
| PatternMatching | DNA motif search algorithms |
| SkewArray | GC skew visualization in genomes |
| GCContent | GC content analysis in DNA sequences |
| ReverseComplement | Reverse complement computation with validation |
| MotifFinding | Identification of motif positions in DNA sequences |
| FASTA-Essentials | Multi-FASTA analysis (GC%, heatmaps, boxplots, CSV export) |

---

## Current Focus

- Preprint: [Transcription factor activity and inferred myeloid-CD8 signaling by pathological response in lung adenocarcinoma and squamous cell carcinoma after neoadjuvant PD-1 therapy](https://doi.org/10.5281/zenodo.24423380), with its reproducible pipeline in [`LUAD_LUSC_CD8_TAM_antiPD1`](https://github.com/yasmina-bioinfo/LUAD_LUSC_CD8_TAM_antiPD1)
- Extending the analysis of the tumor microenvironment toward spatial context and cell–cell communication
- Preparing a PhD application in computational cancer biology
---

## Connect with Me

<p align="center">
  <a href="mailto:m.yasminasoumahoro@gmail.com">
    <img src="https://img.shields.io/badge/Email-m.yasminasoumahoro%40gmail.com-blue">
  </a>
  <a href="https://github.com/yasmina-bioinfo">
    <img src="https://img.shields.io/badge/GitHub-yasmina--bioinfo-black?logo=github">
  </a>
  <a href="https://orcid.org/0009-0009-8549-5340">
    <img src="https://img.shields.io/badge/ORCID-0009--0009--8549--5340-A6CE39?logo=orcid&logoColor=white">
  </a>
</p>
