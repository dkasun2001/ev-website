## EV-Website | React Landing Page
This project is a React implementation of a landing page with dynamic features.

## Screenshots

![Screenshot 1](https://github.com/dkasun2001/ev-website/blob/main/Capture1.JPG)
![Screenshot 2](https://github.com/dkasun2001/ev-website/blob/main/Capture2.JPG)
![Screenshot 3](https://github.com/dkasun2001/ev-website/blob/main/Capture3.JPG)

Features
Changing background image/video with a smooth fade-in transition.
Navbar component for navigation.
Hero section with text and a button to control background video playback (play/pause).
Dots indicating the current background image.

## Folder Structure

src/
  - components/ (folder containing reusable components)
    - Background.jsx (Background component)
    - Navbar.jsx (Navbar component)
    - Hero.jsx (Hero component)
  - assets/ (folder for images and videos used in the project)
  - App.jsx (Main application component)
  - index.css (Global stylesheet)

Files/
  -App.jsx: Renders the Background, Navbar, and Hero components.
  -Background.jsx: Handles displaying the background image/video with fade-in animation.
  -Navbar.jsx: Contains the logo and navigation menus.
  -Hero.jsx: Displays text, a play/pause button for the background video, and dots for background image indication.
  -index.css: Defines global styles for the application.
  -assets/: Stores images and video used in the project.

## Getting Started

1. Clone this repository.
```Bash
git clone https://github.com/dkasun2001/ev-website/.git
```

2. Install dependencies:
```Bash
npm install
```

3. Run the development server:
```Bash
npm start
```

This will start the development server at http://localhost:3000 by default.
