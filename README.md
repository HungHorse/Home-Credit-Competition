# Home-Credit-Competition

# Description of project
### Goal
This is a part of the Practice Project Capston class IS6812 at the University of Utah, David Eccles School of Business. This is my personal notebook for the project, but my team also include Linh Do, Ali Ladha and Sudeeptha Sivarajan. 

This competition originated from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data). Home Credit is a well-established lender operating primarily in the Southeast Asia region. While the region is developing rapidly, the personal loan market still lags behind that of more developed countries. This gap is largely due to a lack of formal credit history. In many cases, credit has been culturally overlooked or limited to informal arrangements between acquaintances or low-tier individual lenders. This pose as a lucrative market for many large credit lenders, that said if they could solve the problem of managing credit risk.

This is where our team comes in. With limited data points on borrowers’ credit history, we clean, train, and test a machine learning model that allows Home Credit to reliably expand its services to new borrowers and proactively manage its risk appetite.

### Datasets
The competition provided seven datasets, but for the purpose of our modeling and to optimize both training time and simplicity, we chose to focus on just two: application_train.csv and previous_application.csv.

### Outcome
Our champion model is a CatBoost classifier, which achieved an accuracy of 70% on the training dataset and a Kaggle score of approximately 70.

# Future Analysis and feedback
## More data points to consider?
Although using only two datasets was part of our initial strategy, I’d love to take this project further for Home Credit. Rather than stopping at a machine learning model that predicts default risk for new customers, I envision expanding it to include models tailored for existing customers and those with established credit histories. This next phase could be seamlessly integrated into every application and become an inseparable part of Home Credit’s lending process.

### Leverage different metrics for success?
Even though accuracy was acceptable and easy to explain, I couldn’t help but envision using other metrics that better reflect the true goal of the competition: identifying default borrowers. In this context, metrics like precision, recall, or a balanced metric such as the F1-score would more effectively capture the business objective. Additionally, I’d be interested in exploring metrics like ROC-AUC, which offer deeper insight into the model's performance across various classification thresholds.

### Learnd from this?
-Function, function, function!
When I first started this competition, I barely used functions in my code. This made my EDA process and the application of models to the test set inconsistent, difficult to manage and overall a nightmare for anyone who try to make sense of my code. However, in this final notebook, embracing the use of functions made managing datasets and training workflows much smoother. Going forward, I plan to take full advantage of this modularity by building reusable function files that can be easily applied to future projects.

-I didn't loved cross validation enough!
Back in my original notebook, I was training each machine learning model manually—one at a time—then testing each on the test set with hand-picked parameters. It was time-consuming, and honestly, the results sometimes felt random. Each model could take hours, and doing this repeatedly really slowed me down. To make things more efficient, I created a cross-validation function that could work with any model from the sklearn library. This made it much easier to train and test consistently, all in one place. It also gave me more confidence in my results, knowing they were based on cross-validation instead of just a single train-test split.

 
