# Wazuh SIEM SOC Lab

## Objective
Deploy a SIEM environment and simulate real-world attacks to analyze logs and generate security alerts.

## Architecture
- Ubuntu Server (Wazuh Manager)
- Kali Linux (Attacker)
- SSH Service Enabled

## Attacks Performed
- Nmap reconnaissance scan
- SSH brute-force attempt

## Logs Generated
- Authentication failures
- SSH login attempts
- File integrity alerts

## Mitigation Steps
- Firewall configuration (UFW)
- SSH hardening
- Password policy enforcement
