Dataset can be downloaded from: https://www.kaggle.com/datasets/

1. Train_data.py is used to convert training dataset to .csv file which contains the image locations and the labels

2. Test_data.py is used to convert test dataset to .csv file which contains the image locations and the labels


Run the above .py files with the changes in the locations so that the folder of the image is updated as per the system.




3. Run the model.ipynb which can save model file in .h5 extension

4. Model prediction is also incorporated in the Model.py 

	Following changes should be done to predict_imgs function:
		
		Line that has to be changed:       img = cv2.resize(X_test[1000], (32, 32))
			
				we can use any number with in the range of the testing dataset to check for the different images