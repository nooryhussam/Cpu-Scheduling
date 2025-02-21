CPU Scheduling Algorithms

CPU Scheduling is the method by which an operating system decides the order in which processes are executed by the CPU. It aims to:

Maximize CPU utilization

Minimize waiting time

Ensure fair resource allocation

Common Scheduling Algorithms

First-Come, First-Served (FCFS)
Processes are executed in the order they arrive.

Non-preemptive algorithm.

Simple but can lead to the convoy effect, where short processes wait for long ones.

Shortest Job First (SJF)
Selects the process with the smallest execution time.

Can be preemptive or non-preemptive.

Provides optimal waiting time but requires knowledge of process burst times.

Round Robin (RR)
Each process gets a fixed time (time quantum) in a cyclic order.

Preemptive algorithm ensuring fairness.

Ideal for time-sharing systems, but performance depends on the chosen time quantum.

Priority Scheduling
Each process is assigned a priority; the CPU selects the highest priority process.

Can be preemptive or non-preemptive.

Can lead to starvation, where low-priority processes wait indefinitely (solved with aging technique).

Conclusion

Choosing the right scheduling algorithm depends on the system requirements. While FCFS is simple, SJF minimizes waiting time, RR ensures fairness, and Priority Scheduling allows differentiated task handling. A balanced approach is needed for optimal CPU scheduling.
