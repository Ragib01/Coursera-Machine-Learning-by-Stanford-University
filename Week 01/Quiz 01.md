# Machine Learning Week 1 Quiz 1 (Introduction) Stanford Coursera

Question 1 
----------
A computer program is said to learn from experience E with

respect to some task T and some performance measure P if its

performance on T, as measured by P, improves with experience E.

Suppose we feed a learning algorithm a lot of historical weather

data, and have it learn to predict weather. What would be a

reasonable choice for P? 


Answer: **The probability of it correctly predicting a future date's weather.**

### Explanation

>T = The weather prediction task.  
P = The probability of it correctly predicting a future date's weather.  
E = The process of the algorithm examining a large amount of historical weather data.


Question 2
----------
Suppose you are working on weather prediction, and use a
learning algorithm to predict tomorrow's temperature (in
degrees Centigrade/Fahrenheit).

Would you treat this as a classification or a regression problem?

* Regression

* Classification

Answer: **Regression**

### Regression
>Continuous values

								OR
Suppose you are working on weather prediction, and you would like to predict whether or not it will be raining at 5pm tomorrow. You want to use a learning algorithm for this. Would you treat this as a classification or a regression problem?

Answer: **Classification**

### Classification
>Classification gives the Prediction in Classified Form or we can say in YES/NO form.

								 OR
The amount of rain that falls in a day is usually measured in either millimeters (mm) or inches. Suppose you use a learning algorithm to predict how much rain will fall tomorrow. Would you treat this as a classification or a regression problem?

Answer: **Regression**
[The amount of rainfall is a continuous-valued output]

Question 3
----------
Suppose you are working on stock market prediction. You would like to predict whether or not a certain company will declare bankruptcy within the next 7 days (by training on data of similar companies that had previously been at risk of bankruptcy). Would you treat this as a classification or a regression problem?

* Regression

* Classification

Answer: **Classification**
[predict whether or not]
								
								OR
Suppose you are working on stock market prediction, and you would like to predict the price of a particular stock tomorrow (measured in dollars). You want to use a learning algorithm for this. Would you treat this as a classification or a regression problem?

Answer: **Regression**
[since as the price of a stock is a continuous-valued output]

Question 4
----------
Some of the problems below are best addressed using a supervised learning algorithm, and the others with an unsupervised learning algorithm. Which of the following would you apply ***supervised*** learning to? (Select all that apply.) In each case, assume some appropriate

dataset is available for your algorithm to learn from.

1.  Examine a web page, and classify whether the content on the web page should be considered "child friendly" (e.g., non-pornographic, etc.) or "adult."
Answer: **supervised**
[A dataset of web pages that have been labeled as "child friendly" or "adult" ]

2. Given data on how 1000 medical patients respond to an experimental drug (such as effectiveness of the treatment, side effects, etc.), discover whether there are different categories or "types" of patients in terms of how they respond to the drug, and if so what these categories are.
Answer: **unsupervised**
[we group 1000 medical patients into different clusters ]

3. In farming, given data on crop yields over the last 50 years, learn to predict next year's crop yields.
Answer: **supervised**
[historical data  to predict next year's crop yields ]

4. Given a large dataset of medical records from patients suffering from heart disease, try to learn whether there might be different clusters of such patients for which we might tailor separate treatments.
Answer: **unsupervised**

5. Take a collection of 1000 essays written on the US Economy, and find a way to automatically group these essays into a small number of groups of essays that are somehow "similar" or "related". 
Answer: **unsupervised**
[This is an unsupervised learning/clustering problem (similar to the Google News example in the lectures) ]

6.  Given genetic (DNA) data from a person, predict the odds of him/her developing diabetes over the next 10 years.
Answer: **supervised**
[we can learn from a labeled dataset comprising different people's genetic data, and labels telling us if they had developed diabetes ]

7. Given 50 articles written by male authors, and 50 articles written by female authors, learn to predict the gender of a new manuscript's author (when the identity of this author is unknown). 
Answer: **supervised**
[we learn from the labeled data to predict gender ]

8. Examine a large collection of emails that are known to be spam email, to discover if there are sub-types of spam mail. 
Answer: **unsupervised**
[This can addressed using a clustering (unsupervised learning) algorithm, to cluster spam mail into sub-types ]

9. Examine the statistics of two football teams, and predicting which team will win tomorrow's match (given historical data of teams' wins/losses to learn from). 
Answer:  **supervised**
[we learn from historical records to make win/loss predictions. ]

Question 5
----------
Which of these is a reasonable definition of machine learning?

* Machine learning is the field of allowing robots to act intelligently.

* Machine learning is the field of study that gives computers the ability to learn without being explicitly programmed.

* Machine learning learns from labeled data.

* Machine learning is the science of programming computers.

Answer: **Machine learning is the field of study that gives computers the ability to learn without being explicitly programmed.**