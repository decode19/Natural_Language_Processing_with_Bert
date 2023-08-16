# Natural_Language_Processing_with_Bert

Applying transfer learning using a pre-trained Bert model for a Natural Language Processing task - Fake News Detection. The Pretrained model has been sourced from Hugging face. The dataset is downloaded from Kaggle. It contains a two CSV files with fake and true news. Data from both CSV's are combined randomly and labels are assigned for Fake and True. 

We freeze the layers of the pretrained Bert model is that it does not loose it previous training and then add a dense layer for the new task. Finally we test the model on an unseen validation dataset. 
