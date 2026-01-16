# 🏋️ Lean Body Workout Planner (PWA)
link :- https://kundan789.github.io/My-Helth/

A **clean, distraction-free workout planner web app** designed to help you stay consistent, build a **lean physique**, and track your workout streak — without bulky muscle goals.

This app works **offline**, supports **dark mode**, and can be installed on mobile as a **Progressive Web App (PWA)**.

---

## 🚀 Features

- 📅 **Automatic Daily Workout**
  - Shows workout based on today’s date (Monday–Sunday)
- 🎥 **Embedded Exercise Videos**
  - Learn correct form directly inside the app
- ✅ **One-Tap “Mark Workout as Done”**
  - Instantly updates streak & progress
- 📊 **Weekly Progress Bar with Percentage**
  - Visual feedback to stay motivated
- 🟢🔴 **Calendar Streak View**
  - Green → completed workout  
  - Red → skipped day  
  - Blue ring → today
- 🔢 **Completed Days Counter**
  - Shows total workouts completed this week
- 🌙 **Dark / Light Mode Toggle**
- 🗑️ **Delete All Data Button**
  - Clears all stored progress safely
- 📱 **Installable as Mobile App (PWA)**
  - Works offline after first load

---

## 🧠 Who Is This For?

- Beginners starting fitness
- People focusing on **fat loss + lean muscle**
- Home workout users
- Anyone who wants **simple, no-confusion workouts**
- Developers learning **localStorage + PWA basics**

---

## 🗓️ Default Weekly Workout Plan

| Day | Focus |
|----|------|
| Monday | Upper Body + Abs |
| Tuesday | Lower Body + Cardio |
| Wednesday | Core + Mobility |
| Thursday | Chest + Triceps |
| Friday | Full Body Functional |
| Saturday | Active Recovery |
| Sunday | Rest (Auto Reset) |

> ⚠️ Every Sunday, the weekly progress resets automatically.

---

## 🛠️ How to Customize Workouts

You can easily change exercises by editing this section in the HTML file:

```js
const workouts = {
  Monday: {
    title: 'Upper Body + Abs',
    exercises: ['Push-ups', 'Shoulder Press', 'Crunches']
  },
  Tuesday: {
    title: 'Lower Body + Cardio',
    exercises: ['Squats', 'Lunges', 'Jumping Jacks']
  }
};

➕ Add New Exercises

Just add names inside the exercises array.

🎥 Add / Change Exercise Videos

Edit the videos object:

const videos = {
  'Push-ups': 'https://www.youtube.com/embed/IODxDxX7oi4'
};

📂 Project Structure
📁 Lean-Body-Workout-Planner
│
├── index.html        # Main app file
├── manifest.json     # PWA settings
├── sw.js             # Service worker (offline support)
└── README.md         # Documentation

💾 Data Storage

Uses browser localStorage

No login required

No external database

Fully private (data stays on your device)

📱 How to Install as Mobile App

Open the website in Chrome / Edge

Tap “Add to Home Screen”

App works like a native mobile app

🔐 Privacy

❌ No ads

❌ No tracking

❌ No data sent to servers

✅ 100% local & private

🧩 Tech Stack

HTML5

Tailwind CSS

Vanilla JavaScript

LocalStorage API

Progressive Web App (PWA)

⭐ Future Enhancements (Optional)

Monthly calendar navigation

Weight tracking

Cloud backup

Multiple workout profiles

Export progress as CSV

🙌 Contribution

Feel free to:

Fork this project

Customize workouts

Improve UI

Share with others

📜 License

Free to use for personal and educational purposes.

💪 Stay consistent. Progress follows.

---

## 🔥 Tip (Important for SEO on GitHub)
When uploading:
- Name repo like  
  **`lean-body-workout-planner`**
- Add tags:


workout planner, fitness app, pwa, home workout, fat loss

