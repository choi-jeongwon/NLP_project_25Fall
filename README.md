Code, data, and references used for the 2025 Fall NLP project:
Comparing Language Use Across Academic Disciplines Using arXiv Preprints

----Repository Structure---
df_sample.csv

code_arxiv_NLP.ipynb

dictionary/elp_database.csv

References/
* Bafna et al. (2016) – Document clustering TF–IDF approach 
* Chen et al. (2023) – When text mining meets science mapping in the bibliometric analysis
* Haggan. (2024) - Research paper titles in literature, linguistics and science: dimensions of attraction 
* Hong et al. (2025) – Has higher education become more interdisciplinary 
* Kostoff (2012) – Text mining for science and technology: a review, part I 
* Kostoff et al. (2001) – Text mining using database tomography and bibliometrics 
* Lucy et al. (2023) – Words as Gatekeepers 
* McCarthy et al. (2008) – Are Three Words All We Need? 
* McGillivray et al. (2022) – Investigating patterns of change, stability, and interaction among disciplines using embeddings 
* Rahman et al. (2025) – Automated Research Article Classification and Recommendation Using NLP and ML 
* Suurmond et al. (2024) – Text mining and network analytics for literature reviews 
* Whissell (1999) – Linguistic Complexity of Abstracts and Titles in Highly Cited Journals 


----Details----
1. Dataset:
   df_cleaned.csv is the cleaned analysis dataset. Sample size: N = 1000, Sampling: 200 papers each from five selected arXiv disciplines with three variables: paper_id, Title, Summary, Cleaned_Primary_Category.
   * Raw data source: Kaggle “Papers by subject” dataset (arplusman): https://www.kaggle.com/datasets/arplusman/papers-by-subject

2. Code
   code_arxiv_NLP.ipynb contains the full workflow (data cleaning, sampling, and analysis).
   * Notes: Originally run in Google Colab. If running locally, update file paths as needed.

3. Dictionary
   used elp_database.csv as dictionary
   
4. References
   References folder PDFs of papers cited in the paper.
