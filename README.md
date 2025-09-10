# **3D Electric Truck Challenge**

Welcome to the 3D Electric Truck Challenge\! This is a fast-paced, arcade-style driving game built with Three.js and plain JavaScript. Navigate a winding off-road course, collect lightning bolts to keep your battery charged, and try to survive all 10 progressively difficult levels to get the high score\!

[**Live Demo Link**](https://gRanStaff66.github.io/3d-electric-truck-game-demo/)



## **Features**

* **10 Challenging Levels:** Each level increases in speed, length, and difficulty.  
* **Procedurally Generated Courses:** Every level features a unique, winding off-road path.  
* **Battery Management:** Your electric truck's battery constantly drains. Collect lightning bolts to recharge it or find a rare charging station for a full boost\!  
* **Speed Boost:** Use the up arrow to go faster, but be careful—it drains your battery much more quickly\!  
* **Classic High Score Board:** Compete for the top spot on the 10-slot leaderboard, complete with 3-initial entries.  
* **Full Game Controls:** Pause, resume, quit, and view high scores, all from within the game.  
* **Responsive Design:** The game canvas scales to fit your browser window for an immersive experience.

## **How to Play**

The controls are simple:

* **Steer:** Use the **Left/Right Arrow Keys** or the **A/D** keys.  
* **Boost:** Hold the **Up Arrow Key** to go faster.  
* **Pause:** Press the **'P' Key** or click the "Pause" button.  
* **Touch Controls:** On mobile devices, **swipe left or right** to steer.

The goal is to survive to the end of each course without hitting an obstacle or running out of battery.

## **Tech Stack**

This game was built from the ground up using modern web technologies:

* **HTML5:** For the basic structure of the game.  
* **Tailwind CSS:** For all UI styling and layout.  
* **JavaScript (ES6+):** For all game logic, physics, and interactions.  
* **Three.js:** For all 3D rendering, including the truck, environment, and objects.

The entire game is self-contained in a single HTML file with no external dependencies beyond the CDN-hosted libraries.

## **How to Run Locally**

Since this is a single-file project, running it locally is very easy.

1. **Clone the repository:**  
   git clone \[https://github.com/gRanStaff66/3d-electric-truck-game-demo.git\](https://github.com/gRanStaff66/3d-electric-truck-game-demo.git)

2. Open the file:  
   Navigate to the project directory and open the truck\_game.html file in your favorite web browser.  
   For the best results (to avoid any potential browser security issues with local files), it's recommended to serve the file with a local web server. If you have Python installed, you can run this command in the project directory:  
   \# For Python 3  
   python \-m http.server

   Then, open your browser and go to http://localhost:8000.

## **License**

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).
