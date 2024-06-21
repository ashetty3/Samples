# Midterm
## Machine Learning Foundations with Python (90-803)
### Spring 2023


---

**This is an individual test. No communication with other students is allowed. Do not post questions about the midterm in Piazza; this assignment is under exam conditions. You are only allowed to ask clarification questions.**

#### DUE DATE: Thursday, March 16th before 11:59 PM

*Note: even a 1-minute later (whatever the reason) will result in a 0. Plan ahead and deliver ahead of time!*

From the datasets provided, you will be required to complete a series of tasks; please read carefully through them.


---

## Part 1: Prediction

Datasets: [https://www.kaggle.com/unsdsn/world-happiness](https://www.kaggle.com/unsdsn/world-happiness)


From the dataset provided, you will be required to complete the following tasks:

1. Join all 6 datasets into a single dataset and print its output to a file called `WH_2015_2020.csv`. You will work with this file moving forward. 
2. Perform any necessary cleaning steps. 
3. Draw at least two plots that will give you insight into your data and your next steps (this can be a correlation matrix, the distribution of a particular variable, or a density plot, among others). Include an explanation of why these plots are relevant and how they will help you with your models.
4. Predict the happiness score for each country in 2020 (pretend your model hasn't seen 2020!)
	- You will be responsible for creating your training and testing datasets.
	- Take any necessary feature engineering steps
	- Fit three different models, and choose the best model for your data. Make sure to:
		- Properly tune your models(when needed)
		- Perform feature selection (make sure that all the features you are using are significant for your model)
- Validate your model and report your performance metrics. Re-train your model if necessary. Include explanations on the metrics you decide to report.
- Justify - In each step, explain why you choose specific models, features, parameters, and techniques.

Once you have your final model, answer the following questions:

1. What are your predicted scores for the top 5 most happy countries? 
2. What are your predicted scores for the bottom 5 less happy countries?
3. Pick two features to compare the top and bottom 5 countries. How are these features different in the bottom and top countries?
4. How good are the happiness score predictions with your final model?

The submission for this section should be `MidtermMLFP_S23_Prediction_YourNameHere.ipynb`

---

## Part 2: Classification

Dataset: `WFH_WFO_dataset.csv`

Dataset description: [https://www.kaggle.com/datasets/anninasimon/predict-if-people-prefer-wfh-verses-wfo-data](https://www.kaggle.com/datasets/anninasimon/predict-if-people-prefer-wfh-verses-wfo-data)

**Target variable: Target (WFH=1 | WFO=0)**

- WFH = Work from Hom
- WFO - Work from the Office

1. Perform any necessary cleaning steps
2. Draw at least two plots that will give you insight into your data and your next steps (this can be a correlation matrix, the distribution of a particular variable, or a density plot, among others). Include an explanation of why these plots are relevant and how they will help you with your models.
3.  Perform any necessary feature engineering steps (explain and justify).

Classify  the Target variable (WFH vs. WFO)

1. Fit three different models to your dataset
	- Show that you fitted three different models
	- Properly tune all your models
2. Model Selection - Choose the best model for your data
3. Validate all your models and compare the performance between models

Once you have your final model, answer the following questions:

1. Does your classifier have a higher difficulty classifying a particular class? Explain.
2. How good is the classification of your final model?
3. Choose a specific performance metric to report to answer the previous question. Justify why this particular metric would be more relevant to this dataset.

The submission for this section should be `MidtermMLFP_S23_Classification_YourNameHere.ipynb`

---

### General Midterm Notes

- You can decide if you drop any columns, or missing values, but you have to document them and give reasons for them. The reasons cannot be "there were too many variables", "it was too difficult" ,"seemed like an obvious column to drop" or similar.
- You can add subsections to your file if it helps to make it easier/clearer to understand.
- Make each step of the required tasks clear to us, that way, we can easily award you well-deserved points! 
- Remember to use both code and markdown cells, and include comments in your code (we can't read your process off from your mind!).
- Only use the python libraries, techniques, and knowledge learned from Weeks 1-7.
- Please keep all dataset inside the `data` folder.


**Warnings (read carefully)**

- You will receive 0 points for this midterm if you do not submit your Jupyter notebooks (.ipynb) and/or we are not able to run it.
- List any references you used to complete your midterm, even if they are one of the books assigned for this class. If this section is incomplete, you will be deducted 30% of your final grade from this midterm. If you absolutely did not consult any websites, notes, class codes, or even your _own previous code_, then still put a note under references to state this.
- Make sure to name your notebooks properly and push constantly to your github repo.
- Make informative commit messages
- Aside from markdown cells you must include comments throughout your code
- If you use any Python packages that we have not used in class, that specific section of your midterm will receive a 0.

---

### Academic Integrity

- This is strictly an INDIVIDUAL test; any communication with peers, remote people, or anyone will result in an academic integrity violation.
- You are allowed to use your notes, the class material, and the internet to consult package documentation.
- Copying code or text (or similar) from any external sources is considered cheating. This includes stackOverflow, among other websites.
- Even if you are using your own code from previous assignment CITE IT!
-  Using any external tools to generate code or text will also be considered cheating. This includes the use of newer AI technologies such as ChatGPT. According to CMU’s Office of Community Standards and Integrity, CMU’s academic integrity policy addresses the unauthorized use of such tools. Among the three categories of academic integrity violations (i.e., cheating, plagiarism, and unauthorized assistance), “unauthorized assistance” applies most directly, but the other two may also arguably arise. Specifically, the policy states, “In any manner of presentation, it is the responsibility of each student to produce [their] own original academic work. Collaboration or assistance on academic work to be graded is not permitted unless explicitly authorized by the course instructor(s)...Unauthorized assistance refers to the use of sources of support that have not been specifically authorized in this policy statement or by the course instructor(s) in the completion of academic work to be graded.”


**Good luck!**
