# Amazon-Reviews-Classification
The Case

Product reviews play a crucial role in the purchasing decision of a customer. Amazon.com, Inc. is one of the largest retailers in the history of the planet with revenues of USD 280 billion in 2019. Each year, customers leave millions of product reviews on the Amazon.com website. Understanding these reviews is crucial for Amazon. In this project, you will explore and model these customer reviews. 

The Data

We have collected millions (Big Volume) of Amazon reviews (Big Variety and Big Veracity) from the past few years. An example review is:

{ 
  "reviewID": "15632",   
  "reviewerID": "A2SUAM1J3GNN3B", 
  "asin": "0000013714", 
  "reviewerName": "J. McDonald", 
  "vote": 5, 
  “isHelpful”: “True”,
  "reviewText": "I bought this for my husband who plays the piano. He is having a wonderful time playing these old hymns. The music is at times hard to read because we think the book was published for singing from more than playing from. Great purchase though!", 
  "overall": 5.0, 
  "summary": "Heavenly Highway Hymns", 
  "unixReviewTime": 1252800000, 
  "reviewTime": "09 13, 2009" 
}

 
Where each review contains the following fields:

•	reviewID – a unique ID of the review

•	reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B

•	asin - ID of the product, e.g. 0000013714

•	reviewerName - name of the reviewer
•	vote – number of helpful votes of the review
•	label – a flag indicating if the review got at least one helpful vote
•	reviewText - text of the review
•	overall - rating of the product
•	summary - summary of the review
•	unixReviewTime - time of the review (unix time)
•	reviewTime - time of the review (raw)

Our dataset includes reviews of three different product categories: Books (books_5_small), Home and Kitchen (home_and_kitchen_5_small), and Video Games (video_games_5).

MISSION: CLassification of Amazon Reviews to see if they are helpful or not.
***NOTE: The Kaggle competition is private
