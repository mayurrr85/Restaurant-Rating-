# Restaurant-Rating-Analysis

Case Study
Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences.

Dataset Description
Our data set consists of the following observations which include:

Consumers
Consumer_ID - Unique identifier for each consumer
City - City where the consumer lives
State - State where the consumer lives
Country - Country where the consumer lives
Latitude - Latitude where the consumer lives
Longitude - Longitude where the consumer lives
Smoker - Whether the consumer smokes or not
Drink_Level - Whether the consumer is an abstemious, casual, or social drinker
Transportation_Method - Whether the consumer transports on foot, by public transport, or by car
Marital_Status - The consumer's marital status (single or married)
Children - Whether the consumer has dependent/independent children or kids
Age - The consumer's age
Occupation - The consumer's occupation (student, employed, or unemployed)
Budget - The consumer's budget (low, medium, high)
Consumer_Preferences
Consumer_ID - Unique identifier for each consumer
Preferred_Cuisine - Types of food the consumer prefers

Ratings
Consumer_ID - Unique identifier for each consumer
Restaurant_ID - Unique identifier for each restaurant
Overall_Rating - The overall rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
Food_Rating - The food's rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
Service_Rating - The service rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)

Restaurants
Restaurant_ID - Unique identifier for each restaurant
Name - The restaurant's name
City - The restaurant's city
State - The restaurant's state
Country - The restaurant's country
Zip_Code - The restaurant's zip code
Latitude - The restaurant's latitude
Longitude - The restaurant's longitude
Alcohol_Service - Whether the restaurant serves no alcohol, wine & beer, or a full bar
Smoking_Allowed - Whether any smoking is allowed, including in the bar or in smoking sections
Price - The restaurant's price (low, medium, high)
Franchise - Whether the restaurant is a franchise
Area - Whether the restaurant is in an open or closed area
Parking - Whether the restaurant offers any sort of parking (none, yes, public, valet)

Restaurant_Cuisines
Restaurant_ID - Unique identifier for each restaurant
Cuisine - Types of food the restaurant serves

Data Analysis

Local Insights:
What is the distribution of consumers by city and state?
Most of the population is from San Luis Potosí, San Luis Potosí, while the second largest group is from Cuernavaca, Morelos.

How does the age distribution of consumers vary by state?
In all three states, young adults under 30 years of age form the majority of the population. In two states, San Luis Potosí and Morelos, the second largest demographic consists of seniors, aged over 60 years.

What percentage of consumers are smokers or non-smokers in each city?
The vast majority of consumers from all four cities are non-smokers, with Jiutepec having a 100% non-smoking population. In Cuernavaca city, smokers make up 25% of the population.

How common is parking availability at restaurants in different cities?
The majority of restaurants across all cities lack parking facilities, while some have parking available. In San Luis Potosí and Cuernavaca, two restaurants offer valet parking, while public parking is available in San Luis Potosí, Ciudad Victoria, and Cuernavaca.

Dining Insights:
How does the availability of parking correlate with restaurant price levels?
Out of the 16 high-priced restaurants, 16 have parking available, with 3 offering valet parking, 1 providing public parking, and 5 lacking any parking options. Medium and low-priced restaurants do not offer valet parking; however, some provide public parking or have parking available, while others do not have parking available at all.

What is the distribution of restaurants by state?
San Luis Potosí has 84 restaurants, whereas Morelos and Tamaulipas each have 23 restaurants.

How do restaurant franchises compare to non-franchises in terms of consumer ratings?
The majority of the restaurants are non-franchises, and they are equally distributed across three rating categories: unsatisfactory, satisfactory, and highly satisfactory. A small portion of the restaurants are franchises, and they are also equally distributed across the same three rating categories.

What are consumers' preferred cuisines based on their demographic profiles?
Mexican cuisine is the most preferred, followed by American cuisine.

Hospitality Insights:
How does the type of alcohol service offered vary by restaurants in each city?
In the four cities combined—Jiutepec, San Luis Potosí, Cuernavaca, and Ciudad Victoria—66.92% of restaurants don't offer alcohol, 6.93% offer a full bar, and 26.15% offer wine and beer.

What transportation methods are most commonly used by consumers?
61% of consumers use public transportation, 27% use cars, and 11% walk.

