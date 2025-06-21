## Autonomous Parallel Path Planning System  
A web app comparing parallel vs sequential pathfinding algorithms using Chennai's road network.

### 📊 Algorithms Compared  
**Parallel Implementations:**  
- Dijkstra  
- A\*  
- Bellman-Ford  

**Sequential Implementations:**  
- Dijkstra  
- A\*  

### Tech Stack  
**Frontend:**  
- Next.js 15 + React 19  
- React-Leaflet + OpenStreetMap  
- Zustand state management  

**Backend:**  
- Flask (Python)  
- NetworkX/OSMnx for graph processing  
- Python threading/multiprocessing  

### Key Features  
- Interactive map with route visualization  
- Real-time performance comparison  
- Travel time/distance estimates  
- Responsive modern UI  

### Setup  
1. Clone repo:  
   ```sh
   git clone https://github.com/amruthae218/PathFinder.git
   ```
2. **Backend:**  
   ```sh
   cd backend
   python3 -m venv venv
   source venv/bin/activate  # Linux/macOS
   pip install -r requirements.txt
   python app.py  # Runs on http://localhost:9000
   ```
3. **Frontend:**  
   ```sh
   cd frontend
   npm install
   npm run dev  # Runs on http://localhost:3000
   ```

