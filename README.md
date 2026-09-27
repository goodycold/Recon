# Recon

A Bash reconnaissance automation tool.

## Features

- WHOIS lookup
- DNS enumeration
- Passive subdomain discovery (Amass)
- DNS brute force (Gobuster)
- TLS analysis (testssl.sh)

## Requirements

- `whois`, `nslookup`, `amass`, `gobuster`
- `testssl.sh`
- A wordlist for Gobuster (e.g. [SecLists](https://github.com/danielmiessler/SecLists))

## Usage

Default target:

```bash
./recon.sh
```

Custom target:

```bash
./recon.sh example.com
```
