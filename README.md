# CS-330 Final Project: 3D Scene with C++ and OpenGL

**Author:** Connor Martin  
**Course:** CS-330 — Computational Graphics and Visualization  
**Institution:** Southern New Hampshire University  

## 📜 Project Overview
This project is the **final deliverable** for CS-330, developed for Triangle and Cube Studios as part of a simulated client request. The goal was to replicate a selected 2D image into a **fully interactive 3D scene** using **C++**, **OpenGL**, and industry-standard computer graphics techniques.

The 3D scene features:
- Four unique low-polygon objects
- Accurate object placement based on a real-world reference
- Realistic texturing with 1024x1024+ royalty-free images
- Multiple light sources with **Phong shading**
- Smooth, responsive camera navigation
- Perspective and orthographic viewing modes

---

## 🎯 Key Features
- **Low-Polygon Modeling:** Optimized geometry under 1,000 triangles per object to maintain real-time performance.
- **Multi-Primitive Objects:** Complex objects created from combinations of basic shapes (cylinders, torus, planes, etc.).
- **Texture Mapping:** Accurately projected textures with UV scaling for realistic surface detail.
- **Lighting:** Two+ dynamic light sources, including one colored, with ambient, diffuse, and specular components.
- **Camera Controls:**
  - `WASD` — Move forward/backward/left/right
  - `Q/E` — Move up/down
  - Mouse — Look around (pitch/yaw)
  - Mouse Scroll — Adjust movement speed
  - `O` — Orthographic view
  - `P` — Perspective view

---

## 🛠️ Technologies Used
- **C++17**
- **OpenGL 4.4**
- **GLFW** — Window creation and input handling
- **GLAD** — OpenGL function loader
- **GLM** — Mathematics library for transformations
- **stb_image.h** — Image loading
- **Visual Studio 2022**

---

## 📂 Repository Contents
- `src/` — Source code files (`.cpp` and `.h`)
- `textures/` — High-resolution texture images
- `shaders/` — Vertex and fragment shader programs
- `CS-330-Final-Project.exe` — Compiled executable
- `README.md` — This file
- `Design_Decisions.docx` — Written explanation of development approach

---

## 🚀 Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/CS-330-Final-Project.git
