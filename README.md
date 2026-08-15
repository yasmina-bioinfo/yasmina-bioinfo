<p align="center">
  <img src="https://raw.githubusercontent.com/yasmina-bioinfo/yasmina-bioinfo/main/banniere_immuno.png" width="100%">
</p>

<h1 align="center">Hi, I'm <b>Yasmina Soumahoro</b></h1>

<p align="center">
  <em>Immune cell states in human disease, read through single-cell transcriptomics</em>
</p>

---

## About Me

I am a biologist and biology educator working at the interface of experimental immunology and computational transcriptomic analysis. My current work is a single-cell study of the tumor microenvironment in non-small cell lung cancer under neoadjuvant PD-1 blockade, comparing immune organisation between lung adenocarcinoma and lung squamous cell carcinoma (manuscript in preparation).

My interests centre on human immunology — T cell functional states, myeloid programs, and how both are shaped by their tissue context in infection, autoimmunity, and cancer. Across projects, I place equal weight on biological interpretation and on methodological rigour: patient-level statistics rather than cell-level pseudoreplication, documented parameter choices, and pipelines that another person can rerun.

---

## Featured Work

### Immune microenvironment of LUAD versus LUSC under neoadjuvant anti-PD-1 (GSE243013)

Single-cell analysis of tumor-infiltrating CD45+ immune cells across two NSCLC histologies, asking whether lung adenocarcinoma and lung squamous cell carcinoma organise their immune compartment differently under the same therapeutic pressure. Response to treatment (major pathological response versus non-response) is analysed as a secondary axis, used to test the robustness of the histology comparison rather than as the primary question.

**Repository:** [`TAM_CD8_LUAD_LUSC_scRNAseq`](https://github.com/yasmina-bioinfo/TAM_CD8_LUAD_LUSC_scRNAseq) · Manuscript in preparation

- **Nine-block pipeline**, from raw matrix loading to differential cell–cell communication, each block documented with its parameters and the rationale behind them.
- **TME annotation** with CellTypist (`Immune_All_Low`), validated cluster by cluster against canonical markers.
- **CD8 T cell compartment**: ProjecTILs subtyping, UCell signature scoring, transcription factor activity via decoupleR/CollecTRI, and TCR repertoire analysis with scRepertoire.
- **Tumor-associated macrophages**: scGate purification, phenotyping against three published frameworks, metabolic programs, and a full-lineage sensitivity analysis.
- **Cell–cell communication**: MultiNicheNet, both contrast directions declared explicitly, with the authors' geneset-to-background diagnostic run before interpretation.
- **Patient-level throughout.** An apparent difference in macrophage abundance between histologies was traced to pseudoreplication in an early cell-level test and did not survive patient-level retesting. The correction is documented in the repository rather than quietly removed.

---

## Applied Projects

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
| **Repertoire & communication** | scRepertoire, MultiNicheNet |
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

- Finalising the LUAD versus LUSC tumor microenvironment manuscript
- Extending single-cell analysis toward integrative and multi-modal approaches
- Preparing a PhD application in tumor immunology

---

## Connect with Me

<p align="center">
  <a href="mailto:m.yasminasoumahoro@gmail.com">
    <img src="https://img.shields.io/badge/Email-m.yasminasoumahoro%40gmail.com-blue">
  </a>
  <a href="https://github.com/yasmina-bioinfo">
    <img src="https://img.shields.io/badge/GitHub-yasmina--bioinfo-black?logo=github">
  </a>
  <a href="https://linkedin.com/in/yasmina-soumahoro">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin">
  </a>
</p>
