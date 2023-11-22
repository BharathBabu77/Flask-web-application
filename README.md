# Flask-web-application

Project Title: Data Visualization Board

Project Description: The Data Visualization Board is a web application that fetches data from a MongoDB database and presents it in a visually appealing chart format. The application allows users to dynamically filter the data based on various criteria and view the results in real-time. It utilizes AngularJS for the frontend, JavaScript for data manipulation, and Chart.js for chart rendering.

Features:

Interactive Filtering: Users can select different filters such as topic, region, end year, intensity, sector, start year, impact, country, relevance, pestle, and likelihood to refine the data displayed in the chart.

Real-time Data Fetching: The application makes HTTP requests to a MongoDB database to fetch the relevant data based on the selected filter. This ensures that the chart is updated dynamically without needing to reload the page.

Chart Visualization: The fetched data is presented using Chart.js, a popular JavaScript library for creating interactive charts. The chart is rendered in a bar format, allowing users to easily analyze the data and identify trends.

Responsive Design: The web application is designed to be responsive and compatible with different screen sizes and devices. This ensures a consistent and optimal user experience across desktop and mobile platforms.

Technologies Used:

AngularJS: The frontend framework used to build the application's structure and handle data binding and event handling.

JavaScript: Used for data manipulation and handling HTTP requests to fetch data from the MongoDB database.

Chart.js: A JavaScript library for creating interactive charts and visualizations.

MongoDB: The database used to store the data that is fetched and displayed in the chart.

Installation and Usage:

Clone the repository to your local machine.
Install the necessary dependencies by running  npm install  or  yarn install .

Set up a MongoDB database and configure the connection details in the application's code.
Start the application by running  npm start  or  yarn start .

Access the application in your web browser at  http://localhost:3000  or the specified port.
