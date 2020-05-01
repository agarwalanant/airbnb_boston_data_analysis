# AirBnB Boston data analysis

Airbnb is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities. It renders an unique and personalized way of experiencing the world and socializing with new people. This dataset describes the listing activity and metrics in Boston, MA for 2019. This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions. What can we learn about AirBnB rentals if we try to model their price? 

### Question which I tried answering in the analysis
The analysis could provide some insights on:
1. What features affect the price? By how much?
2. What are the popular description words in different price groups?
3. What is the effect of neighbour on price of the property?
4. Do superhosts actually charge high enough for their services?
5. How much do I have to pay for extra bedroom?

The notebook contains detailed data cleaning, EDA, and modelling steps with explaination for easy understanding.

### Conclusion of the analysis

1. According to our model, every additional bedroom will cost extra 28.5 dollars, while each additional bathroom will cost extra 2.3 dollars. Each additional guests will cost 6 dollars more.


2. Neighbourhood areas strongly bias the price.

3. Superhosts' listings are 6 dollars more expensive on average. 

4. Entire room on average will cost 76.6 more than a shared-room.

5. Type of property also effects the price, campers/RV are generally cheaper then boat or villa with shows positive corealation.

6. We observe that bathroom cost higher than bedroom, per incease in bathroom higher than bedroom :P

7. There a a lot of overlapping in different price groups, but there is a significant differecence also:
    1. For low price we have word like, neighborhood close, bus, very and access, thus trying to prove th utility of the property.

    2. High price property have words like queen, great, area, floor, street,restraunt trying to justify the price with the facilities and location.
