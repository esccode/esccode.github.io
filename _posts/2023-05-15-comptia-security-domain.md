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
  - [3.8 Given a scenario, implement authentication and authorization solutions](#38-given-a-scenario-implement-authentication-and-authorization-solutions)
- [Domain 4.0 Operations and Incident Response](#domain-40-operations-and-incident-response)
  - [4.1 Given a scenario, use the appropriate tool to assess organizational security](#41-given-a-scenario-use-the-appropriate-tool-to-assess-organizational-security)
- [Domain 5.0 Governance, Risk, and Compliance](#domain-50-governance-risk-and-compliance)
- [5.1 Compare and contrast various types of control](#51-compare-and-contrast-various-types-of-control)
  - [5.2 Explain the importance of applicable regulations, standards, or frameworks that impact organizational security posture](#52-explain-the-importance-of-applicable-regulations-standards-or-frameworks-that-impact-organizational-security-posture)
  - [5.4 Summarize risk management processes and concepts](#54-summarize-risk-management-processes-and-concepts)
- [Security+ (SY0-601) Acronym List](#security-sy0-601-acronym-list)
- [Security+ Proposed Hardware and Software List](#security-proposed-hardware-and-software-list)
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
- Impersonation(simply means pretending to be someone else)
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
  - Maneuver(assessment techniques that avoid alerting threat actors)
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
  - Bug bounty(rewards are given for reporting  vulnerabilities)
  - Pivoting
- **Passive and active reconnaissance**
- Passive
  - Drones
  - War flying(combine war driving with a drones)
  - War driving()
  - OSINT
  - Footprinting
- Active
  - Footprinting(includes active and passive methods)
  
- **Exercise types**
  - Red team(offense)
  - Blue team(defense)
  - White team(judge / referee)
  - Purple team(process improvement)

## Domain 2.0 Architecture and Design

### 2.1 Explain the importance of security concepts in an enterprise environment

- Configuration management
  - Diagrams
  - Baseline configuration
  - Standard naming conventions
  - Internet protocol(IP) scheme
- Data sovereignty
- Data protection
  - Data loss prevention(DLP)
  - Masking
  - Encryption
  - At rest
  - In transit/motion
  - In processing
  - Tokenization
  - Rights management
- Geographical considerations
- Response and recovery controls
- Secure Sockets Layer(SSL)/Transport Layer Security(TLS)inspections
- Hashing
- API considerations
- Site resiliency
  - Hot site
  - Cold site
  - Warm site
- Deception and disruption
  - Honeypots
  - Honeyfiles
  - Honeynets
  - Fake telemetry
  - DNS sinkhole

### 2.2 Summarize virtualization and cloude computing concepts

- Cloud models
  - Infrastructure as a service(IaaS)
  - Platform as a service(PaaS)
  - Software as a service(SaaS)
  - Anything as a service(XaaS)
  - Public
  - Community
  - Private
  - Hybrid
- Cloud service providers
- Managed service provider(MSP)/managed security service provider(MSSP)
- On-promises vs. off-premises
- Fog computing
- Edge computing
- Thin client
- Containers
- Microservices/API
- Infrastructure as code
  - Software-defined networking(SDN)
  - Software-defined visibility(SDV)
- Serverless architecture
- Services integration
- Resource policies
- Transit gateway
- Virtualization
  - Virtual machine(VM) sprawl avoidance
  - VM escape protection

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
  - Directory service
  - Federation
  - Attestation(approved device compliant with company policies)
  - Technologies
    - Time-based one-time password(TOTP)
    - HMAC-based one-time password(HOTP)
    - Short message service(SMS)
    - Token key(one-time password provided on a hardware of software token generator)
    - Static codes
    - Authentication applications
    - Push notifications
    - Phone call
  - Smart card authentication
- Biometrics
  - Fingerprint
  - Retina
  - Iris
  - Facial
  - Voice
  - Vein(żyła)
  - Gait analysis(chód)
  - Efficacy acceptance
  - False rejection
  - Crossover error rate(FAR=false acceptace rate and FRR=false rejection rate)
- Multifactor authentication(MFA) factors and attributes
  - Factors
    - Something you know
    - Something you have
    - Something you are
  - Attributes
    - Somewhere you are
    - Something you can do
    - Something you exhibit(eksponowac)
    - Someone you know
- Authentications authorization, and accounting(AAA)
- Cloud vs. on-premises requirements

### 2.5 Given a scenario, implement cybersecurity resilience

- Redundancy
  - Geographical dispersal
  - Disk
    - Redundant array of inexpensive disks(RAID) levels
    - Multipath
  - Network
    - Load balances
    - Network interface card(NIC)teaming
  - Power
    - Uninterruptible power supply(UPS)(essentially a battery)
    - Generator(standby power source)
    - Dual supply
    - Manager power distribution units(PDUs)
- Replication
  - Storage area network(SAN)
  - VM
- On-premises vs. cloud
- Backup types
  - Full
  - Incremental
  - Snapshot
  - Differential
  - Tape
  - Disk
  - Copy(useful in one-off/add hoc scenario)
  - Network-attached storage(NAS)
  - Storage area network
  - Cloud
  - Image
  - Online vs. Offline
  - Offsite storage
    - Distance consideration
- Non-persistence
  - Revert to know state
  - Last known good configuration
  - Live boot media
- High availability(the ability to keep services up and running for long periods of time)
  - Scalability(the ability of a system to handle of users or work)
- Restoration order
- Diversity(impact of diversity on availability, resiliency,and security)
  - Technologies(different technology)
  - Vendors(multiple vendors)
  - Crypto(multiple algorithms)
  - Controls

### 2.6 Explain the security implications of embedded and specialized systems

- Embedded systems
  - Raspberry Pi
  - Field-programmable gate arrey(FPGA)
  - Arduino
- Supervisory control and data acquisition(SCADA)/industrial control system(ICS)
  - Facilities
  - Industrial
  - Manufacturing
  - Energy
  - Logistics
- Internet of Things(loT)
  - Sensors
  - Smart devices
  - Wearables
  - Facility automation
  - Weak defaults
- Specialized
  - Medical systems
  - Vehicles
  - Aircraft
  - Smart meters
- Voice over IP(VoIP)
- Heating, ventilation, air conditioning(HVAC)
- Drones
- Multifunction printer(MFP)
- Real-time operating system(RTOS)
- Surveillance systems
- System on chip(SoC)
- Communication considerations
  - 5G
  - Narrow-band
  - Baseband radio
  - Subscriber identity module(SIM)cards
  - Zigbee
- Constraints
  - Power
  - Compute
  - Network
  - Crypto
  - Inability to patch
  - Authentication
  - Range
  - Cost
  - Implied trust

### 2.7 Explain the importance of physical security controls

- Bollards(stop car moving after point)/barricades
- Access control vestibules
- Badges
- Alarms
- Signage(discourage intruders)
- Cameras
  - Motion recognition
  - Object detection
- Closed-circuit television(CCTV)
- Industrial camouflage
- Personnel
  - Guards
  - Robot sentries
  - Reception
  - Two-person integrity/control
- Locks
  - Biometrics
  - Electronic
  - Physical
  - Cable locks
- USB data blocker
- Lighting
- Fencing
- Fire suppression
>?|Class|Type|Suppression material|
|---|---|---|
|A|Common combustibles|Watre,soda acid(a dry powder or liquid chemical)|
|B|Liquids|CO2,halon,soda acid|
|C|Electrical|CO2,halon|
|D|Metal|Dry powder|
|K|Kitchen|Wet chemicals|

- Sensors
  - Motion detection
  - Noise detection
  - Proximity reader(nearness)
  - Moisture detection(humidity)
  - Cards
  - Temperature
- Drones
- Visitor logs
- Faraday cages(prevents wireless or cellular phones)
- Air gap
- Screened subnet(previously known as demilitarized zone)(like DMZ)
- Protected cable distribution
- Secure area
  - Air gap
  - Vault
  - Safe
  - Hot aisle
  - Cold aisle
- Secure data destruction
  - Burning
  - Shredding(shred a metal hard drive into powder)
  - Pulping(if burning is not available, pulping, which turns the data into paper mache, is the best option)
  - Pulverizing(use a hammer and smash frive into pieces, or drill through all the platters)
  - Degaussing(create a stronge magnetic field that erases data on some media and destroy electronics)
  - Third-party solutions

### 2.8 Summarize the basic of cryptographic concepts

- Digital signatures(encrypted hash of a message, encrypted with the sender's private key)
- Key length(large keys tend to be more secure, Since 2015, NIST recommands a minimum of 2048-bit keys for RSA)
- Key stretching
- Salting(random data that is used as an additional input to a one-way function that hashes data, a password or passphrase)
- Hashing(one-way function that scrambles plain text to produce a unique message digest)
- ?Encryption(two-way function;what is encrytped can be decrypted with the proper key)
- Key exchange
- Elliptic-curve cryptography(small, fast key that is used for encryption in small mobile devices)
- Perfect forward secrecy
- Quantum()
  - Communications
  - Computing
- Post-quantum
- Ephemeral
- Modes of operation
  - Authenticated
  - Unauthenticated
  - Counter
- Blockchain
  - Public ledgers
- Cipher suites
  - Stream
  - Block
- Symmetric vs. asymmetric(Symetric relies on the use of a shared secret key. Asymmetric- public-privates key pairs for communication between parties.)
- Lightweight ctyptography
- Steganography(a computer file,message,image, or video is cancealed within another file,message,image,or video)
  - Audio
  - Video
  - Image
- Homomorphic encryption(allows users to run calculation on data while it is still encrypted)
- Common use cases
  - Low power devices
  - Low latency
  - High resiliency
  - Supporting confidentiality
  - Supporting integrity
  - Supporting obfuscation
  - Supporting authentication
  - Supporting non-repudiation
- Limitation
  - Speed
  - Size
  - Weak keys
  - Time
  - Longevity
  - Predictability
  - Reuse
  - Entropy
  - Computational overheads
  - Resource vs. security constraints

## Domain 3.0 Implementation

### 3.8 Given a scenario, implement authentication and authorization solutions

- Authentication management
  - Password keys(like USB device and works in conjuction with your password to provide multi-factor authentication)
  - Password vaults(use strong encryption(e.g. AES-256))
  - **TPM**(Trusted Platform Module normally built into the motherboard of a computer)
  - **HSM**(Hardware Security Module)
  - Knowledge-based authentication(KBA normally used by banks)
- Authentication/authorization
  - EAP(Extensible Auth Protocol)
  - Challenge-Handshake
  - Authentication Protocol(CHAP)
  - Password Authentication Protocol(**PAP**)
  - 802.1X
  - RADIUS(uses UDP and encrypts the passwords only, remote access)
  - Single sign-on(SSO)(means a user doesn't have to sign into every application they use. the user logs in once and that credential is used for multiple apps)
  - Security Assertion Markup Language(SAML)(common in on-prem federation scenarios)
  - Terminal Access Controller Access Control System Plus(**TACACS+**)(admin access to network devices, uses TCP and encrypts the entire session)
  - OAuth(for internet users to log into third party websites using their Microsoft, Google, Facebook, Twitter etc. accounts without exposing their passwords)
  - OpenID(loggin into spotify with your FB account)
  - Kerberos(authorization protocol in Microsoft Azure Directory)
- Access control scheme
  - Attribute based access control(ABAC)
  - Role-based access control(RBAC)(typical mapped to job roles)
  - Rule-based access control(global rules)
  - MAC(Mandatory access control)
  - Discretionary access control(DAC)
  - Conditional access
  - Privileged access management(privileged accounts within a domain)
  - Filesystem permissions(NTFS(Windows), SUID and SGID(Linux))

## Domain 4.0 Operations and Incident Response

### 4.1 Given a scenario, use the appropriate tool to assess organizational security

- Network reconnaissance and discovery
  - tracert/traceroute
  - nslookup/dig
  - ipconfig/ifconfig
  - nmap
    - TCP SYN (-sS)—this is a fast technique also referred to as half-open scanning, as the scanning host requests a connection without acknowledging it. The target's response to the scan's SYN packet identifies the port state.
    - UDP scans (-sU)—scan UDP ports. As these do not use ACKs, Nmap needs to wait for a response or timeout to determine the port state, so UDP scanning can take a long time. A UDP scan can be combined with a TCP scan.
    - Port range (-p)—by default, Nmap scans 1000 commonly used ports, as listed in its configuration file. Use the -p argument to specify a port range.
  - ping/pathping
  - hping
  - netstat
  - IP scanners
  - arp
  - route
  - curl
  - theHarvester
  - sniper
  - scanless
  - dnsenum
  - Nessus
  - Cuckoo
- File manipulation
  - head
  - tail
  - cat
  - grep
  - chmod
  - logger
- Shell and script environments
  - SSH
  - PowerShell
  - Python
  - OpenSSL
- Packet capture and replay
  - Tcpreplay
  - Tcpdump
  - Wireshark
- Forensics
  - dd
  - Memdump
  - WinHex
  - FTK imager
  - Autopsy
- Exploitation frameworks
- Password crackers
- Data sanitization

## Domain 5.0 Governance, Risk, and Compliance

## 5.1 Compare and contrast various types of control

- Category
  - Managerial
  - Operational
  - Technical
- Control type
  - Preventive
  - Detective
  - Corrective
  - Deterrent
  - Compensating
  - Physical

### 5.2 Explain the importance of applicable regulations, standards, or frameworks that impact organizational security posture

- Regulations, standards, and legislations
  - General Data Protection Regulation(GDPR)
  - National,territory, or state laws
  - Payment Card Industry Data Security Standard (PCI DSS)
- Key frameworks
  - Center for Internet Security(CSI)
  - National Institute of Standards and Technology(NIST) Risk Management Framework(RMF)/Cybersecurity Framework(CSF)
  - International Organization for Standardization(ISO)27001/27002/27701/31000
  - SSAE SOC2 Type I/II
  - Cloud security alliance
  - Cloud control matrix
  - Reference architecture
- Benchmarks/secure configuration guides
  - Platform/vendor-specific guides
    - Web server
    - OS
    - Paalication server
    - Network infrastructure devices

### 5.4 Summarize risk management processes and concepts

- Risk types
  - External
  - Internal
  - Legacy systems(vulnerabilities to legacy systems tend to increase over time)
  - Multiparty
  - IP theft
  - Software compliance/licensing
- Risk management strategies
  - Acceptance
  - Avoidance
  - Transference
    - Cybersecurity insurance
  - Mitigation(The act of reducing risk)
- Risk analysis
  - Risk register
  - Risk matrix/heat map
  - Risk control assessment
  - Risk control self-assessment
  - Risk awareness
  - Inherent risk
  - Residual risk
  - Control risk
  - Risk appetite(willing to accept)
  - Regulations that affect risk posture
  - Risk assessment types
    - Qualitative
    - Quantitative
  - Likelihood of occurrence
  - Impact
  - Asset value
  - Single-loss expectancy(SLE)
  - Annualized loss expectancy(ALE)
  - Annualized rate of occurrence(ARO)
- Disasters
  - Environmental
  - Person-made
  - Internal vs. external
- Business impact analysis
  - Recovery time objective(RTO)
  - Recovery point objective(RPO)
  - Mean time to repair(MTTR)
  - Mean time between failures(MTBF)
  - Functional recovery plans
  - Single point of failure
  - Disaster recovery plan(DRP)
  - Mission essential functions
  - Identification of critical systems
  - Site risk assessment

## Security+ (SY0-601) Acronym List

The following is a list of acronyms that appear on the Comptia Security+ exam Candidates are encouraged to review the complate list and attain a working knowledge of all listed acronyms as part of a comprehensive exam preparation program.

|ACRONYM|DEFINITION|
|---|---|
|3DES|Triple Data Encryption|
|AAA|Authentication, Authorization, and Accounting|
|ABAC|Attribute-based Access Control|
|ACL|Access Control List|
|CSF|Cybersecurity Framework|
|CSIRT|Computer Security Incident Response Team|
|NIST|National Institute of Standards and Technology|
|RMF|Risk Management Framework|
|TTP|tactic, technique, or procedure|
|UEBA|User and Entity Behavior Analytics|
|||
|||
|||
|||

## Security+ Proposed Hardware and Software List

> CompTIA has included this sample list of hardware and software to assist candidates as they prepare for the Security+ exam. This list may also be helpful for training companies that wish to create a lab component for their training offering. The bulleted lists below each topic are sample lists and are not exhaustive.

- Hardware
- Software
- Other

## Reference

[CompTIA](https://comptia.org)
