# CS 3502 - CPU Scheduling Simulator

Extended by Sam Spear - KSU CS 3502 Operating Systems, Section W03, Spring 2026


## About This Project

This project extends the provided CPU Scheduling Simulator starter code by adding two new scheduling algorithms, performance metrics, and a CSV export feature.

## New Features Added

- **SRTF (Shortest Remaining Time First)** - Preemptive version of SJF
- **HRRN (Highest Response Ratio Next)** - Balances efficiency and fairness using response ratio formula
- **Performance Metrics** - CPU utilization, throughput, average waiting time, average turnaround time displayed after each algorithm run
- **CSV Export** - Export results data to CSV file

## Algorithms Available

| Algorithm | Type | Notes |
|-----------|------|-------|
| First Come First Serve (FCFS) | Non-preemptive | Processes execute in arrival order |
| Shortest Job First (SJF) | Non-preemptive | Selects process with shortest burst time |
| Priority Scheduling | Non-preemptive | Higher number = higher priority |
| Round Robin (RR) | Preemptive | Each process gets a time quantum before switching |
| SRTF | Preemptive | Always runs process with shortest remaining time |
| HRRN | Non-preemptive | Selects process with highest response ratio |

## Platform

- Windows 11
- .NET 7.0
- Visual Studio 2022

## Requirements

- Windows operating system
- .NET 7.0 SDK or newer
- Visual Studio 2022

## How to Run

1. Clone the repository
2. Open `CpuScheduler.sln` in Visual Studio 2022
3. Press F5 to build and run

## Usage

1. Enter the number of processes in the Scheduler panel
2. Fill in burst time, priority, and arrival time for each process
3. Click any algorithm button to run
4. View results in the Results panel including performance metrics

## GitHub

https://github.com/sammm12349/CS-3502-CPU-Scheduler

## License

MIT License
