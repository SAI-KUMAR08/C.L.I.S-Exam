# Question 3 Explanation

- The original file, hard link, and symbolic link were created to compare how Linux tracks file references. The hard link shared the same inode, while the symbolic link did not.
- The inode and metadata output showed that hard links are aliases of the same file, while symbolic links are separate files pointing to a path.
- Deleting the original file left the hard link intact because it still referenced the same inode. The symbolic link failed because its target path no longer existed.
- This experiment demonstrates the difference between hard links and symbolic links in Linux file systems.
