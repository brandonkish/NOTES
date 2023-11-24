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

## **MODULE 4**

### **ISO Clauses**
| Term | Description |  
| ------- | ----------- | 
|Sector-specific guidelines standards clause 5.5 | Adresses unique challenges and provides guidelines tailored for specific sectors or industries.
|Guidelines standards clause 5.4 | Offers suggestions for achieving the mandatory requirements and provides guidance on the application of the standard |
|Vocabulary standard clause 5.2 | Ensures clarity by defining gterms used through the standard |
| Requirement standards clause 5.3 | Outlines mandatory criteria that must be met for compliance. |


| Term | Description |  
| ------- | ----------- | 
|Security is not a | feature property, it is an emergent property |
|Security testing | Is trying to break the system not repair the system  <br> Find unexpected, or intentional misuses of the application <br> is a risk-based method |
| Vulnerability | A weakness in the system that can permit an attack to access the system |
| Attack| An attempt to gain un authorized accessories system information or resources |
| Exploit | Software tool/recipe for using a vulnerability to compromise the system security <BR> ** The too used to perform the hacking ** |
| Attack Pattern | describe a common sets of methods to attack msystems in a more abstract from |
| Attack Surface| Set of ways that a system can be attacked <br> ** What the hacker does to perform the attack ** |
| White Box Testing | Tester knows all information about system |
| Black Box testing | Tester only knows input or output of system |
| Grey Box testing | Tester knows some of the system but not the whole system |
| Security Testing | Use risk analysis to build tests. |
| Penetration Testing | Test software in deployed environment by attacking it |
| Equivalence Class Testing | divide input data into partitions to streamline tests, test the same thing |
| Fuzz Testing | Wel-formed inputs are randomly changed and used for testing |
| Secure testing | Doing the functionallity testing <br> Looking for injections of flaws overflows <br> used to break the code not repair. <br> Security defects and vulnerabilities aren't related to security functionality. <br> Find unexpected or untentional misuses of the application|
| Functional testing | Going to see when the program actually runs <BR> Used to repair |

![Image](mod4img1.gif "Image1")

| Term | Description |  
| ------- | ----------- | 
| Pen Testing | breaking into the system (With permission) to uncover security weaknesses <br> Not risk analysis based |
| Experience Testing | ad hock method of testing based on the testers experience. <br> kind of like guessing |
| Static Analysis | Analyzing the code without actually running the code <br> tests your codes through scanning <br> Quality of code is increased <br> finding errors earlier reducing cost <br> does not need to be complete and does not need to be executable. |
| Shift Left | The practice of integrating testing activities earlier in the SDLC <br> Early detection, improved quality and cost efficiency.|
|SAST| Static analysis for security testing |
| What is Sound | logical |
| Dynamic Analysis | Analysis on complete compiled executable code |
| Penetration Testing | Looking for security faults by breaking into the system with malignant intent (Playing hacker) |
|Experience Testing | ad hoc method of testing based on the testers experience (Guessing) |

| Term | Description |  
| ------- | ----------- |
|Manual Code Analysis | Reviewer walks through each ine of code manually. |
|Static Code Analysis | Done without executing the code |
|Dynamic Code Analysis | done while program is executing |
|False Negative | The program contains bus that the tool / process doesn't report  <br> contains a bug that it does not report |
| false positive | Tool / process reports bug that the program doesn't really contain <br> there but doesn't report it |
| A tool is sound if | for  a given set of assumptions, it produces no false negatives. |
| A Code Review | A specialized task to assess code base for security related weaknesses |


### **Static Code Analysis**

| Term | Description |  
| ------- | ----------- |
|Advantage| No requirements of executing target programs |
|Advantage| Sound to describe properties of programs
|Advantage| easily integrated into the whole software development cycle |
|Advantage| faster than manual code analysis |
|Advantage| Can out perform automated analysis tools for security if done correctly |
|Disadvantage | not enough precise enough to describe program properties |
|Disadvantage |  high false positive |
|Disadvantage |  need human to verify the results and cannot be entirely automatic |
|Disadvantage | most methods depend on source code |
|Disadvantage |  unable to detect design bugs and vulnerabilities cause by configurations or environment. |
||Disadvantage | find bugs based on the rule set of the tool. i.e. the tool will have a predefined set of vulnerabilities scan for . (Leads to blind spots.)

