#### 1.
##### (i)
Operating System.
- A software between hardware and application program
- Manage all hardwares & control application software
- How? Interface, auto allocate resources for sw, e.g. more RAM for games

##### (ii)
- Windows
- MacOS

##### (iii)
- Make computer system easy to use (interface)
- Execute application softwares
- Allocate resources e.g. CPU time
- Control I/O operations

##### (iv)
- Use Windows 11 GUI, click This PC, go to Downloads or other folders to access files stored in storage hardware.

##### (v)
- Memory manager (RAM)
- File manager
- Device manager (I/O e.g. pendrive)
- Processor manager (CPU)
- Network manager


#### 2.
##### a)
Batch System > routine tasks

##### b)
Embedded System > In printer, specific purposes

##### c)
Can work on windows / mac (kiosk, desktop, laptop) & on ios / android (tablet)


#### 3.
The purpose of system calls is to provide an interace between a process and  operating system to allow use-level processes to request services of the operating system.

- Process Control (e.g. fork(), exit())
- File Management (e.g. open(), close())
- Device Manager (to request device, e.g. ioctl())
- Information Maintenance (to get time or date, set time or date)


#### 4.
##### i)

| Interrupts                                                                                     | Traps                               |
| ---------------------------------------------------------------------------------------------- | ----------------------------------- |
| Called hardware interrupts                                                                     | Called software interrupts          |
| Trigered by hardware                                                                           | Triggered by software               |
| A signal indicating an event that requires immidiate attention                                 |                                     |
| Trigger processor to execute corresponding interrupt handler routine (e.g. stop infinite loop) | Transfer control to trap controller |

##### ii)
If the computer is without interrupt capability, the CPU protection cannot maintain control on every process. It will lead to the process having infinity looping. In conclusion, without interruption, the CPU will not know that a certain process has been completed or otherwise and the next task could not be initiated. The processor will run the program forever, other programs will wait to be executed until the program is finished, the computer will be damaged.

1. Cannot maintain control -> e.g. cannot stop infinite loop, lose control
2. Cannot know process status (completed, abourted etc)
3. No interrupt, cannot multitask

##### iii)
- When a user sends an instruction to execute, then the program executes in user mode. When an interrupt occurs, the hardware switches from user mode to monitor mode.
- OS preserves the state of the interrupt process by storing registers and the program counter.
- Control transfer to Interrupt Service Routine (ISR), after the Interrupt Stack Pointer (ISP) has completed, the saved process will return register values that are loaded into the CPU. The machine is switched back to user mode and the interrupted computation resumes.

