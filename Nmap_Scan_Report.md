# Nmap Scan Report

**Scan Date:** 2025-05-26  
**Scan Type:** TCP Connect Scan (`-sT`)  
**Target IP:** 192.168.29.29  
**Nmap Version:** 7.97  
**Scan Duration:** 0.89 seconds  
**Host Status:** Up (Latency: 0.00028s)

## Open Ports and Services

| Port | Protocol | State | Service       |
|------|----------|-------|----------------|
| 135  | TCP      | Open  | msrpc          |
| 139  | TCP      | Open  | netbios-ssn    |
| 445  | TCP      | Open  | microsoft-ds   |

## Summary

- A total of **3 TCP ports** are open on the host.
- The scanned host is responsive with very low latency.
- Common Windows networking services (RPC, NetBIOS, SMB) are exposed, indicating the system may be running a Windows OS.
- **Security Implication:** These services are often targets for exploitation in unpatched or misconfigured systems. Proper firewall rules and patch management should be ensured.
