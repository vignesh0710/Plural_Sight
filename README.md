# Plural_Sight
Solutions for Data Challenge


Instructions to run the code:

1. Download the folder from Github and unzip which will create Plural_sight-master
2. Open this folder -> Unzip the FOLDER data_files_ml_engineer.zip and FILE plural_sight.db.zip. The following image will be the folder structure after these s2 steps

<img width="983" alt="screen shot 2018-05-31 at 6 03 00 pm" src="https://user-images.githubusercontent.com/19801399/40810786-e47888d8-64fc-11e8-949b-ffbe7196c40a.png">

3. Transfer the file to the plural_sight.db to the unzipped data_files_ml_engineer folder.he following image will be the folder structure after these s2 steps
   
<img width="1025" alt="screen shot 2018-05-31 at 6 07 11 pm" src="https://user-images.githubusercontent.com/19801399/40810979-7b49954a-64fd-11e8-9a42-21fb5f9252fc.png">

4. There are 2 ways to run the API

First:

Note: Please use this method to test the results

1. Run the file webapp.py in a editor, copy the URL and run it in a browser
2. The browser window will be like the following image.
<img width="595" alt="screen shot 2018-05-31 at 6 10 46 pm" src="https://user-images.githubusercontent.com/19801399/40811123-0d82d0a2-64fe-11e8-99e9-6bff7c22d0af.png">

3. Enter the user_handle and click 'Submit', in a time of 5 - 10 secs, It will display the summmary of similar users.

<img width="1367" alt="screen shot 2018-05-31 at 6 12 51 pm" src="https://user-images.githubusercontent.com/19801399/40811189-47dbda3c-64fe-11e8-9f28-dde711cf8cfe.png">

4. Please scroll down to check the similar users with the 3 diffrent feature configurations mentioned.

Second:

Note: Please use this in and only if the full pipeline has to be tested, from accessing the csv to displaying the results.
Method 1 mentioned above is preferred

1. Run the file main.py in a editor, to 
  	a. Process the CSV and load into the DB through automatically recognizing the data type of the variables
	b. Preprocess data after converting it into Pandas DF
	c. Creates the feature matrices as mentioned in the approaches section of the Solutions pdf
	d. Stores the feature matrices into /same_folder/dense_matrix.db
	e. Pickles the user_mapping to find the similar users
2. Then follow steps 1 - 4 mentioned in the 'First' way above to run the code
	






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


