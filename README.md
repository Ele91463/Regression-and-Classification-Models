# Regression-and-Classification-Models
Regression and Classification methods

For this work, I will investigate three different datasets, each requiring a unique approach to either regression or classification analysis. My report will be structured as a mini scientific paper, following the guidelines and feedback provided on the first homework. In particular, I will introduce the analysis, discuss and justify the choices made, provide comments on the obtained results, and draw some conclusions.
(In this folder, both the R Quarto code and the PDF of the final report generated from it are included.)

In this folder, three homework datasets are presented:

1- Breastfeeding Factors: The data for this part are available in bf.csv, sourced from a study conducted at a UK hospital. The study investigates potential factors influencing pregnant women’s decisions on breastfeeding. The findings could help direct breastfeeding promotion efforts toward women with a lower likelihood of choosing it. For the study, 135 expectant mothers were surveyed on their intended feeding method, classified into two categories: category 1 (coded as 1) includes “breastfeeding,” “attempting to breastfeed,” and “mixed breast and bottle-feeding,” while category 0 represents “exclusive bottle-feeding.” Factors available include pregnancy advancement (pregnancy), how the mothers were fed as babies (howfed), their friends’ feeding choices for their babies (howfedfr), partnership status (partner), age (age), age at the end of full-time education (educat), ethnic group (ethnic), and smoking history (smokebf for past smoking, smokenow for current). All factors are binary, with the first listed level coded as 0.

2- Prostate Cancer Data: For this part, I will work with cancer data investigating the association between the level of prostate-specific antigen (lpsa, measured in ng/ml and log-transformed) and various clinical measures from 97 men about to undergo radical prostatectomy. The explanatory variables include:

lcavol: log(cancer volume in cm³),
lweight: log(prostate weight in g),
age: age in years,
lbph: log(amount of benign prostatic hyperplasia in cm²),
svi: seminal vesicle invasion (1 = yes, 0 = no),
lcp: log(capsular penetration in cm),
gleason: Gleason score for prostate cancer (6, 7, 8, or 9),
pgg45: percentage of Gleason scores 4 or 5 recorded over previous visits before the final score.

3- Leukemia Gene Expression: For this part, I will analyze a gene expression dataset from 79 leukemia patients divided into two subgroups: patients with a chromosomal translocation (coded as “1”) and cytogenetically normal patients (coded as “-1”). The data, provided in gene_expr.tsv, contains expression values for 2,000 genes alongside patient labels. I will perform supervised analysis using support vector machines (SVM) to predict the subgroups.

For each part, I will apply appropriate methods and discuss the rationale behind each choice, interpreting the results and drawing relevant conclusions.


