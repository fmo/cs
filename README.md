# Process vs Thread

## Program

Program is an executable file which has code or set of processor instructions, that is stored as a file on the disk.

## Process

Each process has its own memory address space. Own process can not corrupt the other process's memory space.
If one process malfunction the other process keeps functioning. I.E Chrome is running each tab 
as a process to take advantage of this concept.

## Thread

A thread is the unit of execution within a process. A process at least has one thread, its called as main thread.
Its not uncommon a processor has many threads. Thread has stack, registers, program counters. Its possible to 
communicate between threads with shared memory however one misbehaving thread could bring down the entire process.

Its faster context switching between threads than between processes.

<img width="1492" alt="Screenshot 2024-08-18 at 11 16 45" src="https://github.com/user-attachments/assets/43bc686d-f1b4-4100-906f-11be0e4dbb98">


https://www.youtube.com/watch?v=4rLW7zg21gI
