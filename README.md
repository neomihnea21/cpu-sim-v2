# Scheduling Simulator

This project simulates various real time algorithms and benchmarks their
performance in different scenarios.

Implemented algorithms:

 - [x] First Come, First Served (FCFS)
 - [x] Shortest Job First (SJF)
 - [x] Preemptive Shortest Job First (PSJF)
 - [x] Priority based
 - [ ] Round Robin (RR)
 - [ ] Rate monotonic (RM)
 - [ ] Earliest Deadline First (EDF)

# Metrics

In order to compare scheduling algorithms we will evaluate them based on the
following metrics:

- [x] Turnaround time (T_completion - T_arrival)
- [x] Waiting time (T_turnaround - T_burst)
- [x] Response time (T_first_on_cpu - T_arrival)

# Results

![Workload 1 Usage.jpg](plots/Workload_1_Usage.jpg)
![Workload 1 Turnaround.jpg](plots/Workload_1_Turnaround.jpg)
![Workload 1 Waiting.jpg](plots/Workload_1_Waiting.jpg)
![Workload 2 Usage.jpg](plots/Workload_2_Usage.jpg)
![Workload 2 Turnaround.jpg](plots/Workload_2_Turnaround.jpg)
![Workload 2 Waiting.jpg](plots/Workload_2_Waiting.jpg)
![Workload 3 Usage.jpg](plots/Workload_3_Usage.jpg)
![Workload 3 Turnaround.jpg](plots/Workload_3_Turnaround.jpg)
![Workload 3 Waiting.jpg](plots/Workload_3_Waiting.jpg)
![Workload 4 Usage.jpg](plots/Workload_4_Usage.jpg)
![Workload 4 Turnaround.jpg](plots/Workload_4_Turnaround.jpg)
![Workload 4 Waiting.jpg](plots/Workload_4_Waiting.jpg)
![Workload 5 Usage.jpg](plots/Workload_5_Usage.jpg)
![Workload 5 Turnaround.jpg](plots/Workload_5_Turnaround.jpg)
![Workload 5 Waiting.jpg](plots/Workload_5_Waiting.jpg)

# References
- https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf
- Operating System Concepts, 10th Edition
by Abraham Silberschatz, Peter B. Galvin, Greg Gagne
