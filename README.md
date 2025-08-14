# MoodPalette-6-Daily-Mood-Tracker

Description
A simple and visually appealing web app that allows users to log their daily moods and view them as a colorful calendar heatmap.

## Tech Stack
- React

## Requirements
- Mood selection interface (Use emoji or color buttons for mood selection)
- Calendar heatmap display (Map moods to colors and show them on a monthly grid)
- Local storage persistence (Save moods locally so data stays after refresh)

## Installation
1. Clone the repo:
   bash
   git clone https://github.com/your-username/MoodPalette-6-Daily-Mood-Tracker.git
   
2. Navigate to the project directory:
   bash
   cd MoodPalette-6-Daily-Mood-Tracker
   
3. Install dependencies:
   bash
   npm install
   
4. Start the development server:
   bash
   npm start
   

No environment variables are required for this project.

## Usage
1. Open http://localhost:3000 in your browser.
2. Select your mood for the current day using the emoji/color buttons.
3. View your mood history on the calendar heatmap.
4. Your data is saved automatically and persists across page reloads.

## Implementation Steps
1. Bootstrap the project with Create React App.
2. Create `MoodSelector` component with emoji/color buttons for mood input.
3. Create `CalendarHeatmap` component to render a monthly grid and color-code days based on mood.
4. Implement mood-to-color mapping logic.
5. Use the Web Storage API to save and load mood data in `localStorage`.
6. Compose the main layout in `App.js`, integrating both components.
7. Apply styling using CSS modules or your preferred styling solution.
8. Test user interactions and data persistence in the browser.