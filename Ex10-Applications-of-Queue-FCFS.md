# Ex2E Applications of Queue – FCFS
## DATE:12-03-2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Define a function to count the number of elements in the deQueue.
4. Run a loop from zero index to maximum index value and increment count if the value is not equal to zero. Return the counted value.
5. End the program.
## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: GAYATHRI M
RegisterNumber: 212223220024
*/

#include <stdio.h>
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
   int i;
   for(i=0;i<n;i++)
   {
       tat[i]=burst_time[i]+wait_time[i];
   }
   return 0;
}
```


## Output:

![437105363-2ddc42eb-6fbe-4b3a-a7b8-89c8e8c244b4](https://github.com/user-attachments/assets/0e1a0806-1356-4a1d-8f29-4d6fd808fc72)



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
