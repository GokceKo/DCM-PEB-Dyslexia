DCM-PEB-Dyslexia

Project Summary

Developmental dyslexia (DD) is a heritable neurodevelopmental disorder that primarily affects reading skills and is often accompanied by motor, attentional, and sensory challenges. This project investigates the neural mechanisms underlying DD by focusing on visuo-attentional processing and its modulation by reading skills and the READ1 variant in the DCDC2 gene (READ1d). Using dynamic causal modelling (DCM), we quantified effective connectivity (EC) within the visuo-attentional system in children with DD and typical readers (TR). Parametric empirical bayes (PEB) analysis was applied to assess the effects of reading skills, genetic susceptibility, and their interaction on cortico-cerebellar connectivity. The results highlight distinctive EC patterns in children with DD, particularly in relation to cerebellar involvement, and underscore the role of genetic factors in shaping neural circuits associated with reading.

Installation & Requirements

Clone the repository:

git clone https://github.com/GokceKo/DCM-PEB-Dyslexia.git

Software Requirements:

MATLAB (R2023a or later)

SPM12 toolbox

Dependencies:
Ensure that SPM12 is added to your MATLAB path.

Usage Instructions

GLM Specification:

Specify and estimate first-level and group-level general linear models using spm batch.

VOI Extraction:

Use the XXXXX.m script to extract Volumes of Interest (VOIs) for DCM analysis.

run('scripts/extract_VOI.m');

DCM Specification & Estimation:

Specify and estimate DCM models using specify_estimate_DCM.m.

run('scripts/specify_estimate_DCM.m');

Group-Level PEB Analysis:

Perform PEB analysis using the SPM batch editor. Load your first-level DCM models and specify the PEB model from the batch interface.

Citation

If you use this code or dataset in your research, please cite our paper:

Author(s). (Year). Title of the paper. Journal Name. DOI: [insert DOI]

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact Information

For questions or further information, please contact:

Gökçe Korkmaz
University of Pavia
goekce.korkmaz01@universitadipavia.it
GitHub: GokceKo