### **Manual Code Analysis**
| Term | Description |  
| ------- | ----------- |
| Advantage | Can outperform automated analysis tools for security if done correctly
| Advantage | no false positive |
| Disadvantage | can be time consuming, more than 10k-15k LoC can be analyzed |
| Disadvantage | Typically requires an expert to audit the code. |
| Disadvantage | Unable to detect design bugs and vulnerabilites cause by configurations or environment |

### **Dynamic Code Analysis**

| Term | Description |  
| ------- | ----------- |
| Advantage | vulnerability discovery equal to vulnerability exploit |
| Advantage | No requirements of executing target programs |
| Disadvantage | code base has to be abe to compile and execute to scan effectively. |
| Disadvantage | May do harm to the system being tested due to code has to be in the execution phase |

![Image](mod4img2.gif "Image2")
| Term | Description |  
| ------- | ----------- |
| Formal | A heavy process review with multiple participant meeting together in single room. a "moderator" and keeps everyone on task, controls the pace and acts as arbiter of disputes. Everyone reads through the material beforehand to properly prepare |
|Over-The-Shoulder | A reviewer standing over the author's workstation while the author walks the reviewer through a  set of code changes. Typically the author "drives" the review by sitting at the keyboard and mouse, opening various files. pointing out the changes, and explaining why it was done this way.
|Email Pass-Around | Whole files or changes are packaged up by the author and set to reviewers via e-mail. reviewers examine the files, ask questions and discuss with the author and other developers, and suggest changes.
|Pair Programming| Two developers writing cod at a single workstation with only one developer typing at a time and continuous free-form discussion and review. |
|Tool Assisted | A process where specialized tools are used in all aspects of the review; collecting files, transmitting and displaying giles, commentary and defects among all participants collecting metrics and giving product managers and administrators some control over the workflow. 

## **MODULE 5**

| Term | Description |  
| ------- | ----------- |
| Manual Code Analysis | Reviwer walks through each line of code manually |
| Static Code Analysis | Done without executing the code|
| Dynamic Code Analysis | Done while program is executing|


| Term | Description |  
| ------- | ----------- |
| Compiler | Translates source code to object code native to the CPU type |
| Linker | Creates the executeable bundle |
| The loader | Loads executeable bundle into memory and resolve the logical ref into concrete memory addresses |
| Kernal |Core component of the OS, Handing the management of low-level hardware resources | 
| System Calls | Functions use dby a progam to request services from the operating system's kernel |
| Library | Allows applications to use a predefined series of APIs that define the functions for communicating with the kernel |
| Process |An instance of a program that is currently executing |
| The Program Code Section | Stores executeable program instructions of execution by the CPU|
| Program data section |Stores program variables that aren't local to functions|
| Program Stack Section| Stores currently executing functions, and keeps track of the chain of function calls|
| Vigilance | Required for the Operating System Monitoring|
| Dynamic Analysis of Programs | Monitored execution of a program in order to perform analysis |
|Kernel Definition| The core component of the OS, handling the management of low-level hardware resources, including memory, processors, and input/output (I/O) devices, such as a keyboard, mouse, or video display. <BR> <BR> Most OSs define the tasks associated with the kernel in terms of a layer metoaphor, with the hardware components, such as the CPU, memory and input/output devices being on the bottom, and the users and applications being on the top.|


### **Dynamic Code Analysis**

| Term | Description |  
| ------- | ----------- |
| Dynamic Analysis of Programs | Monitored execution of a program in order to perform analysis <BR> Often comes after static analysis is complete or to complement static analysis activities |
| Positives | Efficient way to determine program functionality, i.e. File activity, process creation, etc. |
| Drawbacks | Not all functional paths maybe be explored |
| Techniques | Debuggers <BR> Runtime analyzers <BR>  Trace Programs <BR>  String analyzers <BR> Advanced tools |

