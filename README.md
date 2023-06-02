# Team: The Phospho Force: Protein-prediction project


<p align="center">
  <a href=" https://buckeyemailosu-my.sharepoint.com/:p:/r/personal/dhanashree_1_osu_edu/_layouts/15/Doc.aspx?sourcedoc=%7BA958E0F2-BA24-457D-8319-F0E27EE77B52%7D&file=Protein%20Function%20Prediction.pptx&action=edit&mobileredirect=true">
      <img width="525" height="300" src="slide_preview.png">
  </a>
</p>

The project on Protein Function Prediction (Differentiating Kinases for Targeted Drug Discovery) addresses a critical challenge in drug development by distinguishing between kinases present in prokaryotes, precisely probiotic strains, and those in eukaryotes or pathogenic bacteria. Kinases, a protein essential for cellular signaling, are promising targets for drug discovery due to their involvement in various biological processes. However, the lack of differentiation between kinases across different organisms hinders the development of specific drugs for eukaryotic diseases and infections caused by pathogens.
 
The primary objective of this project is to develop robust models that can accurately predict the functions of proteins based on their sequences. We collected protein sequences from Kaggle.com (CAFA 5 Protein Function Prediction) to use as valuable training data for the models.



## Table of Contents

  - [Process](#process)
  - [Results](#results)
  - [Value](#value)
  - [Future Work](#future-work)
  - [Slides](#slides)


## Process

1. Data preprocessing: Random subsample (n=2000, 10000, 60000), select 100 most frequent GO terms, filter for data with kinases function, K-mer numeric representation, truncate 'sequence' of data, vectorize with TfidfVectorizer().
2. Classifying models: Keras Neural Network, Supposrt Vector Machine, Random Forest.
3. Tuning the models and try to improve their performance in predicting protein functions using different encoding or numeric representation strategies, sub-sampling sizes, layer choice, etc.



## Results

Accuracy was used to assess model performance. 

The Keras neural network performed best with an accuracy of 10-11%. We were able to run this model on our personal computers before the deadline by using k-mer numeric representation, selecting more efficient layers, and reducing the number of observations and classes by extracting the relevant kinase data.


## Value

the Differentiating Kinases for Targeted Drug Discovery project represents a promising opportunity to advance drug development. By establishing strategies to differentiate kinases in prokaryotes from those in eukaryotes or pathogenic bacteria, the project opens doors for designing particular drugs for eukaryotic diseases and infections caused by pathogens. The resulting advancements in targeted drug discovery will have far-reaching implications, including personalized therapies, improved.

## Future Work

1. This model can continue to be improved if allowed more time or computational memory.
2. To comprehensively understand the distinctive characteristics and kinase variations among prokaryotes, eukaryotes, and pathogenic bacteria. 
3. Comparative proteomic study: To compare kinase sequences and regulatory elements, enabling the identification of distinctive patterns.
4. Structural biology techniques:  We will examine kinase protein structures, including active sites and binding pockets. 
5. Kinase profiling: To analyze known kinases in prokaryotic strains, eukaryotes, and pathogenic bacteria to identify shared and unique features. 

## Slides

Additional information can be found in our presentation slides at: https://buckeyemailosu-my.sharepoint.com/:p:/r/personal/dhanashree_1_osu_edu/_layouts/15/Doc.aspx?sourcedoc=%7BA958E0F2-BA24-457D-8319-F0E27EE77B52%7D&file=Protein%20Function%20Prediction.pptx&action=edit&mobileredirect=true
