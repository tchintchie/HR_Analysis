# HR_Analysis

The HR department has tasked you with building a prediction model.
You are supposed to figure out if an employee is going to leave or no.

Below are two files, one for training and the other for testing.
The data is nicely formatted, with no missing values, no outliers... can be used as-is but you can wrangle it if you like.

We are predicting the 'left' column, 1 meaning yes and 0 meaning no.

The purpose of this exercise is to get you comfortable with using different models, reading the documentation, trying stuff out...

Here are the steps:

1. Load the HR_train data and do EDA as you see fit. I am not giving instructions as you should explore and decide what to do by yourself.
2. Split data into training/testing sets: https://pastebin.com/1pJkrTCV
3. Build your model with the train data: https://pastebin.com/4JqpvWxV
4. With your model built you need to import the testing data (HR_test) and try your model on it: https://pastebin.com/kpP3vTGf
5. Once done and happy with your score you need to summarize your findings: the HR department would like to know which groups are the most risky and if you see any trends or have suggestions for them on how to improve retention. (for that you will need to do EDA, dataviz... but as mentioned at the beginning, that's up to you).

And that's it.
Try to raise the score by experimenting with column selection, filtering, model tweaking and the introduction of new models.
e.g. if you want to try a decision tree you just do: https://pastebin.com/ffVM0Sit

There are many more models if you want to play around: https://scikit-learn.org/stable/supervised_learning.html
They all follow the same logic of:
1. Import
2. Create an instance of it
3. Train
4. Score

