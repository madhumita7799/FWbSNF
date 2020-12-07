# FWbSNF
A Feature Weighting-Assisted Approach for Cancer Subtypes Identification from Paired Expression profiles

# Related Articles
Madhumita and Sushmita Paul, A Feature Weighting-Assisted Approach for Cancer Subtypes Identification from Paired Expression profiles, 
IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2020, DOI: 10.1109/TCBB.2020.3041723. 
URL: https://pubmed.ncbi.nlm.nih.gov/33259308/

Madhumita and Sushmita Paul, Importance of Feature Weighing in Cervical Cancer Subtypes Identification, 
Proceedings of 19th IEEE International Conference on Bioinformatics and Bioengineering (BIBE2019), Athens, Greece, pp. 86-93, October 2019.
URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8941728

# Abstract
Identification of cancer subtypes is critically important for understanding the heterogeneity present in tumors. Projects like
The Cancer Genome Atlas (TCGA), have made available the data-sets containing expression profiles of multiple types of biomarkers
across the same set of samples. Availability of these types of data-sets help in capturing heterogeneity underlying, complex biological
processes and phenotypes. Further, by integrating information from multiple sources, homogeneous groups for cancer can be
identified. However, there is a lack of computational approaches to identify histological subtypes among the patients suffering from
different types of cancers. Assigning weight to the biomarkers prior to the integration of multiple information sources for the same set of
samples can play an important role in cancer subtypes identification, which has not been explored previously. Sub-typing of cancers
can help in analyzing shared molecular profiles between different histological subtypes of solid tumors. This can further help in
designing appropriate therapies and treatments. A novel method for feature weighting based on robust regression fit is developed in
this study. This method assigns a weight to every biomarker on the basis of variability present across the samples. Later, this weight is
utilized to find similarity between patients individually from each of the information sources. In this study, the two information sources
that have been utilized are miRNA and mRNA expression profiles across the same set of samples. Patient-similarity networks, that are
generated from each of the expression profiles are then integrated using the approach of Similarity Network Fusion. Finally, Spectral
clustering is applied on the fused network to identify similar groups of patients that represent a cancer subtype. To establish the
efficiency of the proposed approach, it has been applied to three types of cancer data-sets and is also compared with the other existing
methods.



