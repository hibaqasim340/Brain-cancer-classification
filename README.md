# Brain-cancer-classification
Brain-Cancer-Gene-Expression-Classification
This project classifies brain cancer using gene expression data. It includes preprocessing, handling missing values, class balancing, feature selection, and training models (Random Forest, XGBoost, SVM) in pipelines to compare performance to better insights in biomedical informatics and cancer research.

Brain cancer
is one of the most aggressive and deadly forms of cancer, with a lower survival rate compared to most other cancers. Tumors in the brain vary by type, shape, and location, making diagnosis and treatment complex.

Early detection is crucial for improving survival chances, but the subtle nature of initial symptoms makes early diagnosis difficult. Because of these challenges, there is a growing demand for Computer-Aided Diagnosis (CAD) systems using Artificial Intelligence to support doctors in identifying and classifying brain tumors more accurately

How Gene Expression is Used for Classification
What Gene Expression Means
Each patient sample (tissue) can be represented by thousands of genes. The expression value tells us how active a gene is. Higher or lower expression levels may indicate disease-specific patterns.

Why It’s Useful in Brain Cancer
Brain cancer subtypes (and normal tissue) each have unique gene expression “signatures.” For instance, a gene may be highly expressed in glioblastoma but low in astrocytoma. These differences form a biological fingerprint that can be exploited for classification.

Turning Biology into Data
• Each sample = one row
• Each gene = one feature (column) • Expression values = numerical features • Label = cancer type (class) This creates a large table where genes are features, and the cancer type is the label.

Machine Learning Role
• Training: The model learns patterns of gene activity that distinguish one cancer type from another. • Testing: Given a new gene expression profile, the model predicts the correct cancer subtype. • Methods: Logistic Regression, Random Forests, SVM, Neural Networks, or dimensionality reduction + classification.

Dataset GSE50161 on brain cancer gene expression from CuMiDa
https://www.kaggle.com/datasets/brunogrisci/brain-cancer-gene-expression-cumida

This project uses the GSE50161 brain cancer gene expression dataset from the Curated Microarray Database (CuMiDa).

Samples: 130

Genes (features): 54,676

Classes (labels): 5

Ependymoma (46 samples)

Glioblastoma (34 samples)

Medulloblastoma (22 samples)

Pilocytic Astrocytoma (15 samples)

Normal Brain Tissue (13 samples) CuMiDa is a collection of 78 carefully curated microarray datasets selected from more than 30,000 GEO studies. The database ensures high-quality preprocessing including removal of unwanted probes, background correction, and normalization.

This dataset is specifically prepared for machine learning research in cancer classification tasks, making it an excellent benchmark for testing feature selection, class balancing, and predictive modeling techniques in bioinformatics.
