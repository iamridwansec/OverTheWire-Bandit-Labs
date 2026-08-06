# Bandit Level 19 → Level 20

## Objective

Learn how SetUID (SUID) programs work and how they allow controlled privilege escalation in Linux.

## Concepts Learned

* SetUID (SUID)
* File permissions
* Privilege escalation
* Executable binaries

## Key Command

### `ls -l`

Displays detailed information about files, including permissions, ownership, and special permission bits such as SetUID. It is one of the primary commands for inspecting file permissions in Linux.

## Commands Introduced

| Command      | Purpose                                           |
| ------------ | ------------------------------------------------- |
| `ls -l`      | Displays detailed file permissions and ownership. |
| `file`       | Identifies the type of a file.                    |
| `./<binary>` | Executes a program in the current directory.      |

## Key Takeaway

The SetUID permission allows an executable to run with the privileges of its owner rather than the user executing it. Understanding SUID is essential for Linux administration, privilege management, and cybersecurity, as misconfigured SUID binaries can introduce security risks.

