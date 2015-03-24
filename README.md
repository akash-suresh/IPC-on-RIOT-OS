## IPC Tic-Tac-Toe!
-------------------

To run this first clone the git repo given below.  
https://github.com/RIOT-OS/RIOT  
Then clone this repository.  
This example is to illustrate the usage of RIOTs IPC messaging system.
In this example we have presented the implementation of IPC on RIOT OS by using message passing between threads. We've coded a simple single player Tic Tac Toe game which uses 4 threads for-   
	  * gameplay (MAIN thread)
	  * background music 
	  * sound thread 
	  * result thread  

Run the make file from examples/ttt directory. Execute the .elf file generated in the examples/ttt/bin/native directory.
