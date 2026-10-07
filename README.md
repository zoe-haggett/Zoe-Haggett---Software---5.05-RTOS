# Zoe-Haggett---Software---5.05-RTOS
RTOS Project for PAST Software Onboarding

This project is to be completed in 8 weeks, due on the 18th of October 2026.
All coding and programs will be done in C using STM32CubeIDE software and Microsoft Visual Studio.


## RTOS Project Deliverables
- Explain what a queue, mutex and semaphore are in the context of an operating system.
    - Describe a suitable use case for each.
- Re-create the LED blink program from 5.3 but use two separate tasks to switch the LED on and off at different rates.
- Create a program that can safely transfer data between two tasks.
    - Some examples of data that could be transferred: Current iteration number, the number of blinks to do, the speed of blinks.
- Provide an Inter-Process Communication (IPC) Diagram or Task Synchronization Flowchart. 
    - This should outline how the processes interact, share resources, and avoid race conditions.


## Extra Project Deliverables
- Research how an RTOS could be used in a Flight Computer.
    - Which tasks the system would be responsible for, e.g. polling subsystems, creating packets, sending packets, responding to commands.
    - Which tasks require the highest priority.
    - How the system would handle task failures.
 


## Directions of Use

Research Phase (Word Document)
- Explains the purpose of a real-time operating system and the importance of one.
- Includes what a mutex, semaphore, and queue is in the context of a RTOS.

Understanding STM32CubeIDE Functions (Word Document)
- Defines components called upon in the main file and key functions used on this application, as well as an explanation of where the names of these functions come from.

PAST Logbook (Word Document)
- A week-by-week log of what has been completed/added/changed in the project, a timeline for this, proof of work, as well as a reflection of what has gone wrong and how it has been fixed.

L432KC Blink Program - Two Tasks (File - Language: C)
- The completed first deliverable for the project.
- To view the main.c file which includes the created tasks, go to Core --> Src --> main.c
    - *This is the same directory for two files that cover the second deliverable*.
