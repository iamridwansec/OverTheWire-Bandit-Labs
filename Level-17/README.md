# Bandit Level 16 → Level 17

## Objective

Learn how to discover network services by scanning ports and identify those that use SSL/TLS encryption.

## Concepts Learned

* Port scanning
* Open ports
* Network service enumeration
* SSL/TLS detection
* Service verification

## Key Command

### `nmap`

Scans hosts to discover open ports, running services, and other network information. It is one of the most widely used tools for network discovery and security auditing.

## Commands Introduced

| Command            | Purpose                                               |
| ------------------ | ----------------------------------------------------- |
| `nmap`             | Discovers open ports and identifies running services. |
| `openssl s_client` | Connects to services using SSL/TLS.                   |
| `nc`               | Connects to TCP/UDP network services.                 |

## Key Takeaway

Before interacting with a network service, it is important to identify which ports are open and determine the protocols they support. Network enumeration is a fundamental phase of cybersecurity assessments, penetration testing, and troubleshooting.

