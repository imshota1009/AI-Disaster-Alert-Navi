# 🛠️ Disaster Preparedness App

This app is a **browser-based disaster support tool** that provides **one-stop access to essential information during emergencies**.  
By leveraging public APIs, you can view **earthquake information, evacuation site search, disaster news, and preparedness checklists** all on a single screen.  

It also supports **multiple languages (Japanese, English, Korean, Chinese)**, making it useful for foreign residents in Japan.  


---

## ✨ Key Features

### 1. Earthquake Information
- ⏱ **Real-time updates**: Automatically fetches the latest earthquake data every minute  
- 🏠 **Regional settings**: Select from all 47 prefectures (saved in your browser)  
- 🔔 **Personalized display**: Prioritizes earthquakes in your selected region  
- 🎨 **Visualized intensity**: Card colors change according to seismic intensity for quick risk recognition  

---

### 2. Evacuation Site Search
- 📍 **Search from current location**: Uses device geolocation to display nearby evacuation sites (*demo data for now*)  
- 🗺️ **Route guidance**: Linked with Google Maps for evacuation routes  

---

### 3. Disaster News
- 📰 **Latest news**: View disaster and weather news provided by NHK  
- 🔗 **Official article links**: Tap to read full details on NHK’s official website  

---

### 4. Preparedness Checklist
- 🎒 **Visualized preparedness**:  
  - Emergency go-bag  
  - Home stockpile  
  Organized into two categories for easy tracking  
- 💾 **Progress saved**: Your checklist is stored in the browser and remains available on return visits  

---

### 5. Multi-language Support
- 🌏 **Available in 4 languages**:  
  - Japanese  
  - English  
  - Korean  
  - Simplified Chinese  

Switch the UI language with a single tap.  

---

## 🚀 How to Use

1. **Download**  
   Get `moshimo-sonae-app-v3.html` from the repository  

2. **Open in browser**  
   Simply open the file in any modern browser to start using the app  

3. **Set your region**  
   Go to the "Earthquake Info" tab and select your prefecture from the dropdown list  

---

## 🛠️ Technologies & APIs

- **Frontend**: HTML, JavaScript, Tailwind CSS  
- **Earthquake Data API**: P2P Earthquake Information API  
- **News Feed**: NHK Disaster & Weather RSS feed  
- **Location Services**: Browser’s built-in Geolocation API  

---

## ⚠️ Notes

- The evacuation sites shown in the “Evacuation Site Search” feature are **demo data only**.  
  Always check your **local government’s official information** during an actual evacuation.  

- An **internet connection is required** to use this app.  
