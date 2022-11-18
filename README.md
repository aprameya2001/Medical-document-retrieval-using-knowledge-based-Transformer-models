# Medical-document-retrieval-using-knowledge-based-Transformer-models

## Overview
When it comes to document retrieval for a query, vocabulary mismatch is a significant issue in the medical field. Since the documents are typically authored by professionals, they may contain many specialized terms that are not widely understood or used. Therefore, this retrieval issue in the medical context needs to be resolved. Traditional models like VSM and BM-25 fail in this regard. There has been a lot of work done using neural networks. This kind of model is popularly known as neural learning to rank(NLTR). The more recent method, particularly in the medical field, involves using knowledge bases (KB) that map words to concepts and aid in connecting several words to the same concept. Transformers have recently had a lot of success in NLP. This paper experiments with various Siamese-structured transformer and knowledge based retrieval models to address the retrieval issues in the medical area. After thorough experimentation, it is observed that the proposed retrieval model when combined with UMLSBert\_ENG transformer gives the best results on almost all metrics.


## Repository Link
Link to GitHub Repository:  
https://github.com/aprameya2001/Medical-document-retrieval-using-knowledge-based-Transformer-models


## File Structure
- nfcorpus/ : NFCorpus dataset
- training_scripts/ : All training python notebooks, each notebook containing the methodology to train the model with a different core encoder model
- retrieval_evaluation.ipynb : Notebook for displaying evaluation results of each model
- iap.jpg : Plot of 11-point Interpolated Averaged Precision (IAP)


## Setup
- Clone the git repository:
> git clone https://github.com/aprameya2001/Medical-document-retrieval-using-knowledge-based-Transformer-models.git

- Install all requirements:
> pip install -r requirements.txt

- Each variation of the retrieval model (with a different core encoder model) can be trained by running the corresponding notebook in training_scripts/ folder

- Evaluation of the trained model can be done by the following the process displayed in retrieval_evaluation.ipynb

## Contributors
- Aprameya Dash
- Alimurtaza Mustafa Merchant
- Suyash Chintawar