#### Q1

|                | Batch                          | Time Sharing                    | Real-Time                         | Hybrid                                                                                                     | Embedded                          |
| -------------- | ------------------------------ | ------------------------------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------- |
| Characteristic | Similar jobs, process serially | Interactive                     | Minimum delay, fast               | Batch + Interaction                                                                                        | Add to other product. Add feature |
| Execution      | First come first served        | Round robin                     | priority                          | Batch at background with interactive (can say either FCFS or RR, since combination of Batch & Interactive) | Value added (FCFS)                |
| Best used for  | Serial job                     | Interactive environment         | Time critical system              | High demand / low demand                                                                                   | Additional features               |
| App            | Payroll, billing               | Directory Board, Mcd Kiosk, ATM | Hospital system, National defense | Manufacturing system, Chemical Process, Control system                                                     | Photocopier                       |

#### Q2
- OS is a required component of the computer system.
- Without an OS, computer hardware is only and inactive 

#### Q3
- Batch mode processing is actually done by MOS businesses in some way. Usually at months end when they are sending out their invoices.
- Printing shipping labels and packing slips.
- Generation of payroll. Bank Statements. monthly utility bills, etc.
- Banking - Processing transactions (e.g. check clearing) overnight.
- Airline Ticketing - Generating flight schedules and passenger manifests.

#### Q4
##### i)
True. A time-sharing operating system is an operating system design that allows multiple users or processes to concurrently share the system resources, such as the CPU, memory and peripherals

Multiple users / programs share the CPU by getting small time slices (e.g. 10ms per process).
The CPU switches between processes so quickly that it feels like everything runs simultaneously.
Example: Windows, Linux, MacOS

##### ii)
- False. Kernal is the core part of the OS which is responsible for managing resources, allowing multiple processes to use the resource3s and provide services to various processses. Kernal modules can be loaded and unloaded in run-time i.e. in running OS.
##### iii)
- False
- Requesting allocate or deallocate memory space in the OS is a privileged instruction.
- A privileged instruction is an instruction that can only be executed in kernel mode. Instructions are divided in this manner because privileged instructions can harm the kernel.