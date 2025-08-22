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
- Frontend: [Bootstrap]  
- Mobile Wrapper: [Capacitor]  
- Backend API: [Node.js]  
- Maps: [OpenLayers]  

---

## 🚀 Installation (Development)
### Prerequisites  
Make sure you have installed:  
- [Node.js](https://nodejs.org/) (LTS version recommended)  
- [npm](https://www.npmjs.com/) (comes with Node.js)  
- [Capacitor CLI](https://capacitorjs.com/)  

### 1. Clone the Repository  
```bash
git clone https://github.com/username/DIMSum-Mobile-App.git
cd DIMSum-Mobile-App
2. Install Dependencies
```bash
Copy
Edit
npm install
3. Run as Web App (Development)
bash
Copy
Edit
npm run start
The app will run on your local browser (default: http://localhost:3000/ or depending on your configuration).

📱 Build as Mobile App
1. Add Platform
For Android:

bash
Copy
Edit
npx cap add android
For iOS:

bash
Copy
Edit
npx cap add ios
2. Build Project
bash
Copy
Edit
npm run build
npx cap copy
3. Open in IDE
Android → open in Android Studio:

bash
Copy
Edit
npx cap open android
