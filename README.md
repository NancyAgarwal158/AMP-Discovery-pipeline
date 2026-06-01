# AMP-Discovery-pipeline
This project presents an end-to-end bioinformatics pipeline designed to identify antimicrobial peptides (AMPs) from transcriptomic datasets. The workflow integrates sequence processing, ORF prediction, redundancy reduction, and AMP classification to generate high-confidence peptide candidates.
Objective
To efficiently process large-scale transcriptomic data and identify potential antimicrobial peptides using a structured, reproducible computational workflow.

---

##  Pipeline Workflow

The AMP discovery pipeline was designed to identify novel antimicrobial peptides from transcriptomic datasets and evaluate their therapeutic potential against Sortase A.

Step 1: Transcriptome Data Collection

Raw transcriptomic sequences were obtained from publicly available databases and used as the starting dataset for analysis.

Step 2: ORF Prediction

TransDecoder was employed to identify coding regions and generate candidate peptide sequences from transcriptomic data.

Step 3: Redundancy Reduction

CD-HIT was used to cluster similar sequences and remove redundancy, ensuring a non-redundant peptide dataset.

Step 4: AMP Prediction

Candidate peptides were screened using antimicrobial peptide prediction tools to identify sequences with potential antimicrobial activity.

Step 5: Physicochemical Characterization

Selected peptides were evaluated for molecular weight, isoelectric point, hydrophobicity, stability, and other physicochemical properties.

Step 6: Toxicity Assessment

ToxinPred was used to eliminate potentially toxic peptides and retain safe candidates for further investigation.

Step 7: Structure Prediction

Three-dimensional peptide structures were generated using AlphaFold to understand structural features and facilitate docking studies.

Step 8: Molecular Docking

The predicted peptide structures were docked against Sortase A using HADDOCK to evaluate binding affinity and interaction patterns.

Step 9: Structural Validation and Visualization

Ramachandran plot analysis and PyMOL visualization were performed to validate and interpret peptide–protein interactions.

Final Outcome

Five high-confidence antimicrobial peptide candidates (Pep4, Pep8, Pep20, Pep25, and Pep80) were identified and evaluated through computational screening, structural modeling, and docking analyses.

![AMP Discovery Workflow](workflow/methodology_workflow.png)


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
