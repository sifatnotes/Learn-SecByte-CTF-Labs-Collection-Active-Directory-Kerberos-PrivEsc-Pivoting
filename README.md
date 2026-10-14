# Learn-SecByte-CTF-Labs-Collection-Active-Directory-Kerberos-PrivEsc-Pivoting
A curated collection of hands-on penetration testing CTF labs covering Active Directory Enumeration &amp; Exploitation, Kerberos Delegation Attacks, Windows/Linux Privilege Escalation, Pivoting &amp; Tunneling, Modern Auth (OAuth/JWT/SAML), and Wireless Security from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on Active Directory exploitation, Kerberos abuse, Windows and Linux privilege escalation, post-exploitation persistence, network pivoting, modern authentication security, and wireless network penetration testing labs designed for cybersecurity students, CTF players, penetration testers, red team operators, and network security engineers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Navigating modern corporate networks requires deep technical proficiency across enterprise domain structures, identity protocols, privilege boundaries, and lateral movement vectors. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs provides comprehensive hands-on training across full-chain network penetration testing.

From discovering enterprise Active Directory topologies and abusing Kerberos delegation primitives, to escalating privileges on Windows/Linux endpoints, pivoting through dual-homed networks, bypassing identity provider security (OAuth, JWT, SAML), auditing legacy network services, and cracking wireless security protocols, these exercises build real-world offensive security capabilities.

---

## Lab Collection & Index

