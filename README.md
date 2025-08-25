# YouTube Video Search 🎥

A modern, distraction-free **YouTube Video Search Web App** built with **HTML, TailwindCSS, and JavaScript**.  
This project allows you to search YouTube videos, view them in a draggable/resizable modal, and manage your search history with night-mode support.

---

## 🚀 Features

- 🔍 **Search YouTube Videos** with multiple API keys for fallback  
- 🎬 **Embedded Video Player** with Play/Pause, Next/Previous, Autoplay, and Fullscreen support  
- 📌 **Draggable Video Modal** (move video around the screen freely)  
- 🌙 **Dark/Light Mode Toggle** with preference saved in LocalStorage  
- 📖 **Search History Panel** – view and reopen previous searches & watched videos  
- 📊 **API Key Health Check** (logs key status in the browser console)  
- 🔄 **Sorting Options** – relevance, views, latest, likes, and channel A-Z  
- 📱 **Responsive Layout** for mobile, tablet, and desktop  

---

## 🛠️ Technologies Used

- **HTML5** – structure  
- **TailwindCSS** – styling & responsive design  
- **JavaScript (Vanilla)** – app logic  
- **YouTube Data API v3** – video search & statistics  

---

## 📂 Project Structure

```
├── NEW.html      # Main application file
├── README.md     # Project documentation
```

---

## ⚡ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/youtube-video-search.git
   cd youtube-video-search
   ```

2. Open `NEW.html` in any modern browser.

3. Enter a search term and click **Search**.

4. Click a video thumbnail to open the modal player.

5. Use the history panel to revisit past searches & videos.

---

## 🔑 API Keys

The project is preconfigured with multiple API keys:
```js
const API_KEYS = [
  "YOUR_API_KEY_1",
  "YOUR_API_KEY_2",
  "YOUR_API_KEY_3"
];
```
- The app automatically switches to the next key if one fails.  
- Replace these with your own keys from the [Google Cloud Console](https://console.cloud.google.com/).

---

## 📸 Screenshots

### 🔍 Search Interface  
*(screenshot placeholder)*  

### 🎬 Video Modal Player  
*(screenshot placeholder)*  

### 📖 History Panel  
*(screenshot placeholder)*  

---

## 🏗️ Future Improvements

- Add **download/watch-later list**  
- Advanced filtering (duration, HD/4K, etc.)  
- User authentication with Google  

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share ✨
