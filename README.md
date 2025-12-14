# ShopFinder 🛍️📍

**ShopFinder** is a location-based application that helps users **discover shops**, view shop details, and quickly find places based on **search + categories + distance**.


---

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Clone](#clone)
  - [Run the App](#run-the-app)
- [Environment Variables](#environment-variables)
- [Database (Optional)](#database-optional)
- [Troubleshooting](#troubleshooting)
- [Author](#author)

---

## Overview

ShopFinder is designed to make it easy to:
- Find shops near a user’s current location
- Search shops by **name / category**
- View shop details such as **address, contact info, open/close status**
- Navigate to a selected shop using maps/directions

---

## Key Features

- **Nearby shop discovery** (GPS/location-based)
- **Fast search** by shop name/category
- **Filters** (category, distance, rating, open now) 
- **Map view + directions** 
- **Favorites / saved shops** 
- **Admin CRUD** for managing shops 
- Authentication 

---
---

## Tech Stack

> Update this section to match your actual project (keep what applies).

### Option A: Web App (React / Node)
- Frontend: React / Vite / Next.js
- Backend: Node.js (Express) / Java / .NET *(if any)*
- Database: MySQL / MongoDB / PostgreSQL *(if any)*
- Maps: Google Maps / Mapbox *(if used)*

### Option B: Mobile App (Android / Flutter / React Native)
- Android: Java/Kotlin + Google Maps SDK *(if used)*
- Flutter: Dart + Maps plugin *(if used)*
- React Native: Expo / RN + maps *(if used)*

### Common
- REST API / JSON
- Location services (GPS)
- Search + filters

---

## Architecture

> Keep what matches your repo.

**Typical setup:**
- **Client (Web/Mobile):** UI + location + search
- **Backend (Optional):** shop management, authentication, APIs
- **Database (Optional):** store shop records, categories, users, favorites

---

## Getting Started

### Clone
```bash
git clone https://github.com/Induranga-kawishwara/ShopFinder.git
cd ShopFinder
```

### Run the App

#### If this is a Node/React project (`package.json` exists)
```bash
npm install
npm run dev
# or
npm start
```

## Environment Variables

Create a `.env` file (or update your config file) with values like:

```env
# API
API_BASE_URL=http://localhost:5000

# Maps
GOOGLE_MAPS_API_KEY=YOUR_KEY_HERE

# Database (if applicable)
DB_HOST=localhost
DB_PORT=3306
DB_NAME=shopfinder
DB_USER=root
DB_PASSWORD=your_password
```

---

## Troubleshooting

**Location not working**
- Enable device location services
- Allow location permission for the app
- Test on a real device if emulator location is not set

**Maps not loading**
- Confirm Maps API key is valid and enabled
- Check billing/API restrictions (Google Maps)

**Backend connection errors**
- Confirm backend is running and `API_BASE_URL` is correct
- Check CORS settings (for web)

---

## Author

**Induranga Kawishwara**  
GitHub: `Induranga-kawishwara`
