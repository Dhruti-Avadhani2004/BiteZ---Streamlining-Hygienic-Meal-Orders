# BiteZ---Streamlining-Hygienic-Meal-Orders
Everything you need to build your very own BiteZ !

<br><br>
As part of my curriculum, for the course, Engineering Exploration and Exploring Sciences, we built this project that beautifully syncs embedded systems and microcontrollers with web dev and computer science. I learnt a ton from working on this project and it was also a lot of fun. In this article, I would delve into "why" and "what motivated me" to choose this topic, and also, how you can build your own version of this project, just like how we did.
<br><br>
As a person who is passionate about food, not just flavors, but also the quality and the life of food fascinates me. Sometimes, we just fail to understand that environmental factors, like temperature and humidity and pollutants in the air also impact the rate of decay of food. When recipes are carefully crafted in our kitchens, why isn't the spoilage given the same amount of care? 
Food at Cafés and Restaurants are barely checked for their stage of decay before consumption. This is where I wish to make a change with our project. Alongside food quality, the quality of crowd management also is an important pointer, to motivate customers to purchase and retain customers. In this project, we also developed a web app through which customers can place their orders and café owners can track the orders, which reduces overcrowding at small cafés and handles wait time correctly. 
With time, this setup can be extended to any kitchen, and not only cafes and restaurants.
<br><br>
We used Thonny IDE for development and Micropython as the programming language.
<br><br>
We wanted to build a fully functional prototype for streamlining meal orders, both for customers and café owners, and ensure that both the customer and the café owners have access to real time sensor data (the sensors are expected to be kept in the kitchen). Which is why, the sensor data is hosted directly onto the webserver on the Raspberry Pi Pico W. 
Later, we also connected an LED display to our sensors and Pico W, so that the real time data can also be displayed onto the LED display. This setup was done due to the following reasons : 
1. We found out from café owners that they do not have the time to check their mobile phones during working hours, and hence they wouldn't be able to track the sensor data. This is where the LED display comes into play. 
2. This sensor data not only helps customers know how good or bad their food is, but it can also help the café owners to keep track of which food to push faster onto their counter based on the sensor readings. 
3. Since the sensor also measures LPG levels in the air, any abnormal levels of LPG due to gas leaks can easily be detected and helps prevent mishaps.
The users/ customers have an order page, through which they can place their orders. The café owners have the admin page through which they can control the meal orders with ease, and both of these web pages can be easily navigated to, through a webserver hosted on the Pico W, that holds the real time data from these sensors.
