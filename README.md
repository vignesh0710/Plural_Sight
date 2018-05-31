# Plural_Sight
Solutions for Data Challenge


Instructions to run the code:

1. Download the folder from Github and unzip which will create Plural_sight-master
2. Open this folder and Unzip data_files_ml_engineer.zip
3. In the same folder (Plural_sight-master) unzip the file plural_sight.db.zip and transfer the file to the 
   unzipped data_files_ml_engineer folder.
   
4. <img width="983" alt="screen shot 2018-05-31 at 6 03 00 pm" src="https://user-images.githubusercontent.com/19801399/40810786-e47888d8-64fc-11e8-949b-ffbe7196c40a.png">




Files Description in Data_Files_ML_Engineer:


1. __pycache__ : Folder for python functionality
2. main.py: Runs the main program to process:

	a. Process the CSV and load into the DB through automatically recognizing the data type of the variables
	b. Preprocess data after converting it into Pandas DF
	c. Creates the feature matrices as mentioned in the approaches section of the Solutions pdf
	d. Stores the feature matrices into /same_folder/dense_matrix.db
	e. Pickles the user_mapping to find the similar users
	
3. utilities.py: Helper Functions for pre processing the data and loading the database in main.py
4. model_1.py: creates the dense feature matrices from user-data in main.
5. webapp.py: The files which creates and runs the API to display the similar user details.
6. (4 input CSVs)
7. Templates Folder: Which contains the home.html and pagination.html for the RESTful API


