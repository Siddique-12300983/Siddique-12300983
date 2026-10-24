```
$ whoami
Md Abu Bakar Siddique  (ruxcipher)

$ cat ./about
Second-year Bachelor of IT student at CQUniversity.
Cyber Security major, Application Development minor. Based in Sydney.
Learning both sides of security and building toward a purple team internship.
```

I spend most of my time in a home lab, running attacks and then trying to catch
them in my own logs. I like the point where the red and blue sides meet: an
attack is only interesting to me once I can see what it left behind.

### Currently working on

- An Active Directory home lab on Arch Linux with KVM: a Windows Server 2025
  domain controller, a Windows 11 client and Kali on an isolated network, run as
  a fake company called Harbourline Freight.
- Detection on that lab: audit policy, Sysmon, and next a Wazuh SIEM collecting
  the logs, with Sigma rules on top.
- The first full attack-and-detect write-up: Kerberoasting, and why a modern
  AES-only domain breaks the classic RC4 detection.

It is all in [purple-team-journey](https://github.com/Siddique-12300983/purple-team-journey).

### Skills I'm building

```
Linux         Fedora, Arch, systemd, permissions, shell
Windows / AD  Active Directory, Group Policy, Kerberos, event logs
Networking    TCP/IP, DNS, firewalls, nmap, Wireshark
Detection     Sysmon, Wazuh, Sigma, MITRE ATT&CK
Scripting     Python, Bash
```

### Projects

| Repo | What it is |
|---|---|
| [purple-team-journey](https://github.com/Siddique-12300983/purple-team-journey) | My AD lab, attack-and-detect write-ups and weekly notes |
| [log-analyzer](https://github.com/Siddique-12300983/log-analyzer) | Python tool that flags brute-force and Kerberoasting in auth logs |
| [sigma-detection-rules](https://github.com/Siddique-12300983/sigma-detection-rules) | Sigma rules mapped to MITRE ATT&CK |
| [linux-hardening-script](https://github.com/Siddique-12300983/linux-hardening-script) | Idempotent Debian/Ubuntu hardening script |

### Links

- Portfolio: https://siddique-12300983.github.io/ruxchipher-portfolio/
- LinkedIn: https://linkedin.com/in/siddiqueabu
- GitHub: https://github.com/Siddique-12300983
