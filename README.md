#  CanSat Ground Control Software (GCS)

A web-based **Ground Control Station (GCS)** developed during my internship at **India Space Lab (ISL)** for monitoring CanSat telemetry in real time. The application simulates aerospace mission operations through live telemetry visualization, GPS tracking, mission control features, and data monitoring in a modern interactive dashboard.

##  Overview

The CanSat Ground Control Software provides a centralized dashboard for monitoring mission telemetry and controlling various mission operations. It enables users to visualize sensor data, track payload location on a map, monitor system health, and simulate mission commands through an intuitive aerospace-style interface.

##  Features

-  Real-time Telemetry Monitoring
-  Live Data Visualization using Chart.js
-  GPS Tracking with Leaflet.js and OpenStreetMap
-  Mission Control Panel
-  Error Monitoring System
-  Orientation Display (Roll, Pitch & Yaw)
-  Live Camera Streaming using MediaDevices API
-  CSV Export Support
-  Graph Export Functionality
-  Responsive Aerospace-Style Dashboard

##  Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Dashboard Structure |
| CSS3 | Styling & Responsive UI |
| JavaScript | Dynamic Functionality |
| Chart.js | Real-Time Telemetry Graphs |
| Leaflet.js | Interactive GPS Map |
| OpenStreetMap | Mapping Service |
| MediaDevices API | Live Camera Streaming |

##  Screenshots

### Dashboard
<img width="1915" height="827" alt="dashboard" src="https://github.com/user-attachments/assets/3f597dcd-88a1-4717-82ad-a63ec1f35346" />


### Real-Time Telemetry Graph
<img width="1914" height="825" alt="Real Time Graphs" src="https://github.com/user-attachments/assets/cf2e0c4a-b9ae-422c-bad6-d6f1dfa8589c" />


### GPS Tracking
<img width="1875" height="724" alt="GPS" src="https://github.com/user-attachments/assets/bb54e2c3-4e92-49be-824a-3f4a6ebc0a21" />


### Live Video Streaming
<img width="1865" height="820" alt="Vedio" src="https://github.com/user-attachments/assets/2dbe01fa-4426-4c03-a7e8-cb2636d404e1" />


##  Modules

###  Telemetry Dashboard
Displays live mission parameters including:
- Altitude
- Temperature
- Pressure
- Battery Voltage
- GPS Coordinates
- Descent Rate

###  Mission Control
Provides controls for:
- Start Telemetry
- Stop Telemetry
- Export CSV
- Export Graph
- Sync Time
- Reset Packet
- Manual Separation
- Emergency Parachute Deployment
- Redundant Activation

###  Data Visualization
Continuously updates telemetry graphs to help monitor mission performance in real time.

###  GPS Tracking
Tracks payload location on an interactive map using **Leaflet.js** with **OpenStreetMap**.

###  Error Monitoring
Implements a four-digit error code system to identify mission faults and abnormal conditions.

###  Live Video Streaming
Accesses the system camera using the browser MediaDevices API to simulate onboard payload monitoring.

##  Future Improvements

- Connect with real CanSat telemetry hardware
- Live WebSocket communication
- Interactive 3D Orientation Model
- Historical telemetry playback
- Flight path animation
- Mobile responsive layout
- Cloud telemetry storage
- User authentication

##  Learning Outcomes

Through this project, I gained practical experience in:
- Web Application Development
- Aerospace Ground Control Systems
- Real-Time Data Visualization
- GPS Mapping Technologies
- JavaScript APIs
- Frontend Dashboard Design
- Telemetry Monitoring Systems

---

## ⭐ If you found this project interesting, consider giving it a star!
