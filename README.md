# Digital Design Verification Projects

This repository contains three implementations of counters with different verification methodologies, demonstrating progression from SystemVerilog to UVM-based verification approaches.

## Projects Overview

### 1. Module-12 Up/Down Loadable Counter with SystemVerilog Verification
- Implementation of a parameterized 12-bit up/down counter with load functionality
- Comprehensive SystemVerilog testbench with:
  - Constrained random stimulus
  - Functional coverage
- Detailed verification reports and waveforms

### 2. Up Counter with UVM Testbench
- Basic up counter implementation
- Complete UVM-based verification environment featuring:
  - Reusable components (Sequencer, Driver, Monitor)
  - Scoreboard for result checking
  - Coverage collection
  - Test scenarios
- Performance and coverage reports

### 3. Module-12 Up/Down Loadable Counter with UVM
- Advanced implementation combining previous projects
- Comprehensive UVM verification environment including:
  - Layered testbench architecture
  - Sequence library
  - Configuration database usage
  - Advanced coverage metrics
  - Comprehensive test scenarios
- Full verification reports and analysis

## Directory Structure
```
.
├── counter_sv
│   ├── counter.sv
│   └── README.md
├── mod12_counter_uvm
│   ├── env
│   ├── rd_agt
│   ├── README.md
│   ├── report
│   ├── rtl
│   ├── sim
│   ├── test
│   ├── top
│   └── wr_agt
└── up_counter_uvm
    ├── dest
    ├── env
    ├── README.md
    ├── report
    ├── rtl
    ├── sim
    ├── source
    ├── test
    └── top
```

## Key Features
- Multiple verification methodologies
- Comprehensive test coverage
- Detailed reports

## Requirements
- QuestaSim for simulation
- SystemVerilog supported simulator
- UVM 1.2 or later
- VCS/Questa verification platforms

## Getting Started
1. Clone the repository
2. Navigate to the desired project directory
3. Follow the specific README in each project folder for detailed instructions
4. Run simulation using provided Makefile in the sim directory

## Reports
Each project contains detailed reports including:
- Functional coverage metrics
- Test scenarios and their results
- Follow the each README.md file for more instructions

## Contributing
Feel free to contribute by:
- Reporting bugs
- Suggesting enhancements
- Adding new test scenarios
- Improving documentation


