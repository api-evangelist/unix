# UNIX System Call (unix)
Core UNIX/POSIX system calls providing low-level operating system interfaces for process management, file operations, interprocess communication, and system control.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/unix/refs/heads/main/apis.yml)

## Tags:

 - C-Api, Ieee-1003, Kernel, Open-Group, Operating-System, Posix, System-Calls, Unix

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### File System Operations API
System calls for file and directory manipulation, including open, read, write, and file descriptor management.

**Human URL:** [https://man7.org/linux/man-pages/dir_section_2.html](https://man7.org/linux/man-pages/dir_section_2.html)

#### Tags:

 - Directories, Files, Filesystem, Io

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/contents.html)
- [APIReference](https://man7.org/linux/man-pages/man2/)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9799919799/functions/open.html)

### Process Management API
System calls for process creation, execution, termination, and control.

**Human URL:** [https://man7.org/linux/man-pages/man2/fork.2.html](https://man7.org/linux/man-pages/man2/fork.2.html)

#### Tags:

 - Execution, Processes, Scheduling

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fork.html)
- [GettingStarted](https://sourceware.org/glibc/manual/)
- [APIReference](https://man7.org/linux/man-pages/man2/fork.2.html)

### Interprocess Communication API
System calls for communication between processes including pipes, signals, and shared memory.

**Human URL:** [https://man7.org/linux/man-pages/man7/pipe.7.html](https://man7.org/linux/man-pages/man7/pipe.7.html)

#### Tags:

 - Ipc, Pipes, Shared-Memory, Signals, Sockets

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/V2_chap02.html)
- [CodeExamples](https://beej.us/guide/bgipc/)
- [GettingStarted](https://beej.us/guide/bgnet/html/)
- [APIReference](https://man7.org/linux/man-pages/man7/pipe.7.html)

### Memory Management API
System calls for memory allocation, mapping, and protection.

**Human URL:** [https://man7.org/linux/man-pages/man2/mmap.2.html](https://man7.org/linux/man-pages/man2/mmap.2.html)

#### Tags:

 - Allocation, Memory, Mmap, Virtual-Memory

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/mmap.html)
- [APIReference](https://man7.org/linux/man-pages/man2/mmap.2.html)

### System Information API
System calls for retrieving system information and configuration.

**Human URL:** [https://man7.org/linux/man-pages/man2/uname.2.html](https://man7.org/linux/man-pages/man2/uname.2.html)

#### Tags:

 - Configuration, Groups, Information, System, Users

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/uname.html)
- [APIReference](https://man7.org/linux/man-pages/man2/uname.2.html)

### POSIX Threads API
POSIX threads (pthreads) interface for creating and managing threads, mutexes, condition variables, and thread-specific data.

**Human URL:** [https://man7.org/linux/man-pages/man7/pthreads.7.html](https://man7.org/linux/man-pages/man7/pthreads.7.html)

#### Tags:

 - Concurrency, Mutexes, Pthreads, Synchronization, Threads

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/pthread_create.html)
- [APIReference](https://man7.org/linux/man-pages/man7/pthreads.7.html)
- [APIReference](https://man7.org/linux/man-pages/man0/pthread.h.0p.html)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9799919799/functions/pthread_create.html)

### I/O Multiplexing API
System calls for monitoring multiple file descriptors for readiness, enabling event-driven and non-blocking I/O patterns.

**Human URL:** [https://man7.org/linux/man-pages/man2/select.2.html](https://man7.org/linux/man-pages/man2/select.2.html)

#### Tags:

 - Event-Driven, Io, Multiplexing, Non-Blocking, Poll, Select

#### Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/select.html)
- [APIReference](https://man7.org/linux/man-pages/man2/select.2.html)
- [Tutorials](https://man7.org/linux/man-pages/man2/select_tut.2.html)

### POSIX Semaphores API
POSIX named and unnamed semaphore interfaces for process and thread synchronization.

**Human URL:** [https://man7.org/linux/man-pages/man7/sem_overview.7.html](https://man7.org/linux/man-pages/man7/sem_overview.7.html)

#### Tags:

 - Concurrency, Ipc, Semaphores, Synchronization

#### Properties

- [Documentation](https://man7.org/linux/man-pages/man7/sem_overview.7.html)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_open.html)

### POSIX Message Queues API
POSIX message queue interfaces for exchanging messages between processes with priority support.

**Human URL:** [https://man7.org/linux/man-pages/man7/mq_overview.7.html](https://man7.org/linux/man-pages/man7/mq_overview.7.html)

#### Tags:

 - Asynchronous, Ipc, Message-Queues, Messaging

#### Properties

- [Documentation](https://man7.org/linux/man-pages/man7/mq_overview.7.html)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/mq_open.html)

### Terminal and Device I/O API
POSIX terminal interface (termios) and device control system calls for managing terminals, serial ports, and device parameters.

**Human URL:** [https://man7.org/linux/man-pages/man3/termios.3.html](https://man7.org/linux/man-pages/man3/termios.3.html)

#### Tags:

 - Device-Io, Serial, Terminal, Termios, Tty

#### Properties

- [Documentation](https://man7.org/linux/man-pages/man3/termios.3.html)
- [APIReference](https://man7.org/linux/man-pages/man0/termios.h.0p.html)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/termios.h.html)

### File Locking API
POSIX advisory file locking interfaces for coordinating file access between processes.

**Human URL:** [https://man7.org/linux/man-pages/man2/fcntl.2.html](https://man7.org/linux/man-pages/man2/fcntl.2.html)

#### Tags:

 - Advisory-Locking, Concurrency, Fcntl, File-Locking

#### Properties

- [Documentation](https://man7.org/linux/man-pages/man2/fcntl.2.html)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fcntl.html)

## Common Properties

- [Documentation](https://pubs.opengroup.org/onlinepubs/9799919799/)
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/)
- [Documentation](https://man7.org/linux/man-pages/dir_section_2.html)
- [GettingStarted](https://sourceware.org/glibc/manual/)
- [Resources](https://en.wikipedia.org/wiki/POSIX)
- [APIReference](https://unix.org/apis.html)
- [Documentation](https://standards.ieee.org/ieee/1003.1/7700/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
