# adversarial-detection

For any dataset:

You should run the colab file multiple times by selecting different options from the below menu:

Press 0, 1, 2 , 3 , 4 , 5 :

train mode (0)

test set uncertainty metrics for correct and wrong predictions (1)

Prepare Last Hidden Layer Outputs (2)

Train MLP (3)

Prepare Data (4)

Plot Performances (5)


You first need to train your CNN model by chosing option 0.

Then, you need to get the last hidden layer activations of all clean, noisy and perturbed samples by chosing option 2.

Then, chose option 3 to train the MLP model on previously obtained last hidden layer activations.

Chose Option 4 to quantify all the metrics for clean, noisy and perturbed test samples and label the data appropriately.

Chose Option 5 to train the LR model and obtain the ROC-AUC scores for adversarial detection.

To obtain the detection results, you should complete option 0, 2, 3 , 4 and 5 in the given order.

All the files will be stored on your google drive. 


*Cite The DataSet*  
If you find those results useful please cite them :

@ARTICLE{2020arXiv201206390F,
       author = {{Faruk Tuna}, Omer and {Ozgur Catak}, Ferhat and {Taner Eskil}, M.},
        title = "{Closeness and Uncertainty Aware Adversarial Examples Detection in Adversarial Machine Learning}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Machine Learning, Computer Science - Artificial Intelligence},
         year = 2020,
        month = dec,
          eid = {arXiv:2012.06390},
        pages = {arXiv:2012.06390},
archivePrefix = {arXiv},
       eprint = {2012.06390},
 primaryClass = {cs.LG},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2020arXiv201206390F},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
