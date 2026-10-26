# Understanding-Cyber-Threats-and-Defence-Mechanisms
A cybersecurity report covering the main cyber threats facing a medium-sized organization, the defences used against them, and lessons from major real-world attacks.


# Understanding Cyber Threats and Defence Mechanisms

A cybersecurity report covering the main cyber threats facing a medium-sized organization, the defences used against them, and lessons from major real-world attacks.

**Author:** Sunilkumar Amarjith (M24W0187)
**Course:** Cyber Security(e), 124N5256
**Program:** Masters in IT (ERP), The Kyoto College of Graduate Studies for Informatics
**Semester:** Fall 2024
**Submitted:** 2025-01-19

## Objective

As organizations depend more on connected systems, cyberattacks cause growing financial loss, reputational damage, and even national security risks. This report explains the fundamentals of cybersecurity and identifies common threats and organizational weaknesses. It then recommends practical defences, tools, and standards to reduce risk.

### Skills Learned

- Understanding core cybersecurity principles, including the CIA Triad, authentication, authorization, and encryption.
- Identifying common cyber threats and the vulnerabilities behind them.
- Matching each threat with suitable defences and tools.
- Analyzing real-world breaches and extracting lessons from them.
- Knowing key security standards and best practices.
- Comparing traditional and modern defence approaches.

## Core Concepts

**CIA Triad**

| Principle | Meaning |
|-----------|---------|
| **Confidentiality** | Only authorized people can access sensitive information |
| **Integrity** | Data stays accurate, consistent, and unaltered |
| **Availability** | Systems and data are accessible when needed |

Other key concepts are **authentication** (verifying who a user is), **authorization** (deciding what they can access), **encryption** (protecting data in transit and at rest), **endpoint protection**, **network security**, and **incident response**.

## Threats and Defences

The report assumes an organization with employee devices, cloud storage, on-premises servers, and IoT devices.

| Threat | Main Weakness | Defence |
|--------|---------------|---------|
| Phishing | Untrained staff | MFA, email filtering (e.g., Proofpoint), regular training |
| Ransomware | Weak backups, outdated systems | Patching, endpoint protection (e.g., SentinelOne), secure backups |
| DDoS | Poor traffic monitoring | Load balancing and traffic control (e.g., Cloudflare, Akamai) |
| SQL injection | Weak database security | Parameterized queries, penetration testing |
| Man-in-the-middle | Unencrypted communication | VPNs, TLS encryption |
| Insider threats | No role-based access control | Background checks, strict access control, SIEM (e.g., Splunk) |
| Zero-day exploits | Unpatched software | Proactive patching, behavioral analytics, threat intelligence |
| IoT vulnerabilities | Default credentials, old firmware | Network segmentation, firmware updates, IoT security tools |
| Malware | Weak endpoint security | Antivirus, routine scans, safe-browsing training |
| Social engineering | Human trust | Awareness culture, simulated phishing tests |
| Credential stuffing | Reused weak passwords | MFA, strong password policies, breach monitoring |
| Supply chain attacks | Weak third-party security | Vendor risk assessments, secure contracts, security scoring tools |
| Cloud misconfiguration | Open storage, loose permissions | CSPM tools (e.g., Prisma Cloud), audits, least privilege |

**General strategies:** regular software updates, employee education, and the principle of least privilege.

**Advanced tools:** intrusion detection systems (IDS), firewalls, endpoint protection platforms (EPP), encryption, behavioral analytics, SIEM, AI-based detection (e.g., Darktrace), and Zero Trust Architecture.

## Case Studies

| Incident | What Happened | Key Lesson |
|----------|---------------|------------|
| **WannaCry (2017)** | Ransomware exploiting a Windows SMB flaw hit 200,000+ systems in 150 countries, including the UK's NHS | Patch promptly, keep backups, segment networks |
| **Equifax (2017)** | An unpatched Apache Struts flaw exposed data of 140+ million people | Regular audits, vulnerability management, transparent breach reporting |
| **Target (2013)** | Attackers used a vendor's stolen credentials to reach point-of-sale systems | MFA, network segmentation, vendor risk management |
| **SolarWinds (2020)** | Malicious code inserted into software updates affected thousands of organizations | Code integrity checks, secure development, Zero Trust |

