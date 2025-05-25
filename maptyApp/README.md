# 🏃‍♂️🚴‍♀️ Mapty - Workout Tracking App

![Mapty Screenshot](./mapty-screenshot.png) _Add your screenshot here_

A geolocation-based workout tracker that lets you log running and cycling activities on an interactive map. Built with JavaScript and the Leaflet library as part of Jonas Schmedtmann's "The Ultimate React Course 2025".

## 🌟 Features

- **Interactive Map**: Click anywhere to log your workout
- **Workout Types**:
  - 🏃‍♂️ Running: Track distance, duration, pace, and cadence
  - 🚴‍♀️ Cycling: Track distance, duration, speed, and elevation
- **Data Persistence**: Workouts saved to local storage
- **Responsive Design**: Works on desktop and mobile devices
- **Visual Markers**: Color-coded pins for different workout types

## 🛠️ Technologies Used

- **Leaflet JS** - Interactive maps
- **Geolocation API** - Get user's current location
- **LocalStorage** - Persist workout data
- **Modern JavaScript** (ES6+ features):
  - Classes & OOP architecture
  - Arrow functions
  - Destructuring
  - Spread operator

## 🚀 Installation & Usage

1. Clone the repository:

```
git clone https://github.com/your-username/mapty.git
```

Open index.html in your browser (no build tools required)

## 📖 Key Implementation Details

Architecture

- Workout Class: Base class with shared properties
- Running/Cycling Classes: Extend Workout with type-specific calculations
- App Class: Main application logic (map, forms, storage)

Notable Methods

- \_getPosition(): Gets user's location via Geolocation API

- \_loadMap(): Initializes Leaflet map

- \_renderWorkoutMarker(): Places workout pins on map

- \_setLocalStorage(): Saves workouts between sessions

## Future Improvements

Planned enhancements:

- Edit existing workouts
- Delete individual workouts
- Sort workouts by distance/duration
- Geocoding for location names
- Weather data integration
- Draw routes/paths between workouts
