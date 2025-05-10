# 🗺️ Accessible Navigation: Smart, Inclusive, Efficient Map Routing System

---

## ✨ Project Overview

This project implements an interactive, accessible, and high-performance geographic map system. The system provides:
- ✅ **Accessible navigation** for users with color-blindness or language barriers
- ✅ **Intuitive user interface** with fast feedback and visual clarity
- ✅ **Efficient routing** for couriers and delivery agents across city maps

---

## 📅 Timeline & Milestones

| Milestone | Highlights |
|----------|-----------|
| **M1** | Built back-end APIs and fast data structures |
| **M2** | Developed interactive map visualization & partial rendering |
| **M3** | Integrated routing algorithms with UI logic |
| **M4** | Implemented simulated annealing + ACO courier routing engine |

---

## 🔍 Features

### 🗺️ Interactive Map Interface
- Panning and zooming with visual overlays
- Partial rendering: updates only what is needed
- Preloaded map data for speed

![alt text](image.png) 
![alt text](image-1.png)

---

### ⚙️ API and Functionality
- Locate intersections from partial names
- Find closest intersections
- Highlight and label results
- Built with performance constraints: <0.1s interactions

---

### 🔄 Routing Algorithms
- **Dijkstra-based Greedy**: fast, but not always optimal
- **Simulated Annealing**: explores alternate paths
- **ACO (Ant Colony Optimization)**: pheromone-inspired global search
- **2-Opt / 3-Opt**: fine-tune route paths for travel-time reduction

![alt text](image84.jpg)
![alt text](image94.png)

---

### 🧑‍🦯 Accessibility First
- **Color Blind Mode**: simulate Protanopia, Tritanopia with friendly palettes
- **Language Switch**: auto-detect spoken language and switch UI
- **Instructional Aids**: route arrows, hover info, helper videos

![alt text](image83.png)
![alt text](image114.png)

---

## ✅ Usability & Performance

| Metric | Description |
|--------|-------------|
| ⏱️ **Responsiveness** | Feedback within 100ms–1s |
| 🔢 **Search Speed** | Constant or log-time lookup |
| 🌐 **Inclusivity** | Designed for color-blind, low-literacy, multilingual users |

---

## 🌐 Future Extensions

- Integrate real-time traffic for adaptive routing
- Personalize paths for wheelchair users, elderly, etc.
- Fully voice-driven UI interaction

---

## 📚 References

For full sources, see slide 66 of our final presentation. Major citations include:
- Colblindor: Color-blind simulation
- Nielsen Norman Group: UI responsiveness
- Kakao Maps Tech Blog

---

## 👨‍💻 Team Members

- **Ryan (Shidu) Ren** 
- **Cathy Zhang**
- **Paul Yang**