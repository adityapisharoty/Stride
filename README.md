# Stride
Stride is a full-stack mapping and navigation application made in C++ that prioritizes non-motorized travellers. It integrates public transit and weather APIs for an enhanced user experience. Made for ECE297 at the University of Toronto (Docs Only)

> **Note:** This repository documents the project only. **Source code is not included** per course policy.

## 📖 Overview  
Stride is a usability-driven mapping tool designed for **non-motorized travellers**, including pedestrians, cyclists, and transit riders. Built for **ECE297: Software Design and Communication**, it prioritizes **clarity, responsiveness, and live feedback** to support car-free travel.    

## ✅ Demo

| Dark Mode | Transit Toggles |  
|-----------|----------------|  
| <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/dark_mode_demo.gif" /> | <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/transit_all_demo.gif" /> |  

| Dynamic Rendering | Directions for Cars |  
|-----------------|----------------|  
| <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/zoom_demo.gif" /> | <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/car_directions.png" /> |  

| Directions for Cyclists | Directions for Pedestrians |  
|---------------------|-----------------------|  
| <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/cyclist_directions.png" /> | <img width="400" src="https://github.com/adityapisharoty/Stride/blob/main/Demo%20Files/pedestrian_directions.png" /> |  

## 🔑 Features  

### 🧭 Usability & UI  
- **Minimalist Interface**: Clear layouts and simple travel options.  
- **Dark Mode**: Reduces eye strain and improves readability at night.  
- **Dynamic Rendering**: Zoom-based rendering reduces clutter and speeds up performance.  
- **Customizable Appearance**: Toggle subway, bus, and streetcar routes.  
- **Responsive Search**: Autocomplete and fuzzy matching for faster input.  

### ⚡ Smart Navigation & Optimization  
- **Optimized Dijkstra’s Algorithm**: Pre-loading + minimized runtime computations → faster than baseline A*.  
- **Courier/TSP Routing**:  
  - Multi-destination Dijkstra’s  
  - Greedy depot selection  
  - 2-Opt, 3-Opt, and Simulated Annealing refinements  
- **Performance**: ~6.89% better than TA Moderate benchmark.

## ⚙️ Technical Highlights  
- **Language**: C++
- **Graphics**: EZGL and GTK libraries  
- **Routing Algorithms**: Optimized Dijkstra, 2-Opt, 3-Opt, Simulated Annealing  
- **Rendering**: Smart rendering, dynamic grouping, zoom-aware selective display  
- **UI Design**: Dark mode, customizable toggles, minimalist layout  
- **Scalability**: Tile-based loading for large map datasets  
  
## 👥 Team  
**Team CD-042**: 
- Aayush Chellani
- Aditya Pisharoty    
- Katherine Ye  

## 📌 Acknowledgements  
- Course staff for framework and datasets  
- External references on **usability, rendering, active transportation, and urban navigation**  

## 📜 License  
This repository contains documentation and media only. No source code is distributed. Unless otherwise noted, text and images © the authors. For educational use.  

## 📝 References  
- Nielsen, J. (1999). *Designing Web Usability: The Practice of Simplicity*.  
- Palmer & Schloss (2016). *Color Preference*.  
- Hopfauf, B. *Is Dark Mode Better for Your Eyes?*  
- De Boer, W. *Fast Terrain Rendering Using Geometrical MipMapping*.  
- Olayode et al. (2024). *Barriers Affecting Promotion of Active Transportation*.  
- Pew Research Center (2015). *Usage and Attitudes Toward Smartphones*.  
- United Nations (2023). *World Population Urbanization Projections*.  
- U.S. Census Bureau (2014). *Biking to Work Statistics*.  
