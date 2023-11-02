# SER322

## **MODULE 1**

### **OSI MODEL**
| Layer | Description |  
| ------- | ----------- |  
| Application <BR> (Host Layer) | Data: Data <BR> Network Process to Application |
| Presentation <BR> (Host Layer) | Data: Data <BR> Data Representation and Encryption |
| Session <BR> (Host Layer) | Data: Data <BR> Interhost Communication |
| Transport <BR> (Host Layer) | Data: Segments <BR> End-to-End Connections and Reliability |
| Network <BR> (Media Layer) | Data: Packets <BR> Path Determination and IP (Logical Addressing)
| Data Link <BR> (Media Layer) | Data: Frames <BR> MAC and LLC (Physical Addressing) <BR> SubLayers: Logical Link Control, Median Access Control |
| Physical <BR> (Media Layer) | Data: Bits <BR> Media, Signal, and Binary Transmission | 

### **TRANSMISSION PROTOCOL**

| Term | Description |  
| ------- | ----------- | 
|  ARP | Address Resolution Protocol <BR> It is a request to get the MAC address for the IP address. This is because switches use MAC addresses and not IP addresses. This request is sent to the whole network.|


### **SECURITY TERMINOLOGY**
| Term | Description |  
| ------- | ----------- |  
| Asset | Something of value which has to be protected. The asset may be the software system itself or data used by that system. |
| Attack or Exploit | An exploitation of a system’s vulnerability. Generally, this is from outside the system and is a deliberate attempt to cause some damage. |
| Control | Protective measure reducing a system’s vulnerability. Encryption is an example of a control that reduces the vulnerability of a weak access control system. |
| Exposure | Possible loss or harm to a computing system. This can be loss or damage to data, or can be a loss of time and effort if recovery is necessary after a breach. |
| Threat | Circumstances that have potential to cause loss or harm. You can think of these as a system vulnerability that is subjected to an attack. |
| Vulnerability | A weakness in a computer system that may be exploited to cause loss or harm. |
| Risk | The likelihood that a threat agent will exploit a vulnerability. |

### **SECURITY POLICIES**
| Term | Description |  
| ------- | ----------- |  
| Acceptable Use Policy | Defines the actions users may perform while accessing systems and networking equipment |
| Security-Related Human Resource Policy | Information about technology resources, due process, due diligence |
| Password Management Policy | Specifies strong passwords rules & how frequently they are changed |
| Personally Identifiable Information (PII) | Relates to info that could be used to distinguish or trace an individual's identity |
| Disposal and Destruction Policy | Addresses the disposal of resurces that are considered confidential and equpment Covers how long records and data will be retained. |
| Classification of Information Policy | Produce a standardized framework for classifying information assets |

#### **Reasons For Policies**
* Guide Employee behavior
* Enable Accountability Measures
* Manage expectations (to an extent)
* Ensure self-regulation
* Protect information
* Protect the company

| Term | Description |  
| ------- | ----------- |  
| Physical Security | A physical object creating a barrier to unauthorized access |
| Destructive Entry | Using force to defeat physical security |
| Nondestructive Entry | Comprimises security without leaving signs of a breach |
| Host | Individual computing resource |
| Operating System (OS) | Software that manages computer hardware and services for computer programs |
| Discretionary Access Control "DAC" | Model where a user is able to grant allow/deny rights on resources they own |
| Mandatory Access Control | Model where system-enforced policies dictate user access to resources |
| Closed Policy | Users only permitted to access files if an explicit access rule is given | 
| Open Policy | Users are permitted to access files if no explicit deny rule is given |
| Biometric Identification | Uniquely identify a person based on biological or physiological traits |


#### **Host Security Importance**
* The enterprise is only as secure as its weakest link
* Host has already been trusted on certain networks
* Privileges of a host can be raised
* Typically much easier to attack the host then the network

**Why is the operating system the main focus when it comes to mapping host security issues?**
- An operating system (OS) manges a computer's resources and as such is the foal point of security (and attacks!).
- OSs are heavily instrumented to record various events and allow real-time monitoring of processes & resource consumption.

