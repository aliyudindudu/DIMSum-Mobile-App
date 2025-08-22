# DIMSum (Data Indikator Makro Sumedang)

**DIMSum** is a hybrid application that provides access to Sumedang’s macro indicator data.  
It combines a modern web app with a mobile experience (packaged using [Capacitor](https://capacitorjs.com/)), allowing users to explore **infographics, statistical tables, key indicators, and thematic maps** anytime, anywhere.

---

## ✨ Features
- 📊 Interactive infographics and visualizations  
- 📑 Statistical tables and key indicators  
- 🗺️ Thematic maps with regional insights  
- 📱 Works on both **web and mobile (Android)**  
- 🔍 User-friendly data exploration  

---

## 🛠️ Technology Stack
- Frontend: [Bootstrap](https://getbootstrap.com/)  
- Mobile Wrapper: [Capacitor](https://capacitorjs.com/)  
- Backend API: [Node.js](https://nodejs.org/)  
- Maps: [OpenLayers](https://openlayers.org/)  

---

## 🚀 Installation (Development)

### Prerequisites
Make sure you have installed:  
- [Node.js](https://nodejs.org/) (LTS version recommended)  
- [npm](https://www.npmjs.com/) (comes with Node.js)  
- [Capacitor CLI](https://capacitorjs.com/)  

### Installation Steps
```bash
# 1. Clone the Repository
git clone https://github.com/username/DIMSum-Mobile-App.git
cd DIMSum-Mobile-App

# 2. Install Dependencies
npm install

# 3. Run as Web App (Development)
npm run start
# The app will run on your local browser (default: http://localhost:3000/)

# 4. Build as Mobile App
# Add Platform
npx cap add android
npx cap add ios

# Build Project
npm run build
npx cap copy

# Open in IDE
npx cap open android  # For Android Studio
npx cap open ios      # For Xcode
```

## 🤝 Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

-Copyright (c) 2025 Aliyudin Saptari

All rights reserved.

You must obtain explicit permission from the author before cloning, copying, or redistributing this repository. 
Unauthorized use is prohibited.

---

