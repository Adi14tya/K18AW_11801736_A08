~~~# K18AW_11801736_A08
Ques 8:
       The following processes are being scheduled using a preemptive, round robin scheduling
       algorithm. Each process is assigned a numerical priority, with a higher number indicating
       a higher relative priority. In addition to the processes listed below, the system also
       has an idle task (which consumes no CPU resources and is identified as P_idle ).
       This task has priority 0 and is scheduled whenever the system has no other available
       processes to run. The length of a time quantum is 10 units. If a process is preempted
       by a higher-priority process, the preempted process is placed at the end of the queue.
Thread Priority Burst Arrival
P1 	40 	20 	0
P2	 30 	25 	25
P3 	30 	25 	30
P4	 35 	15 	60
P5 	5 	10 	100
P6 	10 	10 	105
Write a C code to 
a. Show the scheduling order of the processes using a Gantt chart.
b. What is the turnaround time for each process?
c. What is the waiting time for each process?
d. What is the CPU utilization rate?




Ques 19:
        Ten students (s1,s2,s3,s4,s5,s6,s7,s8,s9,s10) are going to attend an event.
        There are lots of gift shops, they all are going to the gift shops and randomly
        picking the gifts. After picking the gifts they are randomly arriving in the 
        billing counter. The accountant gives the preference to that student who has
        maximum number of gifts. Create a C program to define order of billed students?
~~~
# Solution
~~~
Ans 8:  In preemptive Round Robin scheduling we know how to find the turn around time and waiting time.
        Turn Around Time (TAT) : Completion time - Arrival Time
        Waiting Time (WT) : Turn Around Time - Burst Time
        CPU utilization - Ideally the CPU would be busy 100% of the time, 
        so as to waste 0 CPU cycles. On a real system CPU usage should 
        range from 40% ( lightly loaded ) to 90% ( heavily loaded. )
        

Ans 19: The above problem is based upon the priority of students who have
        more gifts .If the student has more gifts than he will get the bill first.
        If two students have same number of gifts then the student who camed first 
        will get billed first .here the students are considered as the processes.
        The process having maximum brust time will be implemented first.
~~~
