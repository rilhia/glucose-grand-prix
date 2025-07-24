![Glucose Grand Prix](images/Glucose-grand-prix.png)
# Glucose Grand Prix  
*Visualise your daily blood sugar as a Formula 1 race.*

Author: Richard Hall  
[LinkedIn](https://www.linkedin.com/in/rilhia/)  
[EarthTunnelling.com](https://earthtunnelling.com)

---

## 📖 Introduction

**Glucose Grand Prix** is a quirky project I put together after finding a neat way to extract my blood sugar data from [Glooko](https://glooko.com/). I wanted to create my own charts, but the data downloads only allowed 90 days at a time and came as multiple CSV files bundled in a ZIP. It was not exactly user-friendly.

With a bit of hacking around, I discovered how to use their session-authenticated browser APIs. That meant I could now grab all my data (or just a few hours’ worth) in JSON format using Chrome’s DevTools. Perfect.

At first, I thought it would be a great trick to share with other Glooko users. Then I remembered not everyone is quite as obsessed with data as I am. That thought completely sidetracked me. I started wondering what someone else might actually do with this data.

I’d recently seen stories about a diabetic Barbie and a diabetic Marvel superhero. Both were created for kids, which is a lovely idea. But not all kids relate to dolls or superheroes. There are loads of kids (and adults) who are really into F1.

That’s when it hit me. What if I could use glucose data to “fuel” Formula 1 cars? Just like that, the idea of Glucose Grand Prix was born. A webpage that turns your blood sugar readings into something a bit different. A race car tearing around a virtual F1 track.

Each day’s data becomes a lap. Each data point becomes a step forward. Your glucose control becomes the determining factor in how smoothly your car makes it around the track. The better your day, the faster and cleaner the lap.

This project is a proof of concept. It'll be open to anyone who wants to try it or enhance it. 

---

## 🛠️ What this project does

This is a browser-based web app (no install needed!) that:

- Loads your blood glucose data from a JSON file  
- Animates multiple days as racing laps around a real F1 circuit  
- Maps glucose control to car speed, using Gaussian scoring  
- Shows leaderboard-style stats like time-in-range, high/low/mid, and deviation  
- Lets you choose which F1 drivers to include  
- Includes multiple tracks with real F1 circuit data
- The result of the race reveals your best days with regard to control
- You can download the details of your best days

**What it doesn't do:**

- Upload your data anywhere (everything runs in the browser)  
- Require any medical device integration (you load your JSON manually)

---

## 🚀 How to use this

1. **Download and open the HTML file**
   Download the [webpage](https://raw.githubusercontent.com/rilhia/glucose-grand-prix/main/glucose-grand-prix.html) and double click on it to open it in a browser.
   
2. **Prepare your data**  
   Download your data from Glooko, paste it into a file, give the file a name with the suffix ".json", then click "Load JSON" to load it.

3. **Pick a track**  
   Choose from real F1 circuits like Silverstone, Yas Marina, or Monza.

4. **Start the race**  
   Press **Start Race** and watch your data come to life!

---

## 🎯 Customisation Ideas

- Add a multi-user "competitive" feature and compete with diabetic friends 
- Change how performance is calculated (edit `getPerformance()`)    
- Show month-over-month comparison laps
- Get Glooko to include features like this into their website 

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
