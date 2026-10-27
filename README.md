```
$ whoami
Md Abu Bakar Siddique  (ruxchipher)

$ cat ./about
Final-year Bachelor of IT student at CQUniversity.
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
- Measuring the gaps rather than guessing at them. My own coverage map reads
  every rule and tool I have written and reports 22 ATT&CK techniques covered
  and 11 techniques on my target list that I still cannot detect. That gap list
  is what decides the next rule I write.

It is all in [purple-team-journey](https://github.com/Siddique-12300983/purple-team-journey).

### Skills I'm building

```
Linux         Fedora, Arch, systemd, permissions, shell
Windows / AD  Active Directory, Group Policy, Kerberos, event logs
Networking    TCP/IP, DNS, firewalls, nmap, Wireshark
Detection     Sysmon, Wazuh, Sigma, MITRE ATT&CK, ATT&CK Navigator
Scripting     Python, Bash
```

### Projects

**Security**

| Repo | What it is |
|---|---|
| [purple-team-journey](https://github.com/Siddique-12300983/purple-team-journey) | My AD lab, attack-and-detect write-ups and weekly notes |
| [attack-coverage-map](https://github.com/Siddique-12300983/attack-coverage-map) | Reads my rules and tools and reports what they cover, how deep, and where the gaps are. [Live heatmap](https://siddique-12300983.github.io/attack-coverage-map/) |
| [persistwatch](https://github.com/Siddique-12300983/persistwatch) | Hunts persistence in systemd units and timers, mapped to ATT&CK |
| [log-analyzer](https://github.com/Siddique-12300983/log-analyzer) | Flags brute-force and Kerberoasting in auth logs |
| [sigma-detection-rules](https://github.com/Siddique-12300983/sigma-detection-rules) | Sigma detection rules mapped to MITRE ATT&CK |
| [linux-hardening-script](https://github.com/Siddique-12300983/linux-hardening-script) | Idempotent Debian/Ubuntu hardening script |
| [ioc-extractor](https://github.com/Siddique-12300983/ioc-extractor) | Pulls IOCs from text, handles defanged input |
| [file-integrity-monitor](https://github.com/Siddique-12300983/file-integrity-monitor) | SHA-256 baseline and change detection for a directory |
| [phishing-email-analyzer](https://github.com/Siddique-12300983/phishing-email-analyzer) | Offline .eml triage: headers, auth, URLs, red flags |
| [password-breach-checker](https://github.com/Siddique-12300983/password-breach-checker) | Checks a password against HIBP using k-anonymity |

**For fun**

Small browser things, each a single page you can open and play with:

| Repo | Live | What it is |
|---|---|---|
| [password-strength-visualizer](https://github.com/Siddique-12300983/password-strength-visualizer) | [open](https://siddique-12300983.github.io/password-strength-visualizer/) | Live password meter, entropy and crack-time, all in the browser |
| [network-attack-map](https://github.com/Siddique-12300983/network-attack-map) | [open](https://siddique-12300983.github.io/network-attack-map/) | Animated map of simulated cyber attacks |
| [typing-speed-game](https://github.com/Siddique-12300983/typing-speed-game) | [open](https://siddique-12300983.github.io/typing-speed-game/) | A clean typing speed test with WPM and a best score |

### Links

- Portfolio: https://ruxchipher.com/
- LinkedIn: https://linkedin.com/in/siddiqueabu
- GitHub: https://github.com/Siddique-12300983