How does the presence of alcohol service influence consumer ratings?
Among non-drinkers, 303 rated their experience as highly satisfactory, 289 as satisfactory, and 170 as unsatisfactory. For wine and beer consumers, the ratings were 146 highly satisfactory, 105 satisfactory, and 68 unsatisfactory. At full bars, 37 rated highly satisfactory, 27 satisfactory, and 16 unsatisfactory.

What percentage of restaurants allow smoking in each state?
Roughly 73% of restaurants maintain smoke-free policies, while only 1.5% in San Luis Potosí and Morelo allow smoking in bar sections. About 7% of restaurants permit smoking overall, with approximately 18.46% offering designated smoking areas.

Behavior Insights:
What are the common occupations of consumers in different state?
In San Luis Potosí, 93% of the population consists of students, with the remaining portion comprising both employed and unemployed individuals. In Morelos, the population is almost equally split between employed individuals and students. In Tamaulipas, 94% of the population are students, while the remaining 6% are employed.

How does the drink level (abstemious, casual, social) vary across different states?
In San Luis Potosí, almost 40% of the population are social drinkers, 36% are casual drinkers, and 23% are abstemious. In Morelos, 45% are abstemious, 41% are casual drinkers, and 12% are social drinkers. In Tamaulipas, 52% are abstemious, 31% are casual drinkers, and 15% are social drinkers.

How does marital status correlate with smoking or drinking habits?
Among 88 single consumers, all are non-smokers, with values decreasing respectively as abstemious, casual drinkers, and social drinkers. Among the married non-smokers, 2 are abstemious and 5 are social drinkers. Additionally, 23 single consumers smoke with values combined, and they are social drinkers and casual drinkers. Lastly, 2 married smokers are also social drinkers.

Is there a relationship between consumers' occupations and their budget levels?
Among the students, 67 have a medium budget, 33 have a low budget, and 4 have a high budget. Additionally, 15 employed individuals and 1 unemployed individual have a medium budget.

Review Insights:
What are the top 5 restaurants by food rating?
The top 5 restaurants with high customer satisfaction - food ratings are Tortas Locas Hipocampo and Puesto de Tacos, where most consumers are highly satisfied. Cafeteria y Restaurante El Pacífico has 9 consumers rating it highly satisfactory, while Gorditas Doa Gloria has received 10. La Cantina Restaurante is rated highly satisfactory by 11 consumers, with the remaining votes split between satisfactory and unsatisfactory.

What are the top 5 restaurants by service rating?
The top 5 restaurants with high customer satisfaction for service ratings are Tortas Locas Hipocampo, where most consumers are satisfied. Puesto de Tacos has received 12 satisfied consumer ratings. Cafeteria y Restaurante El Pacífico also has 12 consumers rating it as satisfactory, while Gorditas Doña Gloria has received the same number. La Cantina Restaurante is rated satisfactory by 7 consumers, with the remaining votes split between highly satisfactory and unsatisfactory.

What are the top 5 restaurants by overall rating?
The top five restaurants with high customer satisfaction ratings are Tortas Locas Hipocampo, where most consumers are highly satisfied, and Puesto de Tacos, which has received 30 highly satisfied consumer ratings. Cafeteria y Restaurante El Pacífico follows closely with 24 consumers rating it as highly satisfactory, while La Cantina Restaurante boasts 28 highly satisfied ratings. Rounding out the list, Restaurant la Chalita has garnered 20 high satisfaction ratings from its customers.

DASHBOARD

<img width="1032" height="592" alt="Screenshot 2025-07-27 185156" src="https://github.com/user-attachments/assets/6b4f3c7e-ef58-46e3-a559-23d993989475" />
<img width="1037" height="599" alt="Screenshot 2025-07-27 185208" src="https://github.com/user-attachments/assets/029a4e46-2fbf-4d97-bbf4-2899b3f833ff" />
<img width="1035" height="605" alt="Screenshot 2025-07-27 185222" src="https://github.com/user-attachments/assets/2581700d-d4a0-426b-9518-7c4fe590c2db" />
<img width="1035" height="593" alt="Screenshot 2025-07-27 185237" src="https://github.com/user-attachments/assets/4e7d96dd-67bb-403d-b254-8346ca418a09" />
<img width="1034" height="601" alt="Screenshot 2025-07-27 185248" src="https://github.com/user-attachments/assets/1dabe0a9-cdaa-4e20-82c5-661d8d0802db" />
