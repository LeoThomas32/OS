# FCFS CPU Scheduling

A C implementation of the **First Come First Serve (FCFS)** CPU scheduling algorithm — the simplest non-preemptive scheduling method where processes are executed in the order they arrive.

## Features
- Accepts n processes with Process ID, Arrival Time, and Burst Time
- Handles CPU idle time (when no process is available)
- Computes Waiting Time and Turnaround Time for each process
- Outputs Average Waiting Time and Average Turnaround Time

## Input Format
n
PID1 AT1 BT1
PID2 AT2 BT2
...
PIDn ATn BTn

## Compilation & Usage
gcc -o fcfs fcfs.c
./fcfs

## Topics
C · CPU Scheduling · Operating Systems · FCFS · Process Scheduling
