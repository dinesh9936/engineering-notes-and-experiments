# Processes

## Definition
A process is an instance of a program in execution. It includes the program code, data, and resources allocated by the operating system.

## Key Characteristics
- **Process ID (PID)**: Unique identifier for each process
- **State**: Running, waiting, ready, or terminated
- **Memory**: Code, data, heap, and stack segments
- **Context**: CPU registers, program counter, stack pointer

## Process States
- **New**: Process being created
- **Ready**: Waiting to be assigned to CPU
- **Running**: Currently executing on CPU
- **Waiting**: Blocked on I/O or event
- **Terminated**: Process finished

## Process Control Block (PCB)
Contains process information:
- PID
- Program counter
- CPU registers
- Memory limits
- I/O status
- Scheduling info

## Context Switching
The OS switches between processes by:
1. Saving current process state to PCB
2. Loading next process state from PCB
3. Resuming execution of next process

## Process vs Thread
- **Process**: Independent with separate memory space
- **Thread**: Shares memory with other threads in same process