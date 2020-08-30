# Q-A-Classifier
Fetch Q&amp;A Questions and classify similar questions together.

Goal : Fetch Q&A Questions and classify them together.

Plan : 
	Input : Twitter thread link .
	Output : Question classified together and summarized to the highest "similarity" question.


How To : 
		a. Fetch a thread
			i. Through the API
			ii. Through web scrapping
		b. Data Structure the thread 
		c. Use some sort of ML / AI to categorize the data 
			i. Keywords
			ii. Similarity between the questions
		d. Output :
			i. Header List : Questions 
List under : User questions. 