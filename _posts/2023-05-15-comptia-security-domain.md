---
title: CompTIA Security Domain
categories:
- cyber
excerpt: |
## CompTIA Security Domain excerpt
feature_text: |  
  ## CompTIA Security Domain features
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
aside: true
---

- [Domain 1.0 Threats, Attacks, and Vulnerabilities](#domain-10-threats-attacks-and-vulnerabilities)
  - [1.1 Compare and contrast different types of social engineering techniques](#11-compare-and-contrast-different-types-of-social-engineering-techniques)
  - [1.2 Given a scenario, analyze potential indicators to determine the type of attack](#12-given-a-scenario-analyze-potential-indicators-to-determine-the-type-of-attack)
  - [1.3 Given a scenario, analyze potential indicators associated with application attacks](#13-given-a-scenario-analyze-potential-indicators-associated-with-application-attacks)
  - [1.4 Given a scenario, analyze potential indicators associated with network attacks](#14-given-a-scenario-analyze-potential-indicators-associated-with-network-attacks)
  - [1.5 Explain different threat actors, vectors, and intelligence sources](#15-explain-different-threat-actors-vectors-and-intelligence-sources)
  - [1.6 Explain the security concerns associated with various types of vulnerabilities](#16-explain-the-security-concerns-associated-with-various-types-of-vulnerabilities)
  - [1.7 Summarize the techniques used in security assessments](#17-summarize-the-techniques-used-in-security-assessments)
  - [1.8 Explain the techniques used in penetration testing](#18-explain-the-techniques-used-in-penetration-testing)
- [Domain 2.0 Architecture and Design](#domain-20-architecture-and-design)
  - [2.1 Explain the importance of security concepts in an enterprise environment](#21-explain-the-importance-of-security-concepts-in-an-enterprise-environment)
  - [2.2 Summarize virtualization and cloude computing concepts](#22-summarize-virtualization-and-cloude-computing-concepts)
  - [2.3 Summarize secure application development, deployment, and automation concepts](#23-summarize-secure-application-development-deployment-and-automation-concepts)
  - [2.4 Summarize authentication and authorization design concepts](#24-summarize-authentication-and-authorization-design-concepts)
  - [2.5 Given a scenario, implement cybersecurity resilience](#25-given-a-scenario-implement-cybersecurity-resilience)
  - [2.6 Explain the security implications of embedded and specialized systems](#26-explain-the-security-implications-of-embedded-and-specialized-systems)
  - [2.7 Explain the importance of physical security controls](#27-explain-the-importance-of-physical-security-controls)
  - [2.8 Summarize the basic of cryptographic concepts](#28-summarize-the-basic-of-cryptographic-concepts)
- [Domain 3.0 Implementation](#domain-30-implementation)
- [Domain 4.0 Operations and Incident Response](#domain-40-operations-and-incident-response)
- [Domain 5.0 Governance, Risk, and Compliance](#domain-50-governance-risk-and-compliance)
  - [5.2 Explain the importance of applicable regulations, standards, or frameworks that impact organizational security posture](#52-explain-the-importance-of-applicable-regulations-standards-or-frameworks-that-impact-organizational-security-posture)
- [Security+ (SY0-601) Acronym List](#security-sy0-601-acronym-list)
- [Reference](#reference)

## Domain 1.0 Threats, Attacks, and Vulnerabilities

### 1.1 Compare and contrast different types of social engineering techniques

- Phishing
- Smishing
- Vishing
- Spam
- Spam over instant messaging(SPIM)
- Spear phishing
- Dumpster diving
- Shoulder surfing
- Pharming
- Tailgating
- Eliciting information
- Whaling
- Prepending
- Identity fraud
- Invoice scams
- Credential harvesting
- Reconnaissance
- Hoax
- Impersonation
- Watering hole attack
- Typosquatting
- Pretexting
- Influence campaigns
  - Hybrid warfare
  - Social media
- Principles(reasons for effectiveness)
  - Authority
  - Intimidation
  - Consensus
  - Scarsity
  - Familiarity
  - Trust
  - Urgency

### 1.2 Given a scenario, analyze potential indicators to determine the type of attack

- **Malware**
  - **Ransomware**
  - **Trojans** (Masquerades as desirable software to trick user into installing it)
  - **Worms** (Spreads between systems by exploiting vulnerabilities;no user action require)
  - Potentially unwanted programs(**PUPs**)
  - **Fileless** viruses
  - Command and control
  - Bots
  - **Cryptomalware**
  - Logic bombs
  - Spyware
  - Keyloggers
  - Remote access Trojan(RAT)
  - Rookit
  - Backdoor
- **Password attack**
  - Spraying
  - Dictionary
  - Brute force
    - Offline
    - Online
  - Rainbow table
  - Plaintext/unencrypted
- **Physical attacks**
  - Malicious Universal
  - Serial Bus(USB) cable
  - Malicious flash drive
  - Card cloning
  - Skimming
- **Adversarial artificial intelligence(AI)**
  - Tained training data for machine learning(ML)
  - Security of machine learning algorithms
- **Supply-chain attacks**
- **Cloud-based vs. on-promises attacks**
- **Cryptographic attacks**
  - **Birthday**(an attempt to find collisions in hash functions)
  - **Collision** (replay attack - an attempt to reuse authentication requests)
  - Downgrade

### 1.3 Given a scenario, analyze potential indicators associated with application attacks

- Privilege escalation
- Cross-site scripting
- Injections
  - Structured query language(SQL)
  - Dynamic-link library(DLL)
  - Lightweight Directory Access Protocol(LDAP)
  - Extensible Markup Language(XML)
- Pointer/object dereference
- Directory Traversal
- Buffer overflows
- Race conditions
  - Time of check/time of use
- Time of check/time of use
- Error handling
- Improper input handling
- Reply attack
  - Session replays
- Integer overflow
- Request forgeries
  - Server-side
  - Cross-site
- Application programming interface(API) attacks
- Resource exhaustion
- Memory leak
- Secure Socket Layer(SSL) stripping
- Driver manipulation
  - **Shimming** (Small library that handle the operation itself, change the arguments passed, or redirect the request elsewhere)
  - **Refactoring** (Identify the flow and then modify the internal structured code)
- **Pass the hash** (attacker captures a password hash and then passes it through for authentication and lateral access)

### 1.4 Given a scenario, analyze potential indicators associated with network attacks

- Wireless
  - **Evil twin** ( a malicious fake wireless access point)
  - Rogue access point
  - **Bluesnarfing** (data theft using Bluetooth)
  - **Bluejacking** (pranksters to push unsolicited messages to engage/ennoy other nearby Bluetooth)
  - Disassociation (break the wireless connection)
  - **Jamming** (a DoS attack that using channel by occupying the channel)
  - Radio frequency identification(**RFID**) (commonly used in access badge systems)
  - Near-field communication(**NFC**) (the touch pay system at the grocery)
  - Initialization vector(**IV**) (modifies the initialization vector of an encrypted wireless packet during transmission)
- **On-path attack**(previously known as man-in-the-middle attack/man-in-the-browser attack)
- Layer 2 attacks
  - Address Resolution Protocol(ARP)poisoning
  - Media access control(MAC) flooding
  - MAC cloning
- Domain name system(DNS)
  - Domain hijacking
  - **DNS poisoning** (attacker alter the domain-name-to-IP-address mapping in a DNS system)
  - Uniform Resource
  - Loctor(URL) redirection
  - Domain reputation
- Distributed denial-of-service(DDoS) (**DoS** is a resource consumption attack, **DDoS** is use multiple compromised computer systems as source of attack traffic)
  - Network (targeting flaws in network protocols)
  - Application (exploit weaknesses in the application layer (layer 7))
  - Operational technology(OT) (targets the weaknesses of software and hardware devices)
- Malicious code or script execution
  - PowerShell
  - Python
  - Bash
  - Macros
  - Visual Basic for Applications(VBA)

### 1.5 Explain different threat actors, vectors, and intelligence sources

- Actors and threats
  - Advanced persistent(APT)
  - Insider threats
  - State actors
  - Hacktivists
  - Script kiddies
  - Criminal syndicates
  - Hackers
    - Authorized
    - Unauthorized
    - Semi-authorized
  - Shadow IT (often done with good intensions)
  - Competitors
- Atributes or actors
  - Internal/external
  - Level of sophistication/capability
  - Resources/funding
  - Intent/motivation
- Vectors
  - Direct access
  - Wireless
  - Email
  - Supply chain
  - Social media
  - Removable media
  - Cloud
- Threat intelligence sources
  - Open-source inteligence(OSINT)
  - Closed/prioprietary
  - Vulnerability databases
  - Public/private information-sharing center
  - Dark web
  - Indicators of compromise
  - Automated indicator Sharing (AIS)
    - Structured Threat Information
    - eXpression(STIX)/Trusted
    - Automated eXchange of Inteligence Information(TAXII)
    - Predictive analysis(a mix of automation and human intelligence)
    - Threat maps
    - File/code repositories
- Research sources
  - Vendor websites
  - Vulnerability feeds
  - Conferences
  - Academic journals
  - Request for comments(RFC)
  - Local Industry groups
  - Social media
  - Threat feeds
  - Adversary tactics, techniques, and procedures(TTP)

### 1.6 Explain the security concerns associated with various types of vulnerabilities

- Cloud-based vs. on-promises vulnerabilities
- **Zero-day** (an attack that uses a vulnerability that is either unknow to anyone but  the attacker or known anly to a limited group of people)
- Weak configuration
  - Open permissions
  - Unsecure root accounts
  - Errors
  - Weak encryptions
  - **Unsecure protocols** (telnet, SNMPv1/v2,ftp)
  - Default settings
  - Open ports and services
- Third-party risks
  - Vendor management
    - System integration(potential for increased risk of insider attack)
    - Lack of vendor support
  - **Supply chain**(include: supplier, manufacturers,distributors and customers)
  - Outsourced code development
  - Data storage
- Improper or weak patch management
  - Firmware
  - Operating system(OS)
  - Applications
- Legacy platforms
- Impacts
  - Data loss
  - Data breaches
  - Data exfiltration
  - Identity theft
  - Financial
  - Reputation
  - Availability loss

### 1.7 Summarize the techniques used in security assessments

- **Threat hunting**
  - *Inteligence fusion*(involves industry and government)
  - Threat feeds()
  - Advisories and bulletins()
  - Maneuver
- **Vulnerability scans**
  - False positives
  - False negatives
  - Log reviews
  - Credentialed vs. non-credentialed
  - Intrusive vs. non-intrusive
  - Application
  - Web application
  - Network
  - Common Vulnerabilities and Exposure(CVE)/Common Vulnerability Scoring System(CVSS) (The CVE list feeds into the NVD)
  - Configuration review
- **Syslog/Security information and event management(SIEM)**
  - Review reports
  - Packet capture
  - Data inputs
  - User behavior analysis
  - Sentiment analysis(Artificial intelligence and machine learning)
  - Security monitoring
  - Log aggregation
  - Log collectors
- **Security orchestration, automation, and response(SOAR)** ()

### 1.8 Explain the techniques used in penetration testing

- **Penetration testing**
  - Known environment(white box test)
  - Unknown environment(black box test)
  - Partially known environment(limited information, grey box test)
  - Rules of engagement
  - Lateral movement
  - Privilege escalation
  - Persistence
  - Cleanup
  - Bug bounty
  - Pivoting
- **Passive and active reconnaissance**
- passive
  - Drones
  - War flying(combine war driving with a drones)
  - War driving()
  - OSINT
  - Footprinting
- active
  - Footprinting(includes active and passive methods)
  
- **Exercise types**
  - Red team(offense)
  - Blue team(defense)
  - White team(judge / referee)
  - Purple team(process improvement)

## Domain 2.0 Architecture and Design

### 2.1 Explain the importance of security concepts in an enterprise environment

- Configuration management
- Data sovereignty
- Data protection
- Geographical considerations
- Response and recovery controls
- Secure Sockets Layer(SSL)/Transport Layer Security(TLS)inspections
- Hashing
- API considerations
- Site resiliency
- Deception and disruption

### 2.2 Summarize virtualization and cloude computing concepts

- Cloud models
- Cloud service providers
- Managed service provider(MSP)/managed security service provider(MSSP)
- On-promises vs. off-premises
- Fog computing
- Edge computing
- Thin client
- Containers
- Microservices/API
- Infrastructure as code
- Serverless architecture
- Services integration
- REsource policies
- Transit gateway
- Virtualization

### 2.3 Summarize secure application development, deployment, and automation concepts

- Environment
- Provisioning and deprovisioning
- Integrity measurement
- Secure coding techniques
- Open Web Application Security Project(OWASP)
- Software diversity
- Automation/scripting
- Elasticity
- Scalability
- Version control

### 2.4 Summarize authentication and authorization design concepts

- Authentication methods
- Biometrics
- Multifactor authentication(MFA) factors and attributes
- Authentications authorization, and accounting(AAA)
- Cloud vs. on-premises requirements

### 2.5 Given a scenario, implement cybersecurity resilience

- Redundancy
- Replication
- On-premises vs. cloud
- Backup types
- Non-persistence
- High availability
- Restoration order
- Diversity

### 2.6 Explain the security implications of embedded and specialized systems

### 2.7 Explain the importance of physical security controls

### 2.8 Summarize the basic of cryptographic concepts

## Domain 3.0 Implementation

## Domain 4.0 Operations and Incident Response

## Domain 5.0 Governance, Risk, and Compliance

### 5.2 Explain the importance of applicable regulations, standards, or frameworks that impact organizational security posture

- Regulations, standards, and legislations
- Key frameworks
- Benchmarks/secure configuration guides

## Security+ (SY0-601) Acronym List

The following is a list of acronyms that appear on the Comptia Security+ exam Candidates are encouraged to review the complate list and attain a working knowledge of all listed acronyms as part of a comprehensive exam preparation program.

|ACRONYM|DEFINITION|
|---|---|
|3DES|Triple Data Encryption|
|AAA|Authentication, Authorization, and Accounting|
|ABAC|Attribute-based Access Control|
|ACL|Access Control List|
|CSF|Cybersecurity Framework|
|NIST|National Institute of Standards and Technology|
|UEBA|User and Entity Behavior Analytics|
|||
|||
|||
|||

## Reference

[CompTIA](https://comptia.org)
