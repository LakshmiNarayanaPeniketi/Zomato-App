# Cost Prediction for Zomato Dataset

Bangalore is most multi-cultural city of India and it is the largest city of Karnataka state. Therefore, it has the restaurants having cuisines from all over the world. It is the best place for food lovers. There are approximately 12000 restaurants in Bangalore.
Therefore, it becomes difficult for someone to decide which restaurant is better and which restaurant provides better rates. Also, if
anyone wants to open a new restaurant in any location, then they have tough competition deciding which cuisine to choose and what
should be the range of approximate cost. Therefore, this Zomato dataset aim to analyse restaurants according to their demography. Also, we can predict the approximate cost for 2 people based on certain number of attributes.
Zomato dataset has following 17 attributes:

url: It shows the url of the restaurant. Each restaurant is assigned a unique url on the Zomato website. There are 51717 unique
values of url in the dataset.

address: It contains the address of the restaurant. There are 11495 unique values in address column.

name: It shows the name of the restaurant. There are 8792 unique values for this column.

online_order: It shows whether the restaurant accepts online order or not. There are approximately 30000 restaurants which accepts
online ordering and approximate 22000 restaurants which doesn’t accept the online order.

book_table: It shows whether table booking is available at the restaurant. There are approximately 45000 restaurants which allows
for table booking and approximate 7000 restaurants which doesn’t allow table booking.

rate: It shows the rating of the restaurant out of 5 stars. It has some values as “NEW”, “-” and null, which means that the restaurant is
not rated yet.

votes: It shows how many numbers of votes the restaurant has received. Mostly all the restaurant has number of votes between 0
and 1000.

phone: It shows the phone number of the restaurant. Only 2% values are null in this column.

location: It shows the neighbourhood in which the restaurant is located. 10% of restaurant are in the BTM neighbourhood and HSR
neighbourhood has 5 % of the total restaurants.

rest_type: It shows the type of the restaurant. This column contains values which are comma separated. For example, value
“Beverage Shop, Quick Bites” means that the restaurant server Quick Bites and Beverages both.

dish_liked: This column shows the dishes liked by people in this restaurant. 54% values are null in this column.

cuisines: It shows the cuisines server by the restaurant. This column also contains comma separated values. For example, value
“Chinese, North Indian, Thai” means that the restaurant server Chinese, North Indian, and Thai.

approx_cost: It shows the approximate cost for two people at the restaurant.

reviews_list: It shows the review posted by customer for the restaurant. It contains rating and the review comment.

menu_item: It shows the menus available at the restaurant.

listed_in(type): It shows the type of meal. 50% values are “Delivery” and 34% values are “Dine-out”. Rest all the values are
combined in 16%.

listed_in(city): It shows the neighbourhood in which the restaurant is located.
REF: https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants
