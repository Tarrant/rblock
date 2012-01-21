`rblock` is a simple command to allow you wrap other commands in a lock.

This provides a simple interface for locking with built-in protection against
events like `kill -9` or early exit due to error.

Simply call `rblock /path/to/lockfile command to execute`.
