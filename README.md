# AMP-Discovery-pipeline
This project presents an end-to-end bioinformatics pipeline designed to identify antimicrobial peptides (AMPs) from transcriptomic datasets. The workflow integrates sequence processing, ORF prediction, redundancy reduction, and AMP classification to generate high-confidence peptide candidates.
Objective
To efficiently process large-scale transcriptomic data and identify potential antimicrobial peptides using a structured, reproducible computational workflow.

---

##  Pipeline Workflow

Input Data
Raw transcriptomic sequences (FASTA format)
ORF Prediction
Tool: TransDecoder
Extraction of candidate coding regions from transcripts
Protein Filtering
Removal of incomplete and low-quality sequences
Selection of biologically relevant protein sequences
Redundancy Reduction
Tools: CD-HIT / MMseqs2
Clustering similar sequences to eliminate redundancy
Improves computational efficiency and dataset quality
AMP Prediction
Tool: AMPEP
Classification of peptides based on antimicrobial properties
Output
High-confidence AMP candidate sequences for further validation  

---

##  Tools Used

| Analysis | Tool |
|-----------|---------|
| ORF Prediction | TransDecoder |
| Clustering | CD-HIT |
| AMP Prediction | AMP Scanner |
| Toxicity | ToxinPred |
| Structure Prediction | AlphaFold |
| Docking | HADDOCK |
| Visualization | PyMOL |

---

##  Key Features
- Handles large-scale sequence datasets  
- Modular and reproducible workflow  
- Optimized for efficient filtering and prediction  
- Suitable for research and exploratory analysis  

---

##  Future Improvements
- Integration with machine learning models  
- Automation using Python scripts  
- Deployment on cloud platforms (AWS)

## Top Docking Results

| Candidate | HADDOCK Score |
|------------|------------|
| Pep20 | -78.9 |
| Pep4 | -76.2 |
| Pep25 | -74.3 |
| Pep80 | -72.1 |
| Pep8 | -70.5 |

## Skills Demonstrated

Bioinformatics • Transcriptomics • AMP Discovery • Structural Biology • Molecular Docking • Python • Biopython • HADDOCK • PyMOL
---

## 👩‍💻 Author
Nancy Agarwal
