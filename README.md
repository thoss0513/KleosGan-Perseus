# Supervised GAN-BERT for Authorship Attribution on Archaic Greek Poetry
Co-Authored by Olivia McCauley, Toufiq Hossain, and Austin Ho 

## Abstract 
This study presents the application of a super- vised BERT-GAN model to authorship attri- bution tasks on Archaic Greek texts. 
Due to small text corpora, linguistic obscurity, and limited availability of open-source NLP tools, authorship attribution with 
traditional neural classifiers in this problem area is challenging. We incorporated adversarial training into an authorship 
attribution task on Archaic Greek corpora as a means of data augmentation in a low-resource language setting. Using a BERT 
model fine-tuned on Ancient Greek, we ex- tracted CLS tokens that the GAN’s generator could imitate, introducing more training examples without the need for feature extraction and text modification. 
Our BERT-GAN outperforms our baseline model by a small margin, but through our experiments, we demonstrate that employing sampling techniques for data augmentation significantly optimizes our model’s performance. 
This approach not only pushes the boundaries of traditional literary analysis but also sets a precedent for the use of advanced machine-learning techniques in the study of ancient texts.


## Code 
For the organized file structure, please see the following Google Drive folder: [Supervised_Greek_GAN-BERT](https://drive.google.com/drive/folders/1v0XvzgL1NaGIRTIXZrr0T6zwvl8eWcWz?usp=sharing).
Updated versions of the code and data repeatedly failed to push to GitHub due to large file sizes, we were unable to resolve this error prior to
the submission deadline. Please refer to the Google Drive files instead of the GitHub repo, although all critical files are available 
but unorganized in the GitHub. 

The Modeling Notebooks are in the Model folder in Drive: 
* best_10k_sgan_metrics_final.ipynb
* undersampled_sgan_metrics_final (1).ipynb
* imbalanced_sgan_metrics_final (1).ipynb

Data is stored in Google Drive as the files are too large to store in Github. 
