# Project Description
This project is a web application that fetches weather data from the OpenWeather API using a OneAPI key. The application is built using Java Servlet technology and JSP for the frontend, enabling users to get current weather information by entering the city name.

Features
Fetch Weather Data: Users can enter a city name to get the current weather information, including temperature, humidity, and weather conditions.
Simple User Interface: A user-friendly interface built with JSP for entering the city name and displaying the weather information.
Error Handling: Handles cases where the city name is invalid or the API request fails.
Tech Stack
Java Servlet: The core backend logic is implemented using Java Servlets to handle HTTP requests and responses.
JSP (JavaServer Pages): Used for creating dynamic web content and rendering the weather information on the web page.
Jakarta EE: Utilized for web application development, leveraging the latest version for better performance and features.
OpenWeather API: Fetches weather data using the OneAPI key provided by OpenWeather.
HTML/CSS: Basic HTML and CSS for structuring and styling the web pages.
Project Structure
index.jsp: The main page where users can enter the city name and see the weather results.
MyServlet.java: The servlet that processes the request, interacts with the OpenWeather API, and sends the response back to the JSP page.
web.xml: Configuration file for the web application, defining servlet mappings and welcome files.
