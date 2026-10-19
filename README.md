# PowerOS — Battery-Aware Process Scheduling Simulator

**PowerOS** is a web-based Operating System simulator that demonstrates how CPU scheduling algorithms affect process performance and simulated battery energy consumption.

The project combines traditional CPU scheduling algorithms with a Battery-Aware Adaptive Scheduling (BAAS) approach. It allows users to simulate process execution, compare scheduling results, and observe how CPU utilization relates to estimated power consumption.

## Features

- **Interactive Dashboard:** Displays battery status, energy consumption, CPU utilization, and scheduling performance metrics.
- **Process Management:** Add, edit, and manage processes with configurable arrival times, burst times, priorities, and other scheduling parameters.
- **CPU Scheduling Simulator:** Simulates processes using FCFS, Shortest Job First (SJF), Round Robin, and Priority Scheduling.
- **Battery and Power Monitoring:** Displays simulated battery capacity, energy usage, and power-related metrics.
- **Battery-Aware Adaptive Scheduling (BAAS):** Compares an adaptive scheduling approach with conventional CPU scheduling algorithms.
- **Algorithm Comparison:** Compares waiting time, turnaround time, response time, makespan, and CPU utilization.
- **Gantt Chart Visualization:** Displays process execution order and scheduling timelines.
- **Simulation History:** Allows users to review previous simulation results.
- **Academic Report:** Generates a structured report of simulation results.
- **Automated Tests:** Helps verify scheduling logic and metric consistency.

## Tech Stack

- **Frontend:** React, TypeScript
- **Build Tool:** Vite
- **Styling:** CSS, Tailwind CSS
- **Testing:** Scheduling and consistency tests

## Scheduling Algorithms

| Algorithm | Description |
|---|---|
| FCFS | Executes processes in order of arrival. |
| SJF | Selects the process with the shortest CPU burst time. |
| Round Robin | Allocates CPU time using a configurable time quantum. |
| Priority Scheduling | Selects processes according to their priority. |
| BAAS | Implements a battery-aware adaptive scheduling approach for comparison with conventional algorithms. |

## Performance Metrics

PowerOS calculates and displays the following metrics:

- **Waiting Time:** Time a process spends waiting for CPU execution.
- **Turnaround Time:** Total time from process arrival to completion.
- **Response Time:** Time from process arrival until its first CPU execution.
- **Makespan:** Total elapsed time required to complete the workload.
- **CPU Utilization:** Percentage of elapsed time during which the CPU is busy.
- **Energy Consumption:** Estimated energy used during the simulation.
- **Battery Level:** Simulated remaining battery capacity.

**Note:** Battery levels and energy consumption are simulated estimates. They do not represent real-time measurements of the laptop's physical battery.

## Getting Started

### Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/) — preferably a current LTS version
- npm, which is included with Node.js
- [Git](https://git-scm.com/) — optional, for cloning the repository

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/tanishiraj321/PowerOS.git
```

**2. Open the project directory**

```bash
cd PowerOS
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

Open the local URL displayed in the terminal, usually `http://localhost:5173/`.

## Testing

Run the test suite using the test script configured in `package.json`. For example, if the project uses Vitest:

```bash
npm test
```

To create a production build, run:

```bash
npm run build
```

## Project Objectives

PowerOS aims to demonstrate:

- How different CPU scheduling algorithms influence process execution and performance.
- How scheduling decisions can be evaluated alongside simulated energy consumption.
- How an adaptive scheduling strategy can be compared with traditional scheduling methods.
- How operating system concepts can be demonstrated through an interactive web interface.

## Academic Context

PowerOS is an educational Operating Systems project developed to explore CPU scheduling, performance analysis, and battery-aware process management through simulation.

## Author

**Raghav Ojha**
