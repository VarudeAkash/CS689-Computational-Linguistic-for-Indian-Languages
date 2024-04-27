Data preprocessing code is written in cleaner.ipynb
The project code is in MarathiHateSpeechClassification.ipynb

As per instructions, Dataset and Model are uploaded to dropbox
Link: https://www.dropbox.com/scl/fo/78xhl9knrtmr91mczn5ig/AHYe63WkfqGbZNoIIC4ozlw?rlkey=hbp2g6cyhnmoaguy7fyg8a1gh&st=olnlr7y6&dl=0	


Dataset:  
	 

	 hate_train, hate_test, hate_valid :		are raw dataset files. 
	 clean_test, clean_train, clean_valid: 		cleaned dataset files (Removed all twitter handles, hashtags, asterisks, special symbols, emojis, english words and links)
	 clean2_test, clean2_train, clean2_valid: 	cleaned dataset files (Removed all twitter handles, special symbols, english words and links)


	 We have used clean2_test, clean2_train, clean2_valid files as final dataset

Implementation:
	Implementation required GPU, hence we used kaggle for implementation
	(if want to run on local machine then change the addresses for importing dataset and saved model accordingly. Also ensure all libraries are installed on local machine)
	

	 