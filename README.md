Stale Bus Detector (Real-Time Transit Analytics System)
Demo: https://www.linkedin.com/feed/update/urn:li:activity:7369404926990409733/
During my internship at Infotact Solutions, I worked on developing a Real-Time Stale Bus Detector, a data analytics engine and interactive React-based dashboard that monitors live transit activity using GTFS-RT feeds from TransLink (Brisbane, Gold Coast, Sunshine Coast – Australia).
Problem Addressed
Public transit users often rely on real-time maps that sometimes show buses which are not in service, stationary for long period, or off-route — commonly referred to as “ghost buses.”
The goal was to build a system that flags such unreliable vehicles to improve public transit visibility and trust.
Key Contributions & Deliverables
Designed a data ingestion pipeline to continuously fetch and parse GTFS-Realtime transit feeds.
Implemented anomaly detection logic to identify:
Stale or outdated GPS updates
Non-moving buses
Route deviation beyond acceptable thresholds
Built a live map dashboard where:
Active buses → shown in Green
Stale/Stationary buses → shown in Red with an explanation tooltip
Users can toggle visibility of flagged buses to focus on reliable routes.
Tech Stack
React.js, Leaflet.js (Map Visualization)
GTFS-RT Data, REST API Data Pipeline
Docker for containerization
Render for cloud deployment
