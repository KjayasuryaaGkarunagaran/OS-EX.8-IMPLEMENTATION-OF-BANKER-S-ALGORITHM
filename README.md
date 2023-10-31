# OS-EX.8-IMPLEMENTATION-OF-BANKER-S-ALGORITHM

## AIM:
To write a C program to implement Bankers Algorithm to avoid Deadlock.
## ALGORITHM:
1: Get the no of processes.

2: Get the process numbers.

3: Get the no of resources types and instances of it.

4: Get Max demand of each process of n x m matrices.

5: Get the n x m matrices the number of resources of each type currently allocated to each process.

6: Calculate the n x m of the remaining resource need of each process.

7: Initialize work as available resource and array of finish to false.

8: Check the Needed resource is lesser than the available resource if not display the System not in safe state and if it is lesser than system in safe state.

9: Initialize work as sum of work and allocation, check if array of finish is true go to step 7 again if not go to step 8.

10: Check that request can be immediately granted.

11: If single request is lesser than or equal to available if true means arrive to new state.

12: Print the sequenc
