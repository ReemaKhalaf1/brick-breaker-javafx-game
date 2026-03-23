# 🧱 Brick Breaker Game – JavaFX

## 📌 Overview
A complete **Brick Breaker (Breakout)** game built with **JavaFX** as part of the **CI401 Introduction to Programming** module at the University of Brighton.  
The project transforms a basic game skeleton into a fully featured, polished gaming application with professional UI, sound, and clean architecture.

## 🎮 Features
- **Main Menu System** — Start game, How to Play, Exit, Theme selector
- **Four Visual Themes** — Space, Ocean, Forest, Default (dynamically switchable)
- **Audio** — Background music + sound effects for collisions and menu actions
- **Scoring & High Scores** — Persistent score tracking (planned for file-based storage)
- **MVC Architecture** — Clean separation of Model, View, and Controller
- **Unit Testing** — 8 JUnit test cases covering core game logic
- **Responsive Controls** — Keyboard (arrows / A-D) + mouse paddle control

## 🛠️ Technologies Used
- **Java 17**
- **JavaFX 17** (UI, Animation, CSS styling)
- **JUnit 4.13.2** (Testing)
- **Maven** (Project structure)

## 🧱 Gameplay
- Break all bricks by bouncing the ball off the paddle
- Prevent the ball from falling
- Score increases with each brick hit
- Special effects and visual feedback on hits

## 🧠 What I Learned
- Game loop implementation using `AnimationTimer`
- Collision detection and physics simulation
- JavaFX layout management and CSS styling
- MVC architecture for maintainable code
- JUnit testing for non-UI game logic
- Resource loading and error handling (audio, images)
- Writing technical documentation and project reports

## 🖼️ Screenshots
| Main Menu | Gameplay | How to Play |
|-----------|----------|-------------|
| (Add screenshot) | (Add screenshot) | (Add screenshot) |

## 🧪 Testing
- **8 JUnit tests** (GameModelUnitTest.java)
- Test coverage: ball movement, collisions, scoring, paddle input
- All tests pass ✅

## 📁 Project Structure
brick-breaker-javafx-game/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ ├── model/ # GameState, Ball, Paddle, Brick
│ │ │ ├── view/ # MainMenu, GameView
│ │ │ ├── controller/ # GameController
│ │ │ └── Main.java
│ │ └── resources/ # Audio files, CSS, images
│ └── test/ # JUnit tests
├── JAVASUB2.pdf # Full project report (1736 words)
└── README.md

text

## 📎 Files in This Repository
| File | Description |
|------|-------------|
| `JAVASUB2.pdf` | Full project report with design, testing, and reflection |
| `brick-breaker.zip` | Complete source code (JavaFX project) |
| (Optional) `screenshots/` | Game screenshots |

## 👩‍💻 Author
**Reema Khalaf**  
BSc (Hons) Computer Science with Cybersecurity | University of Brighton  
📍 Brighton, UK  
🔗 [LinkedIn](https://www.linkedin.com/in/reema-khalaf) | [GitHub](https://github.com/ReemaKhalaf1)

## 🚀 Next Steps
- Add persistent high scores (file I/O)
- Introduce power-ups (multi-ball, laser, etc.)
- Add particle effects on brick destruction
- Migrate to JavaFX 21 and modularize with Java modules