| Term | Description |  
| ------- | ----------- |
| Debuggers | Software tools used by programmers to test and debug code. they allow the execution of a program to be started, paused, and stopped, and they enable the programmer to inspect and potentially modify the state (e.g. the values of variables) at various points during execution. Debuggers often provide functionality to set breakpoints and step through code line by line.|
|Runtime Analyzers and Trace Programs | Used to observe the behavior of a program while it's running, often for the purpose of finding errors, monitoring system calls, or profiling resource usage like CPU and memory. These tools can help identify performance bottlenecks, memory leaks, and other inefficiencies. |
| String Analyzer | Can help identify security vulnerabilities, such as format string vulnerabilities, improper input validation, and potential buffer overflows. Can analyze string to detect patterns indicative of malware, such as common obfuscation techniques. |
|Call Graphs and Profilers| call graphs are visual or textual representations of calling relationships between functions in a program, showing which functions call which other functions. Profilers, on the other hand, help you determine the computational footprint of a module of executable code. | 
| Injection Attacks | Most common and mos successful types of attacks |
| Defend against injection attacks |  sanitize data, sandbox, execution environment |
| Data Injection | Malicious data intended to circumvent parsers |
| Command Injection | Attempt to run processes from existing program through injected command input |
| Sanitizing Data | Clean and filter user input, prevent potentially harmful code from executing |
| Sandboxing | allow code to run in a isolated environment where it can be tested |
| SQL Injection | malicious SQL statements are inserted into an entry field for execution. |
| Buffer Overflow Attack |Overwrite memory with malicious code and then forcing a jump to that  ode by overwriting the next instruction pointer |
|Types Of Buffer Overflows | Stack <BR> Heap |
|Counters to Buffer Overflow | Stack Canaries, non-executable memory, compiler-based techniques |
| Canary | Placed in the stack prior to the return address, so that any attempt to overwrite the return address overwrites the Canary |


### **Buffer Overflow Mitigation Strategies**

| Term | Description |  
| ------- | ----------- |
| Canaries | A canary is a known value placed on the stack between local variables and control information like return address and frame pointers. When a function is about to return, the canaries value is checked. If it has been altered, a buffer overflow is suspected, and the program can take action to halt execution and prevent exploitation |
| Non-Executable Stack Protection | Non-executeable stack protection is a security feature that marks the stack region of memory as non-executeable, meaning that if on overflow alters the return address to point to code within the stack, the system will not execute this code. |
| Bounds Checking | Bounds checking is the process of verifying that every memory access respects the boundaries of the memory buffer allocated. This can prevent writing data past the allocated buffer, which would otherwise lead to a buffer overflow. Bounds checking can be performed by the compiler or at runtime. |
| Memory Protection | Protection is a security feature that marks the stack region of memory as non executable memory

### **Exception Handling Best Practices**
| Term | Description |  
| ------- | ----------- |
| Use exceptions for exceptional circumstances | use if test for more frequent /expected circumstances <BR> Try/catch/finally blocks add overhead |
| Use finally to clean up resources | Don't put resource clean up in the catch or finalize |
|Resolve the problem as close to where the error occurs | Otherwise, propagate to calling routine ("Rethrow") |


## **MODULE 6**
| Term | Description |  
| ------- | ----------- |
| Canaries | A canary is a known value placed on the stack between local variables and control information like return addresses and frame pointers. When a function is about to return the canary value is checked. If it has been altered, a buffer overflow is suspected, and the program can take action to halt execution and prevent exploitation. |
| Non-Executeable Stack Protection | Non-Executeable stack protection is a security feature that marks the stack region of memory as non executeable meaning that if an overflow alters the return address to point to code withing the stack, the system will not execute this code. |
| Bounds Checking | Bounds checking is the process of verifying that every memory access respects the boundaries of the memory buffer allocated. This can prevent writing data past the allocated buffer, which would otherwise lead to a buffer overflow. Bounds checking can be performed by the compiler or at runtime.|

### **Security Design Principles**

