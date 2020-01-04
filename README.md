# Devkit

View the project at [https://devkit-ce752.firebaseapp.com](https://devkit-ce752.firebaseapp.com)

This web application helps software developers find the optimal software tool such as APIs or libraries for their project. The project was created to limit the time spent on researching for a software tool. Devkit allows software developers to search for tools and filter the list based on their requirements for the project. Users can recommend specific software tools by clicking the thumbs up button, and other users can view which software tool other developers recommend. If the user has used a tool that is not on the web application, they can request to add it to the list directly from the web application. The request will have to be approved by the developers before it is added to the list.

## Developers
Eshaan Chaudhari<br>
Anton Kanugalawattage

## How we built the project
We created a [REST API](https://github.com/eshaanc20/DevKit-backend) using Express.js and Node.js that is being used by our React front-end. The back-end was deployed to Heroku, and the front-end was deployed to Firebase. The React front-end is using Material-UI. The back-end controls the MongoDB database for this application and uses Mongoose.

Front-end: React, Material-UI<br>
Back-end: Node.js, Express.js<br>
Database: MongoDB with Mongoose

## Running the project locally

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

