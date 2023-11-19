# Simple Multi-Threaded Server

This is a simple multi-threaded server written in C using pthreads. The server listens on a specified port and handles incoming connections concurrently by creating threads for each client.

## Compilation

To compile the program, use the following commands in your terminal:

```bash
gcc -c server.c -o server.o
gcc -c handler.c -o handler.o
gcc server.o handler.o -o myserver -pthread
```

After compilation, you can run the server:

```bash
./myserver
```
