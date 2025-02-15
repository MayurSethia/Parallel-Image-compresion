# Parallel Image Compression Using JPEG Algorithm

This project implements parallel image compression using the JPEG algorithm. The code utilizes the Message Passing Interface (MPI) for parallel execution, significantly reducing the compression time by utilizing multiple cores.

## Main File

- **`seq-mpi.cpp`**: This is the main source file containing the core logic for parallel image compression using the JPEG algorithm. This file leverages MPI for parallel execution, allowing you to specify the number of cores (processors) to use for the task.

## Requirements

- **Linux OS**: The project is designed and tested to run on Linux environments. It takes advantage of the ability to allocate a specific number of CPU cores using MPI.
- **MPI**: The Message Passing Interface (MPI) library is required to run the parallelized code. Install MPI by running the following on a Linux machine:
  ```bash
  sudo apt-get install mpich
