SENTRA – AI Powered Women's Safety System

SENTRA is an AI-driven proactive safety platform designed to help women travel safely by combining intelligent routing, real-time monitoring, and on-device threat detection.

Unlike traditional safety apps that depend only on a manual SOS button, SENTRA continuously evaluates the surrounding environment and guides users through safer routes while monitoring potential threats automatically.

The system integrates AI models, geospatial analysis, and sensor data to detect risks and notify authorities in real time.



🚀 Key Features

🗺️ SafeNav – Intelligent Safe Routing

Traditional navigation apps optimize for shortest distance or fastest time.
SENTRA introduces safety-aware routing.

The system evaluates multiple routes and assigns a safety score based on environmental factors.

Safety Score Calculation





Base Score: Distance of route (shorter routes preferred)



Safety Bonus: Segments near open businesses or crowded areas



Risk Penalty: Segments passing through high-risk zones

The safest route is highlighted for the user.



🔋 Adaptive Polling – Smart Battery Optimization

Continuous monitoring can drain device battery. SENTRA solves this using zone-based adaptive polling.

Zone TypeBehaviorGreen ZoneGPS updates every 5 minutes, monitoring disabledYellow ZoneGPS updates every 1 minute, sensors on standbyRed ZoneReal-time GPS streaming and active threat detection

This ensures maximum safety with minimal battery usage.



🎧 Sentinel Audio – AI Threat Detection

SENTRA includes an on-device machine learning model that detects potential threats using environmental audio.

The model detects sounds such as:





Screaming



Glass breaking



Aggressive shouting



📍 Algorithmic Geofencing

Instead of manually marking unsafe areas, SENTRA automatically identifies risk zones using clustering algorithms.

Method Used

DBSCAN (Density Based Spatial Clustering)

Input





Historical incident reports



Crowd density indicators



Location patterns

Output

Automatically generated high-risk zones displayed on the map.



🧠 Core Technologies





Flutter / React Native



Python FastAPI



TensorFlow Lite



Firebase / Supabase



Mapbox / Google Maps API



DBSCAN Clustering Algorithm



📊 Example Workflow





User starts navigation in the app.



SENTRA fetches multiple possible routes.



Each route is analyzed using safety scoring logic.



The safest route is suggested.



While travelling:





location updates are monitored



sensors activate in high-risk zones



If a threat is detected:





SOS alert is triggered



location is sent to the monitoring dashboard.



🔒 Privacy & Security





All audio analysis is performed on-device



No continuous recording or cloud storage of user audio



Location data is encrypted and shared only during emergencies.
