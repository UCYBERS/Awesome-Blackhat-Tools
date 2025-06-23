# Europe 2022
---
📍 This document lists cybersecurity tools demonstrated during the **Black Hat Arsenal 2022** event held in **Europe**.
Tools are categorized based on their **track theme**, such as Red Teaming, OSINT, Reverse Engineering, etc.

## 📚 Table of Contents
- [Others](#others)
- [⚙️ Miscellaneous / Lab Tools](#⚙️-miscellaneous-lab-tools)
- [🌐 Web/AppSec](#🌐-webappsec)
- [🌐 Web/AppSec or Red Teaming](#🌐-webappsec-or-red-teaming)
- [🔍 OSINT](#🔍-osint)
- [🔴 Red Teaming](#🔴-red-teaming)
- [🔴 Red Teaming / AppSec](#🔴-red-teaming-appsec)
- [🔵 Blue Team & Detection](#🔵-blue-team-detection)
- [🟣 Red Teaming / Embedded](#🟣-red-teaming-embedded)
- [🧠 Reverse Engineering](#🧠-reverse-engineering)
---
## Others
<details><summary><strong>a bridge to laser beam from IR remote controller</strong></summary>

![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![michihiro imaoka](https://img.shields.io/badge/michihiro%20imaoka-informational)

🔗 **Link:** Not Available  
📝 **Description:** This summer, Michihiro Imaoka presented IR-BadUSB at the Black Hat USA 2022 Arsenal. This IR-BadUSB allows an attacker to control a BadUSB plugged into a target's PC with an infrared remote control. Since this IR-BadUSB uses a household infrared remote control, the attacker and the IR-BadUSB must be within the infrared range of this remote control. Basically, the target and the attacker must be in the same room. Therefore, various improvements have been made to extend the reach of this IR-BadUSB.
https://github.com/imaoca/irBadUSBbyButton/blob/master/irbadusb.md

This is one such attempt. This is an attempt to extend the limited range of infrared remote control units for home appliances by converting them into laser beams and irradiating them. Let us explain the method. The module that emits the laser beam has a wavelength of 940 nm, the same wavelength as the infrared ray for home appliances.
The transmitted beam from the infrared remote control for home appliances is received by an infrared receiver such as VS1838B. After adding a 38 KHz subcarrier to the received signal, the laser module is driven by a transistor or similar device.
Perhaps if IR-BadUSB is located near a window, it would be possible to control IR-BadUSB from outdoors. Even if the IR-BadUSB is not near a window, it may be possible to control other IR-BadUSBs if the IR laser beam is reflected and diffused by something inside the room. Infrared light is invisible to the human eye, so the target will not notice it. The only way to prevent this might be to close the curtains or lower the blinds.

Operating the IR-BadUSB with an infrared laser beam does not require a PC or other large device, since it is a remote control for home appliances. If you have a remote control for home appliances that you have used to operate IR-BadUSB, you can use that remote control. No separate programming is required.

</details>

<details><summary><strong>hacking tools</strong></summary>

![Category: Others](https://img.shields.io/badge/Category:%20Others-lightgrey) ![ade saputra](https://img.shields.io/badge/ade%20saputra-informational)

🔗 **Link:** [hacking tools](https://github.com/orgs/openswoole/followers)  
📝 **Description:** 1. COUNTABLE NOUN
A tool is any instrument or a simple piece of equipment that you hold in your hands and use to do a particular kind of work. For example, spades, hammers, and knives are all tools.
I find the best tool for this purpose is a pair of shears.
Synonyms: implement, device, appliance, apparatus More Synonyms of tool
2. See also the machine tool
3. COUNTABLE NOUN

You can refer to anything that you use for a particular purpose as a particular type of tool.
Writing is a good tool for discharging overwhelming feelings.
The computer has become an invaluable teaching tool.
The threat of bankruptcy is a legitimate tool to extract money from them.
Synonyms: means, the agency [old-fashioned], vehicle, medium More Synonyms of tool

</details>

---
## 🌐 Web/AppSec or Red Teaming
<details><summary><strong>AppsecStudy - open-source elearning management system for information security</strong></summary>

![Category: 🌐 Web/AppSec or Red Teaming](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec%20or%20Red%20Teaming-blue) ![Ivan Iushkevich](https://img.shields.io/badge/Ivan%20Iushkevich-informational)

🔗 **Link:** [AppsecStudy - open-source elearning management system for information security](https://github.com/zzzteph)  
📝 **Description:** AppsecStudy is an open-source platform for seminars, training, and organizing courses for practical information security for developers and IT specialists. This tool has all the built-in basic requirements needed for organizing normal and productive training.

</details>

---
## 🌐 Web/AppSec
<details><summary><strong>BlueMap</strong></summary>

![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Maor Tal](https://img.shields.io/badge/Maor%20Tal-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>c{api}tal - Learn OWASP API Security Top 10 by playing with vulnerable by design application</strong></summary>

![Category: 🌐 Web/AppSec](https://img.shields.io/badge/Category:%20🌐%20Web/AppSec-blue) ![Lior Kaplan](https://img.shields.io/badge/Lior%20Kaplan-informational) ![Ravid Mazon](https://img.shields.io/badge/Ravid%20Mazon-informational)

🔗 **Link:** Not Available  
📝 **Description:** APIs are a critical part of modern mobile, SaaS, and web applications and can be found in customer-facing, partner-facing, and internal applications.

By nature, APIs expose application logic and sensitive data, potentially leading to data breaches, account takeovers, and much more.

Because of this, APIs have increasingly become a target for attackers. Without secure APIs, organizations would face many security risks and rapid innovation would be impossible.

It is extremely important to be aware of the OWASP API top 10 risks and enforce proper API security mitigations for your APIs. Therefore, we developed c{api}tal - an Open Source API training and learning platform by Checkmarx.

c{api}tal is a built-to-be-vulnerable API application based on the OWASP top 10 API vulnerabilities. Use c{api}tal to learn, train and exploit API Security vulnerabilities within your own API Security CTF.

In DefCon30, 2022, we first introduced c{api}tal to the world by conducting an API security CTF event to allow users to learn about the API security top 10 risks and exploit them in an isolated, vulnerable platform. Now we're open sourcing it.

In this session, you will learn about:
- The OWASP API top 10 risks
- c{api}tal overview
- Demo of exploiting one of the OWASP API top 10 risks
- How to mitigate API risks to keep your APIs safe

</details>

---
## 🔴 Red Teaming
<details><summary><strong>Codecepticon - One Obfuscator to Rule Them All</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Pavel Tsakalidis](https://img.shields.io/badge/Pavel%20Tsakalidis-informational)

🔗 **Link:** Not Available  
📝 **Description:** Codecepticon is an obfuscator that works with C#, PowerShell, and VBA (macros), and has been battle-tested for the last 1.5yr against modern ERD and AV technologies with great success. It supports a variety of obfuscation techniques such as renaming classes, and functions, rewriting strings and the tool's command line arguments, and even generating "English sounding" variable names using Markov chains. Instead of targeting compiled executables/assemblies, it focuses on the source code and utilizes Roslyn for C#, PS Automation for PowerShell, and ANTLR for VBA, in order to achieve the best possible result.

</details>

<details><summary><strong>Dragnmove: Infect Shared Files In Memory for Lateral Movement</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Baris Akkaya](https://img.shields.io/badge/Baris%20Akkaya-informational)

🔗 **Link:** Not Available  
📝 **Description:** People share files with each other every day using different applications like email clients, chat applications, browsers, etc. These channels are commonly used for lateral movement usually in the context of internal phishing. Dragnmove tool provides a different approach to abuse file sharing in order to move laterally in the target environment. Dragnmove can be used to inject payloads into the files that are being sent without touching the files in the file system.

The tool works on Windows targets and can be executed as Beacon Object File (BOF) or Reflective DLL in order to work with various C2 servers. Dragnmove injects itself into the target processes that the attacker chooses and waits for the user to drag a file into this process or attach a file to it.

When a compromised user starts the sharing process, Dragnmove can modify files in memory to inject the attacker's payload into the shared files by hooking the Windows mechanisms used by actions like "drag and drop" or "attach file". This method provides a better opportunity for the attackers to get their payloads executed in the lateral targets because the files sent will be relevant to the targets' contexts. Since the context and sender are relevant, it is more possible that the target sees this file as trustable and opens it. Dragnmove can also be used in environments where the targets are working in different locations or in isolated networks (like working from home) so the usual lateral movement methods cannot be utilized.

</details>

<details><summary><strong>EmoLoad: Loading Emotet Modules without Emotet</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Oleg Boyarchuk](https://img.shields.io/badge/Oleg%20Boyarchuk-informational) ![Stefano Ortolani](https://img.shields.io/badge/Stefano%20Ortolani-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>Exegol</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Charlie Bromberg](https://img.shields.io/badge/Charlie%20Bromberg-informational) ![Mathieu Calemard du Gardin](https://img.shields.io/badge/Mathieu%20Calemard%20du%20Gardin-informational)

🔗 **Link:** Not Available  
📝 **Description:** Exegol is a free and open-source pentesting environment made for professionals. It allows pentesters to conduct their engagements in a fast, effective, secure and flexible way. Exegol is a set of pre-configured and finely tuned docker images that can be used with a user-friendly Python wrapper to deploy dedicated and disposable environments in seconds.

</details>

<details><summary><strong>Invoke-DNSteal: Exfiltrating DNS information "Like a Boss"</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Joel Gámez](https://img.shields.io/badge/Joel%20Gámez-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>JavaScript Obfuscation - It's All About the P-a-c-k-e-r-s</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Or Katz](https://img.shields.io/badge/Or%20Katz-informational)

🔗 **Link:** [JavaScript Obfuscation - It's All About the P-a-c-k-e-r-s](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Web.md)  
📝 **Description:** The usage of JavaScript obfuscation techniques have become prevalent in today's threats, from phishing pages, to Magecart, and supply chain injection to JavaScript malware droppers all use JavaScript obfuscation techniques on some level.

The usage of JavaScript obfuscation enables evasion from detection engines and poses a challenge to security professionals, as it hinders them from getting quick answers on the functionality of the examined source code.

Deobfuscation can be technically challenging (sometimes), risky (if you don't know what you are doing), and time consuming (if you are lazy, as I am). Yet, the need to find and analyze high scaled massive attacks using JavaScript obfuscation is a task I'm faced with on a daily basis.

In this arsenal showcase I will present a lazy, performance cost effective approach, focusing on the detection of JavaScript packer templates. Once combined with threat intelligence heuristics, this approach can predict the maliciousness level of JavaScript with high probability of accuracy.

In addition, the showcase will include insights based on detections of the tool that were collected from the threat landscape, including some of the challenges associated with benign websites using obfuscation.

The showcase will also suggest techniques showing how the tool obfuscation detection can also be combined with other threat intelligence signals and heuristics, that can lead to better classification of detect obfuscated code as being malicious.

</details>

<details><summary><strong>Mr.SIP: SIP-Based Audit and Attack Tool</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Ismail Melih Tas](https://img.shields.io/badge/Ismail%20Melih%20Tas-informational) ![Neslisah Topcu](https://img.shields.io/badge/Neslisah%20Topcu-informational)

🔗 **Link:** Not Available  
📝 **Description:** Mr.SIP Pro is a comprehensive attack-oriented VoIP product developed to simulate VoIP-based attacks and audit VoIP networks and applications from a security perspective. Originally it was developed to be used in academic work to support developing novel SIP-based attacks and then as an idea to convert it to a fully functional SIP-based penetration testing tool. So far Mr.SIP resulted in several academic research papers and journal articles and won first prizes in various cyber security competitions. Mr.SIP can also be used as a SIP client simulator and SIP traffic generator.

Mr.SIP Pro detects SIP components and existing users on the network, intercepts, filters, and manages call information, reports known vulnerabilities and exploits, develops various TDoS attacks, and cracks user passwords. It has many innovative and competitive features such as high-performance multi-threading, IP spoofing, intelligent SIP message generation, self-hiding, and interception capabilities. Mr.SIP also has a customizable scenario development framework for stateful attacks.

In the current state, the public version of Mr.SIP contains 3 modules; SIP-NES (network scanner), SIP-ENUM (enumerator), and SIP-DAS (DoS attack simulator). The Pro version includes 19 modules in 4 categories; Information Gathering, Vulnerability Scanning, Offensive, and Utility modules as listed below.

Information Gathering Modules: SIP-NES (network scanner), SIP-ENUM (SIP enumerator), SIP-SNIFF (SIP traffic sniffer), SIP-EAVES (call eavesdropper)

Vulnerability Scanning Modules: SIP-VSCAN (vulnerability & exploit scanner), Auto-Deep (automated scanner)

Offensive Modules: SIP-DAS (DoS attack simulator), SIP-MITM (man in the middle attacker), SIP-ASP (attack scenario player), SIP-CRACK (digest authentication cracker), SIP-SIM (signaling manipulator), SIP-FUZZ (protocol fuzzer), RTP-EAVES (media sniffer), RTP-MIM (media manipulator), RTP-Robo (robocall/SPIT attacker), RTP-DTMF (DTMF stealer)
Utility Modules: IP Spoofing Engine, Message Generator, GUI

</details>

<details><summary><strong>OMLASP - Open Machine Learning Application Security Project</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Francisco Jose Ramirez Vicente](https://img.shields.io/badge/Francisco%20Jose%20Ramirez%20Vicente-informational) ![Pablo Gonzalez Perez](https://img.shields.io/badge/Pablo%20Gonzalez%20Perez-informational)

🔗 **Link:** Not Available  
📝 **Description:** Generally, when deploying applications that use Machine Learning or Deep Learning algorithms, only security audits check for common vulnerabilities. However, these algorithms are also exposed to other vulnerabilities or weaknesses that attackers could exploit. A framework, called OMLASP - Open Machine Learning Application Security Project, is being developed to gather a list of attack and mitigation techniques for these algorithms. This Framework aims to become a standard for auditing Machine Learning algorithms and has been divided into the following two sections:

• Security: the attack surface and attack scenarios will be defined and the capabilities and goals of the attackers. The different attack and defense techniques will be described in-depth to define a methodology to perform an audit of these algorithms.

• Biases: the reasons, types, and solutions will be explained in detail to define a methodology to minimize them. This part is still under development.

</details>

<details><summary><strong>Shoggoth: Asmjit Based Polymorphic Encryptor</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Furkan Goksel](https://img.shields.io/badge/Furkan%20Goksel-informational)

🔗 **Link:** [Shoggoth: Asmjit Based Polymorphic Encryptor](https://github.com/frkngksl)  
📝 **Description:** From past to present, signature-based detection has been one of the first and most basic methods used to detect malicious files. Even today, every file written to the file system is first scanned using the signatures found in the database of security products. Therefore, when creating variants of a tool or a technique, one of the most used methods to prevent them from being captured by a single signature is Polymorphism.

While polymorphism was used for this purpose, it was embedded in the virus variant as an engine, especially in self-propagating viruses. Nowadays, polymorphism occurs in the obfuscation of a binary or a shellcode. New variants of these codes, which are produced with polymorphic encoders such as Shikata Ga Nai (SGN), make them difficult to detect with a general and single YARA rule. Shoggoth is yet another polymorphic encoder written using asmjit library.

For each encoding period of a binary, Shoggoth generates different encryption routines with different garbage instructions. After obtaining the encrypted form of the payload, the tool merges it with its decryptor stub which again contains different garbage instructions. Shoggoth uses asmjit library for assembling the process of randomly generated encryption and garbage instructions.

</details>

<details><summary><strong>ThunderCloud: Attack Cloud Without Keys!</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Shivankar Shivankar](https://img.shields.io/badge/Shivankar%20Shivankar-informational)

🔗 **Link:** [ThunderCloud: Attack Cloud Without Keys!](https://github.com/Rnalter/ThunderCloud)  
📝 **Description:** "You can't audit a cloud environment without access keys!!".

Well. That's not completely true.

There is a good number of tools that help security teams find cloud misconfiguration issues. They work inside-out way where you give read-only access tokens to the tool and the tool gives you misconfigurations.

There's no single tool that helps Red Teamers and Bug Hunters find cloud misconfiguration issues the outside-in way.

This outside-in approach can find issues like:

1. S3 directory listing due to misconfigured Cloudfront settings
2. Amazon Cognito misconfiguration to generate AWS temporary credentials
3. Public snapshots
4. Generate Account takeover Phishing links for AWS SSO
5. Leaked Keys permission enumeration
6. IAM role privilege escalation
a) From leaked keys
b) Lambda Function

This exploitation framework also helps teams within organizations to do red teaming activities or run it across the accounts to learn more about misconfigurations from AWS and how badly they can be exploited.

ThunderCloud version 2 will now support GCP and Azure exploitation. Additionally will be releasing an open source "CLOUD OFFENSIVE" gitbook along with the same

</details>

<details><summary><strong>Dirty Vanity: A New Approach to Code Injection & EDR Bypass</strong></summary>

![Category: 🔴 Red Teaming](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming-red) ![Eliran Nissan](https://img.shields.io/badge/Eliran%20Nissan-informational)

🔗 **Link:** [A New Approach to Code Injection & EDR Bypass](https://github.com/deepinstinct/Dirty-Vanity)  
📝 **Description:** "This technique challenges current injection detection and prevention means while opening a wider spectrum of attacks that challenges common concepts of EDR TTPs.This technique abuses the lesser-known forking mechanism which is built in Windows operating systems."

</details>

---
## 🔵 Blue Team & Detection
<details><summary><strong>CQSysmon Toolkit: Advanced System Monitoring Toolkit</strong></summary>

![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Paula Januszkiewicz](https://img.shields.io/badge/Paula%20Januszkiewicz-informational) ![Mike Jankowski-Lorek](https://img.shields.io/badge/Mike%20Jankowski-Lorek-informational)

🔗 **Link:** Not Available  
📝 **Description:** Our toolkit has proven to be useful in the 25000 computers environment. It relies on a free Sysmon deployment and its goal is to boost information delivered by the original tool. CQSysmon Toolkit allows you to extract information about what processes have been running in the operating system, get their hashes and submit them into Virus Total for the forensic information about the malware cases. It also allows to extract information into spreadsheet about what types of network connections have been made: what is the destination IP address, which process was responsible for it and who is the owner of IP. The toolkit also allows to extract information about the current system configuration and compare it with the other servers and much more that allows to become familiar of what is going on in your operating system. There is a special bonus tool in a toolkit that allows to bypass some parts of the Sysmon with another tool that allows to spot that situation so that everything stays in control. CQSysmon Toolkit allows you to established detailed monitoring of the situation on your servers and it is a great complement to the existing forensic tools in your organization.

</details>

<details><summary><strong>h0neytr4p - How to catch the external threat actors with an easy to configure Honeypot.</strong></summary>

![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Subhash Popuri](https://img.shields.io/badge/Subhash%20Popuri-informational)

🔗 **Link:** [h0neytr4p - How to catch the external threat actors with an easy to configure Honeypot.](https://github.com/BSidesSG/2021)  
📝 **Description:** Working for large clients, we realised that large enterprises don't have any mechanism to trap external threat actors primarily exploiting web vulnerabilities. They are still reliant on threat intel firms to block potential attacker IPs. Sure, there are honeypots but it's really hard and time taking to configure. The turnaround time for SOC teams to configure a honeypot for a recently disclosed vulnerability is very high, discouraging the use of the same. We aim to fix this by introducing a template based honeypot. Honeytrap is stateless, it understands patterns and it can be configured to catch complicated 0day or 1day vulnerability exploitation attempts within minutes. It empowers and encourages blue teams to put an active honeytrap network around the network which can be used to capture Indicators of compromise that can be used to block at the perimeter firewall. h0neytr4p comes in a light weight single binary deployment mode, takes either one or multiple templates as input and has csv output mode which can be easily piped onto custom tools. Currently, it supports HTTP and HTTPS only but the plan is to make it a unified platform that supports SSH, RDP or any other protocols spanning multiple scenarios.

</details>

<details><summary><strong>Mimicry: An Active Deception Tool</strong></summary>

![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![chaoxin wan](https://img.shields.io/badge/chaoxin%20wan-informational)

🔗 **Link:** Not Available  
📝 **Description:** In incident response scenarios, intercepting attacks or quarantining backdoors is a common response technique. The adversarial active defense will immediately make the attacker perceive that the intrusion behavior is exposed, and the attacker may try to use defense evasion to avoid subsequent detection. These defense evasion may even result in later attacks going undetected. If we mislead or deceive the attacker into the honeypot, we can better consume the attacker's time cost and gain more response time.

We invented a series of toolkits to deceive attackers during the "kill-chain" . For Example:

Exploitation:
1. We return success and mislead the attacker into the honeypot for brute-force attacks.
2. We will simulate the execution of web attack payloads to achieve the purpose of disguising the existence of vulnerabilities in the system.

Command & Control:
1. For the Webshell scenario, we will replace the Webshell with a proxy and transfer the Webshell to the honeypot. When the attacker accesses Webshell, the proxy will forward his request to the honeypot.
2. For the reverse shell, we will inject the shell process and forward the attacker's operation to the shell process in the honeypot.
3. For the backdoor, we will dump the process's memory, resources, etc., and migrate it to the honeypot to continue execution.

</details>

<details><summary><strong>Packing-Box: Playing with Executable Packing</strong></summary>

![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Alexandre D'Hondt](https://img.shields.io/badge/Alexandre%20D'Hondt-informational) ![Charles-Henry Bertrand Van Ouytsel](https://img.shields.io/badge/Charles-Henry%20Bertrand%20Van%20Ouytsel-informational) ![Axel Legay](https://img.shields.io/badge/Axel%20Legay-informational)

🔗 **Link:** [Packing-Box: Playing with Executable Packing](https://github.com/packing-box/docker-packing-box/blob/main/CITATIONS.bib)  
📝 **Description:** This Docker image is an experimental toolkit gathering detectors, packers, tools and machine learning mechanics for making datasets of packed executables and training machine learning models for the static detection of packing. It aims to support PE, ELF and Mach-O executables and to study the best static features that can be used in learning-based static detectors.

</details>

<details><summary><strong>The Eye of Falco: You can escape but not hide</strong></summary>

![Category: 🔵 Blue Team & Detection](https://img.shields.io/badge/Category:%20🔵%20Blue%20Team%20&%20Detection-cyan) ![Stefano Chierici](https://img.shields.io/badge/Stefano%20Chierici-informational) ![Lorenzo Susini](https://img.shields.io/badge/Lorenzo%20Susini-informational)

🔗 **Link:** Not Available  
📝 **Description:** Container technologies rely on features like namespaces, cgroups, SecComp filters, and capabilities to isolate different services running on the same host. However, SPOILER ALERT: container isolation isn't bulletproof. Similar to other security environments, isolation is followed by red-teamer questions such as, "How can I de-isolate from this?"

Capabilities provide a way to isolate containers, splitting the power of the root user into multiple units. However, having lots of capabilities introduces complexity and a consequent increase of excessively misconfigured permissions and container escape exploits, as we have seen in recently discovered CVEs.

Falco is a CNCF open source container security tool designed to detect anomalous activity in your local machine, containers, and Kubernetes clusters. It taps into Linux kernel system calls and Kubernetes Audit logs to generate an event stream of all system activity. Thanks to its powerful and flexible rules language, Falco will generate security events when it finds malicious behaviors as defined by a customizable set of Falco rules.

The recent Falco update introduced the feature to keep track of all the syscalls that may modify a thread's capabilities, modifying its state accordingly, allowing Falco to monitor capabilities assigned to processes and threads. This new feature allows users to create detection over those malicious misconfigurations and automatically respond by implementing actions to address the issue

In this talk, we explain how you can use Falco to detect and monitor container escaping techniques based on capabilities. We walk through show real-world scenarios based on recent CVEs to show where Falco can help in detection and automatically respond to those behaviors

</details>

---
## 🔍 OSINT
<details><summary><strong>Defascan: Defacement Scan and Alert</strong></summary>

![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Ayush Shrestha](https://img.shields.io/badge/Ayush%20Shrestha-informational)

🔗 **Link:** Not Available  
📝 **Description:** Web server defacement is also a major problem especially for government sites. Therefore, this project intends to develop a web server defacement detection tool named DefaScan. This tool, DefaScan will detect a defaced website and notify about it.

</details>

<details><summary><strong>Scammer Detector (NFT Scam Activities Monitoring)</strong></summary>

![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Seyfullah KILIÇ](https://img.shields.io/badge/Seyfullah%20KILIÇ-informational) ![Besim ALTINOK](https://img.shields.io/badge/Besim%20ALTINOK-informational)

🔗 **Link:** Not Available  
📝 **Description:** We protect NFT users and the community from spam, scam and phishing attacks. In this context, we provide this with 4 main modules. (SpamEye, SpamPolice, ScamNotify, and BroExt)

</details>

<details><summary><strong>SCMPrey: Supply Chain Reconstruction Tool</strong></summary>

![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Moshe Zioni](https://img.shields.io/badge/Moshe%20Zioni-informational)

🔗 **Link:** Not Available  
📝 **Description:** Introducing SCMPrey, a threat intelligence tool to be used by either red or blue teams that would like to reconstruct and map-out repositories supply chain infrastructure, CI/CD system, build environment, packaged dependencies etc.

By consuming code repositories, looking for indicators of usage and propagation within the code base and the SCM system that holds the data, enacting post-processing and contextual reconstruction of the data in order to form a thorough reconstruction of the supply chain infrastracture components, configuration and automations in place.

With this knowledge - ethical hackers will be able to spot attack surface and home on designated attack targets of interest, spot weak points and low-hanging fruit; on the other - blue team will be able to spot the same weaknesses to enable them to form a solid threat model and hardening needs to fortify said infrastructure and implementations.

</details>

<details><summary><strong>shrewdeye - low hanging OSINT and reconnaissance</strong></summary>

![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Ivan Iushkevich](https://img.shields.io/badge/Ivan%20Iushkevich-informational)

🔗 **Link:** [shrewdeye - low hanging OSINT and reconnaissance](https://github.com/zzzteph)  
📝 **Description:** The vulnerability searching process requires a lot of time. If you want to cover all the perimeter in an appropriate amount of time and get valuables, automation of routines is one of the cornerstones, that will help you to focus on more complex things.
shrewdeye - opensource web platform for continuous reconnaissance. It allows you to combine other tools in chain to automate your perimeter workflow reconnaissance. It comes with built-in modules for famous tools like amass, assetfinder, subfinder, gau, nmap and others.

</details>

<details><summary><strong>TSURUGI LINUX: DFIR INVESTIGATIONS, MALWARE ANALYSIS AND OSINT ACTIVITIES MADE EASY</strong></summary>

![Category: 🔍 OSINT](https://img.shields.io/badge/Category:%20🔍%20OSINT-lightgrey) ![Giovanni Rattaro](https://img.shields.io/badge/Giovanni%20Rattaro-informational) ![Marco Giorgi](https://img.shields.io/badge/Marco%20Giorgi-informational)

🔗 **Link:** Not Available  
📝 **Description:** Any DFIR analyst knows that every day in many companies, it doesn't matter the size, it's not easy to perform forensics investigations often due to a lack of internal information (like mastery of all IT architecture, having the logs or the right one...) and ready to use DFIR tools.

As DFIR professionals we have faced these problems many times and so we decided last year to create something that can help those who will need the right tool at the "wrong time" (during a security incident).

And the answer is the Tsurugi Linux project that, of course, can be used also for educational purposes.
After more than a year since the last release, a Tsurugi Linux special BLACKHAT EDITION with this major release will be shared with the participants before the public release.

</details>

---
## ⚙️ Miscellaneous / Lab Tools
<details><summary><strong>Drone Threats and Countermeasures</strong></summary>

![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Stephen Scott](https://img.shields.io/badge/Stephen%20Scott-informational) ![Steve Wright](https://img.shields.io/badge/Steve%20Wright-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>Industrial Control Systems: Capture the Train!</strong></summary>

![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Arnaud Soullié](https://img.shields.io/badge/Arnaud%20Soullié-informational) ![Dhruv Sharan](https://img.shields.io/badge/Dhruv%20Sharan-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>Mining for Secrets: Repos, firmware, and more</strong></summary>

![Category: ⚙️ Miscellaneous / Lab Tools](https://img.shields.io/badge/Category:%20⚙️%20Miscellaneous%20/%20Lab%20Tools-gray) ![Anthony Paimany](https://img.shields.io/badge/Anthony%20Paimany-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

---
## 🔴 Red Teaming / AppSec
<details><summary><strong>Extensible Azure Security Tool</strong></summary>

![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![joosua santasalo](https://img.shields.io/badge/joosua%20santasalo-informational)

🔗 **Link:** [Extensible Azure Security Tool](https://github.com/jsa2)  
📝 **Description:** Extensible Azure Security Tool (Later referred to as E.A.S.T) is a tool for assessing Azure and to some extent Azure AD security controls. The primary use case of EAST is Security data collection for evaluation in Azure Assessments. This information (JSON content) can then be used in various reporting tools, which we use to further correlate and investigate the data.

</details>

<details><summary><strong>HazProne: Cloud Security Ed</strong></summary>

![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Staford Titus S](https://img.shields.io/badge/Staford%20Titus%20S-informational)

🔗 **Link:** Not Available  
📝 **Description:** HazProne is a Cloud Pentesting Framework that emulates close to Real-World Scenarios by deploying Vulnerable-By-Demand AWS resources enabling you to pentest Vulnerabilities within, and hence, gain a better understanding of what could go wrong and why!!

</details>

<details><summary><strong>Ipa-medit: Memory modification tool for iOS apps without Jailbreaking</strong></summary>

![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Taichi Kotake](https://img.shields.io/badge/Taichi%20Kotake-informational)

🔗 **Link:** Not Available  
📝 **Description:** Ipa-medit is a memory search and patch tool for resigned ipa without jailbreaking. It supports iOS apps running on iPhone and Apple Silicon Mac. It was created for mobile game security testing. Many mobile games have jailbreak detection, but ipa-medit does not require jailbreaking, so memory modification can be done without bypassing the jailbreak detection.

Memory modification is the easiest way to cheat in games, it is one of the items to be checked in the security test. There are also cheat tools that can be used casually like GameGem and iGameGuardian. However, there were no tools available for un-jailbroken device and CUI, Apple Silicon Mac. So I made it as a security testing tool.

I presented a memory modification tool ipa-medit which I presented at Black Hat USA 2021 Arsenal. At that time, it could only target iOS apps running on iPhone, but now it supports iOS apps running on the Apple Silicon Mac. The Apple Silicon Mac was recently released and allows you to run iOS apps on macOS. For memory modification, I'll explain how the implementation and mechanisms are different for iOS apps running on iPhone or Apple Silicon Mac.

GitHub: https://github.com/aktsk/ipa-medit

</details>

<details><summary><strong>MI-X - Am I Exploitable?</strong></summary>

![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Ofri Ouzan](https://img.shields.io/badge/Ofri%20Ouzan-informational) ![Yotam Perkal](https://img.shields.io/badge/Yotam%20Perkal-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

<details><summary><strong>Prowler v3 the handy multi-cloud security tool</strong></summary>

![Category: 🔴 Red Teaming / AppSec](https://img.shields.io/badge/Category:%20🔴%20Red%20Teaming%20/%20AppSec-red) ![Pepe Fagoaga](https://img.shields.io/badge/Pepe%20Fagoaga-informational) ![Nacho Rivera](https://img.shields.io/badge/Nacho%20Rivera-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

---
## 🟣 Red Teaming / Embedded
<details><summary><strong>Remote Assessment and Proctoring using Intelligent Devices (RAPID)</strong></summary>

![Category: 🟣 Red Teaming / Embedded](https://img.shields.io/badge/Category:%20🟣%20Red%20Teaming%20/%20Embedded-purple) ![Weihan Goh](https://img.shields.io/badge/Weihan%20Goh-informational) ![Kin Ping Tse](https://img.shields.io/badge/Kin%20Ping%20Tse-informational) ![Jasmin Yi Yap](https://img.shields.io/badge/Jasmin%20Yi%20Yap-informational) ![Jubilian Hong Yi Ho](https://img.shields.io/badge/Jubilian%20Hong%20Yi%20Ho-informational) ![Daniel Zhonghao Tan](https://img.shields.io/badge/Daniel%20Zhonghao%20Tan-informational) ![Muhamed Fauzi Bin Abbas](https://img.shields.io/badge/Muhamed%20Fauzi%20Bin%20Abbas-informational) ![Arthur Wee Yeong Loo](https://img.shields.io/badge/Arthur%20Wee%20Yeong%20Loo-informational)

🔗 **Link:** Not Available  
📝 **Description:** Many educational institutions have adopted online proctoring as a mean to conduct and ensure academic integrity during online assessments, spurred by the pandemic. Most of such remote assessment solutions are closed-source, and requires the installation of various libraries or dependencies; this introduces potential risk for students who would not be able to scrutinize, or have a say as to what is installed on their computers. Being closed source, such solutions can also be slow to react to mala fide actions to tamper and bypass measures put in place to deter cheating. In fact, one only needs to perform cursory searches online to find various ways to defeat some well-known closed-source remote assessment solutions.

To tackle the issue at hand, we introduce a proof of concept, open-source system for remote proctoring that does not require prior installation of any software or libraries. It leverages the Raspberry Pi Zero hardware that is programmed to inject fileless scripts into a Windows system to monitor surface level and internal activities during remote assessments. To deter mala fide attempts to tamper with our solution, we incorporate techniques typically used by malware and C2 infrastructure in the development of our solution, with the ultimate goal of using such techniques for good. Hence at the end of each proctoring session, our solution leaves no trace of its presence or any residue within the proctored environment.

Being a proof-of-concept, we envision extending our solution to support other popular operating systems, as well as capture and analyze more data with greater efficiency.

</details>

<details><summary><strong>RFQuack: A Versatile, Modular, RF Security Toolkit</strong></summary>

![Category: 🟣 Red Teaming / Embedded](https://img.shields.io/badge/Category:%20🟣%20Red%20Teaming%20/%20Embedded-purple) ![Federico Maggi](https://img.shields.io/badge/Federico%20Maggi-informational)

🔗 **Link:** [RFQuack: A Versatile, Modular, RF Security Toolkit](https://github.com/rfquack/RFQuack/blob/master/pyproject.toml)  
📝 **Description:** Software-defined radios (SDRs) are indispensable for signal reconnaissance and physical-layer dissection, but despite we have advanced tools like Universal Radio Hacker, SDR-based approaches require substantial effort. Contrarily, RF dongles such as the popular Yard Stick One are easy to use and guarantee a deterministic physical-layer implementation. However, they're not very flexible, as each dongle is a static hardware system with a monolithic firmware. We present RFquack, an open-source tool and library firmware that combines the flexibility of a software-based approach with the determinism and performance of embedded RF frontends. RFquack is based on a multi-radio hardware system with swappable RF frontends, and a firmware that exposes a uniform, hardware-agnostic API. RFquack focuses on a structured firmware architecture that allows high- and low-level interaction with the RF frontends. It facilitates the development of host-side scripts and firmware plug-ins, to implement efficient data-processing pipelines or interactive protocols, thanks to the multi-radio support. RFquack has an IPython shell and 9 firmware modules for: spectrum scanning, automatic carrier detection and bitrate estimation, headless operation with remote management, in-flight packet filtering and manipulation, MouseJack, and RollJam (as examples). We used RFquack in high-schools to teach digital RF protocols, to setup RF hacking contests, and to analyze industrial-grade devices and key fobs, on which we found and reported 11 vulnerabilities in their RF protocols.

</details>

---
## 🧠 Reverse Engineering
<details><summary><strong>Reversing MCU with Firmware Emulation</strong></summary>

![Category: 🧠 Reverse Engineering](https://img.shields.io/badge/Category:%20🧠%20Reverse%20Engineering-orange) ![KAI JERN LAU](https://img.shields.io/badge/KAI%20JERN%20LAU-informational) ![MuChen Su](https://img.shields.io/badge/MuChen%20Su-informational) ![Zheng Yu](https://img.shields.io/badge/Zheng%20Yu-informational) ![Anh Quynh NGUYEN](https://img.shields.io/badge/Anh%20Quynh%20NGUYEN-informational)

🔗 **Link:** Not Available  
📝 **Description:** A microcontroller unit (MCU) is a small computer on a single metal-oxide-semiconductor (MOS) integrated circuit (IC) chip. It is widely used in various types of devices, appliances, automobiles, and many more. Recently MCU security has been raised as a major concern among users and operators, as MCU vulnerabilities can be catastrophic. For this reason, it is important to audit MCU code for security issues. Unfortunately, due to the limited resources on MCU, the on-device test for MCU is not feasible. Besides, there are no emulation solutions able to provide a full instrumentation analysis platform for MCU firmware.

On the other hand, the tight coupling between MCU and hardware peripherals makes it difficult to build an MCU firmware emulator. This greatly hinders the application of dynamic analysis tools in firmware analysis, such as fuzzing.

This talk discusses how we emulated MCU emulation without real peripheral hardware. This requires to model peripheral's registers and interrupts, and implements their internal logic based on the official peripheral documentation and hardware abstraction layer (HAL). We can now emulate widely used MCU chips from top MCU vendors such as STM, Atmel, NXP, and so on. Each of them includes a diverse set of peripherals, including UART, I2C, SPI, ADC, Ethernet, SD Card, Timer, etc.

Upon our emulation, we built several analysis tools for various firmware formats, such as ELF, Binary, and Intel Hex, which are widely used in MCU libraries (RTOS, Arduino, Protocol Stack, etc). We are able to perform advanced tasks, such as:

- Instrument and hijack MCU's activities (e.g, reads and writes to peripherals).
- Save and restore current peripheral/execution states (e.g. register and interrupts).
- Supports multi-threaded firmware, such as RTOS.
- Hijack the interrupts from peripherals, so users can control the scheduling policy of multi-threaded firmware.

To demonstrate the power of our work, we will have live demos to show some exciting cases:

- Emulate MCU with external devices via SPI. UART and I2C
- Fuzz MCU firmware to find 0days with a customized AFL fuzzer.
- Password brute forcing for MCU firmware
- To solve some MCU challenges on CTFs

New code and demo will be released after the talk.

</details>

<details><summary><strong>Unravelling the Mysteries of Shellcode with SHAREM: A Novel Emulator and Disassembler for Shellcode</strong></summary>

![Category: 🧠 Reverse Engineering](https://img.shields.io/badge/Category:%20🧠%20Reverse%20Engineering-orange) ![Bramwell Brizendine](https://img.shields.io/badge/Bramwell%20Brizendine-informational) ![Jake Hince](https://img.shields.io/badge/Jake%20Hince-informational) ![Shelby VandenHoek](https://img.shields.io/badge/Shelby%20VandenHoek-informational)

🔗 **Link:** Not Available  
📝 **Description:** None

</details>

---
