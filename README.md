> Thesis: [can be viewed here](https://drive.google.com/file/d/14l5Fl6TvY7nGQdPRiQl3Oi9bP4cag2BP/view?usp=sharing)

# Overview
This is my bachelor thesis project.
In this project, a user's persona is infered from their interactions with the UI. Two machine learning models were used; K-Means and Agglomerative Hierarchical clustering models. The dataset used is the EdNet-KT4, which can be found here: https://github.com/riiid/ednet

## Work Details
**Pre-Processing the Dataset**      
A sample of 20,000 files were chosen from the dataset. This sample was pre-processed and converted into a new dataset, with 29 columns and 20,000 rows. Each row represent a user and each column represents a trait.
This can be seen [here](https://colab.research.google.com/drive/1tCUrFvupGT2WnhpO1kf869bEMRiGR5He#scrollTo=-h2P7EMtC0Xy).  

**Agglomerative Hierarchical**  
The steps and results of the Agglomerative Hierarchical clustering algorithm can be viewed [here](https://colab.research.google.com/drive/1nlJow-c8pgiY6Xi0Tv9ebwSZBZTtj8L1?usp=sharing).  

**K-Means**  
The steps and results of the K-Means clustering algorithm can be viewed [here](https://colab.research.google.com/drive/1_OB3ckbNYpNYJY8nmk8AoDVkaKNkgJXw?usp=sharing).   

**Clusters Analysis**  
The clusters created from both algorithms were analyzed using the mean, median and std values as well as histograms. For the Hierarchical algorithms, analysis can be viewed [here](https://colab.research.google.com/drive/1hDCA-9Go8-N22pmOEtBYiiQ63xDWAj76?usp=sharing). While K-Means clusters' analysis can be viewed [here](https://colab.research.google.com/drive/1SqFRlsR9tj1f41DkSFXudkCKHmYdkGyY?usp=sharing).

## Results
K-Means clusters were prefered over Hierarchical clusters. Based on the analysis done on the clusters, seven personas were found. These personas are: Guided Learner, Exploratory Learner, Focused Learner, Agile Learner, Adaptive Explorer and Reviewer. Details about these personas can be found in the thesis.
