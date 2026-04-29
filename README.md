# Study title

Metabolomic Signatures of Disease Severity in Pediatric Dengue: Identification of Candidate Biomarkers in Filipino Children

# Authors

Nelly Grace F. Toñacao<sup>1,3<sup> 

John Lennon L. Calorio<sup>1<sup> 

Charisse Joy M. Lim<sup>3,4,5,6,7<sup>

Gennelyne Juruena-Beley<sup>3,4,5<sup>

Lovelle Mae Galia-Marasigan<sup>1,3<sup>

Genevieve Dable-Tupas<sup>1,2,3,4,5<sup>

# Author Institutions: 

<sup>1</sup>Center for Research and Development, Davao Medical School Foundation, Inc., Davao City, Philippines

<sup>2</sup>Department of Public Health and Primary Care, Faculty of Medicine and Health Sciences, Ghent University, Ghent, Belgium

<sup>3</sup>Research and Development Center for Maternal and Child Health (ReDMatCH), Davao Medical School Foundation, Inc., Davao City, Philippines

<sup>4</sup>College of Medicine, Davao Medical School Foundation, Inc., Davao City, Philippines

<sup>5</sup>Southern Philippines Medical Center, Davao City, Philippines

<sup>6</sup>Davao Regional Medical Center, Tagum City, Davao del Norte, Philippines

<sup>7</sup>Davao Doctors Hospital, Davao City, Philippines

# csv files in this repository 

The attached files contain the QC sample data used in the study. These QC samples were used to assess the analytical stability of the samples throughout the runs and were also used in data processing for drift correction and relative standard deviation (RSD) filtering. The data preprocessing includes sequential application of the following methods/steps:

- Removal of features with excessive missingness
- Missing value imputation with 1/5 of the smallest positive value per features
- Signal drift correction and batch effect correction using Quality Control-Robust Spline Correction via the pmp (version 1.22.1) R package
- Data normalization using median
- Mathematical transformation via variance stabilizing normalization
- Data scaling using unit-variance and pareto scaling methods
- Feature filtering via relative standard deviation (RSD)
- Feature filtering via removal of features with low variance


The **Preprocessed QC (Negative Mode).csv** file contails the preprocessed QC data for the *negative* ionization mode, while the **Preprocessed QC (Positive Mode).csv** file contails the preprocessed QC data for the *positive* ionization mode.

# Questions 

Questions should be directed to the corresponding author:

Genevieve Dable-Tupas

gentupas@email.dmsf.edu.ph

