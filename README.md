# COMP8325 Assignment 1 - Part 2 - 2021


This repository contains individual work for COMP8325 Assignment 1 Part 2.
This readme will also serve as instructions for the tasks in the assignment.

**TASK 1: Touch Biometrics**
Continuous authentication methods for users who are using a smartphone. A touch dataset (in data
folder, available at Google Drive https://drive.google.com/drive/folders/1esR5KU-sw7rqEOi5SjO79_
Okn5vb8b88?usp=sharing) consists of 30 features (in features folder) extracted from raw touch input. Further details about the touch dataset can be found at http://www.mariofrank.net/touchalytics/index.
html. Please answer the following questions:

(1) Implement two more features in addition to the 30 found in the database. Do they have positive
information gain? That is, are the features useful?

(2) Report correlation of these feature to the rest of the implemented features.

(3) Train your model on a binary classifier of your choice (“true user” or “false user” classification problem)
using the following 4 scenarios in which you use a feature selection method to choose top 10 features.
Describe this process. Use 10-fold cross validation to compute precision and recall in the following
scenarios. Try to maximize F1 score when optimizing your classifier. Report F1 and any methods
you used to optimize your classifier.
      
      (a) 10 top features;
      
      (b) 10 top features & your features;
      
      (c) 30 computed features;
      
      (d) 30 computed features & your features and qualitatively describe which family of features are
          most discriminating in your classifier.
          
**TASK 2: Merits of Entropy in Attack Detection/Diagnostics**

Consider a server-log dataset (in server-log.txt) hosted at Google Drive https://drive.google.com/
drive/folders/1esR5KU-sw7rqEOi5SjO79_Okn5vb8b88?usp=sharing. Two attacks happened on a day,
both somewhere around 8am and noon. Please answer the following questions:

      • Identify the exact date and time. What approach did the attackers use?
      
      • There has been significant literature23 discussing how entropy can be used to detect these attacks.
        To do it effectively, approximation schemes are usually used. You do not have to implement these
        approximation techniques, but do present an analysis of whether entropy is useful and which combinations you tried, 
        e.g. src ip, dest ip, src-port, dst-port, etc. Do any reveal anomalies when the two attacks happen?


