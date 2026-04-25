# Hybrid Athlete Tracker

Offline-capable gym & nutrition PWA for hybrid athletes. Built with React, persists all data in localStorage.

## Features

**Training Tracker**
- Weekly program with 4 gym days + sport days (soccer, climbing, running, surfing)
- Smart rest timer with per-exercise countdown targets
- Exercise tips and coaching cues
- Motivational messages based on session completion
- 4 week modes: Normal, Camping, Travel, Deload
- Progressive overload tracking

**Nutrition Tracker**
- Auto-calculated macros based on body weight and training day type
- Meal-by-meal logging with quick-add food database
- Hydration tracking
- Day-specific meal suggestions

## Deploy

This repo is configured for GitHub Pages:

1. Go to **Settings → Pages**
2. Source: **Deploy from branch**
3. Branch: **main** / **root**
4. Save — your app will be live at `https://yourusername.github.io/hybrid-tracker/`

Then on your phone: open the URL → Share → **Add to Home Screen**

## Tech

- Single HTML file, no build step
- React 18 via CDN + Babel standalone
- localStorage for persistence
- Service worker for offline support
- PWA manifest for home screen install
