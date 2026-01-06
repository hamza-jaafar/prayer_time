# Prayetime App 🕌

Prayer times web application for Morocco hosted at:  
https://prayetime.netlify.app/

A simple React app that shows daily prayer timings based on the selected Moroccan city. All main logic is implemented in one code file with a reusable Prayer component.

---

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

## How It Works 🔁

- When the city changes, the app calls AlAdhan service to get timings  
- Times are stored in state  
- Format function converts 24h time to 12h display  
- Prayer component displays name and time

API provider:  
https://aladhan.com/prayer-times-api

---

## Run Locally 🚀

```bash
npm install  
npm run dev
