# MetaLearningAssignment

'DataProcessing' notebook contains all the data analysis,visualizations and processing.  

'MachineLearningModels' notebook contains building models with classic machine learning methods.  

'DeepLearningModels' notebook contains building mdoels with neural networks.  



All the data(Modified/Processed) can be found in the following drive folder: https://drive.google.com/drive/folders/1yJ_kxs74ZCbjuYVAzl9dhkVFo66_MTfh?usp=sharing

The best accuracy I have acheived was 61% on RNN model. This accuracy is also not reliable since its evaluated on 15% of the balanced dataset which contains 4k+ samples. So 15% of that would be 600+ samples.  

Overfitting was quite prominent while using deep learning algorithms due to the size of the dateset.  
There are many redundant features so even the condensed dataset contained 256 features and to create more reduced dataset I've aggresively removed all the data with more than 50% correlation with any other coloumn. This minimized version also contained 140 features.  
