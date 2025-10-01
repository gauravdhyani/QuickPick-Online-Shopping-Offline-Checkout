# 🚀 QuickPick  
*A seamless in-store shopping experience powered by Wi-Fi RTT navigation, RFID-enabled checkout, and intelligent digital cart integration.*  

---

##  Overview  
**QuickPick** redefines physical retail by eliminating inefficiencies like confusing store layouts and long checkout lines.  
Using **Wi-Fi RTT precision navigation**, **RFID-secured checkout**, and a **digital cart app** (hosted as an Android WebView on **Vercel**), QuickPick ensures a **frictionless shopping journey**.  

---

##  Customer Journey  
1. **Plan Ahead** → Shoppers curate their cart in advance.  
2. **Navigate Smarter** → Wi-Fi RTT provides **sub-meter accuracy**; a **dynamic map** guides shoppers via a **custom BFS pathfinding algorithm** on a JSON-based store layout.  
3. **Find Faster** → OpenCV-based shelf detection ensures accurate routing to shelves.  
4. **Checkout Instantly** → Items confirmed in the digital cart are paid online.  
5. **Exit Smoothly** → RFID tags secure exits; unpaid items trigger alerts.  

---

##  Retailer Dashboard  
- Configure **shelf layouts** visually.  
- Manage **inventory in real-time**.  
- Monitor **cart activity** and **store flow**.  
- Gain insights for **layout optimization** and **stock planning**.  

---

##  Tech Stack  

- **Frontend:** React + Android WebView (hosted on [Vercel](https://vercel.com/))  
- **Backend:** Node.js + Express  
- **Database:** MongoDB (NoSQL)  
- **State Management:** Redux Toolkit  
- **Indoor Positioning:** Wi-Fi RTT (Android/Web)  
- **Navigation Engine:** Custom BFS/Dijkstra pathfinding over JSON store layouts  
- **Computer Vision:** OpenCV (shelf detection on store maps)  
- **Security:** RFID tags + Role-Based Access Control (RBAC)  

---

##  Features  
-  **Indoor navigation** with sub-meter accuracy  
-  **Digital cart integration**  
-  **Frictionless checkout** (RFID-based)  
-  **Retailer dashboard** with real-time analytics  
-  **RBAC-secured management**  

---


