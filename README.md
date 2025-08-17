## 🚗 Ride Sharing and Trip Planning System

A Python-based web application built using Streamlit and NetworkX to optimize ride-sharing routes and multi-stop trip planning using powerful graph algorithms like BFS, Prim's, and TSP (Branch & Bound).

## 🔧 Features

🚘 Ride Sharing Optimization
- Supports shared rides for 2 to 5 users
- Calculates shortest and cost-effective paths
- Visualizes optimized routes on interactive maps

## 🗺 Multi-Stop Trip Planning
Create routes with multiple destinations

Choose between:

- Fixed order of stops
- TSP-optimized path for minimum distance
- Displays total distance, estimated time, and cost

## 📊 Algorithms Used
- Shortest Path – BFS (via Dijkstra’s algorithm)
- Minimum Spanning Tree – Prim’s algorithm
- Traveling Salesman Problem – Branch & Bound approach

🗂 Project Structure

     ride_sharing_app/

             ├── app.py             # Streamlit main application file

             └── requirements.txt   # Python dependencies



## ⚙️ Setup and Installation

1.Clone the repository

       git clone https://github.com/yourusername/ride-sharing-app.git

       cd ride-sharing-app



2.Install dependencies

        pip install -r requirements.txt




3.Run the application
        
        streamlit run app.py



## 🧪 Usage Instructions
Use the sidebar to:

- Add multiple locations
- Choose transportation mode (car/bike)
- Plan a single ride or multi-stop trip
- View results as optimized routes with distance, time, and cost

## 📌 Requirements

     Python 3.8 or above

     Required libraries:

     streamlit

     networkx

     folium

     openrouteservice

     pandas

     numpy




