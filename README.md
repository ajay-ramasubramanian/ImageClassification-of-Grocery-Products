  High level description/presentation of the project
 - We will discuss the relevant theory and evaluate the performance of the existing datasets like the Vegetable Image dataset, Freiburg groceries dataset, and Grocery store image dataset by implying three classification models for each using robust CNN architectures like Resnet18, Googlenet, and Alexnet. We also performed image augmentation techniques where input images are transformed using different transformations like horizontal flip, vertical flip, rotation, and normalization to increase the number of images passed through the network, and then feature extraction, map pooling, non-linear functionality, batch normalization are performed to get an output from a CNN architecture. Finally, we have used Adam Optimiser, a combination of RMS Prop and SGD momentum, to back-propagate the error gradients. Overall, our project proposes multiple classification techniques for the extensive training of varying and complex datasets to attain promising classification results with a relatively high degree of accuracy. Moreover, during our project, we dealt with various challenges such as training data, Imbalanced Data, Interpretability of data, Overfitting, Vanishing gradient problem. Throughout the project, we tried to solve the cghalleneges we faced to maximise the performace of the models.
  
- Requirements to run your Python code (libraries, etc)
    Our Python ipynb files in the source code folder has all the neccesary libraries loaded. So to run the ipynb files download and open those files into a pytorch       running environments such as google colab, kaggle notebooks. Now you just need to execute the cell in order to fetch those libraries. Execute     cell by cell in order  so that no cell is missed while execution. However, please be mindful of the dataset path that needs to be set to the dataset either downloaded into your local drive  path or google drive path. 
    
 SOURCE CODE folder explanation:
 The Source code folder consists of 4 main ipynb files namingly googlenet, resnet18, alexnet and 3rd dataset models. The 3rd dataset models file consists of 3 models trained with each of our choosen CNN Architectures on Vegetable Images dataset. The other 3 files consists of Freiburg dataset and Grocery Store Dataset models in each of the respective file. Additionally the resnt18 file consists of hyperparameter tuning and both resnet18 and googlenet consists of transfer learning models on Freiburg Dataset. SO overall the source code folder has 12 models.
    
- Instruction on how to train/validate your model
As two of our datasets are already split to train test and validation sets you just to set paths for each folder in the dataset. However, in case of freiburg dataset you have specifically mention the test split and validation split so that the dataset can be divided. Further, define a model from pytorch library and run it. Now create a train function to train the defined model on the dataset. Next, define the epochs, optimizer and loss function to call the train function and train the model.
You can find our model codes and saved models at this drive link: https://drive.google.com/drive/folders/1joRlq3WCVWv6RkJBfkj9QfLuWW1DGAPD?usp=share_link

- Instructions on how to run the pre-trained model on the provided sample test dataset
The Sample dataset consists of 100 images of each of 3 datasets. So you can choose any dataset and run it. To run it, please load the model using torch.load("modelname.pt") and next execute model.eval(). Now you can create a training loop with the test dataset and run the model for testing.

How to Obtain the datasets: Please click the below links for downloading datasets

  Freiburg Groceries Dataset: https://drive.google.com/drive/folders/1myukmv8kCX-CaxTNRf2aCpekUVs_2om2?usp=share_link
  
  Grocery Store Dataset: https://drive.google.com/drive/folders/1I4VHgdysyN5jxLHYVRtneTPmvQa5hOB3?usp=share_link
  
  Vegetable Images Dataset: https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset
