# Bandit Level 15 → Level 16

## Objective

Learn how to establish a secure connection to a network service using SSL/TLS encryption.

## Concepts Learned

* SSL/TLS
* Encrypted communication
* Secure network services
* Certificates

## Key Command

### `openssl s_client`

Establishes an SSL/TLS connection to a remote service and displays details about the secure session, including certificates and encryption information. It is commonly used to test and troubleshoot secure network connections.

## Commands Introduced

| Command            | Purpose                                                  |
| ------------------ | -------------------------------------------------------- |
| `openssl s_client` | Connects to services using SSL/TLS.                      |
| `ssh`              | Establishes a secure remote connection.                  |
| `nc`               | Connects to TCP/UDP network services without encryption. |

## Key Takeaway

Not all network services use plain TCP connections. SSL/TLS adds encryption to protect data in transit, making it a fundamental technology for secure communication in modern networking and cybersecurity.