**Authentication** 
- The determination of identity, based on combination of:
    - something the person has (like a smart card or radio key fob storing secret keys)
    - something the person knows (like a password)
    - something the person is (like a human with a fingerprint)

**Biometric Identification**  
- Uniquely identify a person based on biological or physiological traits
    - Universality. Almost every person should have this trait.
    - Distinctiveness. Each person should have noticeable differences in the trait.
    - Permanence. The trait should not change significantly over time.
    - Collectability. The trait should be effectively determined adn quantifiable.

**Two Factor Authentication**
- Why is it called two-factor authentication?
    - because it uses 2 of the 3 factors we have discussed: 
        - *something you know* and 
        - *something you have*

## **MODULE 2**

### **TYPES OF ATTACKS**
| Term | Description |  
| ------- | ----------- |  
| MAC Spoofing | Attack impersonates another machine |
| ARP Spoofing | An attacker sends fake ARP (Address Resolution Protocol) messages to a local network, aiming to associate their MAC address with the IP address of another host. |
| Denial of Service Attack | Send large number of packets to host providing service |
| IP Spoofing | Is an attempt by an intruder to send packts from one IP address that appear to originate at another |
| SYN Flood | Send TCP connection requests faster than a server can process |
| TCP Session Hijacking | Using a combination of injected code and IP Spoofing this attack has a malicious client take over session. |

### **ATTACK LEVEL IN OSI MODEL**
| Layer | Description |  
| ------- | ----------- |  
| Application | - |
| Presentation | - |
| Session | - |
| Transport | TCP Hijacking <BR> Syn Flood|
| Network | DDOS <BR> IP Spoofing |
| Data Link | MAC Spoofing <BR> ARP Spoofing|
| Physical  | - | 

| Layer | Description |  
| ------- | ----------- |  
| Network Interface | Device connecting computer to a network. |  
| Logical Link Layer (LLC) | Services for flow control, Acknowledgments, and correcting physical errors |  
| Medium Access Control (MAC) | Defines the protocol for data transmission and access to the network medium |  
| A Protocol | Defines rules for communication between computers i.e. TCP/UDP|  
| TCP | Establishes 3-Way Handshake. Does not use public / private key. |  

## **MODULE 3**

| Layer | Description |  
| ------- | ----------- |  
| OSI Acranym| All (Application) <BR> People (Presentation) <BR> Seem (Session) <BR> To (Transport)  <BR> Need (Network) <BR> Data (Data Link) <BR> Processing (Physical) |
| Blacklist | A firewall rule set that allows all packets through except for those specified identified as originating from network addresses specified in a list |
| Whitelist | A firewall  rule set with a default-deny policy that rejects packets unless specifically allowed. |
| DevOPs  | Collaborative effort to improve the quality and velocity of the service life cycle |
| Cultural Priorities of DevOps | Collaborative, Transparent, Change Oriented | 
| Developers Focus On | Earlier phases of life cycles |
| Operations Focuses On | Later phases of life cycle |
| Cyber Security Is | The practice of defending and protecting data from malicious attacks |
| Network Security | Securing networks from intruders |
| Application Security | Keeping software devices free from threats |
| Information Security | Protects the integrity and privacy of data, both in storage and in transit |
| Operational Security | Handle and protect data assets; training of end-users on operating systems |
| Consider Developing A | Security life cycle model |
| Automate | Almost Everything |
| Defense in Depth | Multiple layers of security controls |
| Strong authentication | To degrade the adversaries' ability to maneuver on information networks |
| Device Hardening | Reduce internal and external attack vectors |
| Risk Management Framework (RMF) | Criteria dictates US government IT systems must be architected, secured and monitored |
| Sec in DevSecOps | Security |
| Applying User Stories is Difficult Because | - It is hard not to write them in the negative <BR> - They are hard to consider in isolation <BR> - A security user story does not directly produce business value <BR>|
| Standards & Requirements | It depends if requirements can be considered standards |
| ISF | Goals <BR> - Analysis <BR> - Research <BR> - Dissemination|
| Security Controls | Countermeasures prescribed for an information system to protect CIA |
| Certification | Independent body asserts with written assurance the product meets specific requirements |
| Differences From Other Software Engineering | - An attacker has knowledge of system weaknesses <BR> - An attacker may conceal the cause of a system failure <BR> - An attacker may want you to shut down the system <BR> - An attacker may probe controls over time to discover vulnerabilities
| Identification Requirements | If or not a system should identify its user before interacting with them |
| Authentication & Authorization Requirements | How users are identified & specifies privileges & permissions on resources |
| Use Case | Describes sequences of events between an actor and a system, yields value positively towards actor|




