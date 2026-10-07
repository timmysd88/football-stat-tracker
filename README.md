# ⚡ Football Match Tracker

A lightweight, mobile-responsive web application designed for tracking live individual player performance during football matches—specifically optimized for wingers and attacking players. 

It provides real-time event logging, a dynamic performance rating algorithm, half-by-half comparative analytics, and CSV report exports.

---

## ✨ Features

* **Real-Time Stat Tracking:** Quickly log key performance metrics with responsive touch controls:
  * ⚡ **1v1 Dribbles / Take-Ons** (Successful Beat vs. Tackled/Dispossessed)
  * 🎯 **Crosses & Cutbacks** (Completed Deliveries vs. Blocked/Incomplete)
  * ⚽ **Shots & Finishing** (On Target/Goals vs. Off Target)
  * 🔑 **Key Passes & Chance Creation**
  * 🛡️ **Defensive Track Backs & Recoveries**
* **Dynamic Performance Rating:** Live calculation of an overall match score out of 10.0 based on positive play, key chance creation, and turnover penalties.
* **Match Timer Widget:** Built-in match stopwatch to monitor elapsed time during halves.
* **Half-by-Half Breakdown:** Separate tracking views for 1st Half, 2nd Half, and a full Match Comparison Summary.
* **Match Notes:** Dedicated text area for logging key tactical moments, halftime adjustments, or opponent notes.
* **CSV Export:** Download full performance reports including half-by-half stats, ratings, and tactical notes for post-match analysis.
* **Local Data Persistence:** Automatically saves active match data to `localStorage` so progress isn't lost if the browser refreshes.

---

## 🚀 Live Demo & Usage

Since this is a single-file application built with pure HTML, CSS, and JavaScript, it runs directly in any modern web browser without needing a backend server or external dependencies.

### Accessing the Web App
If enabled via **GitHub Pages**, you can open the app directly on your phone or desktop at:
```text
[https://timmysd88.github.io/football-stat-tracker/](https://timmysd88.github.io/football-stat-tracker/)
