## COVIRS-reactogen
Analysis of RNA-seq data (mostly) from participants receiving the Pfizer COVID vaccine clustered by symptoms

### Where is the code and the report?
Please read the [summary report](https://htmlpreview.github.io/?https://github.com/artemiyhussnain/COVIRS-reactogen/blob/main/report.html) for some analysis and the key figures, and the [supp](https://htmlpreview.github.io/?https://github.com/artemiyhussnain/COVIRS-reactogen/blob/main/supp.html) for all code and plots generated in this project. The presentation I gave to the host research group is provided for reference, along with the Rmd file with all R code. 

If the html previews don't work, the raw files can be downloaded and viewed through a browser. If that fails, the relevant pdfs are also in the repo. 

### What is this?
Ryan et al. published a [study](https://doi.org/10.1101/2022.09.22.22280180) (accepted for publication at the time of writing) that used deep multi-omics data to analyse the immune response to the Pfizer and AstraZeneca COVID vaccines. They collected bulk RNA-seq, flow cytometry, antibody, T cell response, and other data before vaccination and after each vaccine dose.

I was interested in finding clusters of participants with similar symptoms, and correlating the differences between them with RNA-seq and flow cytometry data. Are any genes or cell types associated with particular symptoms? Is high reactogenicity (i.e., symptoms) associated with a differences in antibody concentration or cell type composition? 

This was done as part of a [Summer Research Award](https://www.flinders.edu.au/scholarships/college-of-medicine-and-public-health-summer-research-scholarship) with the [Lynn Systems Immunology Group](https://sahmri.org.au/research/themes/precision-cancer-medicine/programs/computational-and-systems-biology/groups/lynn-systems-immunology-group) at SAHMRI in Adelaide. 

The main learning outcomes for me were learning to use DESeq2 for differential expression analysis, fgsea for gene set enrichment analysis, ComplexHeatmap and ggpubr for more advanced visualisation than just ggplot2, structuring a research project (exploratory analysis, posing a good question, preparing a presentation, managing opposing commitments), and working in an academic environment.
