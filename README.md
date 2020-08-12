<h1>Amazon fine food reviews </h1>
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
<ul>
<li>Number of reviews: 568,454</li>
<li>Number of users: 256,059
<li>Number of products: 74,258
<li>Timespan: Oct 1999 - Oct 2012
<li>Number of Attributes/Columns in data: 10
  <?ul>

Data set can be found @ https://www.kaggle.com/snap/amazon-fine-food-reviews

Attribute Information:
<ul>
<li>Id
<li>ProductId - unique identifier for the product
<li>UserId - unqiue identifier for the user
<li>ProfileName
<li>HelpfulnessNumerator - number of users who found the review helpful
<li>HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
<li>Score - rating between 1 and 5
<li>Time - timestamp for the review
<li>Summary - brief summary of the review
<li>Text - text of the review
<li>Objective:- Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).
</ul>
How to determine if a review is positive or negative?<br>
We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
