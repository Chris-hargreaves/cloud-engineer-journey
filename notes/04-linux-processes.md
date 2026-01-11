Linux Processes - Day 4

A program is something that can run.
A process is a program that is currently running.

Linux manages many processes at all times, even when no user is logged in.

Key ideas:
- Every running process has a PID (process ID)
- PID 1 is the first and most important system process
- If PID 1 stops, the system stops
- Most processes are started by the system, not the user

Commands used:
- ps        : shows processes started by the current user
- ps aux    : shows all running processes on the system

Processes can:
- Start
- Run
- Stop

Servers rely on background processes to function without user interaction.
