# DS 5001 Final Project: Exploratory Text Analytics on Supreme Court Cases

## Overview
This project is the final assignment for DS 5001 Exploratory Text Analytics at the University of Virginia (Spring 2024). The goal is to create a digital analytical edition of a corpus using various text analytics techniques. The corpus selected consists of opinions from 33 significant Supreme Court cases related to civil rights, particularly focusing on race and equality.

## Project Structure
The project involves the following key steps:

1. **Data Acquisition and Processing:**
   - Conversion of Supreme Court case opinions from plaintext to a structured format compliant with the Standard Text Analytic Data Model.
   - Annotation of the corpus using NLP libraries like NLTK.
   - Generation of TF-IDF values and the creation of VOCAB and CORPUS tables.

2. **Modeling:**
   - Application of various unsupervised learning models, including Principal Component Analysis (PCA), Latent Dirichlet Allocation (LDA), and word2vec.
   - Exploration and visualization of the corpus through these models to uncover linguistic, cultural, psychological, or historical patterns.

3. **Visualization and Interpretation:**
   - Visual representation of model results, including scatter plots of PCA components, LDA topic distributions, and other relevant analyses.
   - Drawing conclusions from the patterns observed in the corpus, particularly in the context of civil rights discourse.

## Data
The dataset consists of 33 Supreme Court case opinions, each containing various elements such as the case title, opinion year, the justice who authored the majority opinion, case citation, and formatted sections.

- **Source:** Cornell Law School's Legal Information Institute (LII)
- **File Format:** Plaintext
- **Number of Documents:** 33
- **Total Size:** 2.9 MB

## Key Files
- **Jupyter Notebooks:**
  - `finalprojectwork.ipynb`: The main notebook containing all the steps from data processing to modeling and visualization.

- **Data Files:**
  - LIB, CORPUS, VOCAB tables in CSV format.
  - Derived tables like BOW, DTM, TFIDF, LDA topics, and PCA components.

- **Visualizations:**
  - Scatter plots and charts generated from the models to visualize the results.

## How to Run
To reproduce the results:
1. Clone the repository: `git clone https://github.com/sfissel/DS5001-Final-Project`
2. Navigate to the project directory: `cd DS5001-Final-Project`
3. Open and run the Jupyter Notebook `finalprojectwork.ipynb`.

## Results
The analysis highlights the evolution of civil rights discourse in the U.S. Supreme Court, revealing how the focus of the court has shifted over time, with significant themes identified in different periods.

## Links
- **GitHub Repository:** [DS5001-Final-Project](https://github.com/sfissel/DS5001-Final-Project)
- **UVA Box (Data):** [Project Data](https://virginia.box.com/s/sqk80pa6zhgam8ux4fzshovvvqa88c1c)

## License
This project is licensed under the MIT License.