### **Department Of Defense (DoD) Cybersecurity Concepts**

| Term | Description |  
| ------- | ----------- |  
| Defense in Depth | Multiple layers of security controls |
| Strong Authentication | To degrade the adversaries' ability to maneuver on information networks |
| Device Hardening | Reduce internal and external attack vectors |
| Risk Management Framework (RMF) 6-Step Process | 0. Prepare <BR> 1. Categorization of information systems  <BR> 2. Selection of security controls  <BR> 3. implementation of security controls  <BR> 4. Assessment of security controls  <BR> 5. Authorization of information systems  <BR> 6. Monitoring of security controls <BR> A security user story should not be discarded. |



![Image](mod3img1.gif "Image2")

### **Types of Security Requirements**

| Term | Description |  
| ------- | ----------- |  
| Identification Requirements | Whether or not a system should identify its users before interacting with them |
| Authentication & Authorization Requirements | Authentication is how users are identified & Authorization specifies privileges & permissions on resources |
| Immunity Requirements | how a system protects itself from viruses, worms, and similar threats. |
| Integrity Requirements | How data corruption can be avoided |
| Intrusion Detection Requirements | Specify what mechanisms should be used to detect attacks |
| Non-repudiation Requirements | Specify what mechanisms should be used to detect attacks |
| Privacy Requirements | How data privacy is maintained |
| Security Auditing Requirements | How can the system be audited and checked |
| System Maintenance Security Requirements | Prevent unauthorized changes to the system (and software) intended to defat existing security mechanisms |

### **Misuse Cases**

| Term | Description |  
| ------- | ----------- | 
| Misuse Case | Instances of threats to a system |
| Interception Threats | Attacker gains access to an asset |
| Interruption Threats | Attacker makes part of a system unavailable |
| Modification Threats | A system asset if tampered with |
| Fabrication Threats | False information is added to a system |

### **ISO/IEC 2700 Security Standards**

| Term | Description |  
| ------- | ----------- | 
| ISO/IEC 2700 Security Standards | - Deals with ISMSs <BR> - Information Security Management System: <BR> - Consists of policies, procedures, guidelines, resources and activities <BR> Collectively managed by an organization to protect information assets <BR> - Based upon a risk assessment and the organization's risk acceptance levels designed to effectively treat mange risks. |
| ISMS | A systematic approach for establishing, implementing, operating, monitoring, reviewing, maintaining and improving an organization's information security to achieve business objectives|
| Requirement Standards (5.3) | Outlines mandatory criteria that must be met for compliance |
| Sector-specific Guidelines Standards <BR> Clause (5.5) | Addresses unique challenges and provides guidelines tailored for specific sectors or industries  |
| Guidelines Standards <BR> Clause (5.4) | Offers suggestions for achieving the mandatory requirements and provides guidance on the application of the standard.|
|Vocabulary Standard <BR> Clause (5.2) | Ensures clarity by defining terms used throughout the standard. |

### **Security Risk Assessment**

| Term | Description |  
| ------- | ----------- | 
| Asset Identification | Identify key system assets or services that have to be protected |
| Exposure Assessment | Assess the potential losses associated with each asset |
| Threat Identification | Identify the most probable threats to the system assets |
| Attack Assessment | Decompose threats into likely attacks on the system and ways they may occur |
| Control Identification | Propose controls that may be put in place to protect an asset |
| Feasibility Assessment | Assess the technical feasibility and cost of the controls |
