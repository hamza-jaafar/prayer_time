# Prayetime App 🕌

Prayer times web application for Morocco hosted at:  
https://prayetime.netlify.app/

A simple React app that shows daily prayer timings based on the selected Moroccan city. All main logic is implemented in one code file with a reusable Prayer component.

---

## 📸 Screenshot

<img width="1204" height="595" alt="image" src="https://github.com/user-attachments/assets/36b9cd43-a675-4a41-998e-6693d1f24e18" />


## Features ✨

- Choose city from Moroccan cities list  
- Fetch prayer times online  
- Display Gregorian date  
- Convert time to 12 hour AM / PM format  
- Lightweight and easy to understand

---

## Technologies Used 🛠

- React Hooks: useState, useEffect  
- Fetch API  
- Component based UI  
- CSS with container layout

---
## API provider:  
https://aladhan.com/prayer-times-api

## How It Works 🔁

- When the city changes, the app calls AlAdhan service to get timings  
- Times are stored in state  
- Format function converts 24h time to 12h display  
- Prayer component displays name and time

---

## Demo Link :
https://prayetime.netlify.app/


---

## Run Locally 🚀

```bash
npm install  
npm run dev
