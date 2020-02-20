Linux Kernel
The Linux kernel is the main component of a Linux operating system(OS) and is the core interface between a computer’s hardware and its processes. It communicates between the two, managing resources as efficiently as possible.
The kernel has 4 jobs:
Memory management: Keep track of how much memory is used to store what, and where
Process management: Determine which processes can use the CPU, when, and for how long
Device drivers: Act as mediator/interpreter between the hardware and processes
System calls and security: Receive requests for service from the processes.
Code executed by the system runs on CPUs in 1 of 2 modes: kernel mode or user mode. Code running in the kernel mode has unrestricted access to the hardware, while user mode restricts access to the CPU and memory to the system call interfaces.
