# Bandit Level 18 → Level 19

## Objective

Learn how shell startup files affect user sessions and how commands can be executed when establishing an SSH connection.

## Concepts Learned

* Shell initialization
* Startup files
* Remote command execution
* Non-interactive SSH sessions

## Key Command

### `ssh`

SSH can execute a command on a remote system without starting an interactive shell. This is useful for automation, remote administration, and situations where the normal login environment is modified.

## Commands Introduced

| Command | Purpose                                                               |
| ------- | --------------------------------------------------------------------- |
| `ssh`   | Connects securely to a remote system and can execute remote commands. |
| `cat`   | Displays the contents of a text file.                                 |
| `ls`    | Lists files and directories.                                          |

## Key Takeaway

Understanding how shell startup files work is important when administering Linux systems. Executing commands through non-interactive SSH sessions is a practical technique for automation, scripting, and troubleshooting remote environments.