### Key Takeaways

1. Timely patch management is critical.
2. Vendor and supply chain security is vital.
3. Network segmentation limits the damage.
4. Proactive monitoring and detection are essential.
5. Incident response planning is non-negotiable.
6. Employee awareness and training reduce risk.
7. Zero Trust should be adopted.

## Current Trends

- AI and machine learning for threat detection and automated response
- Zero Trust Security Architecture
- Cloud Security Posture Management (CSPM)
- Extended Detection and Response (XDR) and Cybersecurity Mesh Architecture
- Quantum cryptography, IoT-specific security, and 5G security
- Cyber resilience planning, threat intelligence sharing, and privacy-enhancing technologies

## Standards and Best Practices

- **Standards and frameworks:** ISO 27001, NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover)
- **Regulations:** GDPR, HIPAA, PCI DSS
- **Practices:** patch management, MFA, encryption, least privilege, network segmentation, Zero Trust, staff training, tested incident response plans, isolated backups, third-party monitoring

## Traditional vs. Modern Defence

| Traditional | Modern |
|-------------|--------|
| Reactive, built around known threats | Proactive and adaptive |
| Firewalls, signature-based antivirus, basic access control | AI/ML detection, behavioral analytics, Zero Trust, EDR, SIEM |
| Struggles with zero-day and internal threats | Detects unusual behavior in real time |
| Hard to scale for cloud, IoT, and remote work | Works across cloud, on-premises, and hybrid environments |

## Conclusion

Strong cybersecurity needs a proactive, layered approach: regular updates, trained staff, vulnerability management, modern tools such as AI and Zero Trust, and adherence to recognized standards. Organizations must keep adapting as threats evolve.

## References

1. G. Loukas, D. Gan, and T. Vuong, "A review of cyber threats and defence approaches in emergency management," *Future Internet*, vol. 5, no. 2, pp. 205–236, 2013.
2. R. K. Goutam, "Importance of cyber security," *International Journal of Computer Applications*, vol. 111, no. 7, 2015.
3. M. M. Chowdhury et al., "ChatGPT: A threat against the CIA triad of cyber security," *2023 IEEE International Conference on Electro Information Technology (eIT)*, 2023, pp. 1–6.
4. M. Humayun et al., "Cyber security threats and vulnerabilities: A systematic mapping study," *Arabian Journal for Science and Engineering*, vol. 45, pp. 3171–3189, 2020.
5. F. N. U. Jimmy, "Cyber security vulnerabilities and remediation through cloud security tools," *Journal of Artificial Intelligence General Science (JAIGS)*, vol. 2, no. 1, pp. 129–171, 2024.
6. S. Mohurle and M. Patil, "A brief study of WannaCry threat: Ransomware attack 2017," *International Journal of Advanced Research in Computer Science*, vol. 8, no. 5, pp. 1938–1940, 2017.
7. C. Kenny, "The Equifax data breach and the resulting legal recourse," *Brook. J. Corp. Fin. & Com. L.*, vol. 13, p. 215, 2018.
8. N. Manworren, J. Letwat, and O. Daily, "Why you should care about the Target data breach," *Business Horizons*, vol. 59, no. 3, pp. 257–266, 2016.
9. J. Huddleston et al., "How VMware exploits contributed to SolarWinds supply-chain attack," *2021 International Conference on Computational Science and Computational Intelligence (CSCI)*, 2021, pp. 760–765.
10. A. B. Pandey, A. Tripathi, and P. C. Vashist, "A survey of cyber security trends, emerging technologies and threats," *Cyber Security in Intelligent Computing and Communications*, pp. 19–33, 2022.
11. C. McCarthy, K. Harnett, and A. Carter, "A summary of cybersecurity best practices," U.S. DOT, NHTSA, Report No. DOT HS 812 075, 2014.
12. F. P. Van der Putten, M. Meijnders, and J. Rood, "Deterrence as a security concept against non-traditional threats," *Clingendael Monitor*, vol. 7, 2015.
