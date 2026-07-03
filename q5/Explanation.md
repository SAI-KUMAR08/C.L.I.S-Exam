# Question 5 Explanation

- `lsblk` provided the disk and partition layout available in the environment. This helped identify the storage devices connected to the system.
- `mount` and `df -h` showed which filesystems were mounted and how much disk space was free. The results show that the main filesystem is healthy but some partitions are more heavily used.
- `df -i` confirmed that inode usage was still low, so the system did not appear to be near inode exhaustion.
- The storage assessment suggests monitoring the busiest filesystems and cleaning unnecessary files to keep the environment efficient.
