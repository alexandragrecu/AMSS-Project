# AMSS-Project
This project was completed as part of the Software Systems Modeling course, taught by Professor Adrian Buturuga. Semester 1, 2022-2023.

## Students - Team 23 
- Grecu Elena-Alexandra
- Necula Alexandru-Florin
- Rotaru Codrut


## Proposed Project
 We created a recycling application that aims to help people recycle more by seeing the recycling process as a game at the end of which they will receive rewards.

 ## How it works
 ![image](https://github.com/alexandragrecu/AMSS-Project/blob/main/how_it_works.jpeg)

 Let's say the users have a water bottle they want to recycle. The first step they take is to scan the barcode of the bottle, thus registering the bottle in the app and earning points for this action. With these points, they can see what rewards they can receive. However, in order to receive a reward, they need to take the water bottle to a recycling center, where their points will be unlocked, and this is when they can receive their rewards.

  The rewards are tickets for buses or theaters, as well as certain discounts at restaurants or local businesses.

## UML Diagrams
All the UML diagrams can be found [here](https://miro.com/app/board/o9J_le1A484=/?share_link_id=783683109578). 
If you can't see the diagrams, zoom out until they appear on the left side of the screen. 

We have:
- One General Diagram - State diagram
- Three Behavioral Diagrams - Communication diagrams
- Three Structural Diagrams - Class diagrams 


## Design patterns
The backend of the application was built in Node.js using the Express framework, the frontend was built in React.js and the database is a non-relational one - MongoDB.

Design patterns:
- Middleware Pattern: We used this pattern [here](https://github.com/alexandragrecu/AMSS-Project/blob/main/backend/controllers/authController.js).
- Singleton Pattern: We used this pattern [here](https://github.com/alexandragrecu/AMSS-Project/blob/main/backend/server.js).



@ Master of Software Engineering, University of Bucharast, Faculty of Mathematics and Computer Science, February 2023
