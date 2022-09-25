**STRUCTURE OVERVIEW OF THIS REPOSITORY**

**1. End to End Process for training and making prediction for multimodal classifier**
--> https://colab.research.google.com/drive/1KOcK7pEm8So9VaGdTp2lnAB58MAM9A9F#scrollTo=4Nrs8gl47RvV

The default unit is "Hate Speech Type". Hovewer, "Protected Categories" unit can bee selected by changing the "unit_type" variable.

**2. End to End Process for training and making prediction for Unimodal Text-Only BERT**
 --> https://colab.research.google.com/drive/1Lc4G7w14x8W62dF4SiFVigTnTInk-PUn#scrollTo=gTUjwxmHGxVm
 
To train and make predictions run all cells. The models will be saved in "hate_type" folder for the "Hate Speech Type" unit or "cat" folder for the "Protected Categories" unit. Predictions will be saved at "hate_type/preds" and "cat/preds".
 
 **3. End to End Process for training and making prediction for Vision-Only Image-Grid**
 --> https://colab.research.google.com/drive/1MI2q2-TaD9f4feUILWdUeZMQX3qJ7RmT
 
To train and make predictions run all cells. The models will be saved in "hate_type" folder for "Hate Speech Type" unit or "cat" folder "Protected Categories" unit. Predictions will be saved at "hate_type/preds" and "cat/preds".
 
 **4. Download 8 trained models for "Protected Categories" unit**
 --> https://drive.google.com/drive/folders/1ImGcveePx-yFOP2ugePxZ1R_jDkIjNAj?usp=sharing
 
 This offers a possibility to skip the training process and make predictions for the "Ptotected Categories" unit right away. 
 
 
 **To see the predictions results and the log files, please look up follwoing foulders**
 
 **5. 20models_cat:** foulder with predictions results in csv format and log files for Ensemble of Twenty Models for the “Protected Category” Unit
 
 **6. 27models_type:** foulder with predictions results in csv format and log files for Ensemble of 27 Models for the “Hate Speech Type” Unit
 
 **7. 8models_cat:** foulder with predictions results in csv format and log files for Unimodal Modals for the “Protected Category” Unit
 
 **8. 8models_type:** foulder with predictions results in csv format and log files for Unimodal Modals for the “Hate Speech Type” Unit
 
 **9. Multiclass Data Preprocessing:** The script where newly labeled multiclass "Hatefull Memes" Dataset have been customzied to fit the multiclass framework. The main contents of this scipts are: 
 - function to convert csv file to jsonl file,
 - function to combine the classes (for more details see chapter of the thesis 3.2.),
 - Dataset split in training, evaluation and test sets.
 
 **10. Multiclass Evaluation Metrics:** The scipt where the Confusion Matrices and F1-Score have been implemented and computed to evalaute the multiclass classifier for both units

 **11. Unimodal Evalaution Metrics:** The script where the Confusion Matrices and F1-Score have been implemented and computed to evalaute the unimodal models 
 
 **12. Unimodals Datasets Preprocessing:** The script where multiclass labeled dataset is splitted to fit the definition of the binary problems (for more details see chapter of the thesis 3.4.)
 
