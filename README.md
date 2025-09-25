# Google_Map_ZoomIn-Out

## 📖 Project Overview
This Android project demonstrates the use of the **Google Maps API** with zoom in/out functionality.  
It displays a Google Map, places a marker at **Sydney, Australia**, enables satellite map type, and provides zoom controls/gestures for user interaction.

---

## 🛠 Tech Stack
- **Language**: Java  
- **Framework**: Android SDK with Google Play Services (Maps)  
- **IDE**: Android Studio  

---

## 🎯 Key Concepts Implemented
- **Google Maps Integration**:  
  - Implemented using `SupportMapFragment`.  
  - `OnMapReadyCallback` initializes the map once it’s ready.  

- **Marker**:  
  - Added a marker at Sydney (`LatLng(-34, 151)`) with a custom title.  

- **Camera Control**:  
  - Map camera moves to the marker location on startup.  

- **Map Type**:  
  - Set to **Satellite View** using `mMap.setMapType(GoogleMap.MAP_TYPE_SATELLITE)`.  

- **Zoom Controls**:  
  - Enabled built-in zoom buttons: `mMap.getUiSettings().setZoomControlsEnabled(true)`.  
  - Enabled pinch/gesture zoom: `mMap.getUiSettings().setZoomGesturesEnabled(true)`.  
  - (Optional) Manual methods `zoomIn()` and `zoomOut()` are present but commented out.  

---

## ⚙️ Features
- Displays Google Map in Satellite mode.  
- Shows a marker in Sydney, Australia.  
- Built-in zoom in/out controls available.  
- Supports gesture-based zoom.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Google_Map_ZoomIn-Out.git
2. Open in Android Studio.
3. Run the app on an emulator or a physical device with Google Play Services.
4. Interact with the map using zoom buttons or gestures.

---

## 📂 Folder Structure
app/
 ├── java/com/parth/googlemapzoominzoomout/
 │     └── MapsActivity.java   # Main Activity with Google Maps setup
 └── res/
       ├── layout/activity_maps.xml   # Contains SupportMapFragment
       └── values/strings.xml

---

## Screenshot 
![WhatsApp Image 2025-09-25 at 7 23 40 PM](https://github.com/user-attachments/assets/b2ef652e-d2d4-4cda-accd-dc61b9b0995e)
