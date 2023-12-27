# Voice_Validation


### import the data bucket
### prerocess the data "Extract more features from the data "
    extract MFCC features from a WAV file
### train the model
    model = OneClassSVM(kernel='rbf', nu=0.1)  # You can adjust hyperparameters
    model.fit(X_train_standardized)
### test the model
