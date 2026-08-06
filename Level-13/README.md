# Bandit Level 12 → Level 13

## Objective

Learn how to reconstruct, inspect, and extract data from files that have undergone multiple encoding and compression stages.

## Concepts Learned

* Hexdump
* File compression
* Temporary directories
* File conversion
* File extraction

## Key Commands

### `xxd`

Creates or reverses a hexadecimal dump of a file, making it useful for converting between binary and hexadecimal representations.

### `mktemp`

Creates a unique temporary file or directory safely, reducing the risk of naming conflicts.

## Commands Introduced

| Command                | Purpose                                               |
| ---------------------- | ----------------------------------------------------- |
| `xxd`                  | Creates or reverses hexadecimal dumps.                |
| `mktemp`               | Creates a secure temporary file or directory.         |
| `cp`                   | Copies files or directories.                          |
| `mv`                   | Renames or moves files and directories.               |
| `file`                 | Identifies the type of a file.                        |
| `gzip`, `bzip2`, `tar` | Compresses, decompresses, and extracts archive files. |
| `mkdir`                | Creates directories.                                  |

## Key Takeaway

When analyzing unknown files, it's important to identify their format before processing them. Linux provides a rich set of utilities for converting, extracting, and inspecting files, making systematic file analysis an essential cybersecurity skill.

