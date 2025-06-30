# Asia 2025
---
📍 This document lists cybersecurity tools demonstrated during the **Black Hat Arsenal 2025** event held in **Asia**.
Tools are categorized based on their **track theme**, such as Red Teaming, OSINT & Recon, Exploit Development, etc.

## 📚 Table of Contents
- [🔴 Red Teaming](#-red-teaming)
- [🔵 Blue Teaming](#-blue-teaming)
- [🔍 OSINT & Recon](#-osint--recon)
- [⚙️ Exploit Development](#%EF%B8%8F-exploit-development)
- [🧪 Malware Analysis](#-malware-analysis)
- [🛠️ DFIR & Forensics](#%EF%B8%8F-dfir--forensics)
- [🧠 Threat Intelligence](#-threat-intelligence)
- [🕹️ ICS / IoT / SCADA](#%EF%B8%8F-ics--iot--scada)
- [🔐 Application Security (AppSec)](#-application-security-appsec)
---
## 🔴 Red Teaming
- <details><summary><strong>.NET Unpacking: When Frida Gets the JIT out of It</strong></summary>

  ![Category: 🧠 Reverse Engineering](https://img.shields.io/badge/Category:%20🧠%20Reverse%20Engineering-orange) ![Yohann Sillam](https://img.shields.io/badge/Yohann%20Sillam-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Revela: Unlock the Secrets of Move Smart Contracts</strong></summary>

  ![Category: 🧠 Reverse Engineering](https://img.shields.io/badge/Category:%20🧠%20Reverse%20Engineering-orange) ![Quynh Nguyen](https://img.shields.io/badge/Quynh%20Nguyen-informational) ![Van Hoa Nguyen](https://img.shields.io/badge/Van%20Hoa%20Nguyen-informational) ![Thanh Nguyen](https://img.shields.io/badge/Thanh%20Nguyen-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Powered by the secure and robust Move language, emerging blockchains like Aptos and Sui are gaining rapid popularity. However, their increasingly complex smart contracts, which are often entrusted with valuable assets, need to provide users with the ability to verify the code safety. Unfortunately, it has become common for Move-based protocols to be deployed solely in low-level bytecode form, without accompanying source code. Therefore, reconstructing the original source of the on-chain contracts is essential for users and security researchers to thoroughly examine, evaluate and enhance security.


  This talk introduces Revela, the first-ever open-source tool designed to decompile Move bytecode back to its original source code, empowering users and researchers with newfound transparency. We will explain how our tool leverages advanced static analysis techniques to recover the original source code structure, including modules, functions, and data types.


  The presentation will include some live demonstrations of using Revela to decompile Move bytecode from online transactions. Additionally, we will showcase how our decompiler can be utilized to uncover vulnerabilities in closed-source protocols running on Aptos and Sui blockchains.

</details>

---
## 🔵 Blue Teaming
- <details><summary><strong>AceTheGame</strong></summary>

  ![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![Nicholas Andreas](https://img.shields.io/badge/Nicholas%20Andreas-informational) ![Jeffrey Jingga](https://img.shields.io/badge/Jeffrey%20Jingga-informational) ![Valencia Violin](https://img.shields.io/badge/Valencia%20Violin-informational) ![Yohan Muliono](https://img.shields.io/badge/Yohan%20Muliono-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>APKDeepLens - Android security insights in full spectrum.</strong></summary>

  ![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![Deepanshu Gajbhiye](https://img.shields.io/badge/Deepanshu%20Gajbhiye-informational) ![Atul Singh](https://img.shields.io/badge/Atul%20Singh-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** APKDeepLens is an open-source Python tool for Android app security analysis. It leverages both static and dynamic analysis techniques to identify vulnerabilities. By static analysis examines APK components like permissions and API calls, while dynamic analysis observes real-time behavior. A key feature is "Contextual Vulnerability Mapping," which assesses vulnerabilities within the code and user flow context. The tool also focuses on extracting sensitive information from the source code, highlighting often overlooked security gaps.

  The tool effectively detects vulnerabilities listed in the OWASP Top 10 mobile, emphasizing the most critical security risks to Android applications. Demonstrations of these features will be included. APKDeepLens is equipped to generate comprehensive reports in various formats like HTML, PDF, and JSON, aiding in the transition from detection to remediation.

</details>

- <details><summary><strong>Efidrill ——Automated Hunting UEFI Firmware Vulnerability through Data-Flow Analysis</strong></summary>

  ![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![Xuxiang Yang](https://img.shields.io/badge/Xuxiang%20Yang-informational) ![QingZhe Jiang](https://img.shields.io/badge/QingZhe%20Jiang-informational) ![WeiXiao Ji](https://img.shields.io/badge/WeiXiao%20Ji-informational) ![ZhaoXing Sun](https://img.shields.io/badge/ZhaoXing%20Sun-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** UEFI, an early stage in the computer booting process, is susceptible to attacks that disrupt the Secure Boot security mechanism , thereby allowing attackers to inject a type of malicious software known as "UEFI Rootkit." This specialized strain of malware adeptly conceals itself within SMM or BootLoader, granting malevolent actors surreptitious control over a victim's computer for a prolonged period.
  Amidst ongoing research into UEFI security, researchers have discovered numerous SMM vulnerabilities, enhancing the robustness of UEFI. Remarkably, the emergence of tools like "efiexplorer" has significantlystreamlined the reverse engineering process for UEFI firmware.
  Yet, contentment with the status quo proves untenable. Many latent UEFI vulnerabilities evade conventional detection techniques, with existing UEFI vulnerability detection tools primarily relying on fuzz testing or assembly instruction matching. Regrettably, no publicly available tool exists that can automatically detect and discover UEFI security vulnerabilities through data flow tracking analysis.
  Efidrill - The First Open-Source IDA Plugin for Data Flow Analysis of UEFI Firmware.
  Efidrill is a tool that enables data flow tracing, taint tracking, automated structure analysis, variable numerical prediction, and automated vulnerability detection for UEFI firmware. It has discovered multiple hitherto unreported vulnerabilities on hardware platforms from eminent vendors such as Asus, Intel, Dell, etc.

</details>

- <details><summary><strong>MORF - Mobile Reconnaissance Framework</strong></summary>

  ![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![Amrudesh Balakrishnan](https://img.shields.io/badge/Amrudesh%20Balakrishnan-informational) ![Abhishek JM](https://img.shields.io/badge/Abhishek%20JM-informational) ![Himanshu Das](https://img.shields.io/badge/Himanshu%20Das-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** MORF - Mobile Reconnaissance Framework is a powerful, lightweight, and platform-independent offensive mobile security tool designed to help hackers and developers identify and address sensitive information within mobile applications. It is like a Swiss army knife for mobile application security, as it uses heuristics-based techniques to search through the codebase, creating a comprehensive repository of sensitive information it finds. This makes it easy to identify and address any potentially sensitive data leak.

  One of the prominent features of MORF is its ability to automatically detect and extract sensitive information from various sources, including source code, resource files, and native libraries. It also collects a large amount of metadata from the application, which can be used to create data science models that can predict and detect potential security threats. MORF also looks into all previous versions of the application, bringing transparency to the security posture of the application.

  The tool boasts a user-friendly interface and an easy-to-use reporting system that makes it simple for hackers and security professionals to review and address any identified issues. With MORF, you can know that your mobile application's security is in good hands.

  Overall, MORF is a Swiss army knife for offensive mobile application security, as it saves a lot of time, increases efficiency, enables a data-driven approach, allows for transparency in the security posture of the application by looking into all previous versions, and minimizes the risk of data breaches related to sensitive information, all this by using heuristics-based techniques.

</details>

- <details><summary><strong>PMDET, a new fuzzing-based detection tool for Android Parcel Mismatch bugs</strong></summary>

  ![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![Zhanyun Fan](https://img.shields.io/badge/Zhanyun%20Fan-informational) ![Qidan He](https://img.shields.io/badge/Qidan%20He-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Android has designed Parcel as its high-performance transport to pass objects across processes.
  For classes to be serialized by Parcel, developers must implement the methods for writing and reading the object's properties to and from a Parcel container. The inconsistency between those methods implemented by careless developers introduces Parcel Mismatch bugs, often occurring in vendor-customed classes due to lack of public scrutiny.
  Parcel Mismatch bugs can be abused by malicious applications to gain system privilege and have been massively exploited in the wild. However, due to the nature of those bugs, it cannot be solved by traditional source-to-sink taint analysis, currently no mature solutions exist to detect Parcel Mismatch bugs.
  Here we proposes PMdet, a new fuzzing-based detection tool for Parcel Mismatch bugs.
  PMdet is capable of handling different vendors' firmware without actual devices. It loads Parcelable classes from Android firmware, emulates the Android runtime environment for Parcel to work, and fuzz & monitors the serialization and deserialization procedures for mismatches.
  We evaluate PMdet with several firmware from different Android vendors, and the results show that PMdet can detect Parcel Mismatch bugs of different causes, including 11 unique undisclosed mismatches, 6 of which are exploitable, and other 5 bugs that have been already confirmed and fixed.

</details>

---
## 🔍 OSINT & Recon
- <details><summary><strong>AI VPN: A Free-Software AI-Powered Network Forensics Tool</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Veronica Valeros](https://img.shields.io/badge/Veronica%20Valeros-informational) ![Sebastian Garcia](https://img.shields.io/badge/Sebastian%20Garcia-informational)

  🔗 **Link:** [AI VPN: A Free-Software AI-Powered Network Forensics Tool](https://github.com/watson/34c3/blob/master/schedule.xml)  
  📝 **Description:** The AI VPN is an AI-based traffic analysis tool to detect and block threats, ensuring enhanced privacy protection automatically. It offers modular management of VPN accounts, automated network traffic analysis, and incident reporting. Using the free software IDS system Slips, the AI VPN employs machine learning and threat intelligence for comprehensive traffic analysis. Multiple VPN technologies, such as OpenVPN and Wireguard, are supported, and in-line blocking technologies like Pi-hole provide additional protection.

  Developed to assist journalists, activists, and NGOs in combating targeted digital attacks, the AI VPN aims to deliver a user-friendly, efficient, and automated solution for network forensics on devices without requiring physical access. Users experience seamless Internet connectivity, akin to conventional VPNs, while the AI VPN server conducts traffic analysis and reporting.

  The AI VPN is designed as a modular collection of micro-services using Docker technology. Ten modules currently handle diverse functionalities such as management, database operations, communication, multiple VPNs, PiHole integration, Slips, and comprehensive reporting.

</details>

- <details><summary><strong>Catching adversaries on Azure - Deception on Cloud</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Subhash Popuri](https://img.shields.io/badge/Subhash%20Popuri-informational)

  🔗 **Link:** [Catching adversaries on Azure - Deception on Cloud](https://gist.github.com/Lysak/a0ca30a3e6732d39199b27c170a8cd28)  
  📝 **Description:** Cloud is a widely adopted technology for organizations across the globe. It's very often a breeding ground for adversaries as the targets are now reachable to adversaries from anywhere in the world. More often than not, foothold into cloud is just a simple "password-spray" away. How to catch adversaries who are eyeing your crown jewels on cloud? Often adversaries are after your keys, secrets, data, emails, etc. A great way to protect is to put traps everywhere and wait for adversaries to fall into them. But deception on cloud is Hard to create, maintain, monitor, remove and most of all it's pricy. Cloud-Deception is a tool that intends to make it easier for individuals and organizations to deploy, monitor, maintain and remove deception with the most minimal price tag to it. This is done with the help of a CLI suite that creates real-like users (with known weak passwords), real-like resources (such as key vaults, storage accounts, etc.) and real-like identities (Managed identities). All these resources and identities have role assignments randomly assigned and the output is a glorious attack path that's very lucrative for an adversary to pursue. Cloud-deception enables logging automatically and creates alert rules so all you have to do relax and wait for adversaries. Cloud-deception currently supports Microsoft Azure. The talk will consist of a breath-taking tale of how to creation & monitoring of deception on cloud.

</details>

- <details><summary><strong>Connect to any device from anywhere with ZERO OPEN NETWORK PORTS</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Colin Constable](https://img.shields.io/badge/Colin%20Constable-informational)

  🔗 **Link:** [Connect to any device from anywhere with ZERO OPEN NETWORK PORTS](https://github.com/HazyResearch/smoothie/blob/main/tutorials/tutorial.ipynb)  
  📝 **Description:** Imagine connecting to a device remotely from anywhere on the planet without having to open any network ports on either end - that translates to having ZERO NETWORK ATTACK SURFACES.

  This is made possible with Atsign's open source No Ports Product suite which is build on the patented Networking 2.0 technology.

</details>

- <details><summary><strong>Deceptively Adaptive Honey Net (dahn)</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![George Chen](https://img.shields.io/badge/George%20Chen-informational) ![Chee Peng Tan](https://img.shields.io/badge/Chee%20Peng%20Tan-informational) ![Ri-Sheng Tan](https://img.shields.io/badge/Ri-Sheng%20Tan-informational)

  🔗 **Link:** [Deceptively Adaptive Honey Net (dahn)](https://github.com/nikhil130yadav/k-means-cluster-on-text-data/blob/master/output_30000words_3000Topics.txt)  
  📝 **Description:** Traditional honey nets offer static infrastructure and static responses. In DAHN, the infrastructure is abstracted, with lambda/gpt API (prompts stipulated) returning seemingly native responses to the threat actor, depending on the complexity index defined by the administrator. In other words, responses are dynamically crafted to entrap and retain threat actors, internal and external, in this environment for as long as possible, giving them a balance of false hope and realistic obstacles as they pass through our simulated layers of defense. Our AI-powered honey net mimics a given corporate environment to create a fictitious digital twin and embeds a controlled-level of simulated vulnerabilities/weaknesses to attract, distract, learn from, and attribute threat actors. The outputs are decoys, diversion, fingerprints, IoCs and IoAs, attributes, TTPs and behaviors, and used to augment threat detection and cyber defense strategies.

</details>

- <details><summary><strong>eBPFShield: Unleashing the Power of eBPF for OS Kernel Exploitation and Security.</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Sagar Bhure](https://img.shields.io/badge/Sagar%20Bhure-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Are you looking for an advanced tool that can help you detect and prevent sophisticated exploits on your systems? Look no further than eBPFShield. Let's take a technical look at some of the capabilities of this powerful technology:

  DNS monitoring feature is particularly useful for detecting DNS tunneling, a technique used by attackers to bypass network security measures. By monitoring DNS queries, eBPFShield can help detect and block these attempts before any damage is done.

  IP-Intelligence feature allows you to monitor outbound connections and check them against threat intelligence lists. This helps prevent command-and-control (C2) communications, a common tactic used by attackers to control compromised systems. By blocking outbound connections to known C2 destinations, eBPFShield can prevent attackers from exfiltrating sensitive data or delivering additional payloads to your system.

  eBPFShield Machine Learning feature, you can develop and run advanced machine learning algorithms entirely in eBPF. We demonstrate a flow-based network intrusion detection system(IDS) based on machine learning entirely in eBPF. Our solution uses a decision tree and decides for each packet whether it is malicious or not, considering the entire previous context of the network flow.

  eBPFShield Forensics helps address Linux security issues by analyzing system calls and kernel events to detect possible code injection into another process. It can also help identify malicious files and processes that may have been introduced to your system, allowing you to remediate any security issues quickly and effectively.

  During the session, we'll delve deeper into these features and demonstrate how eBPFShield can help you protect your systems against even the most advanced threats.

</details>

- <details><summary><strong>ELFieScanner: Advanced process memory threat detection on Linux</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Daniel Jary](https://img.shields.io/badge/Daniel%20Jary-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** ELFieScanner looks to address the relative scarcity and immaturity of non-invasive portable in-memory malware scanning capabilities on Linux. It provides detections with greater context and thus value to the investigative capabilities of blue teams.

  ELFieScanner inspects live process memory to detect a number of malicious techniques used by threat actors and in particular those which have been incorporated into Linux based user-mode rootkits. ELFieScanner inspects every running process (both x86/x64) and its corresponding loaded shared objects (libraries) to look for evil. It then outputs resultant detection telemetry into a format that can be easily ingested into a SEIM and viewed by Threat hunters or IR consultants. It has been designed to be both low impact and portable to work across numerous Linux distributions both old and new.

  ELFieScanner uses 43 custom built and configurable memory heuristics that are constructed through live in-depth binary analysis of both the process image and a corresponding disk backed binary (if present), using this to identify malevolence. It offers four main detection capabilities that identify:
  • Shared Object injection techniques.
  • Entry point manipulation techniques.
  • Shellcode injection and Process hollowing.
  • API Hooking.

  The scanner uses a low impact technique of memory collection that doesn't require interrupts to be sent to remote processes, thereby remaining passive and overcoming ptrace() anti-debug techniques used by malware. The configurability of the binary heuristics provides Blue teams a way to tailor the sensitivity of the detections for their particular environment if used as a persistent monitoring solution; or for incident responders to amass as many suspicious events as possible in one-time collection scenarios. In addition, a portable build is also provided overcoming the unwanted and intrusive default Linux behaviour of building tools on host.

</details>

- <details><summary><strong>findmytakeover - find dangling domains in a multi cloud environment</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Aniruddha Biyani](https://img.shields.io/badge/Aniruddha%20Biyani-informational)

  🔗 **Link:** [findmytakeover - find dangling domains in a multi cloud environment](https://github.com/anirudhbiyani)  
  📝 **Description:** findmytakeover detects dangling DNS record in a multi cloud environment. It does this by scanning all the DNS zones and the infrastructure present within the configured cloud service provider either in a single account or multiple accounts and finding the DNS record for which the infrastructure behind it does not exist anymore rather than using wordlist or bruteforcing DNS servers.

</details>

- <details><summary><strong>Malicious Executions: Unmasking Container Drifts and Fileless Malware with Falco</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Stefano Chierici](https://img.shields.io/badge/Stefano%20Chierici-informational) ![Lorenzo Susini](https://img.shields.io/badge/Lorenzo%20Susini-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Containers are the most popular technology for deploying modern applications. SPOILER ALERT: bypassing well-known security controls is also popular. In this talk, we explain how to use the recent updates in Falco, a CNCF open-source container security tool, to detect drifts and fileless malware in containerized environments.

  As a best practice, containers should be considered immutable. Early this year, Falco introduced new features to detect container drift via OverlayFS, which can spot if binaries are added or modified after the container's deployment. New binaries are often a sign of an ongoing attack.

  Of course, attackers can also use more advanced evasion techniques to stay hidden. By using in-memory, fileless execution, attackers can bypass most of the security controls such as drift detection, and still reach their goals with no stress.

  To combat fileless attacks, Falco has also added memfd-based fileless execution thanks to its visibility superpowers on Linux kernel system calls. Combining Falco's existing runtime security capabilities with these two new detection layers forms the foundation of an in-depth defense strategy for cloud-native workloads.

  We will walk you through real-world scenarios based on recent threats and malware, demoing how Falco can help detect and respond to these malicious behaviors and comparing drift and fileless attack paths.

</details>

- <details><summary><strong>Malware clustering using unsupervised ML : CalMal</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Himanshu Anand](https://img.shields.io/badge/Himanshu%20Anand-informational)

  🔗 **Link:** [Malware clustering using unsupervised ML : CalMal](https://github.com/unknownhad)  
  📝 **Description:** CalMal uses unsupervised machine learning for categorising and clustering of malware based upon the behaviour of the malware.
  Currently CalMal uses data from VirusTotal .
  It provides following functionalities :
  1) Cluster different malware family.
  2) Identifying similarities with any APT malware
  3) Identify new samples.
  4) Providing visual clustering
  It can easily be extended to use data from any sandbox.

</details>

- <details><summary><strong>MITRE ATTACK FLOW Detector</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![ezzeldin tahoun](https://img.shields.io/badge/ezzeldin%20tahoun-informational) ![Lynn hamida](https://img.shields.io/badge/Lynn%20hamida-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Slips: A machine-learning based, free-software, P2P Network Intrusion Prevention System</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Alya Gomaa](https://img.shields.io/badge/Alya%20Gomaa-informational) ![Sebastian Garcia](https://img.shields.io/badge/Sebastian%20Garcia-informational)

  🔗 **Link:** [Slips: A machine-learning based, free-software, P2P Network Intrusion Prevention System](https://github.com/stratosphereips/StratosphereLinuxIPS)  
  📝 **Description:** For the last 7 years we developed Slips, a behavioral-based intrusion prevention system, and the first free-software network IDS using machine learning. Slips profiles the behavior of IP addresses and performs detections inside each time window in order to also *unblock* IPs. Slips has more than 20 modules that detect a range of attacks both to and from the protected device. It is an network EDR with the capability to also protect small networks.

  Slips consumes multiple packets and flows, exporting data to SIEMs. More importantly, Slips is the first IDS to automatically create a local P2P network of sensors, where instances share detections following a trust model resilient to adversaries..

  Slips works in several directionality modes. The user can choose to detect attacks coming *to* or going *from* these profiles, or both. This makes it easy to protect your network but also to focus on infected computers inside your network, which is a novel technique.

  Among its modules, Slips includes the download/manage of external Threat Intelligence feed (including our laboratory's own TI feed), whois/asn/geocountry enrichment, a LSTM neural net for malicious behavior detection, port scanning detection (vertical and horizontal) on flows, long connection detection, etc. The decisions to block profiles or not are based on ensembling
algorithms. The P2P module connects to other Slips to share detection alerts.

  Slips can read packets from the network, pcap, Suricata, Zeek, Argus and Nfdump, and can output alerts files and summaries. Having Zeek as a base tool, Slips can correctly build a sorted timeline of flows combining all Zeek logs. Slips can send alerts using the STIX/TAXII protocol.

  Slips web interface allows to clearly see the detections and behaviors, including threat inteligence enhancements. The interface can show multiple Slips runs, summarize whois/asn/geocountry information and much more.

</details>

- <details><summary><strong>White Phoenix: recovering files from ransomware attacks</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Asaf Hecht](https://img.shields.io/badge/Asaf%20Hecht-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>ZANSIN</strong></summary>

  ![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Yoshinori Matumoto](https://img.shields.io/badge/Yoshinori%20Matumoto-informational) ![Isao Takaesu](https://img.shields.io/badge/Isao%20Takaesu-informational) ![Shun Suzaki](https://img.shields.io/badge/Shun%20Suzaki-informational) ![Daiki Ichinose](https://img.shields.io/badge/Daiki%20Ichinose-informational) ![Takeya Yamazaki](https://img.shields.io/badge/Takeya%20Yamazaki-informational) ![Koki Watarai](https://img.shields.io/badge/Koki%20Watarai-informational) ![Masahiro Tabata](https://img.shields.io/badge/Masahiro%20Tabata-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** ZANSIN is envisioned as a GROUNDBREAKING cybersecurity training tool designed to equip users against the ever-escalating complexity of cyber threats. It achieves this by providing learners with a platform to engage in simulated cyberattack scenarios, supervised and designed by experienced pentesters. This comprehensive approach allows learners to actively apply security measures, perform system modifications, and handle incident responses to counteract the attacks. Engaging in this hands-on practice within realistic environments enhances their server security skills and provides practical experience in identifying and mitigating cybersecurity risks. ZANSIN's flexible design accommodates diverse skill levels and learning styles, making it a comprehensive and evolving platform for cybersecurity education.

</details>

---
## ⚙️ Exploit Development
- <details><summary><strong>AI Wargame (Arsenal Lab)</strong></summary>

  ![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Pedram Hayati](https://img.shields.io/badge/Pedram%20Hayati-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Catsniffer</strong></summary>

  ![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Paulino Calderon](https://img.shields.io/badge/Paulino%20Calderon-informational) ![Eduardo Contreras](https://img.shields.io/badge/Eduardo%20Contreras-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Chip In-depth Analysis - Where is the Key?</strong></summary>

  ![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Kelvin Wong](https://img.shields.io/badge/Kelvin%20Wong-informational) ![Alan Chung](https://img.shields.io/badge/Alan%20Chung-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

---
## 🧪 Malware Analysis
- <details><summary><strong>AutoFix: Automated Vulnerability Remediation Using Static Analysis and LLMs</strong></summary>

  ![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Asankhaya Sharma](https://img.shields.io/badge/Asankhaya%20Sharma-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Damn Vulnerable Browser Extension (DVBE) - Unfold the risks for your Browser Supplements</strong></summary>

  ![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Abhinav Khanna](https://img.shields.io/badge/Abhinav%20Khanna-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** In the ever expanding world of Browser Extensions, security remains a big concern. As the demand of the feature-rich extensions increases, priority is given to functionality over robustness, which makes way for vulnerabilities that can be exploited by malicious actors. The danger increases even more for organizations handling sensitive data like banking details, PII, confidential org reports etc.

  Damn Vulnerable Browser Extension (DVBE) is an open-source vulnerable browser extension, designed to shed light on the importance of writing secure browser extensions and to educate the developers and security professionals about the vulnerabilities that are found in the browser extensions, how they are found & how they impact business. This built-to-be vulnerable extension can be used to learn, train & exploit browser extension related vulnerabilities.

</details>

- <details><summary><strong>GitArmor: policy as code for your GitHub environment</strong></summary>

  ![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Davide Cioccia](https://img.shields.io/badge/Davide%20Cioccia-informational) ![Stefan Petrushevski](https://img.shields.io/badge/Stefan%20Petrushevski-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Monitoring and Detecting Leaks with GitAlerts</strong></summary>

  ![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Nikhil Mittal](https://img.shields.io/badge/Nikhil%20Mittal-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Most organisations put significant effort into maintaining their public GitHub repositories. They safeguard these repositories against various security vulnerabilities and routinely scan for sensitive information, ensuring thorough checks have been carried out before making anything public. However, an aspect that is often overlooked is the monitoring of the public activities of their organisation's users.

  Developers within organisations frequently experiment and test ideas in a public setting, which may inadvertently include sensitive code, hardcoded credentials, secrets, internal URLs, and other proprietary information. This oversight can lead to significant security risks, making it crucial for organisations to monitor such activities to prevent potential data breaches.

  Recent studies on data breaches reveal a startling trend. The leakage of secrets and sensitive information often occurs via individual repositories, rather than organisational ones. This fact underscores the importance of monitoring not just the organisation's repositories but also those created and maintained by individual users.

  This talk aims to shed light on such cases related to GitHub. We will delve into real-world examples, discuss the common pitfalls, and suggest effective strategies to guard against these potential security risks.

</details>

- <details><summary><strong>Surfactant - Modular Framework for File Information Extraction and SBOM Generation</strong></summary>

  ![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Ryan Mast](https://img.shields.io/badge/Ryan%20Mast-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Surfactant is a modular framework for extracting information from filesystems, primarily for generating an SBOM (Software Bill of Materials). The information extracted can then be used to identify the various vendors or libraries associated with a file, and establish relationships between files. The resulting SBOM can be used for system level impact analysis (such as for IoT, Smart Grid, or ICS devices) of vulnerabilities, and the information gathered can be used to help inform what files to focus on for manual analysis.

</details>

---
## 🛠️ DFIR & Forensics
- <details><summary><strong>Automated Audit Simulation</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Syed Ubaid Jafri](https://img.shields.io/badge/Syed%20Ubaid%20Jafri-informational)

  🔗 **Link:** [Automated Audit Simulation](https://github.com/Ubaidjaffery)  
  📝 **Description:** This tool enhances the efficiency of auditing processes, providing a user-friendly interface for seamless operation. Its detailed reporting capabilities empower users with comprehensive insights into endpoint security, facilitating informed decision-making. With a commitment to ethical use, legal compliance, and regular updates, the Automated Audit Simulation tool is a valuable asset for organizations seeking robust cybersecurity assessments.

  In addition to scrutinizing network connections for VPN and Tor usage, the tool searches for critical event IDs and investigates Outlook profiles for personal user accounts configured on official laptops/desktops. The flexibility to customize assessments allows users to adapt the tool to evolving security threats.

</details>

- <details><summary><strong>AWSDefenderGPT: Leveraging OpenAI to Secure AWS Cloud</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Nishant Sharma](https://img.shields.io/badge/Nishant%20Sharma-informational) ![Sherin Stephen](https://img.shields.io/badge/Sherin%20Stephen-informational) ![Rishappreet Singh Moonga](https://img.shields.io/badge/Rishappreet%20Singh%20Moonga-informational)

  🔗 **Link:** [AWSDefenderGPT: Leveraging OpenAI to Secure AWS Cloud](https://github.com/ine-labs/AWSDefenderGPT)  
  📝 **Description:** AWSDefenderGPT is an AI tool designed to identify and rectify cloud misconfigurations by using Open AI GPT models. AWSDefenderGPT can understand complex queries to detect misconfigurations in cloud environments and provide fixes for them.

  This tool merges the capabilities of automated deployment and configuration modification using AI, along with cloud SDK tools. As a result, it transforms into an AI-powered cloud manager that helps you ensure the security of the cloud environment by preventing misconfigurations. By centralizing the process, users can effortlessly address misconfigurations and excessively permissive policies in a single stage, simplifying handling of potential future threats.

</details>

- <details><summary><strong>BinderAPI Scanner & BASS</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Jeffrey Gaor](https://img.shields.io/badge/Jeffrey%20Gaor-informational) ![Valen Sai](https://img.shields.io/badge/Valen%20Sai-informational) ![Eric Tee Hock Nian](https://img.shields.io/badge/Eric%20Tee%20Hock%20Nian-informational) ![Krishnaprasad Subramaniam](https://img.shields.io/badge/Krishnaprasad%20Subramaniam-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** BASS-Environment Synopsis
Binderlabs API Security Simulator (BASS-Env) is an intentionally vulnerable API environment tailored to reflect the OWASP Top 10 API Security Risks of 2023. Its primary goal is to function as a practical training platform for cybersecurity professionals seeking to enhance their API hacking skills and deepen their understanding of API security testing. BASS-Env provides a hands-on experience by allowing users to interact directly with flawed APIs, highlighting the significance of API security within software development.
  The OpenAPI 3 Specifications and Postman Collections serve as the main interface, providing comprehensive documentation and enabling direct testing of API endpoints. At the core of BASS-Env lies its Laravel Backend/API Layer and MySQL Database, intentionally incorporating vulnerabilities across a variety of API endpoints. These components collaborate to simulate real-world scenarios, exposing vulnerabilities such as broken authentication, misconfigurations, and improper inventory management.
  Moreover, BASS-Env offers laboratory-based scenarios and challenges for participants, integrating manual and scanner testing methods. Scoring mechanisms, feedback loops, hints, and tutorials assist users in comprehending and resolving challenges. The environment prioritizes security and privacy considerations, accessible locally and supported through GitHub for community engagement. Future enhancements aim to broaden the spectrum of API flaws and facilitate effective updates for BASS-Env instances.

  BASS-Scanner Synopsis
The BASS-Scanner is a Python3-based tool designed to streamline API Security Testing, focusing on identifying vulnerabilities outlined in the OWASP Top 10 API Security Risks of 2023. It offers a quick and efficient scanning process with minimal installation requirements, making it particularly suitable for penetration testers seeking to expedite API Pentest engagements. The tool's customization options, including the ability to tailor wordlists for specific test cases to enhance detection rates.
  Key features include detection of various vulnerabilities such as broken object-level authorization, broken authentication, unrestricted resource consumption, server-side request forgery, and more. Its architecture is straightforward, leveraging Python3 and supporting REST and JSON type APIs.
  Scanning methodology involves detailed scrutiny of individual API endpoints, employing techniques like fuzzing and header analysis to uncover security flaws.
  User customization is facilitated through options such as specifying scan types and adjusting scanning parameters. Security and privacy considerations ensure that the tool does not handle sensitive information or transmit data to external sources.
  Overall, BASS-Scanner offers a promising solution for efficient and comprehensive API security assessments, with ongoing improvements slated for the future.

</details>

- <details><summary><strong>BucketLoot - An Automated S3 Bucket Inspector</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Umair Nehri](https://img.shields.io/badge/Umair%20Nehri-informational)

  🔗 **Link:** [BucketLoot - An Automated S3 Bucket Inspector](https://github.com/redhuntlabs/BucketLoot/blob/master/docs/documentation.md)  
  📝 **Description:** Thousands of S3 buckets are left exposed over the internet, making it a prime target for malicious actors who may extract sensitive information from the files in these buckets that can be associated with an individual or an organisation. There is limited research or tooling available that leverages such S3 buckets for looking up secret exposures and searching specific keywords or regular expression patterns within textual files.

  BucketLoot is an automated S3 Bucket Inspector that can simultaneously scan all the textual files present within an exposed S3 bucket from platforms such as AWS, DigitalOcean etc.

  It scans the exposed textual files for:
  - Secret Exposures
  - Assets (URLs, Domains, Subdomains)
  - Specific keywords | Regex Patterns (provided by the user)

  The end user can even search for string based keywords or provide custom regular expression patterns that can be matched with the contents of these exposed textual files.

  All of this makes BucketLoot a great recon tool for bug hunters as well as professional pentesters.

  The tool allows users to save the output in a JSON format which makes it easier to pass the results as an input to some third-party product or platform.

</details>

- <details><summary><strong>BugHog</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Gertjan Franken](https://img.shields.io/badge/Gertjan%20Franken-informational) ![Tom Van Goethem](https://img.shields.io/badge/Tom%20Van%20Goethem-informational)

  🔗 **Link:** [BugHog](https://github.com/DistriNet/BugHog)  
  📝 **Description:** BugHog is a comprehensive framework designed to identify the complete lifecycles of browser bugs, from the code change that introduced the bug to the code change that resolved the bug. For each bug's proof of concept (PoC) integrated in BugHog, the framework can perform automated and dynamic experiments using Chromium and Firefox revision binaries.

  Each experiment is performed within a dedicated Docker container, ensuring the installation of all necessary dependencies, in which BugHog downloads the appropriate browser revision binary, and instructs the browser binary to navigate to the locally hosted PoC web page. Through observation of HTTP traffic, the framework determines whether the bug is successfully reproduced. Based on experiment results, BugHog can automatically bisect the browser's revision history to identify the exact revision or narrowed revision range in which the bug was introduced or fixed.

  BugHog has already been proven to be a valuable asset in pinpointing the lifecycles of security bugs, such as Content Security Policy bugs.

</details>

- <details><summary><strong>DetectiveSQ: A Extension Auditing Framework Version 2</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Govind Krishna Lal Balaji](https://img.shields.io/badge/Govind%20Krishna%20Lal%20Balaji-informational) ![Xian Xiang Chang](https://img.shields.io/badge/Xian%20Xiang%20Chang-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** In the modern digital realm, internet browsers, particularly Chrome, have transcended traditional boundaries, becoming hubs of multifunctional extensions that offer everything from AI-integrated chatbots to sophisticated digital wallets. This surge, however, comes with an underbelly of cyber vulnerabilities. Hidden behind the guise of innovation, malicious extensions lurk, often camouflaged as benign utilities. These deceptive extensions not only infringe upon user privacy and security but also exploit users with unasked-for ads, skewed search results, and misleading links. Such underhanded strategies, targeting the unsuspecting user, have alarmingly proliferated.

  In this talk, we will introduce DetectiveSQ Version 2, an enhanced tool revolutionizing the analysis of Chrome extensions. Building on its proven foundation, it now features integrated AI and GPT models for dynamic analysis, sentiment analysis, and sophisticated static analysis capabilities for permissions, local JavaScript, and HTML files. This dual approach offers a comprehensive evaluation, pinpointing potential security and privacy risks within extensions. DetectiveSQ Version 2 will be open source and made available after the talk.

</details>

- <details><summary><strong>exploitdb-images</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Nicola d'Ambrosio](https://img.shields.io/badge/Nicola%20d'Ambrosio-informational)

  🔗 **Link:** [exploitdb-images](https://github.com/NS-unina/cve2docker)  
  📝 **Description:** ExploitDBImages aims to automate the exploiting phase of penetration testing through Docker containers. With this tool, testers can easily execute required scripts for the successful exploitation of vulnerable applications, eliminating the need for manual installation of dependencies.

</details>

- <details><summary><strong>Moonshot: A Testing Framework for Large Language Models</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Thomas Tay](https://img.shields.io/badge/Thomas%20Tay-informational) ![Seok Min Lim](https://img.shields.io/badge/Seok%20Min%20Lim-informational) ![Lionel Teo](https://img.shields.io/badge/Lionel%20Teo-informational)

  🔗 **Link:** [Moonshot: A Testing Framework for Large Language Models](https://github.com/ryanbgriffiths/IROS2023PaperList/blob/main/README.md)  
  📝 **Description:** In today's rapidly evolving AI landscape, large language models (LLMs) have emerged as a cornerstone of many AI-driven solutions, offering increasingly remarkable capabilities in use cases like chatbots and code generation.

  However, this advancement also introduces a unique set of security and safety challenges, ranging from data privacy risks, biases in model outputs, ethical implications of AI interactions, to the risks of generating and executing malicious codes when using these new AI systems. Unfortunately, current LLM testing often focuses on evaluating performance over addressing these vulnerabilities.

  We present Moonshot – a testing tookit designed specifically for security evaluators, penetration testers, red teamers, and bug-bounty hunters to conduct attacks on large language models. Moonshot distinguishes itself through its extensible and modular design, facilitating the systematic creation, testing and execution of attacks on LLMs. It comes equipped with a suite of pre-defined security vulnerabilities and safety tests, while also offering users the ease of integrating their own tests into the framework. Additionally, Moonshot features a specialised red-teaming interface that drastically streamlines the process of vulnerability assessment across various LLMs for red teamers.

  Moonshot is designed with a simple, intuitive, and interactive interface that would be familiar to AI developers and security experts. Additionally, Moonshot is engineered for easy integration into any model development workflow, enabling seamless and repeatable testing for model developers.

</details>

- <details><summary><strong>Nightingale: Docker for Pentesters</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Raja Nagori](https://img.shields.io/badge/Raja%20Nagori-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>R0fuzz</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Season Cherian](https://img.shields.io/badge/Season%20Cherian-informational) ![Vishnu Dev](https://img.shields.io/badge/Vishnu%20Dev-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Industrial control systems (ICS) are critical to national infrastructure, demanding robust security measures. "R0fuzz" is a collaborative fuzzing tool tailored for ICS environments, integrating diverse strategies to uncover vulnerabilities within key industrial protocols such as Modbus, Profinet, DNP3, OPC, BACnet, etc. This innovative approach enhances ICS resilience against emerging threats, providing a comprehensive testing framework beyond traditional fuzzing methods.

</details>

- <details><summary><strong>vet: Policy Driven vetting of Open Source Software Components</strong></summary>

  ![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Abhisek Datta](https://img.shields.io/badge/Abhisek%20Datta-informational)

  🔗 **Link:** [vet: Policy Driven vetting of Open Source Software Components](https://github.com/Liriax/AI-Talents/blob/main/linkedin.csv)  
  📝 **Description:** vet is a tool for identifying risks in open source software supply chain. It helps engineering and security teams to identify potential issues in their open source dependencies and evaluate them against codified organisational policies.

</details>

---
## 🧠 Threat Intelligence
- <details><summary><strong>BlueMap - An Interactive Tool for Azure Exploitation</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Maor Tal](https://img.shields.io/badge/Maor%20Tal-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>DarkWidow: Dropper/PostExploitation Tool (or can be used in both situations) targeting Windows.</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Soumyanil Biswas](https://img.shields.io/badge/Soumyanil%20Biswas-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>PASTEBOMB</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![MARCO LIBERALE](https://img.shields.io/badge/MARCO%20LIBERALE-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

- <details><summary><strong>Quark Script - Dig Vulnerabilities in the BlackBox</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![KunYu Chen](https://img.shields.io/badge/KunYu%20Chen-informational) ![YuShiang Dang](https://img.shields.io/badge/YuShiang%20Dang-informational) ![ShengFeng Lu](https://img.shields.io/badge/ShengFeng%20Lu-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** *Innovative & Interactive*
  The goal of Quark Script aims to provide an innovative way for mobile security researchers to analyze or pentest the targets (YES, the binaries).

  Based on Quark, we integrate decent tools as Quark Script APIs and make them exchange valuable intelligence with each other. This enables security researchers to interact with staged results and perform creative analysis with Quark Script.

  *Dynamic & Static Analysis*
  In Quark script, we integrate not only static analysis tools (e.g. Quark itself) but also dynamic analysis tools (e.g. objection).

  *Re-Usable & Sharable*
  Once the user creates a Quark script for a specific analysis scenario. The script can be used for other targets. Also, the script can be shared with other security researchers. This enables the exchange of knowledge.

</details>

- <details><summary><strong>RedCloud OS : Cloud Adversary Simulation Operating System</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Yash Bharadwaj](https://img.shields.io/badge/Yash%20Bharadwaj-informational) ![Manish Kumar Gupta](https://img.shields.io/badge/Manish%20Kumar%20Gupta-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** RedCloud OS is a Debian based Cloud Adversary Simulation Operating System for Red Teams to assess the security of leading Cloud Service Providers (CSPs). It includes tools optimised for adversary simulation tasks within Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

  Enterprises are moving / have moved to Cloud Model or Hybrid Model and since security testing is a continuous procedure, operators / engineers evaluating these environments must be well versed with updated arsenal. RedCloud OS is an platform that contains:

  - Custom Attack Scripts
  - Installed Native Cloud Provider CLI
  - 25+ Multi-Cloud Open-Source Tools
  - Tools Categorization as per MITRE ATT&CK Tactics
  - Support Multiple Authentication Mechanisms
  - In-Built PowerShell for Attacking Azure Environment
  - Ease to configure credentials of AWS, Azure & GCP & much more...

  Inside each CSP, there are three sub-categories i.e, Enumeration, Exploitation, and Post Exploitation. OS categorises tools & our custom scripts as per the above mentioned sub-categories.

</details>

- <details><summary><strong>The Go-Exploit Framework</strong></summary>

  ![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Jacob Baines](https://img.shields.io/badge/Jacob%20Baines-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

---
## 🕹️ ICS / IoT / SCADA
- <details><summary><strong>CF-Hero</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Musa Şana](https://img.shields.io/badge/Musa%20Şana-informational)

  🔗 **Link:** [CF-Hero](https://github.com/RayBB/random-stock-picker/blob/master/stocks.json)  
  📝 **Description:** All systems, apps, or tools that are internet-facing have to be deployed behind CloudFlare to increase security and stability. As a security engineer, it's experienced that some systems were/are not deployed properly behind CloudFlare. Any attacker, who discovers the system or app in this way, can hack an organisation's applications.

  This tool(CF-Hero) highlights the security risks associated with domains that are not properly configured behind Cloudflare, a content delivery network (CDN) and distributed DNS service provider. The absence of Cloudflare protection exposes these domains to various attacks, increasing the vulnerability of a company's assets.

</details>

- <details><summary><strong>CLay - Reverse Proxy for Concealing and Deceiving Website Informations</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Crisdeo Nuel Siahaan](https://img.shields.io/badge/Crisdeo%20Nuel%20Siahaan-informational) ![Erik Hendrawan Putra Wijaya](https://img.shields.io/badge/Erik%20Hendrawan%20Putra%20Wijaya-informational) ![Chrisando Ryan Pardomuan Siahaan](https://img.shields.io/badge/Chrisando%20Ryan%20Pardomuan%20Siahaan-informational) ![Yohan Muliono](https://img.shields.io/badge/Yohan%20Muliono-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** The beginning of a devastating cybersecurity incident often occurs when an attacker recognize a technology they capable to exploit used in an application. None of our users care about the technology behind an application more than the mal-intent adversaries. CLay offers a unique and powerful features that goes beyond traditional security measures. CLay takes deception to a new level by mimicking the clockwork of a website with false information, as if the website is made with different technology stack. With a quick 3-minutes installation, the primary objective is to mislead and deceive potential attackers, leading them to gather false information about the web application.

</details>

- <details><summary><strong>CloudSec Navigator</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Takuho MITSUNAGA](https://img.shields.io/badge/Takuho%20MITSUNAGA-informational) ![Koki Watarai](https://img.shields.io/badge/Koki%20Watarai-informational) ![Satoshi OKADA](https://img.shields.io/badge/Satoshi%20OKADA-informational) ![Ruka NEGISHI](https://img.shields.io/badge/Ruka%20NEGISHI-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Security incidents on cloud platforms such as AWS are occurring frequently, and many of them are caused by misconfigurations or inappropriate use of features. For the purpose of incident prevention, developers need to read a large amount of documentation, including important security guidelines and best practices. The tool uses Retrieval-Augmented Generation (RAG) and Large Language Models (LLM) vector searches to provide highly accurate, customized security advice and referenced guidelines based on the information retrieved. and best practices information. This allows developers to focus on more efficient and secure software development instead of reading large amounts of documentation.

</details>

- <details><summary><strong>Gerobug: The First Open-Source Bug Bounty Platform</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Billy Sudarsono](https://img.shields.io/badge/Billy%20Sudarsono-informational) ![Felix Alexander](https://img.shields.io/badge/Felix%20Alexander-informational) ![Jessica Geofanie Ganadhi](https://img.shields.io/badge/Jessica%20Geofanie%20Ganadhi-informational) ![Yohan Muliono](https://img.shields.io/badge/Yohan%20Muliono-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Organizations often lack the necessary resources and diverse skills to identify hidden vulnerabilities before attackers exploit them. Bug bounty program, which incentivizes ethical hackers to report bugs, emerged to bridge the skills gap and address the imbalance between attackers and defenders.

  However, integrating bug bounty program into security strategies remains challenging due to limitations in efficiency, security, budget, and the scalability of consulting-based or third-party solutions.

  Gerobug is the first open-source bug bounty platform that allows organizations to establish their own bug bounty platform easily and securely, free of charge.

</details>

- <details><summary><strong>Open-Source API Firewall: New Features & Functionalities</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Nikolay Tkachenko](https://img.shields.io/badge/Nikolay%20Tkachenko-informational)

  🔗 **Link:** [Open-Source API Firewall: New Features & Functionalities](https://github.com/newrelic/node-newrelic/blob/main/NEWS.md?plain=1)  
  📝 **Description:** The open-source API Firewall by Wallarm is designed to protect REST and GraphQL API endpoints in cloud-native environments. API Firewall provides API hardening with the use of a positive security model allowing calls that match a predefined API specification for requests and responses while rejecting everything else.

  The key features of API Firewall are:
  - Secure REST and GraphQL API endpoints by blocking non-compliant requests/responses
  - Stop API data breaches by blocking malformed API responses
  - Discover Shadow API endpoints
  - Block attempts to use request/response parameters not specified in an OpenAPI specification
  - Validate JWT access tokens
  - Validate other OAuth 2.0 tokens using introspection endpoints
  - Denylist compromised API tokens, keys, and Cookies

</details>

- <details><summary><strong>PentestMuse: The Iron Man Suit of Offensive Security Automation</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Haochen Zhang](https://img.shields.io/badge/Haochen%20Zhang-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** entestMuse is not just a tool; it is the embodiment of the Iron Man philosophy in cybersecurity. Like Tony Stark's exoskeleton, which enhances his abilities while allowing him to retain control and focus on higher-level strategies, PentestMuse augments the capabilities of offensive cybersecurity professionals. It automates the repetitive, precision-dependent tasks of penetration testing - much like the meticulous data collection and alerting in a monitoring system - allowing experts to concentrate on tasks requiring human ingenuity and judgment.

  Adhering to the [Compensatory Principle](https://www.notion.so/Compensatory-Principle-efdc076b70d84d1797ab3469a9955ba9?pvs=21), PentestMuse recognizes the distinct strengths of human intuition and machine precision. It executes complex operations autonomously, similar to a state-machine-driven repair system, but steps aside when human intervention is preferable or necessary. This approach mirrors the collaboration between Iron Man's suit and Tony Stark, where automation enhances human skills without overshadowing them.

  The design of PentestMuse ensures that the creativity and learning opportunities for cybersecurity professionals are not stifled. The tool works as a partner, handling the 'boring stuff' and late-night work, thereby enabling human experts to focus on creative problem-solving and system optimization. This collaboration is akin to Iron Man's suit: an advanced assistant that elevates the human operator to new levels of efficiency and effectiveness.

  In conclusion, PentestMuse is a testament to the power of AI in enhancing human capabilities in offensive security, rather than replacing them. It's a system more Iron Man, less Ultron - a perfect blend of human intelligence and machine efficiency, designed to tackle the ever-evolving challenges of the digital world.

</details>

- <details><summary><strong>SecDim Play SDK: Build Defensive AI and AppSec Challenges</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Pedram Hayati](https://img.shields.io/badge/Pedram%20Hayati-informational) ![Muhammad Hamza Ali](https://img.shields.io/badge/Muhammad%20Hamza%20Ali-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** In a typical CTF challenge, the objective is to identify and exploit security vulnerabilities. On the other hand, the aim of a defensive or AppSec challenge is to rectify security vulnerabilities. Historically, building defensive challenges has been challenging due to the requirement for complex tools and infrastructure to manage and review player submissions.
  In this presentation, we will introduce SecDim Play SDK: an open-source SDK designed for building defensive, AppSec, and AISec challenges. We will demonstrate how we model security attacks into software tests that can be used to assess players' security patches. In a live demo, we will explore the process of selecting real-world-inspired security vulnerabilities and transforming them into cloud-native apps with integrated security tests. Using Play SDK, we can create new challenges that focus on finding and fixing security vulnerabilities.

</details>

- <details><summary><strong>Secure Local Vault - Git Based Secret Manager</strong></summary>

  ![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Sriram Krishnan](https://img.shields.io/badge/Sriram%20Krishnan-informational) ![Shibly Meeran](https://img.shields.io/badge/Shibly%20Meeran-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** Problem Statement:
At Companies secrets are being used across various environments for integration and authentication services. However, managing the secrets and preventing incidents from leakage of secrets have been challenging for the organisation. Existing solutions are centralised and warrants considerable code change to be implemented. Following are the problem statement to be resolved:

  - To manage and secure the secrets that are currently in plain text across Git, IaC templates, and workloads.
  - To implement a secrets manager that is developer friendly and reduces operational overheads.
  - To develop a solution that does not expose the secrets even at the compromise of entities storing the credentials. For example, to protect our secrets from CodeCov like incidents.

  Solution:
  We have developed a Git based secret manager which adopts a secure and decentralised approach to managing, sharing, and storing the secrets. In this approach secrets are stored in an encrypted form in Github repositories of the teams.

  Keys Principles
  This implementation follows two important principles
  -A developer can be allowed to add or modify secrets, however should not be allowed to view them
  -An environment should have a single identity that gives access to all necessary credentials irrespective of the number of projects that are deployed.

</details>

---
## 🔐 Application Security (AppSec)
- <details><summary><strong>DefaceIntel-Visionary</strong></summary>

  ![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Ri-Sheng Tan](https://img.shields.io/badge/Ri-Sheng%20Tan-informational) ![George Chen](https://img.shields.io/badge/George%20Chen-informational) ![Chee Peng Tan](https://img.shields.io/badge/Chee%20Peng%20Tan-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** The purpose of this project is to develop a robust Web Defacement Detection tool that monitors websites for signs of defacement, an attack where the visual appearance of a website is altered by unauthorized users.

  The tool aims to promptly provide alert if a website content is manipulated, which is often a result of cyber attacks such as those carried out by hacktivists.

  The system utilizes two primary detection methods: a) analyzing drastic changes in webpage size and b) scanning for keywords and phrases associated with hacktivism, including those within images, using generative AI such as GPT that has been trained on large data including OSINT.

</details>

- <details><summary><strong>Mantis - Asset Discovery at Scale</strong></summary>

  ![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Ankur Bhargava](https://img.shields.io/badge/Ankur%20Bhargava-informational) ![Saddam Hussain](https://img.shields.io/badge/Saddam%20Hussain-informational) ![Prateek Thakare](https://img.shields.io/badge/Prateek%20Thakare-informational)

  🔗 **Link:** Not Available  
  📝 **Description:** None

</details>

---
