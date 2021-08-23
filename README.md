# Resume - Basudev Patel

_Phone:_ +91 88972 60207
_Email:_ [1basudevpatel@gmail.com](mailto:1basudevpatel@gmail.com)

I am a passionate game developer who loves games and the technical challenges involved in building them. I have around a decade of experience working in the games-industry, on games of many different genres.

## Feb 2021 - Present: nCore Games
_Principal Software Engineer_

### Unannounced Multiplayer Sports Title (Unity/C#, Multiplayer)
Working as the Tech Lead and first engineer on the project. The title is still under development and is a 1-vs-1 sports title. This is a server-authoritative game built in Unity. Uses the Mirror library for networking and snapshot interpolation to keep clients in sync with the server.

## Oct 2018 - Feb 2021: Freelancer
_Solo-dev and contract work_

## Contracts/Collaboration

- **Freelance project for Vedantu (Unity/C#, PlayFab):** Proof-of-concept for an interactive classroom with video chat. Where the Teacher could draw on a whiteboard and could launch different kinds of "plugins". Plugins included things such as an interactive model-viewer to display anatomy, a web browser, or a car-racing game.
- **Collaborated with QYJO (Unity/C#):** Developed and programmed a method to generate [random player paths](https://medium.com/@1basudevpatel/random-paths-in-gamedev-beatdown-a913a1d8c5e6) for [Gamedev Beatdown](https://store.steampowered.com/app/1100300/Gamedev_Beatdown/).
- **Survey Creation app for an HR consulting firm (AWS, Nuxt/Vue.js):** Used a server-less stack. AWS-Lambda for APIs and S3 for the site's frontend generated using Nuxt. Let the users create surveys for their clients and collect results.

## Personal Projects

### Game Engine in C++ (WIP)
- Developed std-compliant containers to replace `std::vector` to improve debug build performance and a flat hashmap as alternatives to `std::unordered_map` and `std::unordered_set`
- Implemented a sprite renderer in d3d11 and implemented Tetris as a form of dogfooding

### City-Building game in Unity (On-Hold)
- Experiments in procedural generation of large land-masses in Unity inspired by [redblob's Polygon map generator](https://www.redblobgames.com/maps/mapgen2/)
- Developed a parallel method for generating millions of [poisson points](https://medium.com/@1basudevpatel/faster-poisson-sampling-a76cb9a99825)
- Implemented algorithms for producing terrain features from a Delaunay triangulation of the generated points. Ported Mapbox's [delaunator to C#](https://gist.github.com/bapel/c8888e6e7d365d126f454598331b9f19)
- Implemented a performant debug-renderer to visualize millions of points and lines within the Unity editor using a Mesh and a Geometry shader to draw thick points and lines
- Experiments in using Unity-DOTS for generation, simulation, and rendering of the game-world

## Nov 2016 - Oct 2018: Zynga (Bangalore)
_Senior Software Engineer_

### Empires and Allies (Unity/C#)
Empires and allies was a 3d Action-RTS game for Android and iOS. I was a lead programmer on features and performance optimizations.

- Worked on multiple features that included designing and implementing AI Logic and programming Animations for many units. Worked on a few Shaders for effects when needed.
- Revamped the UI sub-system to support the iPhone-x and other notched screens
- Responsible for multiple performance optimizations to reduce memory usage and improve frame-rates on low-medium end devices
- Created an in-game debug utility to help QA flag problems with texture size and compression settings
- Created a tool for artists to streamline recording in-game footage for trailers

## Sep 2012 - Nov 2016: Electronic Arts (Hyderabad)
_Software Engineer II_

Worked as an individual contributor on multiple projects. Work included implementing gameplay features and some r&d style work.

- **Tetris Blitz (C++):** Very short tenure working on improvements to load times, by separating HTTP requests that are not critical to game launch to a separate parallel-queue
- **Monopoly Slots (Unity/C#):** Earlier an Adobe AIR client that was later ported to Unity. Halved load times, improved first-time load, and improved frame rate on the Unity SKU. Load times were halved by moving all XML assets to Google’s FlatBuffer. The transition was accomplished bug-free using a tool I wrote that parsed all XML assets and figured out their schema and generated code for XML-to-FlatBuffer-to-runtime and other variations automagically.
- **Other titles:** Gameplay Programmer on Monopoly Bingo (Unity/C#), Theme Park (Java/Objective-C/C++), Sims Social (Adobe AIR/Flash)

# Other Experience (2010-2012)

- **Jan 2012 - Sep 2012, Contract Work (Cocos2d/Objective-C/C++):** Infinite running side-scroller with randomly generated levels
- **Aug 2010 - Jan 2012, RZ2 Games (PHP/Android/Java):** Full-stack engineer on a sports betting site
- **Feb 2010 - Aug 2012, Lecturer at ICAT:** Taught math for games for under-grads and as a refresher for post-grads. And a graphics-programming in Direct3D 9.0c class for under-grads

# Education (2006-2010)
_BA Hons. in Digital Media, Game Development from ICAT (Chennai)_

Awarded gold medal for project and dissertation on [Crowd Simulation](https://www.youtube.com/watch?v=vxSII4mlig8). The project was written from scratch in C++ and used Direct3D 9.0c (SM3.0) for rendering. The engine featured Bump-Maps and Soft-shadows. The AI used steering behaviors for movement, a hash-grid for separation, and a flow-map for pathfinding.
