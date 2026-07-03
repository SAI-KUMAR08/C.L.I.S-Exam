# Question 4 Explanation

- The shell was tested for open-file behavior by opening a sample log file on an extra descriptor. This demonstrated how Linux tracks file access through file descriptors.
- Standard output and standard error were redirected into separate files and then combined. This showed how shell redirection works in practice for logging and debugging.
- The `ulimit` output revealed the resource limits for the shell process. These limits affect the number of open files and the size of memory-related resources.
- Closing descriptor 3 confirmed that the extra handle was no longer active. This highlights how Linux manages file I/O at the process level.
