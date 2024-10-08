# Metabologenomic analysis identifies elevated serum sphingosine-1-phosphate as a pathogenic driver of Ménière’s disease

## Introduction
Ménière’s disease (MD) is a debilitating inner ear disorder characterized by episodic vertigo, fluctuating hearing loss, and tinnitus. Emerging evidence suggests MD is a systemic condition with broader implications such as migraine, osteoporosis, and autoimmune disorders. Despite its significant impact on patients' quality of life, the molecular mechanisms underlying MD remain poorly understood.

## Study Overview
In this study, we employed an integrated multi-omics approach, combining whole-exome sequencing (WES) and metabolomics profiling of MD patients, to elucidate the molecular etiology of MD pathogenesis. We identified 13 novel MD-risk genes (MD13) involved in WNT signaling, epithelial polarization, and lipid transferase activity. Our metabolomic analysis revealed significantly elevated serum sphingosine-1-phosphate (S1P) levels in MD patients. Integration of genetic and metabolomic data demonstrated that variants in MD13 genes, particularly APOB, are associated with the metabolic shifts observed in MD. These findings were further validated using our in-house MD mouse model. Additionally, analysis of public transcriptomic datasets revealed dynamic changes in S1P metabolic enzymes during inner ear development and under MD condition, supporting the critical role of S1P in inner ear homeostasis.

## Key Findings
- Identification of 13 novel MD-risk genes (MD13) involved in key biological pathways.
- Discovery of significantly elevated serum S1P levels in MD patients.
- Demonstration of the association between MD13 gene variants, particularly APOB, and metabolic shifts in MD.
- Validation of findings using an in-house MD mouse model.
- Analysis of public transcriptomic datasets showing dynamic changes in S1P metabolic enzymes during inner ear development and under MD conditions.

## Conclusion
Our study provides the most comprehensive molecular landscape of MD to date, proposing S1P as the central player linking genetic defects, metabolic dysregulation, and inflammatory responses in MD pathogenesis. Importantly, we systematically connect MD with its common comorbidities through S1P dysregulation. Our multi-omics approach unveils novel insights into MD pathophysiology, highlighting S1P signaling as a key therapeutic target for holistic management of MD and its associated conditions, leading to more efficient and effective treatments.

## Repository Contents
### Data
- **md_cohort**
  - `md_cohort.zip`: A compressed file containing sensitive patient data (password-protected for confidentiality; please contact the corresponding author for the password). The zip file contains:
    - `metabolomics_data.rdata`: Metabolomics data from the MD patient cohort.
    - `recurrent_variants_final.rdata`: Whole-exome sequencing data with recurrent variants in the MD patient cohort.
- **md_mice**
  - `metabolomics_data_mice.rdata`: Metabolomics data from the MD mouse model.
  - `transcriptomics_data_mice_fpkm.rdata`: FPKM data from transcriptomics analysis of the MD mouse model.

### Scripts
- **R Scripts Used for Data Analysis**
  - `1_analyze_wes.Rmd`: Script for analyzing WES data.
  - `2_analyze_metabolomics.Rmd`: Script for analyzing metabolomics data.
  - `3_analyze_paired_wes_metabolomics.Rmd`: Script for integrated analysis of paired WES and metabolomics data.
  - `4_analyze_mice_metabolomics.Rmd`: Script for analyzing metabolomics data from the MD mouse model.
  - `5_analyze_mice_transcriptomics.Rmd`: Script for analyzing transcriptomics data (FPKM) from the MD mouse model.


### Results
- Outputs of the data analysis, including figures and tables summarizing the key findings.

### Documentation
- Detailed documentation of the methods used in the study, including step-by-step protocols for WES and metabolomics data processing.

## Usage Instructions
1. **Data Preparation**: Follow the instructions in the `Data` folder to prepare and preprocess the raw data.
2. **Running Analysis**: Use the scripts provided in the `Scripts` folder to replicate the analysis. Ensure that all dependencies and required packages are installed.
3. **Interpreting Results**: Refer to the `Results` folder for the output of the analysis, including visualizations and statistical summaries.
4. **Further Information**: Consult the `Documentation` folder for detailed descriptions of the methodologies and analytical steps.

## Contact Information
For any questions or further information, please contact the following emails:
- **Hao Huang** (Email: xyskhuanghao@csu.edu.cn)
- **Shuai Guo** (Email: ashuai.guo.asg@gmail.com)

This README file provides an overview of the study and instructions for accessing and using the repository contents.
