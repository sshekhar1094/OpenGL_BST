Implementation of Tidy Drawings of Trees by CHARLES WETHERELL AND ALFRED SHANNON

Compile: g++ main.cpp -lglut -lGL -lGLU
Execute: ./a.out

Documentation: Doxygen_Documentation/index.html

This project consists of 3 files:
	1. bst.h: Creates a simple binary tree to be used for. Returns the root of the constructed tree to main()
	2. main.cpp: Does the implementation of Tidy Drawings and then calls functions in draw.h for openGL display
	3. draw.h: draws the tree using openGL. The nodes are drawn using Midpoint circle drawing and lines using Bresenham's line drawing algorithm.


