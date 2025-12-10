# Comprehensive Guide to Cyber Attacks

> **A detailed reference covering definitions, examples, and real-world cases from 2023–2024**

---

## Table of Contents

1. [Introduction](#1-introduction)
2. [Social Engineering Attacks](#2-social-engineering-attacks)
   - 2.1 [Phishing](#21-phishing)
   - 2.2 [Spear Phishing](#22-spear-phishing)
   - 2.3 [Whaling](#23-whaling)
   - 2.4 [Smishing](#24-smishing)
   - 2.5 [Vishing](#25-vishing)
   - 2.6 [Pretexting](#26-pretexting)
   - 2.7 [Baiting](#27-baiting)
   - 2.8 [Tailgating / Piggybacking](#28-tailgating--piggybacking)
   - 2.9 [Quid Pro Quo](#29-quid-pro-quo)
3. [Malware-Based Attacks](#3-malware-based-attacks)
   - 3.1 [Ransomware](#31-ransomware)
   - 3.2 [Spyware](#32-spyware)
   - 3.3 [Adware](#33-adware)
   - 3.4 [Trojans](#34-trojans)
   - 3.5 [Worms](#35-worms)
   - 3.6 [Rootkits](#36-rootkits)
4. [Network & Technical Attacks](#4-network--technical-attacks)
   - 4.1 [DDoS](#41-ddos)
   - 4.2 [Man-in-the-Middle (MITM)](#42-man-in-the-middle-mitm)
   - 4.3 [DNS Spoofing / Poisoning](#43-dns-spoofing--poisoning)
   - 4.4 [ARP Spoofing](#44-arp-spoofing)
   - 4.5 [Brute Force Attacks](#45-brute-force-attacks)
   - 4.6 [Credential Stuffing](#46-credential-stuffing)
   - 4.7 [Session Hijacking](#47-session-hijacking)
5. [Application / Software Attacks](#5-application--software-attacks)
   - 5.1 [SQL Injection](#51-sql-injection)
   - 5.2 [XSS (Cross-Site Scripting)](#52-xss-cross-site-scripting)
   - 5.3 [CSRF (Cross-Site Request Forgery)](#53-csrf-cross-site-request-forgery)
   - 5.4 [Zero-Day Exploits](#54-zero-day-exploits)
   - 5.5 [Buffer Overflow](#55-buffer-overflow)
6. [Hardware & Physical Attacks](#6-hardware--physical-attacks)
   - 6.1 [Keyloggers](#61-keyloggers)
   - 6.2 [Malicious USB Devices](#62-malicious-usb-devices)
   - 6.3 [ATM Skimmers](#63-atm-skimmers)
   - 6.4 [Shoulder Surfing](#64-shoulder-surfing)
7. [Insider Threats](#7-insider-threats)
8. [Supply Chain Attacks](#8-supply-chain-attacks)
9. [Business Email Compromise (BEC)](#9-business-email-compromise-bec)
10. [Conclusion](#10-conclusion)

---

## 1. Introduction

Cyber attacks are deliberate attempts by threat actors to steal data, disrupt operations, or gain unauthorized access to systems. These attacks can target individuals, small businesses, corporations, and government systems. Over the last decade, cybercrime has increased dramatically due to the rise of cloud systems, remote work, and AI-generated phishing.

This comprehensive guide explains each attack type in detail, including definitions, examples, and **real recent cases from 2023–2024**.

---

## 2. Social Engineering Attacks

Social engineering attacks manipulate human emotions such as fear, urgency, curiosity, trust, and greed. These attacks exploit psychological vulnerabilities rather than technical weaknesses.

### 2.1 Phishing

**Definition:**  
Fake emails designed to trick victims into giving personal information, clicking malicious links, or opening infected attachments.

**Example:**  
A user receives an email claiming their bank account is locked and must be verified immediately by clicking a link.

**Real Case (2023):**  
In early 2023, **American Airlines** revealed a phishing attack allowed hackers to access employee email accounts, exposing personal data like passport numbers.

---

### 2.2 Spear Phishing

**Definition:**  
A highly targeted phishing attack using personal information to appear more believable and increase success rates.

**Example:**  
An email sent to an accountant referencing a real invoice number and requesting urgent payment to a new account.

**Real Case (2024):**  
A finance employee of a multinational firm was tricked into sending **$25 million** after receiving deepfake video calls posing as the CFO.

---

### 2.3 Whaling

**Definition:**  
Phishing specifically targeting high-level executives (CEO, CFO, Directors) with sophisticated, personalized attacks.

**Example:**  
Fake email impersonating the CEO asking for urgent fund transfers, often using compromised or spoofed email addresses.

**Real Case:**  
In 2023, **FACC (Austrian aerospace supplier)** lost **$61 million** in a whaling attack targeting senior executives.

---

### 2.4 Smishing

**Definition:**  
Phishing attacks delivered via SMS/text messages, exploiting the trust people place in text communications.

**Example:**  
"Your FedEx package is undelivered. Click here to reschedule: [malicious link]"

**Real Case:**  
The **FluBot malware campaign** spread worldwide via SMS claiming package tracking updates, infecting thousands of devices.

---

### 2.5 Vishing

**Definition:**  
Voice-call phishing using fake call centers to manipulate victims over the phone.

**Example:**  
Fake "Microsoft support" telling you your computer is infected and requesting remote access to "fix" it.

**Real Case:**  
In 2023, MGM Resorts suffered a **major ransomware attack** that started from a simple **vishing phone call** to the help desk, resulting in over $100M in losses.

---

### 2.6 Pretexting

**Definition:**  
Attacker creates a believable story or scenario to manipulate the victim into providing information or access.

**Example:**  
Claiming to be from HR needing employee verification, or impersonating IT support requiring password resets.

**Real Case:**  
Attackers pretended to be Uber IT support and tricked an employee into approving an MFA push. This led to the **Uber 2022 breach**, still relevant due to similar attacks in 2023–2024.

---

### 2.7 Baiting

**Definition:**  
Offering something enticing (free software, USB drives, gift cards) to trick victims into taking actions that compromise security.

**Example:**  
Free USB drive left in a parking lot containing malware that auto-executes when plugged into a computer.

**Real Case:**  
In multiple 2023 university security tests, over **45% of staff plugged in random found USB drives**, demonstrating the effectiveness of baiting attacks.

---

### 2.8 Tailgating / Piggybacking

**Definition:**  
Following an authorized employee into a locked building or secure area without proper authentication.

**Example:**  
Someone holding a box or appearing busy asks you to hold the door open, gaining unauthorized physical access.

**Real Case:**  
Security researchers demonstrated how tailgating allowed access into **Meta's headquarters** during authorized penetration tests, highlighting physical security vulnerabilities.

---

### 2.9 Quid Pro Quo

**Definition:**  
Attacker offers something of value in exchange for credentials or access, creating a false sense of mutual benefit.

**Example:**  
Fake IT worker offers to fix a computer issue but installs malware or steals credentials during the "repair."

**Real Case:**  
In 2024, several U.S. companies reported attackers calling employees claiming to be from "technical support" and asking them to disable MFA temporarily, resulting in account compromises.

---

## 3. Malware-Based Attacks

Malware is malicious software designed to damage, disrupt, or gain unauthorized access to computer systems and networks.

### 3.1 Ransomware

**Definition:**  
Malware that encrypts data and demands payment (usually in cryptocurrency) to restore access to the files.

**Example:**  
Your computer files become locked with a message demanding Bitcoin payment within 72 hours, with threats of permanent data deletion.

**Real Case (2023–2024):**
- **MGM Resorts**: Lost over **$100M** due to ransomware that shut down operations for days
- **City of Dallas**: Government systems shut down for weeks, affecting municipal services

---

### 3.2 Spyware

**Definition:**  
Malware that tracks user activity secretly, collecting sensitive information without the user's knowledge.

**Example:**  
Software that records keystrokes, screenshots, browsing history, and personal communications.

**Real Case:**  
The **Pegasus spyware** was found infecting journalists, politicians, and activists worldwide, capable of accessing messages, calls, and device cameras.

---

### 3.3 Adware

**Definition:**  
Software that displays unwanted advertisements and tracks user activity for marketing purposes, often bundled with legitimate software.

**Example:**  
Pop-up ads that appear constantly, browser redirects to advertising sites, and tracking cookies installed without consent.

**Real Case:**  
Over **50+ adware apps** were removed from the Google Play Store in 2023, affecting millions of Android users.

---

### 3.4 Trojans

**Definition:**  
Malware disguised as legitimate software that performs malicious actions once installed, named after the Trojan Horse.

**Example:**  
A seemingly harmless game or utility that, when installed, creates backdoors or steals credentials.

**Real Case:**  
The "Emotet" Trojan resurfaced in 2024, infecting thousands of systems through fake invoice emails and establishing botnets.

---

### 3.5 Worms

**Definition:**  
Self-replicating malware that spreads across networks without human intervention, exploiting vulnerabilities.

**Example:**  
Malware that automatically scans for vulnerable systems and copies itself to them, creating a network-wide infection.

**Real Case:**  
The "Morto" worm exploited Remote Desktop Protocol (RDP) systems globally, spreading rapidly through unsecured connections.

---

### 3.6 Rootkits

**Definition:**  
Malware designed to hide deep inside system firmware or kernel, making detection and removal extremely difficult.

**Example:**  
Software that modifies system files to hide its presence from antivirus software and system administrators.

**Real Case:**  
The "CosmicStrand" rootkit targeted UEFI firmware in 2023, persisting even after operating system reinstallation.

---

## 4. Network & Technical Attacks

These attacks target network infrastructure, protocols, and communication channels to intercept, disrupt, or manipulate data.

### 4.1 DDoS (Distributed Denial of Service)

**Definition:**  
Overwhelming servers or networks with massive amounts of traffic from multiple sources, making services unavailable.

**Example:**  
Thousands of compromised devices simultaneously sending requests to a website, causing it to crash or become unreachable.

**Real Case:**  
In 2023, Google mitigated the **largest DDoS attack ever recorded**, reaching 398 million requests per second, demonstrating the scale of modern attacks.

---

### 4.2 Man-in-the-Middle (MITM)

**Definition:**  
Attacker intercepts and potentially alters data transmitted between two parties without their knowledge.

**Example:**  
Fake WiFi hotspots in public places that capture login credentials and sensitive data from connected devices.

**Real Case:**  
Multiple financial institutions reported MITM attacks in 2023, where attackers intercepted banking transactions and authentication tokens.

---

### 4.3 DNS Spoofing / Poisoning

**Definition:**  
Redirecting users to fake websites by corrupting DNS cache or responses, making malicious sites appear legitimate.

**Example:**  
Users typing "bank.com" are redirected to a fake website that steals their login credentials.

**Real Case:**  
Crypto platform users were redirected to fake domains in 2023, resulting in millions of dollars in cryptocurrency theft.

---

### 4.4 ARP Spoofing

**Definition:**  
Manipulating Address Resolution Protocol (ARP) tables to redirect network traffic through an attacker's device.

**Example:**  
Attacker sends fake ARP messages to make their device appear as the network gateway, intercepting all traffic.

**Real Case:**  
Corporate networks experienced ARP spoofing attacks in 2023, allowing attackers to capture sensitive internal communications.

---

### 4.5 Brute Force Attacks

**Definition:**  
Systematically guessing passwords or encryption keys by trying all possible combinations until successful.

**Example:**  
Automated tools attempting thousands of password combinations per second to gain unauthorized access to accounts.

**Real Case:**  
Multiple cloud service providers reported increased brute force attacks in 2023–2024, targeting accounts with weak passwords.

---

### 4.6 Credential Stuffing

**Definition:**  
Using leaked username and password combinations from previous breaches to gain unauthorized access to other accounts.

**Example:**  
Attackers use credentials from a data breach to attempt login on multiple platforms, exploiting password reuse.

**Real Case:**  
Millions of users were affected after Netflix and Disney+ credential stuffing attacks in 2023, where attackers used credentials from other breaches.

---

### 4.7 Session Hijacking

**Definition:**  
Stealing authentication cookies or session tokens to impersonate authenticated users without knowing their passwords.

**Example:**  
Attacker intercepts a session cookie and uses it to access a user's account, bypassing login requirements.

**Real Case:**  
TikTok session hijack vulnerability exposed in 2023 allowed attackers to take over user accounts by stealing session tokens.

---

## 5. Application / Software Attacks

These attacks exploit vulnerabilities in web applications, software, and programming code.

### 5.1 SQL Injection

**Definition:**  
Injecting malicious SQL code into application inputs to manipulate databases, extract data, or execute unauthorized commands.

**Example:**  
Entering `' OR '1'='1` in a login form to bypass authentication and gain unauthorized database access.

**Real Case:**  
British Airways was fined after a SQL injection attack exposed customer data, including payment card information, affecting hundreds of thousands of customers.

---

### 5.2 XSS (Cross-Site Scripting)

**Definition:**  
Injecting malicious scripts into web pages viewed by other users, allowing attackers to steal cookies, session tokens, or perform actions on behalf of users.

**Example:**  
A comment on a blog that contains JavaScript code that executes when other users view the page, stealing their session cookies.

**Real Case:**  
Multiple major websites patched XSS vulnerabilities in 2023–2024, with attackers using them to steal user credentials and session data.

---

### 5.3 CSRF (Cross-Site Request Forgery)

**Definition:**  
Forcing authenticated users to perform unwanted actions on web applications without their knowledge or consent.

**Example:**  
A malicious website that automatically submits a form to change a user's email address on another site where they're logged in.

**Real Case:**  
Several banking applications were targeted by CSRF attacks in 2023, allowing attackers to initiate unauthorized transactions.

---

### 5.4 Zero-Day Exploits

**Definition:**  
Attacks targeting previously unknown vulnerabilities before developers can create and deploy patches.

**Example:**  
Exploiting a newly discovered flaw in a web browser to execute malicious code before the vendor releases a security update.

**Real Case:**  
Chrome and Windows patched multiple zero-day exploits in 2024, with some being actively exploited in the wild before patches were available.

---

### 5.5 Buffer Overflow

**Definition:**  
Overwriting memory buffers by providing input larger than expected, potentially crashing applications or executing malicious code.

**Example:**  
Sending an extremely long string to an application that doesn't validate input length, causing it to overwrite adjacent memory.

**Real Case:**  
Several critical software applications patched buffer overflow vulnerabilities in 2023, which could allow remote code execution.

---

## 6. Hardware & Physical Attacks

These attacks target physical devices, hardware components, or require physical proximity to the target.

### 6.1 Keyloggers

**Definition:**  
Hardware or software devices that record keystrokes to capture passwords, credit card numbers, and other sensitive input.

**Example:**  
A small USB device inserted between a keyboard and computer that records all keystrokes, or software installed on a system.

**Real Case:**  
Corporate espionage cases in 2023 involved hardware keyloggers installed on executive computers, capturing sensitive business information.

---

### 6.2 Malicious USB Devices

**Definition:**  
USB devices (like BadUSB, Rubber Ducky) that appear as normal storage but execute malicious code when plugged into computers.

**Example:**  
A USB drive that automatically runs malware when inserted, or a device that impersonates a keyboard to execute commands.

**Real Case:**  
FBI warned businesses in 2023 of ransomware-laced USB drives mailed in fake packages, with several companies falling victim to these attacks.

---

### 6.3 ATM Skimmers

**Definition:**  
Physical devices attached to ATMs or card readers that capture credit/debit card information during legitimate transactions.

**Example:**  
A fake card reader overlay on an ATM that captures card data while a hidden camera records PIN entry.

**Real Case:**  
Thousands of ATM skimming devices were discovered in 2023, with criminals using them to clone cards and steal millions from bank accounts.

---

### 6.4 Shoulder Surfing

**Definition:**  
Observing someone enter passwords, PINs, or other sensitive information by looking over their shoulder or using cameras.

**Example:**  
Someone watching you type your password at a coffee shop, or a hidden camera recording PIN entry at an ATM.

**Real Case:**  
Security awareness campaigns in 2023 highlighted the prevalence of shoulder surfing in public spaces, with many users unaware of the risk.

---

## 7. Insider Threats

**Definition:**  
Security risks posed by individuals within an organization who have authorized access to systems and data.

**Types:**
- **Malicious Insiders**: Employees who intentionally steal data or sabotage systems
- **Negligent Insiders**: Employees who accidentally expose data through carelessness
- **Compromised Insiders**: Employees whose accounts have been taken over by external attackers

**Example:**  
An employee with access to customer databases downloads sensitive information before leaving the company, or an employee falls for a phishing attack that compromises their account.

**Real Case:**  
Multiple organizations in 2023–2024 reported insider threats, with some cases involving employees selling customer data or providing access to external attackers.

---

## 8. Supply Chain Attacks

**Definition:**  
Attacking third-party vendors, suppliers, or software providers to gain access to their customers' systems and data.

**Example:**  
Compromising a software update server so that when customers install updates, they also install malware.

**Real Case:**  
The 2023 **MOVEit breach** impacted **over 1,000 organizations** worldwide, including government agencies and major corporations, by exploiting a vulnerability in file transfer software used by thousands of companies.

---

## 9. Business Email Compromise (BEC)

**Definition:**  
Highly targeted attacks impersonating executives or trusted business partners to trick employees into transferring money or sensitive information.

**Example:**  
Fake email from the CEO requesting urgent wire transfer to a new account, or email from a vendor requesting payment to a different bank account.

**Real Case:**  
In 2023, BEC attacks caused losses of **over $3 billion** globally, with the FBI reporting these as one of the most financially damaging cybercrimes.

---

## 10. Conclusion

Cyber attacks are constantly evolving, with attackers developing new techniques and exploiting emerging technologies. The threat landscape has expanded dramatically with the rise of cloud systems, remote work, AI-generated phishing, and sophisticated social engineering tactics.

**Key Takeaways:**
- **Awareness** is the first line of defense against social engineering attacks
- **Strong security practices** including multi-factor authentication, regular updates, and employee training are essential
- **Vigilance** in recognizing suspicious communications and maintaining security hygiene can prevent many attacks
- **Incident response planning** is crucial for minimizing damage when attacks occur

Organizations and individuals must stay informed about emerging threats and continuously adapt their security strategies to protect against the ever-changing cyber threat landscape.

---

*Last Updated: 2024*  
*This guide is intended for educational and awareness purposes to help organizations and individuals understand and defend against cyber threats.*