| Term | Description |  
| ------- | ----------- |
| fail securely | Security design principle for systems <BR> when something fails, the system should place itself in a secure state. |
| Establish secure defaults | Security design principle for systems <BR> Initial configuration of a system should have highest level of security settings by default. |
| Defense in depth | Security design principle for systems <BR> Layer basic security practices to ensure overall safety of an application. |
| Avoid Security by Obscurity | Security design principle for systems <BR> Don't rely on something being hard to find as being secure. |
| Economy of mechanism | Sufficiently small and simple to be verified and implemented |
| Complete Mediation | every access to every object must be checked before allowed to access|
| Open Design | Open design allows many eyes on the software to protect it. |
| Least Common Mechanism | Minimize the amount of mechanisms common to more than one user and dependant on all other users |
| Psychological Acceptability | User interface must be easy to use so that they can perform the correct actions upon using it. |
| Fail-safe Defaults | If the system fails it is still secure. System does not completely break if something fails. |  


| Term | Description |  
| ------- | ----------- |
| Minimize the attack surface | more places to accept into the system creates greater risk of exploits <BR> More points of interaction = More difficult to defend|
| Don't Trust Services | Don't make assumptions that can impact your application's security goals. <BR> Don't make assumptions that can impact your applications security goals. |
| Keeping Security Simple | A security design that is easy to understand is usually more easily implemented.  <BR> The simpler the design of the security, the easier it is to understand and implement correctly. |
| Fix Security Issues Correctly | Address security issues properly rather than using workarounds <BR> Avoid temporary workarounds or fixing just "surface issues". Explore root cause and areas where the issues may exists even in another form.|
| Separation of Duties / Privilege | Access to objects should depend on more than one condition. <BR> Some combinations of permissions don't work well together.  <BR>  Access to objects should depend on more than one condition  <BR>  multifactor authentication  <BR> Two person rule|
| Least Privilege | User/client should only have permissions they need for what they need to do.  <BR>  Not everyone should have access to everything. Even people or accounts you might thing should have access don't always need it.  <BR> Should only have the rights necessary to complete your task.  <BR>  Default should be no access  <BR> If access is needed temporarily, then it should be change dto deny the access right after use  <BR> Recall Host security Module 2:  <BR>  - Closed vs. Open policy  <BR>  - DAC vs MAC|
| Software Architecture | Encompass set of significant decisions about the organization of a software system |
| Domain-Specific Software Architectures (DSSA) | Assembly of software components specialized for a particular type of task  <BR> Tailored to specific application domains. THey encapsulate best practices, design decisions, and structural choices that are effective for a particular type of application or industry sector. |
| Architectural Pattern | A set of architectural design decisions applicable to recurring problem.  <BR>  is a set of architectural design decisions applicable to a recurring problem. |
| Architectural Style | Expresses a fundamental structural organization schema for software systems. Expresses a fundamental structural organization schema for software systems. |
| Design Pattern | Is a catalog of low-level structural and process arrangements in code  <BR>  Is a catalog of low-level structural and process arrangements in code. |

| Term | Description |  
| ------- | ----------- |
| Authentication | People are who they say they are |
| Integrity | Can't change the data or code |
| Non-repudiation | Can't undo something that they did |
| confidentiality  | Can't look at data or information they are not allowed to look at |
| Availability  | No denial of service |
| Authorization | User able to run system at level of trust permitted |
| Defensive Programming | Assume errors will happen |
| Program by Contract | Data must be true precondition, post-condition will have a good output. <BR> Like checking for Null |
| Rework  | teardown and build back up |
| Refactor  | move low level piece around, create structural and interaction consistency  |
| Retrofit | structures are already clean so you can move forward |

### **STRIDE**

| Threat | What We Want |  
| ------- | ----------- |
| Spoofing | Authentication |
| Tampering | Integrity |
| Repudiation | Nonrepudiation |
| Information disclosure | Confidentiality |
| Denial of Service | Availability |
| Elevation of Privilege | Authorization |

| Term | Description |  
| ------- | ----------- |
| Spoofing   | Property: Authentication <BR> Definition: Impersonating someone or something else <BR> Example: Pretending to be any of mjfiindle, asu.edu, or string.dll |
| Tampering |  Property: Integrity <BR> Definition: Modifying code or data <BR> Example:  Modifying string.dll, or network packet|
| Repudiation |  Property: Non-repudiation <BR> Definition: Claiming to not have performed an action <BR> Example: "I didn't send that e-mail", "I didn't modify that file" |
| Information Disclosure |  Property: Confidentiality <BR> Definition: exposing information to someone not authorized to see it. <BR> Example:  reading source code, publishing list of customers information, doxing |
| Denial of Service |  Property: Availability <BR> Definition: degrade or deny service <BR> Example: Crash windows/website, Routing packets into a "Black Hole" |
| Elevation of privilege (EoP) |  Property: Authorization <BR> Definition: Gain unauthorized capabilities <BR> Example: Going from "guest" to "admin" |
| An architectural style | Expresses a fundamental structural organization schema for software systems |
| Microkernel | Supports systems with stable core functionality that must adapt to changing interface requirements |
| plugin | Allows a system or framework to be extended |
| blackboard | Multiple clients collaborate through shared, synchronized data access |
| pipe-and-filter | data processing can be broken down into a series of sequential steps or stages |

