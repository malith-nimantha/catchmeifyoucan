📜 Catch Me If You Can – README
🎮 About the Game
Catch Me If You Can is a simple yet fun multiplayer chase game built in Unity using Netcode for GameObjects.

The server player (host) is the Catcher.
All clients (players who join) are the Runners.
The Catcher’s goal is to chase and tag the Runners.
If a Runner is caught, the game ends, and the Catcher wins!
It’s a fast-paced game of reflexes and movement—where Runners must avoid being caught while navigating the environment.

🛠 Features
✅ Basic multiplayer functionality using Netcode
✅ Host vs. Clients gameplay (Server = Catcher, Clients = Runners)
✅ Random spawn points to prevent overlapping at the start
✅ Simple win condition (Catcher wins if they tag a Runner)

⚠ Challenges & Bugs
The development process wasn’t without its struggles! Here are some of the major roadblocks and current issues:

❌ Collision Detection Problems – The core mechanic of tagging Runners isn't working properly. Players sometimes phase through each other instead of registering a collision.

❌ Wall Collision Issues – To fix player collision, I added two colliders, but it led to a new problem: Players sometimes clip through walls.

❌ Time Reset Bug – After retrying the game, the timer doesn’t properly reset, leading to weird behaviour when starting a new round.

❌ Spawning Issue – At first, the host didn’t spawn properly. After a long debugging session, I realized they were spawning way off the map. Turns out, the fix was a 1-minute solution, but I spent way too long trying to figure it out. 😅

🔧 What’s Next?
Fixing collision detection to ensure the Catcher can properly tag Runners.
Preventing wall clipping by adjusting physics settings or using a better collider setup.
Properly resetting the timer when retrying the game.
General polish (UI, movement improvements, better feedback on when a player is caught).
💻 How to Play
Run the game in Unity
Start a server (Host becomes Catcher)
Clients join the game as Runners
Runners must avoid the Catcher until time runs out
If the Catcher tags a Runner, they win!
📌 Notes for Contributors
If you're checking out this repo and want to help:

Fixing collision detection would be a huge step forward!
Any suggestions for smoother Netcode handling are welcome.
🔗 Future Plans
I might expand this into a better multiplayer chase game with special abilities, better level design, and smoother online play. But for now, it's a fun little project with some tricky bugs. 😆

💬 Final Thoughts
Making Catch Me If You Can was a great learning experience in Unity multiplayer development. While it’s still buggy, I learned a lot about Netcode, player spawning, and collision detection—even if some solutions took way longer than they should have. 😅

If you want to try fixing some of the issues, feel free to contribute! 🚀

