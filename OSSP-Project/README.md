| Name | ID Number |
|------|-----------|
| Samanth Katuri | 2520080011 |
| P. Datta Sai Suraj | 2520090179 |
| V. Pavan Kumar | 252009079 |

# Linux IPC Using Pipes


## Supervisor

**Supervisor:** SUPERVISOR_NAME

## Abstract

This project demonstrates Inter-Process Communication (IPC) in Linux using pipes. Pipes provide a mechanism for communication and data transfer between processes. The project focuses on understanding process creation, communication between parent and child processes, reading and writing through pipes, and synchronization between processes.

The implementation demonstrates how Linux processes can exchange data using pipe-based communication and provides practical understanding of IPC concepts through C programs.

## Problem Statement

Processes in an operating system execute independently and often need to exchange information or coordinate their activities. This project addresses the problem of enabling communication between processes using Linux pipes and demonstrates how data can be transferred safely between related processes.

## Objectives

- To understand Inter-Process Communication in Linux.
- To understand the working of pipes.
- To implement communication between processes.
- To demonstrate reading and writing using pipes.
- To understand parent-child process communication.
- To study process synchronization using IPC mechanisms.

## Proposed Solution

The proposed system uses Linux pipes to establish a communication channel between processes. A parent process and child process are created using process-related system calls. The processes communicate by writing data to and reading data from the pipe.

The project includes practical C programs demonstrating different pipe-based IPC operations.

## Technologies Used

- C Programming
- Linux / Ubuntu
- GCC Compiler
- Linux System Calls
- Git and GitHub

## Project Structure

```text
KLH-AIDS-CSIT-2026-03-LINUX_IPC_USING_PIPES/
│
├── README.md
├── src/
│   └── Source code
│
├── docs/
│   └── Project documentation
│
├── data/
│   └── Data sources / related files
│
├── results/
│   └── Program outputs and results
│
└── reports/
    ├── review-1/
    ├── review-2/
    └── final/
