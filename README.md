# <a name="mbc"></a>Malware Behavior Catalog #
The Malware Behavior Catalog (MBC) is a catalog of malware objectives and behaviors, created to support malware analysis-oriented use cases, such as labeling, similarity analysis, and standardized reporting. Please see the [FAQ](https://github.com/MBCProject/mbc-markdown/blob/master/yfaq/README.md) page for answers to common questions.

Check out the [MBC presentation](https://www.youtube.com/watch?v=KY8Ty-0sdVU) given at BSides DC (October 2019).

To join the **MBC mailing list**, please send a request to mbc@mitre.org.

### MBC-core is a reduced set of objectives and behaviors ###
MBC-core contain objectives and behaviors not captured in ATT&CK and those defined in ATT&CK that have been enhanced with malware-specific content. ###

#### <a name="ids"></a>Identifiers ####
The first letter of a behavior identifier indicates whether the behavior enhances an ATT&CK technique with malware-specific details ("E"; e.g. E1234) or whether it is a newly defined behavior in MBC ("M"; e.g. M1234). When two or more MBC behaviors refine the same ATT&CK technique, each is given an MBC identifier and each references the ATT&CK identifier. When a new ATT&CK technique is defined *after* an MBC behavior has been defined, the preexisting MBC identifier is preserved and the new ATT&CK identifier is referenced. 

## Malware Objective Descriptions ##
Malware objectives are defined below. Only those in MBC-core are included. Follow the links to view associated behaviors.

|**Objective**|**Description**|
|------------------------------------------------------------------|----------------------------|
|[**Anti-Behavioral Analysis**](https://github.com/MBCProject/mbc-markdown/blob/master/anti-behavioral-analysis/README.md) |Malware aims to prevent, obstruct, or evade behavioral analysis done in a sandbox, debugger, etc.|
|[**Anti-Static Analysis**](https://github.com/MBCProject/mbc-markdown/blob/master/anti-static-analysis/README.md)| Malware aims to prevent static analysis or make it more difficult. Simpler static analysis identifies features such as embedded strings, executable header information, hash values, and file metadata. More involved static analysis involves the disassembly of the binary code.|
|[**Command and Control**](https://github.com/MBCProject/mbc-markdown/blob/master/command-and-control/README.md) |Malware aims to communicate (receive and/or execute remotely submitted commands) with controlling or controlled systems within a target network (C2 servers, bots, etc.).|
|[**Credential Access**](https://github.com/MBCProject/mbc-markdown/blob/master/credential-access/README.md)|Malware aims to obtain credential access, allowing it or its underlying threat actor to assume control of an account, with the associated system and network permissions.|
|[**Defense Evasion**](https://github.com/MBCProject/mbc-markdown/blob/master/defense-evasion/README.md)|Malware aims to evade detection or avoid other cybersecurity defenses.|
|[**Discovery**](https://github.com/MBCProject/mbc-markdown/blob/master/discovery/README.md)|Malware aims to gain knowledge about the system and internal network.|
|[**Execution**](https://github.com/MBCProject/mbc-markdown/blob/master/execution/README.md)| Malware aims to execute its code on a system to achieve a variety of goals.|
|[**Exfiltration**](https://github.com/MBCProject/mbc-markdown/blob/master/exfiltration/README.md)|  Malware aims to steal data from the system on which it executes. This includes stored data (e.g., files) as well as data input into applications (e.g., web browser).|
|[**Impact**](https://github.com/MBCProject/mbc-markdown/blob/master/impact/README.md)| Malware aims to achieve its mission of manipulating, interrupting, or destroying systems and data.|
|[**Lateral Movement**](https://github.com/MBCProject/mbc-markdown/blob/master/lateral-movement/README.md)|Malware aims to propagate through the infection of a system or is able to infect a file after executing on a system. The malware may infect actively (e.g., gain access to a machine directly) or passively (e.g., send malicious email).|
|[**Persistence**](https://github.com/MBCProject/mbc-markdown/blob/master/persistence/README.md)|Malware aims to remain on a system regardless of system events.|
|[**Privilege Escalation**](https://github.com/MBCProject/mbc-markdown/blob/master/privilege-escalation/README.md)|Malware aims to obtain a higher level of privilege for execution.|

