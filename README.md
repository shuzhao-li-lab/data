# Data Release Index from Shuzhao Li Lab 

By publications:

---
2025. Chi et al., Constructing a consensus serum metabolome. bioRxiv https://doi.org/10.1101/2025.05.07.652782
- R1 release https://github.com/shuzhao-li-lab/consensus_serum_metabolome

2024. Mitchell, J.M., Chi, Y., Thapa, M., Pang, Z., Xia, J. and Li, S., 2024. Common data models to streamline metabolomics processing and annotation, and implementation in a Python pipeline. PLOS Computational Biology, 20(6), p.e1011912.
- Publication site with supplemental files https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011912
- The HZV029 Plasma and HZV029 Two-Phase datasets: https://zenodo.org/records/10974781
- Code repos: The MetDataModel and pcpfm are available through GitHub (https://github.com/shuzhao-li-lab/metDataModel and https://github.com/shuzhao-li-lab/PythonCentricPipelineForMetabolomics)

2024. Mitchell, J.M., Chi, Y., Zheng, S., Thapa, M., Wang, E. and Li, S., 2024. Annotation of Metabolites in Stable Isotope Tracing Untargeted Metabolomics via Khipu-web. Journal of the American Society for Mass Spectrometry, 35(12), pp.2824-2835.
- Publication site with supplemental files https://pubs.acs.org/doi/abs/10.1021/jasms.4c00175
- All data and analysis scripts needed to recapitulate the findings are uploaded to zenodo, DOI: 10.5281/zenodo.11068202.  
- MS data in .mzML format are available at the Metabolomics Workbench as study ST003387.
- Tool URL: https://metabolomics.cloud/khipu

---
2023. Li, et al. Trackable and scalable LC-MS metabolomics data processing using asari. Nature Communications, 14(1), p.4113.

- asari software code is at https://github.com/shuzhao-li/asari
- Jupyter notebooks for data analysis are here under `notebooks/`.
- The MT02 and SZ22 Datasets are here under `data/`.
- The list of verified NIST SRM 1950 features are here under `data/`.
Potentially redundant isomers are colored. Since the goal here is not metabolite identification, but to test if software detects the presence of a real feature, the isomers are not distinguished in experimental data. 
- The BM21 and HZV029 datasets are available at Metabolomics Workbench (https://www.metabolomicsworkbench.org), by IDs ST002233 and ST002454, respectively. 

- The large SLAW dataset (Delabriere et al, 2021) was retrieved from MassIVE (https://massive.ucsd.edu) by study ID MSV000086486. 
- The Yeast201 data (Chen et al, 2021) were retrieved from MassIVE by study ID MSV000087434. 

- The other public datasets used in this work are under Study IDs ST001667 and ST001237 on Metabolomics Workbench. 


## By events or applications

- Frequently used test dataset for Asari processing: MT02 here under `data/`.


