# Plural_Sight
Solutions for Data Challenge



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


