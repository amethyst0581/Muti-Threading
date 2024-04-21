# Muti-Threading
This repository explains how we performed multithreading using python's threading library.
Experiment performed on: AMD Ryzen 5500 U Hexa-Core CPU [12 Logical units(CPUs thanks to hyper threading)]
1. Firstly we import multiple librariries, including Python's threading library to make multiple threads.
2. The number of threads for each iteration are stored in an array.
3. Two functions are made, first to generate 1000 random 1kx1k matrices, second to multiply them with a constant matrix of size 1kx1k
4. Mutiple threads are made using threading library, and the process visualized using a table and a graph.
5. The result clearly shows, that minimum time is taken when number of threads=number of CPUs, i.e. 12 in this case.
