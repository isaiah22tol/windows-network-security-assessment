# Windows Network Security Assessment



## Project Overview

This beginner cybersecurity project documents a basic network security review performed on my personal Windows computer.



## Objectives

- Review Windows network configuration.

- Identify local TCP listening ports and associated processes.

- Check Windows Defender Firewall status.

- Test outbound HTTPS connectivity.

- Document observations and security recommendations.



## Tools Used

- Windows PowerShell

- Windows networking commands

- Windows Defender Firewall

- Windows Update



## Assessment Results

- **Network configuration:** Retrieved successfully.

- **Listening ports:** TCP listening ports and associated process names were identified.

- **Firewall:** Domain, Private, and Public profiles were enabled during the checks.

- **Connectivity:** A TCP connection test to Google on port 443 succeeded.

- **Updates:** Windows requested a restart to complete updates.



## Security Recommendations

- Keep Windows and applications updated.

- Keep the appropriate Windows Firewall profiles enabled.

- Investigate unfamiliar listening services before taking action.

- Avoid exposing unnecessary network services.

- Repeat these checks periodically.

## Security Findings Summary
-Firewall status: Domain, Private, and Public profiles were enabled during the check.

-Listening ports: Multiple Windows and application listeners were present.

-Process identification: You matched listening ports to running processes.

-Limitations: You have not yet verified every listener’s purpose, firewall-rule exposure, or security risk.


## Scope and Limitations

This assessment was limited to my own Windows computer. No unauthorized systems were scanned or accessed. This was a basic configuration review, not a full penetration test or vulnerability assessment.



## Skills Practiced

- Windows PowerShell

- Basic networking

- TCP ports and connections

- Firewall verification

- Security documentation

- Basic troubleshooting



## What I Learned

I practiced reviewing network configuration, identifying listening ports and processes, checking firewall profiles, and recording security findings. I also learned that individual successful checks do not guarantee that an entire computer or network is secure.


## Evidence and Screenshots

### Windows Firewall
- [View Firewall Status Screenshot](evidence/firewall-status.png)
- [View Firewall Status Results](evidence/firewall-status.txt)

### Listening TCP Ports
- [View Listening Ports Screenshot](evidence/listening-ports.png)
- [View Listening Ports Results](evidence/listening-ports.txt)

### Network Configuration
- [View Sanitized Network Configuration](evidence/network-config.txt)

### Process Mapping
- [View Port-to-Process Mapping](evidence/port-process-mapping.txt)
