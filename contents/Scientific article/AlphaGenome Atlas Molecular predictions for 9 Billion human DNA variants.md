---
already_read: true
link: https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/
read_priority: 0
relevance: 4
source: The Batch
tags:
- Large_Language_Model
type: Content
upload_date: '2026-09-26'
---

https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/

## Summary

Google DeepMind’s AlphaGenome Atlas provides a predictive map of the molecular effects of all 9 billion possible single-letter DNA variants in the human genome, accelerating genetic research and disease understanding.

**Scope & Scale**
- Covers every possible single-nucleotide variant (SNV) in the human genome (9B total).
- 1-petabyte dataset, >30x larger than the AlphaFold Database.
- Precomputed predictions for molecular effects across hundreds of human/mouse cell types and tissues.

**Key Tools & Features**
- **AlphaGenome Variant Impact (AVI) score**: Single metric combining AlphaGenome and AlphaMissense predictions to rank variant impact.
- **AVI feature attributions**: Breaks down AVI scores into specific molecular processes (e.g., RNA splicing, gene expression).
- **DNA sequence motifs**: Catalog of >2,500 recurrent DNA "words" and their genomic locations.

**Validation & Performance**
- AVI score achieves best-in-class performance on variant pathogenicity and rare disease benchmarks.
- Works for both coding (2% of genome) and non-coding (98%) regions.

**Real-World Applications**
- Identified causal variants in unsolved rare diseases (e.g., DNM1 linked to epileptic encephalopathy).
- Uncovered 22% more non-coding genetic associations in UK Biobank data (54K participants).
- Pinpointed regulatory variants affecting protein levels (e.g., PLA2G7, EGLN1) and BMI-linked regions.
- Enabled motif analysis to classify transcription factor binding sites (e.g., DNA accessibility vs. gene activation).

**Access & Integration**
- Free for academic use via website portal, API, or Google Antigravity skill.
- Commercial access available via Google Cloud (Model Garden).
- AlphaGenome base model open-source on GitHub for academic use.

**Collaborations**
- Partners include Broad Institute, University of Exeter, Stowers Institute, and GREGoR Consortium.

## Links

- [AlphaGenome Atlas - Predictive Map of DNA Variants](https://deepmind.google/science/alphagenome/atlas) : The official page for AlphaGenome Atlas, a platform containing predictions for the effects of 9 billion single-nucleotide variants in the human genome. It provides an intuitive portal for exploring molecular impact predictions, AVI scores, and DNA sequence motifs.
- [AlphaGenome - AI for Understanding the Genome](https://deepmind.google/science/alphagenome/) : The official page for AlphaGenome, an AI model that predicts how genetic variants impact biological processes. It is foundational to the AlphaGenome Atlas and provides tools for analyzing specific variants.
- [AlphaGenome Community](https://www.alphagenomecommunity.com/) : A community platform for users of AlphaGenome and AlphaGenome Atlas, facilitating collaboration, discussion, and shared resources among researchers.
- [AlphaGenome GitHub Repository](https://github.com/google-deepmind/alphagenome) : The GitHub repository for AlphaGenome, providing access to the base model, research code, and resources for academic and commercial use.
- [AlphaGenome Research GitHub Repository](https://github.com/google-deepmind/alphagenome_research) : A GitHub repository containing research-related code and resources for AlphaGenome Atlas, including tools for variant impact analysis and feature attributions.


## Topics

![[topics/Platform/AlphaGenome Atlas]]

![[topics/Dataset/UK Biobank]]

![[topics/Concept/AVI score]]

![[topics/Model/AlphaGenome]]

![[topics/Model/AlphaMissense]]

![[topics/Platform/Google Antigravity]]