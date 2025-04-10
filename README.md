# geo-routing-boston

### 🚀 TL;DR  
This project was developed for MIT's 2025 **iQuHack** quantum computing hackathon. It visualizes the shortest paths between hundreds of Boston restaurants (in blue) and homeless shelters (in red) using geospatial data (via Folium) and a combination of greedy and Dijkstra’s algorithms.

---

### 🧠 Project Overview  
At the 2025 **MIT iQuHack**, my team built a solution aimed at minimizing food waste and improving food accessibility for the unhoused population in Boston. The core idea was to connect restaurants with excess food to nearby homeless shelters and soup kitchens, optimizing for both distance and resource distribution.

---

### 🗺️ What I Built  
I developed a **geospatial map** of Boston using the Folium Python library, marking:
- **Restaurants** in blue  
- **Homeless shelters** in red  

To determine efficient food delivery routes:
- I applied **Dijkstra's algorithm** to find the shortest walking/driving path between each restaurant and shelter.
- Then, I used a **greedy algorithm** to assign each restaurant to its **nearest** shelter, reducing redundancy and minimizing travel.

---

### 🧩 Quantum Optimization  
The rest of the program integrates a **quantum annealing function** to:
- Account for food availability at restaurants  
- Consider donation needs of shelters  
- **Optimize the delivery path** so users can meet their food donation quota with the least travel distance

---

### 🎯 Intended Impact  
This project is designed for **Boston-area homeless shelters and soup kitchens**. Using the interactive map, these organizations can:
- Identify nearby restaurants open to food donation  
- Plan efficient pickup routes  
- Reduce transportation costs and time

---

### 🧾 Full Project Repository  
👉 [GitHub: iQuHack_DWave](https://github.com/NandeeneeSingh/iQuHack_DWave)

---

### 📁 Repository Contents  
This repository contains all the code and data necessary for the project, including:

- **Map**: A Folium-based interactive geospatial map that visualizes Boston's restaurants and shelters, with markers for each location.
- **Map Code**: Python code used to generate the interactive map, implement the algorithms, and display the routes.
- **CSV Files**: Geospatial data for the restaurants and shelters in Boston, stored in CSV format for easy access and analysis.
  
You can find all files in the repository to run the project locally, modify it for your own use, or integrate it into future initiatives.
