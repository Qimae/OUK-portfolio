# Day 2 – Nmap Scanning Basics

**Date:** 2025-01-17

Ran Nmap scans on the lab network to identify open ports and services.

## Commands
- `nmap -sS -sV -O 192.168.56.0/24`
- `nmap -A -p- 192.168.56.101`

## Findings
Found SSH and several HTTP services. Next: enumerate web apps with Nikto and Burp Suite.
