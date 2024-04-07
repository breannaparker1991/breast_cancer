Breast cancer IDC image prediction 
By Breanna Parker

Background/History:
The images consist of over 5000, 50 x 50 pixel RGB images of stained breast histopathology samples. Being able to detect cancerous cells can be difficult due to mishandling of specimens or improper staining and can be laborious work. 

Data Explanation (Data prep/Data dictionary/etc): 
There are two folders in this project. One has over 5000 images and the other has the corresponding labels. 1 = positive for IDC and 0 = negative for IDC. The data was then split into a train/test split and reshaped. 

Methods: 
I ran six different models to see which one is the most accurate. Those include keras classifier, decision tree classifier, random forest classifier, svc, logistic regression, and kneighbors classifier. 

Analysis:
The svc or random forest classifier are the two most accurate classifiers at around 78%. However, this still isn’t very accurate, especially for a hospital setting. It might be necessary to get a larger sample size for more accurate data. 

Conclusion:
This sample size and models use as is, are not good enough for a hospital setting. Either a bigger sample size or different model is needed to make this more accurate. 

Assumptions:
The biggest assumption that we’re making with this data set is that the pathologists are correct in which images are IDC positive and which ones are negative. If this is at all incurrent, then it will give us issues when trying to find an accurate method. 

Limitations:
Only having a specific number of images and having to try each method to try and find out which one is the most accurate are all limiting to getting the best results. Also, since this is a very important project, if people have cancer, there has to be a high level of accuracy for it to be useful. 

Future Uses/Additional applications:
Being able to identify cancer cells via images is very useful. However, there are many different ways in which we can use image classification for people’s faces, for forest fire detection from photos taken from a drone, or even for grocery shopping. Image classification is very important in our day to day lives and it would be very useful to find a more accurate method for detection. 

Ethical Assessment:
All of these images had to come from women. I don’t think that these women all gave permission for their images to be used in a medical setting. I’m sure that agreeing to tests means that they agree for their information to be used for training purposes. However, is it really okay to be using people’s test results so freely without their consent? 

Appendix:
A;, J. A. (n.d.). Deep Learning for Digital Pathology Image Analysis: A comprehensive tutorial with selected use cases. Journal of pathology informatics. https://pubmed.ncbi.nlm.nih.gov/27563488/ 
Sharma, P. (2024, March 15). Build your first image classification model in just 10 minutes!. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2019/01/build-image-classification-model-10-minutes 
Image datasets:
https://www.kaggle.com/datasets/simjeg/lymphoma-subtype-classification-fl-vs-cll?resource=download , 
https://www.kaggle.com/code/allunia/breast-cancer

