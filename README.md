# Batch-OS

The CPU scheduling algorithms present today are not appropriate for a wide range of systems. Different algorithms are required by different systems. For example, Batch operating system mostly uses priority CPU scheduling. A comparative analysis of our algorithm for batch operating systems with the algorithms for other systems like fcfs, priority and round robin will be presented on the basis of average turnaround time, average waiting time, varying time quantum and number of context switches.

## Algorithm:
It is generally considered that priority scheduling is best for batch operating systems for optimal use of processor time and enhanced efficiency of the system. In Priority Scheduling, a priority is assigned to each process, which is decided on the basis of memory and other resource requirements. The process with the highest priority is executed first, followed by the processes in the same order. If two processes have the same priority, the First Come First Serve method is used to remove ambiguity. This results in high priority jobs to have low waiting time and so the problem of deadlines being not met can be eradicated. Disadvantage of this method is that of starvation of lower priority processes, i.e. the low priority process to wait indefinitely for its turn. This is possible when a large number of higher priority processes continuously arrive.

## Proposed Solution
The main issue of Batch Operating systems was
• If some job takes too much time i.e. if error occ urs in job then other jobs will wait for unknown time<br>
• To speed up the processing, jobs with similar need to be batched together and run as a group.<br>
• It is difficult to provide the desired priority. <br>

As indicated by the necessities of the Batch type system, we developed a program based on Round Robin and Priority Algorithm which will take advantage from both algorithms to evaluate the requirements and utilize the appropriate scheduling algorithm for maximum efficiency. <br>

A comparative analysis of our algorithm for batch operating systems with the algorithms for other systems like FCFS, priority and round robin was presented on the basis of average turnaround time, average waiting time, varying time quantum and number of context switches to prove our concept.<br>

Thus we have enhanced the working of the computer system by reducing the average waiting time, average turnaround time and reducing the number of context switches
from generic algorithms.<br>
  
## Tables:
![image](https://user-images.githubusercontent.com/70879718/173279903-1c07ba35-5138-46ae-88a1-91209f63b49a.png)

![image](https://user-images.githubusercontent.com/70879718/173279960-c6067410-7066-47af-98d5-68680117a087.png)
