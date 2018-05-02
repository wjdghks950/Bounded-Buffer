# Program
    This program uses POSIX mutex and semaphore functions to solve the classic Bounded-buffer problem in shared memory.
    The Encryptor receives a message, encrypts it (by adding 3 to each character) and puts it within the shared buffer.
    The Decryptor does the opposite; it retrieves an encrypted message from the shared buffer and decrypts it (by subtracting 3 from each character).

# Build
    $ gcc -o exec bounded_buffer.c -pthread

# Prerequisites
    gcc and some knowledge about POSIX.
    Read the documentation before using the POSIX mutex and semaphore functions.
