<!-- "# hack-x-niet-traffic-master"  -->


# Traffic and Route Visualization Web Application
---

![](output.gif)

This is a Python web application that allows users to visualize traffic congestion using a heatmap and find the shortest route between two points. It uses the HERE Traffic API for traffic data and the OpenRouteService API for routing information. The application is built using Flask for the web framework and Folium for map visualization.

## Features
Traffic Heatmap: Users can input coordinates (latitude and longitude) for a specific area and view a traffic heatmap that visualizes traffic congestion in that area.

Shortest Route: Users can input the starting and ending coordinates, select a vehicle type (car, bicycle, or foot), and find the shortest route between the two points on the map.

## Prerequisites
Before running the application, make sure you have the following:

Python 3.x installed on your system.

Required Python packages installed. You can install them using pip:

bash

```pip install folium flask requests openrouteservice herepy

## Getting Started

Clone the repository to your local machine:
```

bash
Copy code
```
git clone https://github.com/your-username/traffic-route-visualization.git
```
Change to the project directory:

bash
Copy code

```cd traffic-route-visualization```
Open the app.py file and replace the API keys with your own API keys:

Replace YOUR_HERE_API_KEY with your HERE Traffic API key.
Replace YOUR_OPENROUTESERVICE_API_KEY with your OpenRouteService API key.
Run the Flask application:

bash
Copy code
```python app.py```
Open your web browser and go to http://localhost:5000 to access the application.

## Usage
Traffic Heatmap:

Enter the latitude and longitude coordinates for a specific area in the input form.
Click the "Show Traffic Heatmap" button to view the traffic congestion heatmap for the selected area.
Shortest Route:

Enter the starting and ending coordinates, select a vehicle type (car, bicycle, or foot) from the dropdown menu.
Click the "Find Shortest Route" button to display the shortest route on the map, along with the estimated duration in hours, minutes, and seconds.
License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
This project uses the HERE Traffic API for traffic data. Make sure to review and comply with their terms of use.
The routing functionality is powered by OpenRouteService. Refer to their documentation for API usage details.
Feel free to customize and enhance this application as needed. Enjoy exploring traffic data and finding the shortest routes!