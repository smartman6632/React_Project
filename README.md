# React_Project
This is a React-based travel website that provides an immersive visual experience, allowing users to explore different seasons and destinations interactively. The website features a dynamic background video,
seasonal selection buttons, and an informative description overlay.
React Components:
App.jsx handles the state management (useState) for the selected season.
Content.jsx dynamically updates video sources and text content based on the selected season.
Menu.jsx provides the interactive buttons to switch between seasons.
Header.jsx and Footer.jsx maintain consistent UI elements.
State Management:
useState is used to track the currently selected season (currentIndex).
Clicking a button updates currentIndex, which re-renders the corresponding background video and text content.
Media Assets:
Video files (island.mp4, spring.mp4, etc.) are stored in /public/assets/videos/.
Icons and logos are stored in /public/assets/icons/.

Instructions for running locally

Clone this repository
git clone my http link to your own terminal

Navigate into the project folder
cd vedio-course-react-travel-site

Install dependencies
npm install

Start the development server
npm run dev