### **Patterns**

| Threat | What We Want |  
| ------- | ----------- |
| Distrustful Decomposition | Vulnerability: A single vulnerability exposes a large-scale exploit. e.g. elevated privileges on a single executeable <BR> Control: Isolate vulnerabilities to a subset of the system components so exploit is limited (i.e. sandboxing)|
| Privilege Separation | Vulnerability: Code requiring special privileges is often mixed with code not requiring such privileges  <BR> Control: Factor the code requiring special privileges into it own scope & separate multiple such blocks|
| Defer to Kernel  | Vulnerability: Also concerned with elevated privileges, similar to Distrustful Decomposition  <BR> Control: Our principle of using system libraries instead of using executeable shell programs to access OS features |
| Secure Logger | Vulnerability: Attackers can cover tracks or gain valuable system information from logs <BR> Control: Use encryption or an OTS secure logging facility. File permissions help but are defeatable. |
| Clear Sensitive Information | Vulnerability: Attackers may probe for sensitive info from reused resources across the system (like DB connections) <BR> Control: Part of oru larger approach to secure default state, ensuring access only for time needed, worrying about not just input validation but post-processing outflow. |
| Secure Directory | Vulnerability: Attackers may seek to modify files that a running program is using (Data at Rest -> Data in Use) <BR> Control:  Programs should use secured directories that have write permissions only by the process owner and root. |
| pathname Cononicalization | Vulnerability: Attackers may exploit soft links or aliases to files or directories (turns into secure Directory) <BR> Control: Verify absolute paths to program-sensitive data, including checking for links (use canonical paths only) |
| Input Validation |  Vulnerability: Root cause of our injection attacks <BR> Control: We have discussed many: sanitize, validation  |
| Resource Acquisition Is initialization | Vulnerability:  Attackers will seek to exploit (shared) system resources. (de)allocation of such resources (RAM, files, sockets) must be managed carefully <BR> Control: All basically suggests ensuring you have identified places in the code for managing resource life cycle. Refactor to Creational patterns to isolate this code.   |
| Single Access Point | Vulnerability: Attackers probe for multiple authentication points and possible forgotten back / open doors<BR> Control: Provide a single access point; use with Check Point and Session to manage per access authentication. |
| Check Point |  Vulnerability: Legitimate users may encounter issues with Singe Access Point and need a recovery mechanism <BR> Control: I see this pattern as motivation for encapsulating security checks in an object for Safe Zone layer.  |
| Roles |  Vulnerability: Authorization based on individual user credentials is difficult to maintain <BR> Control: Implement a consistent role-based security policy  |
| Session |  Vulnerability: Multiuser/tenant apps have different users accessing features in the same set of objects. This creates an opportunity for attackers to spy on others' data <BR> Control: Instead of discrete event tracking across users, create a distinct Session object that encapsulates an operation history for each principle.  |
| Full View with Errors |  Vulnerability: Staying with multiUser/tenant apps, do not reject operations in silence; use intention and raise alarms <BR>  Control: Apply the state pattern for intention to ensure an object is not compromised, and create visibility for other users is the system has been compromised.|
| Limited View | Vulnerability: Interfaces should only expose allowable operations <BR> Control: Use the State pattern and Roles, apply Least Privilege principle to only allow access to valid operations |
| Secure Access Layer | Vulnerability: There are many integration points for your application if you consider the operating system, other running processes, and possibly APIs/network calls. <BR> Control: Like UIs, Minimize the Attack Surface by minimizing the integration points in your code, and factor them into isolated code that can perform security checks. |
