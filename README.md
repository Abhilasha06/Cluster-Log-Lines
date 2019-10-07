
Preprocessing

All the characters were converted to lower case.
All the special characters were removed.

Keyword extraction

From the preprocessed text all the words and their corresponding frequencies were stored.
The words with frequency less than twenty were stored as stop_words (these words were ignored at the time of training).
 

The generated word cloud looked like this -

![image](https://user-images.githubusercontent.com/43816262/66300988-e361d200-e913-11e9-88a5-1956a7c90e7f.png)
 
The larger words depict larger frequency in the text file.

Model 

K means clustering was used for training.
Elbow method was used for deciding the value of k.
The value of k was chosen as 20 (which is also the maximum allowed value).
The model was trained ignoring the pre stored stop_words.

Link for the task-
https://www.hackerrank.com/contests/gs-quantify-2019/challenges/lining-up-logs
