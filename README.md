# Task 1 - Local Network Port Scanning

## Objective

To discover devices and open ports on my local network
using Nmap and understand basic network exposure.

## Tools Used

- Fedora Linux
- Nmap
- Wireshark (optional)

## Network

Local network: 192.168.1.0/24

## Commands Used

### Host Discovery

nmap -sn 192.168.1.0/24

### TCP SYN Scan

sudo nmap -sS 192.168.1.0/24

### Service Detection

sudo nmap -sV 192.168.1.0/24

## Findings

Document the devices and open ports discovered during
the authorized local-network scan.

| IP Address | Port | Protocol | Service |
|------------|------|----------|---------|
| x.x.x.x | xx | TCP | service |

## Security Observations

Open ports indicate services that are reachable over the
network. The security impact depends on the service,
configuration, authentication, software version, and
whether the service needs to be exposed.

## What I Learned

- IP addresses and subnet ranges
- TCP ports
- Open, closed and filtered ports
- TCP SYN scanning
- Basic network reconnaissance
- Service identification
- Network exposure

## Ethical Scope

The scan was performed only against my own/local network
with authorization.
