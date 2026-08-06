# Bandit Level 0

## Objective

Establish a secure remote connection to the Bandit server using SSH.

## Level Goal

Connect to the Bandit game server using the provided SSH credentials and access the remote Linux environment.

## Concepts Learned

* SSH (Secure Shell)
* Remote login
* Hostname
* Port number

## Command Used

```bash
ssh -p 2220 bandit0@bandit.labs.overthewire.org
```

**Explanation:**

* `ssh` – Starts a secure remote connection.
* `-p 2220` – Specifies the custom SSH port.
* `bandit0` – Remote username.
* `bandit.labs.overthewire.org` – Remote server hostname.

## Outcome

Successfully connected to the Bandit server and accessed the Linux shell, preparing the environment for the next challenge.

## Key Takeaway

SSH is the standard method for securely accessing remote Linux systems. Understanding how to connect to a server is a fundamental skill in Linux administration and cybersecurity.

