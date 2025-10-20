# 🐤 Flappy Bird - Java Swing

A simple **Flappy Bird clone** created using **Java Swing**.  
This project replicates the classic Flappy Bird gameplay — where the bird flies through pipes — using basic 2D graphics and event handling in Java.

---

#### 📁 Project Structure

FlappyBird-Java/  
│  
├── README.md   
│  
├── src/  
│   ├── App.java  
│   └── FlappyBird.java  
│  
└── images/  
    ├── flappybird.png  
    ├── flappybirdbg.png  
    ├── toppipe.png  
    └── bottompipe.png  

---

#### 🖼️ Screenshots

![Game Screenshot](Screenshot%202025-10-20%20114237.png)

---

#### 📸 Image Files

Make sure these 4 PNG files are present inside the `images/` folder:  
- `flappybird.png` → Bird sprite  
- `flappybirdbg.png` → Background image  
- `toppipe.png` → Top pipe image  
- `bottompipe.png` → Bottom pipe image  

If the images are missing, the game can still run but will use simple colored shapes.

---

#### 🧠 How It Works

This project is built using **Java Swing** for the graphical interface.  
It contains two main files:  
- **App.java** – The entry point that creates a game window and runs the `FlappyBird` panel.  
- **FlappyBird.java** – Contains the core game logic such as bird movement, gravity, pipes, collision detection, and scoring.

The bird moves automatically due to gravity, and when the player presses the **spacebar** or **mouse click**, the bird “flaps” upward.  
Pipes are continuously generated at random heights, and the player must avoid colliding with them. Each pipe pair passed increases the score by one.

---

#### 🕹️ Controls

| Action | Key / Mouse |
|--------|--------------|
| Start Game | Press **Space** or **Mouse Click** |
| Flap / Jump | **Spacebar** |
| Restart Game | **R** key |

---

#### 🧠 Concepts Used

- **Java Swing** – for GUI components and rendering  
- **Event Handling** – to respond to key and mouse input  
- **Timers** – to manage continuous frame updates (game loop)  
- **Collision Detection** – using rectangles for intersection  
- **OOP Principles** – separate classes for game objects (bird, pipes)

---

##### 🧩 Run from Eclipse or IntelliJ

1. Create a new Java Project.  
2. Copy the two `.java` files into the `src` folder.  
3. Add the `images` folder in your project root.  
4. Adjust image paths in the code if necessary.  
5. Run the `App.java` file.

---

#### 💡 Features

- 🎮 Smooth gameplay using Java’s Swing Timer  
- 🌈 Simple graphics with optional custom images  
- 🐦 Bird physics: gravity, flap strength, and vertical velocity  
- 🧱 Randomly generated pipes with gaps  
- 🔢 Live score display  
- 🚀 Restart option without restarting the program  

---
#### 🪪 License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---

#### 📬 Contact

For any questions or feedback, feel free to open an issue or reach out to me directly.
