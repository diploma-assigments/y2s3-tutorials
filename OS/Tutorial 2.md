## Processor Management
#### Q1
##### a) Describe the term "process" in the context of operating systems.
> - A process is a "job" that an individual program has pushed to the CPU (the executable program)
> - It is allocated a set of resources (registers, program counter, and data section) and will encompass one or more threads.
> - Each process in the OS is represented by a (process control block) PCB repository for information such as Process identification. Process status (HOLD, READY, RUNNING, WAITING), Process state etc. PCB's content varies from process to process

##### b) Elaborate how context switch enables multiple processes to share a single processor.
> - The context-switch is an essential feature of a multiprogramming OS. Context switching is the act of saving a job's processing information in its PCB so the current job can be swapped out of memory and loads the processing information from the PCB of another new coming or interrupted job into the appropriate registers. This enables multiple processes to share CPU.
> - On a large scale, these time slices are nanoseconds long, so it appears to the user that the processor is processing processes concurrently.
> - Time <u>dependent</u> on hardware support. Context switch may take 10 ns, 5 ns (depends on the CPU)
> - The ultimate goal is to keep the system responsive while really maximizing the processor's ability to process.

#### Q2: Differentiate between the following.
##### a) I/O bound and CPU bound

| I/O bound                                                                                              | CPU bound                                                                                    |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| I/O-bound jobs (such as printing a series of documents) have many brief CPU cycles and long I/O cycl CPU-bound jobs (such as first 300 prime numbers) have long CPU cycles and short I/O cycles g  )  |

##### b) With
## Self Review
