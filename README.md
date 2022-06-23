## Project overview:

1. ### Project 2
   Project 2 begin with user program. Code in PintOS supported user program to run in PintOS. But I/O devices and some functions have not satisfied. In project 2 we allow user programs interact with kernel through system calls. However, to work with userprog, we need to consider others processes to make sure the OS will not error by missing interact among processes.
1. ### Requirement
   Run "pintos --filesys-size=2 -p ../../examples/echo -a echo -- -f -q run'echo x'"
1. ### Project 4
   Project 4 work with file system in the PintOS. Code in current PintOS supported interact with the file system but there are some basic function have not been implemented and the system is slow due to lack of optimal functionality.
1. ### Requirement
   Implement buffer cache to increase the OS performance. Change the read/write process to be interacted with buffer cache with the consideration to the synchronization.
