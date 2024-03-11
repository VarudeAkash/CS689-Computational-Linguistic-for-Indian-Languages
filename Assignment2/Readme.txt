I have used 1000000 (1 lakh) samples out of 4.5 lakh as training examples for question 2

All collab notebooks are stored in '/Answers/Collab_notebooks/' folder
All the required outputs are stored in '/Answers/results' folder


Question 1: Downloaded txt file is stored in '/Answers' folder named 'Question1_answers.txt'

Question 2: I have used two collab notebooks one for training and fine tuning and other for calculating precision, recall, macro_f1 scores
	
	IndicNER:
		i) Training_IndicNER.ipynb : 	In this notebook I have trained and fine tuned the indicNER model on naampadam dataset. I have saved this model using checkpoints. 
		ii)Testing_IndicNER.ipynb : 	In this notebook, I have calculated precision, recall and f1_scores. (I have imported my fine tuned model using checkpoints. )

	IndicBERT:
		i) Training_IndicBERT.ipynb : 		In this notebook I have trained and fine tuned the indicBERT model on naampadam dataset. I have saved this model. 
		ii)Testing_IndicBERT_for_NER.ipynb : 	In this notebook, I have calculated precision, recall and f1_scores. (I have imported my saved model )

Question 3: chatgpt responses are stored in  '/Answers' folder named Question3_answers.txt

Question 4: 
	
	i) Testing outputs of finetuned IndicNER model against my question1 outputs: 
			This is solved in  '/Answers/Collab_notebooks/Testing_IndicNER.ipynb'. You can scroll down the notebookfile, there i have mentioned heading as 'Question4'

	ii)Testing outputs of finetuned IndicBERT model against my question1 outputs: 
			This is solved in  '/Answers/Collab_notebooks/Testing_IndicBERT_for_NER.ipynb'. You can scroll down the notebook file, there i have mentioned heading as 'Question4'

	ii)Testing outputs of chatgpt against my question1 outputs: 
			solved in both of above notebooks i.e. Testing_IndicNER.ipynb and Testing_IndicBERT_for_NER.ipynb

Quesiton 5: Details are stored in '/Answers/Que5_solution.pdf' file 
	