
# CPU Scheduling Visualizer Project

This project is a simple and interactive CPU Scheduling Visualizer implemented using Python in Google Colab. It helps to understand and simulate how different CPU scheduling algorithms work using Gantt Charts and other visualizations.

## Project Overview
The CPU Scheduling Visualizer simulates four core scheduling algorithms: FCFS, SJF, Round Robin, and Priority Scheduling. It allows users to input process details and time slices (in case of RR) and view the scheduling behavior through a clear Gantt chart representation.

## Project Structure and Step-wise Development

###  Phase 1: Input Module
- Developed basic UI to input number of processes, burst time, arrival time, etc.
- Integrated Colab widgets for a better input experience.

###  Phase 2: Scheduling Logic Module
- Implemented FCFS scheduling logic.
- Extended logic to SJF (non-preemptive).
- Developed Round Robin with configurable time quantum.
- Added Priority Scheduling using both arrival time and priority queueing.

###  Phase 3: Gantt Chart Visualization
- Matplotlib used to plot the Gantt chart.
- Added color coding for each process.
- Improved visuals to show process start and end times clearly.

###  Phase 4: Output Display
- Printed detailed table of Process ID, Waiting Time, Turnaround Time.
- Displayed average waiting and turnaround time after every scheduling simulation.

## Functionalities

- FCFS (First Come First Serve)
- SJF (Shortest Job First - Non-preemptive)
- Round Robin (with Time Quantum input)
- Priority Scheduling (based on user-defined priorities)

## Technology Used

### Programming Languages:
- Python

### Libraries and Tools:
- Google Colab (for development)
- Matplotlib (for Gantt chart)
- NumPy, IPython (for logic and display)

### Other Tools:
- GitHub (for version control and collaboration)

## GitHub Tracking

- Repository Name: cpu-scheduling-visualizer
- GitHub Link: https://github.com/evxn77/cpu-scheduling-simulator.git

## Conclusion and Future Scope

This project makes CPU scheduling algorithms easier to learn through visual understanding. In future, we can implement:
- Preemptive versions of SJF and Priority Scheduling
- Integration with Streamlit for web app version
- More real-world examples and I/O-bound process handling

