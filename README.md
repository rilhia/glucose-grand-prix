![Glucose Grand Prix](images/Glucose-grand-prix.png)
# Glucose Grand Prix  
*Visualise your daily blood sugar as a Formula 1 race.*

Author: Richard Hall  
[LinkedIn](https://www.linkedin.com/in/rilhia/)  
[EarthTunnelling.com](https://earthtunnelling.com)

---

## 📖 Introduction

**Glucose Grand Prix** is a fun, interactive project that turns your blood glucose data into something more exciting: a race car tearing around a virtual Formula 1 track.

This idea came from a desire to make health data not just informative, but *engaging*. As a long-term type 1 diabetic, I know how easy it is for daily glucose stats to feel abstract or repetitive. But what if you could see your day as a race — one where consistency, control, and timing matter?

Each day’s data becomes a lap. Each data point becomes a step forward. And your glucose control becomes the determining factor in how smoothly your car makes it around the track. The better your day, the faster and cleaner the lap.

This project is open, customizable, and built with clarity in mind. You can use your own data, plug in different tracks, and tinker with how performance is calculated.

---

## 🛠️ What this project does

This is a browser-based web app (no install needed!) that:

- Loads your blood glucose data from a JSON file  
- Animates multiple days as racing laps around a real F1 circuit  
- Maps glucose control to car speed, using Gaussian scoring  
- Shows leaderboard-style stats like time-in-range, high/low/mid, and deviation  
- Lets you choose which drivers (days) to include  
- Includes multiple tracks with real F1 circuit data

**What it doesn't do:**

- Upload your data anywhere (everything runs in the browser)  
- Require any medical device integration (you load your JSON manually)

---

## 🚀 How to use this

1. **Prepare your data**  
   Your JSON file should follow the format exported by the CGM simulator or from your own tool — with arrays like `cgmLow`, `cgmNormal`, and `cgmHigh`, and each entry containing `timestamp`, `x` (epoch), and `y` (bg value).

2. **Open the web app**  
   You can host it yourself from GitHub Pages, or just open the HTML file in your browser.

3. **Load your file**  
   Click the **Load JSON** button, select your file, and wait a second or two for parsing.

4. **Pick a track**  
   Choose from real F1 circuits like Silverstone, Yas Marina, or Monza.

5. **Start the race**  
   Press **Start Race** and watch your data come to life!

---

## 🎯 Customisation Ideas

- Add your own circuits (just import GeoJSON files with line data)  
- Change how performance is calculated (edit `getPerformance()`)  
- Use it for competitions — who had the best lap today?  
- Animate multiple users  
- Show month-over-month comparison laps  

---

## 📝 License

This project is licensed under the MIT License. You can use, modify, and distribute it freely as long as attribution is preserved.

---

## 🧪 Demo and Screenshots

Demo coming soon.

You can also preview it live at: *(GitHub Pages link, if deployed)*

---

## 🧠 Final Thoughts

The Glucose Grand Prix isn’t a replacement for traditional analysis. It’s a *complement*. A way to think differently about daily patterns, to stay engaged, and — frankly — to have a little fun.

If you build on it, I’d love to see what you create. Feel free to fork, remix, or race your own way.

---

**Stay steady. Stay fast.**