Below is the complete, searchable index of all Active Directory, privilege escalation, network pivoting, identity security, and wireless pentesting challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Wireless Network Penetration Testing: WiFi Security & Beacon Analysis** | Wireless & Service Exploitation | WPA2/WPA3 handshake capture, beacon frame auditing, rogue AP detection, enterprise WiFi security | [Access Lab](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-wifi-security-beacon-ri) |
| 2 | **Persistence & Defense Evasion: Post-Exploitation Techniques** | Network Pivoting & Persistence | Windows registry Run keys, scheduled tasks, Linux cron jobs, DLL side-loading, covert persistence | [Access Lab](https://learn.secbyte.org/ctf/persistence-defense-evasion-post-exploitation-techniques) |
| 3 | **Pivoting & Tunneling: Internal Network Compromise** | Network Pivoting & Persistence | SSH dynamic port forwarding, Chisel, Ligolo-ng, SOCKS proxies, routing across segmented subnets | [Access Lab](https://learn.secbyte.org/ctf/pivoting-tunneling-internal-network-compromise) |
| 4 | **Windows Privilege Escalation: Services, Tokens & UAC Bypass** | Privilege Escalation | Unquoted service paths, token impersonation (`SeImpersonatePrivilege`), UAC bypass mechanisms, DLL hijacking | [Access Lab](https://learn.secbyte.org/ctf/windows-privilege-escalation-services-tokens-uac-bypass) |
| 5 | **Linux Privilege Escalation: Misconfigurations, Capabilities & Kernel** | Privilege Escalation | SUID/SGID binaries, Linux capabilities (`cap_setuid`), sudo misconfigurations, vulnerable kernel exploits | [Access Lab](https://learn.secbyte.org/ctf/linux-privilege-escalation-misconfigurations-capabilities-ke) |
| 6 | **Kerberos Attacks: Delegation Abuse & Credential Theft** | Active Directory & Kerberos | Kerberoasting, AS-REP roasting, Unconstrained/Constrained delegation abuse, Golden/Silver Ticket forging | [Access Lab](https://learn.secbyte.org/ctf/kerberos-attacks-delegation-abuse-credential-theft) |
| 7 | **Active Directory Exploitation: Domain Privilege Escalation** | Active Directory & Kerberos | ACL/ACE abuse, DCSync, Domain Admin escalation paths, AD CS (Certificate Services) misconfigurations | [Access Lab](https://learn.secbyte.org/ctf/active-directory-exploitation-domain-privilege-escalation) |
| 8 | **Active Directory Enumeration: Enterprise Domain Discovery** | Active Directory & Kerberos | BloodHound graph analysis, PowerView, LDAP queries, SPN scanning, trust relationship mapping | [Access Lab](https://learn.secbyte.org/ctf/active-directory-enumeration-enterprise-domain-discovery) |
| 9 | **Password Harvesting to Crack the Vault** | Identity & Credential Security | SAM/SYSTEM hive extraction, LSASS memory dumping, hash cracking (Hashcat/John the Ripper), rule-based attacks | [Access Lab](https://learn.secbyte.org/ctf/password-harvesting-to-crack-the-vault) |
| 10 | **SMB, FTP, SSH & RPC Common Service Exploitation** | Wireless & Service Exploitation | Null session enumeration, SMB Relay attacks, SSH key theft, RPC interface abuse, anonymous access | [Access Lab](https://learn.secbyte.org/ctf/smb-ftp-ssh-rpc-common-service-exploitation) |
| 11 | **Network Service Enumeration & Exploitation Bootcamp** | Wireless & Service Exploitation | Nmap service profiling, banner grabbing, vulnerability scanning, service misconfiguration exploitation | [Access Lab](https://learn.secbyte.org/ctf/network-service-enumeration-exploitation-bootcamp) |
| 12 | **OAuth, JWT & SAML: Modern Authentication Security** | Identity & Credential Security | JWT signature bypass (`none` algorithm), OAuth redirect URI hijacking, SAML response spoofing / XML signature wrapping | [Access Lab](https://learn.secbyte.org/ctf/oauth-jwt-saml-modern-authentication-security) |

---

## Categories

### 1. Active Directory, Kerberos & Domain Exploitation
Audit enterprise Active Directory environments, map trust relationships with BloodHound, execute Kerberos roasting attacks, and abuse domain ACLs/delegation.
- [Active Directory Enumeration: Enterprise Domain Discovery](https://learn.secbyte.org/ctf/active-directory-enumeration-enterprise-domain-discovery)
- [Kerberos Attacks: Delegation Abuse & Credential Theft](https://learn.secbyte.org/ctf/kerberos-attacks-delegation-abuse-credential-theft)
- [Active Directory Exploitation: Domain Privilege Escalation](https://learn.secbyte.org/ctf/active-directory-exploitation-domain-privilege-escalation)

### 2. Windows & Linux Local Privilege Escalation
Identify privilege boundary weaknesses on individual host OS targets, including service misconfigurations, token privileges, capabilities, and kernel vectors.
- [Windows Privilege Escalation: Services, Tokens & UAC Bypass](https://learn.secbyte.org/ctf/windows-privilege-escalation-services-tokens-uac-bypass)
- [Linux Privilege Escalation: Misconfigurations, Capabilities & Kernel](https://learn.secbyte.org/ctf/linux-privilege-escalation-misconfigurations-capabilities-ke)

### 3. Network Pivoting, Tunneling & Post-Exploitation
Tunnel traffic through compromised hosts to reach internal subnets, establish covert proxy chains, and maintain persistent access.
- [Pivoting & Tunneling: Internal Network Compromise](https://learn.secbyte.org/ctf/pivoting-tunneling-internal-network-compromise)
- [Persistence & Defense Evasion: Post-Exploitation Techniques](https://learn.secbyte.org/ctf/persistence-defense-evasion-post-exploitation-techniques)

### 4. Identity, Credential Harvesting & Wireless/Service Security
Harvest domain credentials, bypass modern authentication standards (JWT, OAuth, SAML), exploit network protocols, and audit wireless networks.
- [Password Harvesting to Crack the Vault](https://learn.secbyte.org/ctf/password-harvesting-to-crack-the-vault)
- [OAuth, JWT & SAML: Modern Authentication Security](https://learn.secbyte.org/ctf/oauth-jwt-saml-modern-authentication-security)
- [Network Service Enumeration & Exploitation Bootcamp](https://learn.secbyte.org/ctf/network-service-enumeration-exploitation-bootcamp)
- [SMB, FTP, SSH & RPC Common Service Exploitation](https://learn.secbyte.org/ctf/smb-ftp-ssh-rpc-common-service-exploitation)
- [Wireless Network Penetration Testing: WiFi Security & Beacon Analysis](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-wifi-security-beacon-ri)

---

## Learning Path

Follow this structured progression path to master modern network penetration testing and Active Directory exploitation:

1. **Phase 1: Service Enumeration, Exploitation & Credentials** — Enumerate network services, audit wireless security, and harvest local credentials:
   - [Network Service Enumeration & Exploitation Bootcamp](https://learn.secbyte.org/ctf/network-service-enumeration-exploitation-bootcamp)
   - [SMB, FTP, SSH & RPC Common Service Exploitation](https://learn.secbyte.org/ctf/smb-ftp-ssh-rpc-common-service-exploitation)
   - [Wireless Network Penetration Testing: WiFi Security & Beacon Analysis](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-wifi-security-beacon-ri)
   - [Password Harvesting to Crack the Vault](https://learn.secbyte.org/ctf/password-harvesting-to-crack-the-vault)

2. **Phase 2: Host Privilege Escalation & Auth Security** — Gain root/SYSTEM privileges on endpoints and bypass identity frameworks:
   - [Linux Privilege Escalation: Misconfigurations, Capabilities & Kernel](https://learn.secbyte.org/ctf/linux-privilege-escalation-misconfigurations-capabilities-ke)
   - [Windows Privilege Escalation: Services, Tokens & UAC Bypass](https://learn.secbyte.org/ctf/windows-privilege-escalation-services-tokens-uac-bypass)
   - [OAuth, JWT & SAML: Modern Authentication Security](https://learn.secbyte.org/ctf/oauth-jwt-saml-modern-authentication-security)

3. **Phase 3: Network Pivoting & Persistence** — Establish SOCKS tunnels across subnets and deploy post-exploitation persistence:
   - [Pivoting & Tunneling: Internal Network Compromise](https://learn.secbyte.org/ctf/pivoting-tunneling-internal-network-compromise)
   - [Persistence & Defense Evasion: Post-Exploitation Techniques](https://learn.secbyte.org/ctf/persistence-defense-evasion-post-exploitation-techniques)

4. **Phase 4: Active Directory & Enterprise Domain Takeover** — Enumerate AD graph paths, abuse Kerberos delegation, and conquer domain controllers:
   - [Active Directory Enumeration: Enterprise Domain Discovery](https://learn.secbyte.org/ctf/active-directory-enumeration-enterprise-domain-discovery)
   - [Kerberos Attacks: Delegation Abuse & Credential Theft](https://learn.secbyte.org/ctf/kerberos-attacks-delegation-abuse-credential-theft)
   - [Active Directory Exploitation: Domain Privilege Escalation](https://learn.secbyte.org/ctf/active-directory-exploitation-domain-privilege-escalation)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario requirements and target domain directives on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy penetration testing platforms (Kali Linux, BloodHound, Impacket, Mimikatz, Chisel, Hashcat, Burp Suite) inside an isolated laboratory environment.
4. Enumerate domain objects, crack credential hashes, escalate local and domain privileges, pivot through internal proxies, and capture target flags.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, threat research, and authorized technical training purposes. Never test, deploy, or execute penetration testing tools, credential harvesting utilities, or network pivoting scripts against unauthorized networks or production infrastructure.
