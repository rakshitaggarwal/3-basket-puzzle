# 3-basket-puzzle

There are 3 baskets labeled ‘Apples’, ‘Oranges’ & ‘Mixture’. One of them contains only Apples, one only Oranges and  one has mix of apples and oranges both.
These baskets are not labeled correctly. In fact, the labels on these baskets always lie. (i.e. if the label says Oranges, Then you are sure the basket either has only Apples or Mixture).

You are allowed to pick one fruit from one basket (Not allowed to see other fruits), and you have to put all the labels correctly on the basis of that information (by seeing only one fruit from any one basket).
How will you do that ?

Solution:

Pick a fruit from the basket labeled ‘Mixture’. We know from the question that this basket does not contain ‘Mixture’ for sure.

If this fruit is an apple, then label this Basket as ‘Apple’ (Because this basket does not contain Mixture, so if one is apple, all are apples only). Now we’ve determined that the basket labeled as ‘Mixture’ only contains Apples.

If we look at the basket labeled as ‘Oranges’, we know that since the label is incorrect, this basket either has only apples in it or has Mixture. Since we already know which basket contains only apples, we know that the basket labeled as ‘Oranges’ contains ‘Mixture’. So label it as ‘Mixture’. The 3rd basket will be labeled as ‘Oranges’.

You can apply the same logic if you assume you initially picked an orange from the basket labeled as ‘Mixture’.
