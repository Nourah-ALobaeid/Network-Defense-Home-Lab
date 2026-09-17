# Network Defense Home Lab

## Project Overview

This repository documents a series of hands-on labs focused on network defense fundamentals. Each lab explores a different layer of protection: intrusion detection, host-based firewalling, network firewalling, and secure site-to-site communication.

The goal is to demonstrate practical understanding of how modern networks are monitored, filtered, and secured.

---

## Labs Index

| # | Lab | Focus Area | Tools |
|---|-----|------------|-------|
| 01 | [Intrusion Detection with Snort](snort/snort-IDS.md) | IDS / Signature-based detection | Snort |
| 02 | [Windows Defender Firewall](WFirewall/windows-firewall.md) | Host-based firewall rules | Windows Defender Firewall |
| 03 | [pfSense Firewall Rules](PFirewall/pfsense-firewall.md) | Network firewall & rule ordering | pfSense, GNS3 |
| 04 | [IPsec Site-to-Site VPN](vpn/ipsec-vpn.md) | Encrypted tunnel & traffic analysis | IPsec, GNS3, Wireshark |

---

## Skills Demonstrated

- Intrusion Detection System (IDS) configuration
- Custom Snort rule creation
- Windows Defender Firewall inbound rule design
- pfSense firewall rule ordering and ICMP filtering
- IPsec VPN tunnel configuration (IKE, ESP, ACL, Crypto Map)
- Traffic analysis with Wireshark (before/after encryption)
- Network simulation with GNS3

---

## Tools Used

- Snort
- Windows Defender Firewall
- pfSense
- GNS3
- Wireshark
- Kali Linux
- Ubuntu

---

## Ethical Disclaimer

This repository documents my personal learning journey using standard, publicly available cybersecurity tools. All analysis, configuration steps, and observations are my own work, performed in isolated lab environments.
