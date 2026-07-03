# Question 2 Explanation

- The workspace was created with separate directories for documentation, source code, and logs. This made the project layout easier to manage and secure.
- The initial permissions were broad, so they were tightened to prevent unauthorized access. The owner retained control while group and other users were restricted.
- The `umask` value of `0022` influenced the default permissions when the files were created. It removed write access for group and others unless explicitly changed.
- The final permissions protect the project data by allowing the owner to read and write while limiting access for others. This is a common and safe practice for shared systems.
