# Computer_Graphics_Practicals
#NAME - SHIVANI
#ROLL NO. - 20/88005
Setup graphics.h
Follow this link to download MinGW C++ Compiler(GCC).
Download the three setup files, i.e. graphics.h, winbgim.h and libbgi.a.
Copy the files graphics.h & winbgim.h to C:\MinGW\include.
Copy the file libbgi.a to C:\MinGW\lib.
To Run code
To compile any cpp file with <graphics.h>, use below:
g++ **FILENAME**.cpp -o main -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
To run, write ./main.exe.

Practical List
Write a program to implement DDA line drawing algorithm.
Write a program to implement Bresenham’s line drawing algorithm.
Write a program to implement mid-point circle drawing algorithm.
Write a program to apply various 2D transformations on a 2D object.
Write a program to apply various 3D transformations on a 3D object and then apply parallel and perspective projection on it.
