# FIFO Page Replacement Algorithm – Print Spooler Queue Management

## Aim
To implement the FIFO (First-In, First-Out) algorithm to manage a print spooler queue by removing the oldest job when the queue reaches its maximum capacity.

## Description
FIFO is a page replacement algorithm that replaces the oldest item first. In this program, a print spooler queue has a capacity of three jobs. When a new job arrives and the queue is full, the oldest job is evicted to make room for the new one.

## Real-World Application
This algorithm can be used in print spooler systems to manage print jobs in the order they arrive.

## Files
- `FIFO.c` – C program implementing the FIFO algorithm.
- `fifo_output.txt` – Program output.

## Requirements
- GCC compiler
- Linux terminal or Ubuntu environment

## Compilation and Execution

Compile the program:

```bash
gcc FIFO.c -o FIFO
```

Run the program:

```bash
./FIFO
```

## Expected Output

```text
Queued Job 101
Queued Job 102
Queued Job 103
Evict job 101 (oldest)
Queued Job 104
Evict job 102 (oldest)
Queued Job 105
```

## Conclusion
The FIFO algorithm was implemented successfully. The program demonstrates how the oldest print job is removed when the queue reaches its capacity, allowing new jobs to be added in sequence.
