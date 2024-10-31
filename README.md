What's Cooking? 🍲
A dynamic web application for sharing and discovering food recipes. Built with a powerful tech stack and featuring RESTful APIs, "What's Cooking?" allows users to search, view, and contribute unique recipes easily.

Table of Contents
Project Overview
Tech Stack
Features
Setup and Installation
API Endpoints
Usage
Contributing
License
Project Overview
"What's Cooking?" is a full-stack web application developed using Angular for the front end and Spring Boot for the back end. It allows users to browse, search, and add food recipes to a centralized database, making it a versatile platform for food enthusiasts.

Tech Stack
Front-end: Angular
Back-end: Spring Boot
Database: MySQL with Hibernate ORM
API: RESTful APIs for communication between front end and back end


Features
Recipe Browsing: Search and explore recipes from various cuisines.
Recipe Contribution: Registered users can add new recipes.
Database Management: Recipes stored in MySQL for structured data access and scalability.
RESTful APIs: Efficient data exchange between the client and server.


Setup and Installation
Prerequisites
Java: JDK 11+
Node.js: v12+
Angular CLI: Install using npm install -g @angular/cli
MySQL: Ensure MySQL is installed and running
Steps
Clone the Repository

bash
Copy code
git clone https://github.com/praveenreddy2621/Whats-Cooking.git
Back-end Setup

Navigate to the server directory.
Configure MySQL settings in application.properties.
Build and run the Spring Boot application:
bash
Copy code
./mvnw spring-boot:run
Front-end Setup

Navigate to the client directory.
Install dependencies and start the Angular application:
bash
Copy code
npm install
ng serve


API Endpoints
Endpoint	Method	Description
/api/recipes	GET	Retrieve all recipes
/api/recipes/{id}	GET	Retrieve a specific recipe
/api/recipes	POST	Add a new recipe
/api/recipes/{id}	PUT	Update an existing recipe
/api/recipes/{id}	DELETE	Delete a specific recipe


Usage
Access the application at http://localhost:4200.
Use the navigation bar to browse recipes or add a new one if you are a registered user.
Leverage the search feature to find recipes by ingredients, cuisine, or cooking method.


Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License.

