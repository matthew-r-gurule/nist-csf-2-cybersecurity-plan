# Cybersecurity Plan for XYZ Insurance: NIST CSF 2.0 Capstone

A comprehensive, framework-aligned cybersecurity plan for a hypothetical two-office insurance company, written as my cybersecurity degree capstone. The plan uses the **NIST Cybersecurity Framework (CSF) 2.0** to cover governance, risk management, security controls, and incident response.

**Read the full paper:** [`docs/NIST-CSF-2.0-Capstone.pdf`](docs/NIST-CSF-2.0-Capstone.pdf) (23 pages, June 2026)

## The Scenario

I took the role of the new CIO of **XYZ Insurance**, a fictional company with a mix of modern and legacy infrastructure and the sensitive data that comes with insurance work (PII, financial, and policy records).

| | Chicago (corporate) | Denver (satellite) |
|---|---|---|
| Servers | 800 | 400 |
| Users | 1,000 (600 desktop, 400 laptop) | 400 (250 desktop, 150 laptop) |
| Server OS mix | Windows XP through Windows 11 | Windows XP through Windows 11 |
| IT staff | 4 techs, 1 lead, full NOC | 3 techs, 1 lead, full NOC |

The main challenges: **legacy systems that no longer get patches, a small IT team, two locations in different states, and a heavy regulatory load.**

## What the Plan Covers

| CSF 2.0 Function | How it is applied at XYZ |
|---|---|
| **Govern** | Risk-based policies applied across both sites; compliance mapped to NAIC Insurance Data Security Model, NYDFS Cybersecurity Regulation, HIPAA, GLBA, PCI DSS, and Colorado and Illinois state laws; documented risk acceptance for legacy systems that cannot yet be retired |
| **Identify** | Asset and sensitive-data identification; risk assessment of legacy systems |
| **Protect** | MFA, least privilege, encryption, network segmentation to isolate legacy systems, routine patch management, role-based security awareness training |
| **Detect** | IDPS and continuous monitoring, activity baselines, validation of events before the incident response plan is activated |
| **Respond** | Incident response plan and cross-functional response team; containment, eradication, and evidence preservation |
| **Recover** | Disaster recovery plan, tested backups, response and recovery drills, post-incident reviews |

## Highlights

- **Measurable goals:** 100% data classification, encryption, and access controls within six months; 95%+ of critical patches applied within 30 days of release; incident detection within four hours.
- **Current and Target Profiles:** a gap-analysis approach following the CSF 2.0 profile process, prioritized by risk appetite, regulatory obligations, resources, and operational impact.
- **Risk management:** the five-step process (identify, analyze, evaluate, treat, monitor), with qualitative and quantitative assessment and a risk matrix covering legacy systems, phishing, ransomware, and insider threats.
- **ROI vs. ROSI:** a worked comparison of traditional return on investment against Return on Security Investment, using ALE, SLE, ARO, and mitigation ratio to justify security spending.
- **Incident management lifecycle:** preparation, detection and analysis, containment and eradication, recovery, and lessons learned, with MTTD and MTTR as review metrics.

## Paper Outline

1. Cybersecurity at XYZ: roles, key elements, and strategic value
2. Impact of compliance and governance
3. NIST implementation strategy (core functions, goals, profiles)
4. Planning for risk management
5. Assessment model for cybersecurity projects (ROI vs. ROSI, risk matrix)
6. Planning for incident management
7. Conclusion and references

## Skills Demonstrated

Security program design, NIST CSF 2.0, governance, risk, and compliance (GRC), risk assessment, security control selection, incident response planning, regulatory mapping, and security investment analysis.

## Repository Structure

```
.
├── README.md
├── .gitignore
└── docs/
    └── NIST-CSF-2.0-Capstone.pdf
```

## Notes

This is an academic project based on a fictional company. No real organization's data or systems are described. Sources are cited in the References section of the paper.

## Author

**Matthew Gurule**
[LinkedIn](www.linkedin.com/in/matthew-r-gurule) | [GitHub](https://github.com/matthew-r-gurule)

See also: [Pi-hole + Splunk DNS Monitoring](https://github.com/matthew-r-gurule/pihole-splunk-dns-monitoring), a hands-on home lab project.
