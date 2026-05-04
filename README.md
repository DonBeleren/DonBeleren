# DonEliezer Baize 👋

Senior iOS engineer. Hawaii-raised 🌺, Utah-located 🏔️, slightly confused about the weather.

Right now I'm leading iOS at **Alignment Products Llc.** 🚗 — sensor-driven automotive app. It's mostly Swift, networking architecture, and the kind of work where the goal is "make this scale and stop coupling everything together."

The graphics stuff I'm known for is from before. I spent a couple of years at **Miris** 🎬 wiring a C++/Metal engine into a SwiftUI app for spatial streaming, and writing a gRPC SDK from scratch to move the datasets around. A patent came out of that work 📜 — US 11,676,328, prioritized rendering and streaming. Earlier I co-founded **PersonaFi** 📈, a social trading app, where I was the iOS team for a stretch.

These days the graphics work happens on my own time 🌙. That's most of what's on this page.

## projects

🏢 **[Edifice](https://github.com/DonBeleren/edifice)** — write a script, get a 3D building. C++ / Qt / OpenGL, with a Flex/Bison grammar driving split / merge / group / texture ops on a live `Building` model. The DSL has its share of footguns (a color value without a decimal point silently kills the rest of the parse) which I keep meaning to fix and never do.

🪟 **[split-grammar-2d](https://github.com/DonBeleren/split-grammar-2d)** — the 2D version that came before Edifice. Hand-rolled recursive descent parser, fixed 3×3 grid, ~1,600 lines. Edifice is the better one. This is where I figured out what I actually wanted.

🌊 **[gpu-water-rendering](https://github.com/DonBeleren/gpu-water-rendering)** — animated water, all in shaders. Three sine waves at different wavelengths and directions, four octaves of Perlin FBM on top, and a domain-warp pass that nudges the sample position so the wave fronts curve instead of marching in straight lines. Normals come from finite differences of the height function. There's a procedural island in the middle of it.

🧠 **[vtk-volume-rendering](https://github.com/DonBeleren/vtk-volume-rendering)** — direct volume rendering of a CT head scan and a turbulent jet flame. The head transfer function pulls three tissue layers out of one scalar field — skin around 550, muscle around 1100, skull around 1450. Raise opacity on one range, that layer pops out. Tuning the transfer function is most of the project.

☄️ **[asteroid-rendering](https://github.com/DonBeleren/asteroid-rendering)** — VTK rendering of LANL's deepwater asteroid impact ensemble. Five PyQt5 viewers for tuning transfer functions on each scalar (water, asteroid, temperature, pressure, isosurface), plus a batch renderer that walks a folder of VTI timesteps and spits out PNGs you can hand to ffmpeg.

## stack

🍎 **Apple** — Swift, SwiftUI, UIKit, Objective-C, Metal, CoreBluetooth, CoreML, ARKit, Combine, NearbyInteractions, CoreAnimation, CoreGraphics

🎨 **Graphics / native** — C++, OpenGL, GLSL, Qt, Flex/Bison, GLFW, GLM

🐍 **Python** — VTK, PyQt5

🌐 **Networking & backend** — REST, gRPC, Alamofire, AWS Amplify, Firebase

📧 doneliezerbaize@gmail.com · 💼 [linkedin](https://linkedin.com/in/doneliezer-baize/)
