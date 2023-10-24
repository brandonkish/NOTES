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
| Data Link <BR> (Media Layer) | Data: Frames <BR> MAC and LLC (Physical Addressing) |
| Physical <BR> (Media Layer) | Data: Bits <BR> Media, Signal, and Binary Transmission | 

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
| Term | Description |  
| ------- | ----------- |  
