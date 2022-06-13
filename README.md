# Covid-Reproducible
Reproducible Material for my final project. 

**NOTE this wont be able to be reproduced unless you have a ProQuest research account.** 

The steps to follow for reproducing the results are outlined by the number on each notebook.

Notebook [one](https://github.com/Halifaxi/Covid-Reproducible/blob/main/(1)_Roberta_Covid_News_Training.ipynb) goes over the training process so that the SiEBERT model is finetuned on the 1000 covid annotations which is also in the repository. The annotations.csv file should be moved into your own google drive for it to work. The [colab requirements](https://github.com/Halifaxi/Covid-Reproducible/blob/main/colab_training_requirements.txt) file will allow the correct packages to be installed. The other [requirements file](https://github.com/Halifaxi/Covid-Reproducible/blob/main/proquest_requirements.txt) is used for notebook two. 

With the trained model, you have to transfer it to ProQuest which will take around two hours. All you need to transfer is the saved .pth file from torch.save(). 

Next, you use notebook [two](https://github.com/Halifaxi/Covid-Reproducible/blob/main/(2)TDM_data_preprocessing_exploratory.ipynb) to preprocess all of the proquest data and get it into the right form for model prediction which happens in notebook [3](https://github.com/Halifaxi/Covid-Reproducible/blob/main/(3)prediction_w_roberta.ipynb). Running the predictions on the articles takes about 80 hours with a GPU. Notebook [four](https://github.com/Halifaxi/Covid-Reproducible/blob/main/(4)corona_analysis.ipynb) will then get you the article data required which is finally analyzed in notebook [five](https://github.com/Halifaxi/Covid-Reproducible/blob/main/(5)plotting_and_analysis.ipynb).

Because of ProQuest's rules, I am avoiding putting the saved article data in the repo. So the only way to complete notebook five is to use all of the steps as outlined above. 

Message me for further information.

