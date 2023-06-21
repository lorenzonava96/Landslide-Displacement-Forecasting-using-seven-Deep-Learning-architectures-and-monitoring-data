## Training and hyperparameter tuning of the Deep Learning models.

#### The notebook will save four outputs for each model. The user has to generate the following folder structure:

    data/
    
        models/
    
              "name of the model"
              (repeate for every model)/
          
                                  weights/
                                          "the notebook will save .hdf5 file with the best weights 
                                           of each parameters combinations"

                                  plots/
                                        "the notebook will save plots of training and validation learning and loss curves"
                                  
                                  preds/
                                         "the notebook will save plots of predictions vs measured values for the entire test set"      
            
                                  results/
                                         "the notebook will save a .csv file containing all details of each 
                                          models with respectives evaluation scores on the test data"      
