# 🎬 NEON WORLD CAMS - Live Streaming Platform

Beautiful neon-styled live camera viewing platform with real-time RTMP streaming support.

## ✨ Features

- 🎨 **Neon Cyberpunk Design** - Purple (#8b5cf6) + Acid Green (#22c55e) theme
- 📺 **Live RTMP Streaming** - Real-time video feeds from world locations
- 🌍 **Interactive World Map** - Powered by Leaflet.js
- 🔍 **Smart Search** - Filter cameras by city, country or name
- 📱 **Responsive Design** - Works on desktop, tablet, mobile
- ⚡ **Zero Dependencies** - Pure HTML/CSS/JavaScript
- 🚀 **GitHub Pages Ready** - Deploy instantly, runs everywhere

## 🌐 Live Demo

👉 **[OPEN APP NOW](https://sokolzefir.github.io/neon-world-cams/)**

## 🚀 How to Use

### Option 1: Online (Instant - No Setup)
Just visit: https://sokolzefir.github.io/neon-world-cams/

### Option 2: Local Setup
```bash
# Clone repository
git clone https://github.com/Sokolzefir/neon-world-cams.git
cd neon-world-cams

# Start local server (Python)
python -m http.server 8000

# Or with Node.js
npx http-server

# Open http://localhost:8000
```

## 🎥 Adding Your Own Streams

Edit `index.html` and add to the cameras array:

```javascript
const cameras = [
  {
    name: 'Your Camera Name',
    url: 'rtmp://your-stream-url:1935/live/stream',
    city: 'City Name',
    country: 'Country',
    type: 'RTMP'
  },
  // ... more cameras
];
```

## 📡 RTMP Stream Sources

Supported formats:
- RTMP (rtmp://...)
- RTMPS (secure)
- HTTP Live Streaming (HLS)
- MJPEG streams

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Maps**: Leaflet.js
- **Hosting**: GitHub Pages (Free)
- **Real-time Video**: RTMP/HLS protocols

## 📋 Current Camera Feeds

- Times Square (NYC, USA)
- Red Square (Moscow, Russia)
- Eiffel Tower (Paris, France)
- Big Ben (London, UK)
- Colosseum (Rome, Italy)
- Sagrada Familia (Barcelona, Spain)
- Kremlin Palace (Moscow, Russia)
- St. Petersburg Square (Russia)
- Tokyo Shibuya (Japan)
- And more...

## 🔧 Customization

### Colors
Modify CSS variables in `<style>` section:
```css
#8b5cf6 /* Purple */
#22c55e /* Acid Green */
#0a0e27 /* Dark Background */
```

### Camera Database
Add/remove cameras in JavaScript `cameras` array.

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers

## 🐛 Troubleshooting

**Video not playing?**
- Check RTMP stream URL is valid
- Verify stream is live/broadcasting
- Check browser console for CORS errors

**Search not working?**
- Make sure camera names/cities are in data
- Check JavaScript console for errors

## 📄 License

MIT License - Free to use and modify

## 👤 Author

Created with ❤️ as a cyberpunk streaming platform

---

**Live Now:** https://sokolzefir.github.io/neon-world-cams/
