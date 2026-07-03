# Question 1 Explanation

- `whoami` confirmed the active user account. The output showed that the shell was running as `codespace`.
- `id` displayed the UID, GID, and group memberships. This verified the account’s effective permissions and groups.
- `echo "$SHELL"` showed that the current shell was `/bin/bash`. This confirms the shell environment being used for the session.
- `pwd` reported the current working directory as `/`. This verified the starting location of the shell.
- `ls -ls` listed the top-level filesystem layout. The output helped confirm the visible directories and their permissions.
- The network test using `curl` succeeded and printed a reachability message. This demonstrated that the environment had internet access.
