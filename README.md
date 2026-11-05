# HabitBloom — Habit Tracker

A responsive habit tracker built with HTML, CSS, and vanilla JavaScript.

## Features
- Add habits with emoji and category
- Complete/uncomplete habits for the current day
- Daily completion percentage and habit streaks
- Weekly insights chart (Chart.js)
- Dark mode
- Responsive layout
- Data saved in browser LocalStorage

## Run locally
Open `index.html` in your browser.

## Deploy to Vercel
1. Upload this project to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.`.
4. Click **Deploy**.

## Database note
This first version uses LocalStorage, which persists data in the same browser/device. To use a cloud database across devices and users, configure Supabase and add authentication + Row Level Security policies. Do not put a Supabase service-role key in frontend code.
