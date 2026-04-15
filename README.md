# Fail2Ban Defense Lab

## Objective
The Fail2Ban Defense Lab focused on implementing automated protection against SSH brute-force attacks by configuring Fail2Ban to monitor logs and block malicious IP addresses.

---

### Skills Learned
- Intrusion detection and prevention using Fail2Ban
- Log monitoring and alert-based response
- Understanding of automated defense mechanisms
- SSH security hardening techniques

---

### Tools Used
- Ubuntu Linux
- Fail2Ban
- SSH
- Linux Logs (`auth.log`)

---

## Steps

*Ref 1: Fail2Ban Installation*  
Installed and configured Fail2Ban on the Ubuntu server.

*Ref 2: Jail Configuration*  
Configured SSH jail rules to monitor failed login attempts.

*Ref 3: Attack Trigger*  
Simulated brute-force attack from Kali Linux.

*Ref 4: IP Banning*  
Verified that attacking IP was automatically banned.

*Ref 5: Status Verification*  
Used `fail2ban-client status sshd` to confirm active bans.
