							Inter Process Communication with different Methods.


								
						

 
Problem: Matrix Multiplication

Methods:
1.Named Pipes
2.Unnamed Pipes
3.Shared Memory

Named Pipes:
	This type of communication is bi-directional and pipe is used for communication.
	There are two files fifo_write.c,fifo_read.c 
	
fifo_write:writes 2 matrices of 2*2 dimensions and fifo read reads it and multiply it and shows results;
first run fifo_write with following command on terminal :  gcc -o fifo_write fifo_write.c then gcc -o fifo_read fifo_read.c
then run ./<Filename>


Unanamed Pipes:

This is a one way communication method.
In this a child process is created and given data matrices to run multiplication on and show output
To run : same gcc -o ...

Shared Memory:
 In this communication method we have written data matrix on some temp/location after generating a key and with help of that key we attach our data to some temp memory
 and same method of generating key is used and data matrices are read from temp location and multiplied and output is shown on terminal
	 	

 
