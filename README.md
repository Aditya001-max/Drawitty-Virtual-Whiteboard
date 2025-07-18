# Drawitty-Virtual-Whiteboard

![](https://github.com/Aditya001-max/Rubiks-Cube-Solver/raw/main/assets/rubiks-cube-preview.png)

Rubik’s Cube Solver
===
This is a personal project aimed at developing a **Rubik’s Cube solver** using Python.  
It begins with the logical structure of the cube, move sets, and visualization, and progresses toward implementing solving algorithms like **IDA\*** and **Korf’s Algorithm**.  
Currently, work is being done on **3D modeling using OpenGL**. Once the visual model is completed, the next step is integrating a solver.  
The ultimate goal is to use **OpenCV** for real-time cube scanning and apply the solver to real-life inputs.

**Key Objectives:**
- Build a 3D interactive Rubik’s Cube
- Implement cube rotations and user interactions
- Apply optimal solving algorithms
- Integrate real-time image processing for cube recognition

You can follow development on:
- [Blogger](https://bitsits.blogspot.com/2011/06/rubiks-cube.html)
- [Tumblr](https://suvozit.tumblr.com/post/96210256543/rubiks-cube)

---

Rubik's Cube Solver Engine
===
✅ Built in Python  
✅ Cube state representation using arrays  
✅ Move simulation (U, D, L, R, F, B)  
✅ Plans for 3D rendering using OpenGL  
✅ Aiming for optimal solver using [Korf's Algorithm][korf] / [IDA\*][ida]

![](https://github.com/Aditya001-max/Rubiks-Cube-Solver/raw/main/assets/rubiks-cube-solver-demo.png)

Download: [RubiksCubeSolver.zip][zip] (253 KB)

---

## How to Run

1. **Clone the Repository**
```
git clone https://github.com/Aditya001-max/Rubiks-Cube-Solver.git
cd Rubiks-Cube-Solver
```
2. Install Required Libraries
```

pip install -r requirements.txt
```
3. Run the Main Script
```
python main.py
```
4. Folder Structure
```
Rubiks-Cube-Solver/
│
├── assets/                    # Demo images, UI mockups
├── core/                      # Logic for cube rotation and state
├── solver/                    # Planned space for solving algorithm
├── opengl_model/              # 3D model rendering files
├── main.py                    # Entry point
└── requirements.txt           # Python dependencies
```
Author
```
Aditya Raj Kaushik
GitHub: @Aditya001-max
```

References
- Korf's Algorithm
- IDA* Algorithm
