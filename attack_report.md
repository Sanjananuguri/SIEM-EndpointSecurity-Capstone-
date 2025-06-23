# SIEM & Endpoint Security Capstone Report

## Attack Simulations
- Simulated brute-force SSH login attempts from Kali to Ubuntu.
- Enabled OpenSSH server on Ubuntu and attempted logins using incorrect usernames and passwords.

## Observations
- Events captured in /var/log/auth.log on Ubuntu.
- Splunk successfully ingested logs and indexed failed login attempts.
- Queries confirmed visibility into brute-force activity and user enumeration.

## Tools Used
- Kali Linux (Nmap, Metasploit, SSH)
- Ubuntu Server (target machine)
- Splunk Enterprise
