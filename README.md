# DDoS Incident Response Analysis Using NIST CSF

**Cybersecurity Portfolio Project | Incident Response | Network Security**

## 1. Project Overview

This project analyzes a simulated Distributed Denial-of-Service (DDoS) incident involving Internet Control Message Protocol (ICMP) flooding.

The case study is based on an activity from the Google Cybersecurity Professional Certificate.

I applied the five NIST Cybersecurity Framework (CSF) functions taught in the course to analyze the incident, document security controls, and recommend improvements.

## 2. Incident Summary

The company experienced a DDoS attack that caused its network services to stop responding.

The cybersecurity team identified a flood of incoming ICMP packets that disrupted network availability.

The team blocked attack traffic and temporarily stopped non-critical network services to prioritize restoring critical operations.

**Attack Type:** DDoS — ICMP Flooding

**Affected Systems:** Internal network and network services

**Primary Security Impact:** Availability

**Attack Duration:** Not specified in the provided scenario

## 3. NIST Cybersecurity Framework Analysis

### Identify
Identify the affected network resources and understand the risks associated with the ICMP flooding attack.

### Protect
Use firewall rate limiting and IDS/IPS filtering to reduce the impact of malicious ICMP traffic.

### Detect
Monitor abnormal traffic patterns and use source IP verification to help identify suspicious network activity.

### Respond
Follow incident response procedures, investigate network logs, contain disruptions, and communicate findings to management.

### Recover
Prioritize restoring critical network services, verify stability, and then restore non-critical operations.

## 4. Security Improvement Recommendations

1. Review and improve firewall filtering and ICMP rate limiting.
2. Maintain IDS/IPS monitoring and prevention capabilities.
3. Configure alerts for abnormal network traffic.
4. Develop and test a DDoS incident response playbook.
5. Prioritize recovery of critical network services.
6. Consider upstream DDoS mitigation for attacks that overwhelm internet connectivity.

## 5. Skills Demonstrated

- NIST Cybersecurity Framework application
- Security incident analysis
- DDoS and ICMP flooding fundamentals
- Network security concepts
- Incident response and recovery planning
- Security recommendations
- Technical report writing

## 6. Project Documents

- [Incident Response Report](01-Incident-Report/NIST-CSF-DDoS-Incident-Report.pdf)
- [Lessons Learned](02-Lessons-Learned/Lessons-Learned-DDoS.pdf)

## 7. Lessons Learned

This project helped me understand how DDoS attacks can disrupt network availability and how security teams can use structured response procedures to reduce their impact.

I also learned the importance of traffic monitoring, protective controls, clear communication, and prioritizing critical services during recovery.

## 8. Future Improvements

My next objective is to strengthen my practical network analysis skills by examining ICMP traffic in Wireshark using a controlled lab or an authorized sample packet capture.

## 9. Project Disclaimer

This is an educational case study based on a simulated security incident from the Google Cybersecurity Professional Certificate.

It does not represent an investigation of a real production network or hands-on implementation of the security controls described.

The course activity uses five NIST CSF functions. NIST CSF 2.0 also includes the Govern function.

## 10. References

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity)
