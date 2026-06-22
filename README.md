# Two-Stage Shutdown Maintenance Scheduling under Decision-Dependent Failure Uncertainty
## Overview
This repository contains the benchmark instances and computational results associated with the paper:
Two-Stage Shutdown Maintenance Scheduling under Decision-Dependent Failure Uncertainty

The paper studies a two-stage stochastic shutdown maintenance scheduling problem in which first-stage maintenance decisions influence component failure probabilities before a second planned shutdown. The repository provides all benchmark instances and computational results used in the numerical experiments reported in the paper.

# Contents
## Instances
This folder contains the benchmark instances used in the computational experiments.

Instances were generated using benchmark project data from the Resource-Constrained Multi-Project Scheduling Problem (RCMPSP) library. In the shutdown maintenance setting, each project is interpreted as a maintenance component consisting of multiple maintenance activities with precedence relationships and resource requirements.

Five instances were generated for each problem size:

- |J|=5
- |J|=6
- |J|=7
- |J|=8
- |J|=10
- |J|=15

Each instance contains:

- Component information
- Activity durations
- Resource requirements
- Precedence relationships
- Corrective maintenance costs
- Failure probabilities
- Shutdown capacities
- Budget parameters

## Results
This folder contains the computational results reported in the paper, including:

- Objective values
- Computational times
- Solution quality comparisons
- Optimality gap results
- Sample Average Approximation (SAA) results
- Clustered SAA results
- Proxy-based solution results
- Satistical robutness analyses
