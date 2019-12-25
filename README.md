# Introduction

Books are valuble materials for humans. Throughout history, the books industry has evolved from hand written books, to mechanical typing machines, and now to the age of electronic, and audio books. Amazon, Google and many other companies are investing in this field. As the books industry evolved, the number of books has increased dramatically giving the readers very wide variaty of books materials and many options. However, this also put the readers in so much confusion.

# Problem Statment

To make it easier for readers it is very important to classify the books accuratly depending on thier content. Each single book must be labeled according to the title and the description of the book. This process of assigning books to different generes when done manually, can be very tidues, time consuming and costy. <br>
    
Machine Learning with the aid of Natural Language Processing (NLP), can help automating this process and thus, saving the companies both time and money.

In this project our aim is to design a classifier that can assign genere to each book, given their title and description. NLP would be used to process the title and the description of each book before using a Naive Bayes classifier to classify the books.


# Data Descreption

|Feature|Type|Description|
|---|---|---|
|title|object|The title of the book|,
|author|object|The author of the book|,
|rating|float|The rating of the book by the customers|,
|voters|int|The number of customers who voted|,
|price|float|The book price on Google store|,
|currency|object|The currency in which the price is reported|,
|description|object|A breif description of the book given in the store|,
|publisher|object|The publisher of the book|,
|page_count|int|The number of pages of the book|,
|generes|object|The generes under which the book is catogrized|,
|ISBN|object|the unique identification of each book|
|language|object|The language in which the book is written|
|published_date|object|The date at which the book was published|


# Conclusion & Recommendation

- In this project a classification model was developed using NLP analysis and Naieve Bayes Models.
- The best Accuracy found was 0.7427385892116183 for the test and 0.8708333333333333 for train data. 
- The score can be enhanced with more data.
- We recommend that more books be scraped from google books store to achieve higher accuracy for the model.
- It is also recommewnded to build a recommender system and use the NLP analysis to help enhancing the recommendations accuracy.