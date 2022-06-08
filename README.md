# PartitionPIM: Practical Memristive Partitions for Fast Processing-in-Memory
## Overview
This is the simulation environment for the following paper, 

`O. Leitersdorf, R. Ronen, and S. Kvatinsky, “PartitionPIM: Practical Memristive Partitions for Fast Processing-in-Memory,” 2022.` 

The goal of the simulator is to verify the correctness of the algorithms proposed in the paper,
to mesaure the performance of the algorithms (cycles & area), and to provide interfaces for the models proposed in this paper. The simulator is 
adapted from the MultPIM [1] simulator.

## User Information
### Dependencies
This project requires the following libraries:
1. python3
2. tqdm

### Organization
The repository is organized into the following directories:
- `unlimited`: Contains the simulator and implementation for the unlimited model.
- `standardized`: Contains the simulator and implementation for the standardized model.
- `minimal`: Contains the simulator and implementation for the minimal model.

Each directory includes the simulator that models that PIM model, and the implementation of MultPIM for that model.

## References

[1] O. Leitersdorf, R. Ronen and S. Kvatinsky, "MultPIM: Fast Stateful Multiplication for Processing-in-Memory," in _IEEE Transactions on Circuits and Systems II: Express Briefs_, vol. 69, no. 3, pp. 1647-1651, March 2022.
