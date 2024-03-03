# SMS-Spam-Detection-ML
SMS Spam Detection ML Project: This project utilizes various classification models for spam SMS message filtering. It covers data preprocessing, TF-IDF vectorization, classification model training, and evaluation.

### Purpose of the Project:
The SMS-Spam-Detection-ML project is a machine learning initiative focused on enhancing cybersecurity measures in digital communication. In the contemporary business environment, spam messages pose a significant threat not only as a nuisance but also as a potential vector for more serious cybersecurity attacks, including phishing and malware distribution. This project addresses the critical business problem of identifying and filtering unsolicited or harmful messages, thereby protecting the integrity of communication channels, safeguarding sensitive information, and improving overall user experience.

Through the application of advanced classification algorithms—including Random Forest, Logistic Regression, Naive Bayes, and XGBoost—the project aims to develop a robust and reliable model capable of distinguishing between genuine and spam messages. It encompasses a comprehensive approach that includes meticulous data preprocessing, the application of TF-IDF vectorization for feature extraction, rigorous model training, and thorough evaluation metrics. The outcome is a scalable and adaptable solution that businesses can integrate into their existing communication frameworks to minimize the risk of spam, ensuring that message flows remain secure and efficient.

### Data Source:
The data set is a public dataset found on Kaggle, it’s in CSV format, with about 5573 rows. This dataset is a collection of a set of SMS messages that have been collected for SMS Spam research, each message is labeled either as ham(legitimate) or spam. The dataset consists of two columns:

v1 (str)	Label of whether the text message is legit or spam.
Possible values: ham, spam

v2 (str)	Raw text messages

Sample snippet of data:
v1	v2								
ham	Go until jurong point, crazy.. Available only in bugis n great world la e buffet... Cine there got amore wat...
ham	Ok lar... Joking wif u oni...						
spam	Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's
ham	U dun say so early hor... U c already then say...				
spam	FreeMsg Hey there darling it's been 3 week's now and no word back! I'd like some fun you up for it still? Tb ok! XxX std chgs to send, å£1.50 to rcv

Link to dataset: 
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/ 

### How to Run:
Usage

To run the notebook, you will need to have Jupyter installed. If you don't have Jupyter Notebook or JupyterLab installed, you can install it using pip:

```bash
pip install notebook
```

Install packages:
```bash
pip install -r requirements.txt
```


To run the main script:
Open jupyter notebook:
```bash
jupyter notebook
```
This will open a web interface in your default browser. From there, navigate to the SMS_spam_detection.ipynb file and open it. You can run the notebook cells sequentially by pressing Shift + Enter on your keyboard or by using the run button in the interface.

### Libraries Used:

numpy

pandas

nltk

scikit-learn

matplotlib

seaborn

xgboost

lightgbm

catboost

### Classification Models Used:

Naive Bayes

KNN

Decision Tree

Logistic Regression

LightGBM

Random Forest

Catboost

XGBoost
