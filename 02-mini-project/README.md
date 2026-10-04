# Mini Project — Pong

---

### The Project

Made pong ghost themed. The ghost/ball becomes "angry" after each paddle collision, making it go faster and faster.

---

### Output

![Video](activity5b-video04.mp4)

<!-- Drop a screenshot or GIF of your finished project.
     Save it to a readme-assets/ folder inside this project folder.
     Got more than one good screenshot? Add them. -->

[Watch Online](https://your-link-here)

<!-- Replace the link above with a URL to a screen recording or video of your project.
     ⚠️ Make sure the file or page is set to public before submitting. -->

---

### ✍️ Reflection

I chose Pong for my assignment. I’m not particularly interested in the gameplay loop of Flappy Bird, and also thought Pong might be easier to make being a beginner at programming. I had already imagined how to code certain parts as I had worked on a similar Pong related game project for one of my game modules.

I implemented a “game over” screen which stated the final score and the winner of the match. I also implemented a way for the ball to change states upon colliding with the paddle, allowing it to be either “happy” or “angry”. When it collides with a paddle it moves incrementally faster.

 A player needs to knock the ball behind the other player’s paddle and past the edge of the screen to score a point, same as regular Pong. However, I chose best of three as my scoring system. The original Pong went up to eleven as it mimicked actual table tennies, but I felt like that was too long so I shortened it to three.

I decided to go with a ghost/exorcism aesthetic with the ball being the ghost and the paddles being talisman papers. The background takes place in a temple. I imagined the ball/ghost getting angrier whenever it gets hit by the paddle so it moves faster and faster.

I found the most challenging part was figuring out how all the code linked together. I would spend a significant amount of time reading every line of code over and over again to try and get a grasp of how everything works. Being an artist, coding in comparison is extremely precise and logic driven which makes it difficult for me.

---

<!-- ─────────────────────────────────────────────────────
     GOING FURTHER — want to document more? Try any of these:

     ### ✨ What I Changed
     A short list of the additions and modifications you made to the scaffold.
     - Changed the paddle to use mouse tracking instead of keyboard
     - Redesigned the visual language with a retro CRT aesthetic

     ### 🔍 Code Structure
     Briefly explain how your files are organised.
     - `sketch.js` — main game loop
     - `Ball.js` — ball class with collision logic
     - `assets/` — sprites and sounds

     ### 🧩 Something I'm Proud Of
     A snippet of code, a design decision, a moment where it clicked.
     ```js
     // your code here
     ```

     ### 🔗 References
     Anything that helped or inspired you — tutorials, artworks, tools.
     ───────────────────────────────────────────────────── -->
