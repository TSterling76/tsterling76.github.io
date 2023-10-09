# Cheatsheets and Notes

## Docker

## Splunk
[Fundamentals link](https://www.splunk.com/en_us/training/splunk-fundamentals.html)

## Kubernetes

**Node** = Server

1 **node** can contain multiple _Containers_

A **pod** houses a set of containers that are coupled

Get all installed/running pods : **kubctl get pods**

## Kali Linux

[percipio](https://lockheedmartin.percipio.com/search?q=pentest)
[test](index.html)

1. Phase 1: Passive reconnaissance:
	- Look at job posting
2.  Phase 2: SCANNING
	- What ports and service are available
3. Phase 3: GAINING ACCESS
	- PASSWORD ATTACKS, REMOTE CODE VULNS , INJECTION ATTACKS
4. Phase 4: MAINTAIN ACCESS
	- Install malware for C2 capabilities
	- Rootkits
	- Creating backdoors
	- Crack user passwords
	- System hardening so other attackers don’t gain access
5. Phase 5: COVERING YOUR TRACKS
    - Don’t identify yourself

## Nmap

- **Nmap *-sS*** : Perform  SYN Flag Scan  on host 

- **Nmap -sA**: Perform ACK Flag Scan  on host

- **nmap -sN**: Perform a NULL scan, avoid detecting non-stateful firewalls

- **Nmap -sF** : Perform  FIN Flag Scan

- **Nmap -sX**: Xmas scan, which sends the TCP segment with three flags raised. These flags are FIN, PSH, and URG

The -s means stealth scan

 - **Nmap -sV**: Scan for services/version info running

 - **Nmap -sT**: TCP Scan, Port scanning

 - **Nmap -sU**: UDP Scan, Port Scanning

 - **Nmap -T**:  the speed of your stealth scan. T0 is paranoid, T1 is sneaky, T2 Is polite, T3 Is normal, T4 is aggressive, and T5 is insane

 - **Nmap -v**: increases verbosity level, tells you more about the host

 - **Nmap -A**: Enable OS Detection AND version detection AND tracroute

 - **Nmap -sn**: PING Scan

 - **Nmap -PR**: Perform/Send ARP Request

 - **Nmap -sn -PS 80**:     send the SYN message to a specific port

-O: only enable OS Detection

  - **Nmap -F** : FAST Scan

  ## GENERAL Linux TIPS

    - loginctl
    - systemctl