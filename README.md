# Question
Write a multithreaded application in C++ as defined below:

•
In main program create a thread that generates 300 random numbers and save then in an array

•
Once this thread is completed then create three more threads such that: the first thread counts even
and odd digits in first 100 random numbers. Similarly, the second and third threads do the same with
the numbers at 100-199 and 200-299 indexes in the array respectively.

•
In the end, the main thread shows how many even and odd digits are counted by each of the thread

# Download

Move the multithreaded.cpp file to the desired directory and then right click to open the terminal

# To compile this program, enter:

g++ multithreaded.cpp -o multithreaded

# To run this program, type:

./multithreaded
