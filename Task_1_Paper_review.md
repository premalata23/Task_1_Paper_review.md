# **TCGAbiolinks: an R/Bioconductor package for integrative analysis of TCGA data**
### **Authors** ([@slack](https://slack.com/)):
- Dua Gulzar ([@Dua](https://hackbiointern-leo4437.slack.com/team/U07K6A4L18C))
- Premalata Pati ([@Premalata](https://hackbiointern-leo4437.slack.com/team/U07JD8NKQ30))
- Hana Mahmoud Mazroua ([@Mazroua](https://hackbiointern-leo4437.slack.com/team/U07K7K6PVKQ))
- Nourhan Adel Elhifnawy ([@Hifnawy](https://hackbiointern-leo4437.slack.com/team/U07L328NPHN))

### **Video Illustrations**
To check our review video [Click Here](https://www.linkedin.com/posts/nourhan-elhifnawy-577a491b4_cancerresearch-bioinformatics-genesignatures-activity-7238161607745241089-FnLT?utm_source=share&utm_medium=member_android)
## **Introduction**
The growing worldwide cancer burden has prompted programs such as The Cancer Genome Atlas (TCGA), which collects and analyzes clinical and genetic data from 33 cancer types. While TCGA's powerful multi-omics data, which includes genomic, transcriptomic, and proteomic information, presents numerous benefits, it also introduces new hurdles in data integration and interpretation. To address this, the TCGAbiolinks package was created as an R/Bioconductor utility that allows for effective querying, downloading, and analysis of TCGA data. This tool helps researchers undertake integrated analyses, promotes repeatability, and enables breakthrough discoveries in cancer research.

![Fig (1): TCGA Data Overview](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/nar/44/8/10.1093_nar_gkv1507/3/m_gkv1507fig1.jpeg?Expires=1728497241&Signature=re8h2H-lfFR3XPXyJnwLqhhnjnipaMhHIlQ2MgUmsTk9bxU6ceinMfV9K-qoI2jNozHyn-zc2z6SePtUmJjYztNsvTfi8mPo9g7iwN3PW2f4Bf1zvT~YcG1djzeLDx8oGilpq0IG5V9vBAGkkWqA9CugU-0vlhxYsrToEUerZrro2PiVDhXSUgkESgKn9Obe8LqppPQU~buPFMiGv3GiI1EwW2~-BynUH2xPMsyGYxUp3cFwKe27lAWnrjJNB6hubFFlICbOaGOCvb36B403EU0xnpWa-ahjwQ45ZqrUGHGSLjRKXtknLM-rvrG0lb-~Ic0~s3m-YdamoQMt8FjlXg__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)
Fig (1): TCGA Data Overview
## **Materials and Methods**
The **TCGAbiolinks package** includes a number of tools for interacting with TCGA datasets. The primary tools include: \
•	**TCGAquery:** Retrieves clinical and molecular data, including historical records.\
•	**TCGAdownload:** Allows users to download datasets based on their preferences.\
•	**TCGAprepare:** Prepares data for analysis using standard data frames or Summarized Experiment objects.\
•	**TCGAanalyze:** Analyzes TCGA data using molecular and clinical methods, including differential expression, clustering, and survival studies. 

![Fig (2): Materials and Methods](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/nar/44/8/10.1093_nar_gkv1507/3/m_gkv1507fig2.jpeg?Expires=1728497241&Signature=Q4U2gvAiNQtzCJU~-bw~6Rvmxn8-DsXEmMYH96cMUMp8XGuaFd9hLUnkaQow3mpCHq2oub4jaIKmBPVlqWIy42VyJFqwYTR-wJq-MUKSso5X3sFXTB9qO20-Lsb1r-ZXYqL3ddbCdoisJ8s4-hiLNTMEVZvE-jM10SN3xOaAe9vqeOB5VtsMvf~mvNgjI2d68QZ1Q80AULyqCdCebH9KGKIgHuXd7fXnma2XjM~3PGpaG9puWIIP6P3cMyOni6d3Vb0PnbUw-aYbjzNvJUsEStbmhfNN0djGeTh~K9rsdy0xtPxVNMEwozE2Ta766G6rZwT1dDjNP6ECBg~6IRfJ3g__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)
Fig (2): Overview of TCGAbiolinks Functions

TCGAbiolinks also includes tools for heatmaps, survival plots, and other graphical representations. The package has been used in research on breast, brain, kidney, and colon carcinomas. 

## **Results and Discussion**
In **breast cancer research**, TCGAbiolinks found 555 genes with significant differential expression, 160 of which were correlated with survival outcomes via Kaplan-Meier and Cox regression analysis. Gene expression analysis in **lower-grade gliomas (LGG)** identified four subgroups with unique survival characteristics. 

Furthermore, in **colon cancer**, TCGAbiolinks revealed genes with aberrant methylation patterns that were related with differential expression. The **ELMER** software was used in **kidney cancer research** to build regulatory networks and identify key functional modules involved in tumor growth.

These case studies demonstrate TCGAbiolinks' ability to combine several data types, allowing for integrative analysis across multiple malignancies. The package enhances cancer research by providing a streamlined way to investigating the molecular underpinnings of disease, thereby facilitating the discovery of new treatment targets and a better knowledge of cancer biology. 

## **Literature References**

[Colaprico, A., Silva, T. C., Olsen, C., Garofano, L., Cava, C., Garolini, D., ... & Noushmehr, H. (2016). TCGAbiolinks: an R/Bioconductor package for integrative analysis of TCGA data. Nucleic acids research, 44(8), e71-e71.](https://academic.oup.com/nar/article/44/8/e71/2465925)
