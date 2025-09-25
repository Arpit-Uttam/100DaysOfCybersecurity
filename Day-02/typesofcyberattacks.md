# Day 02 - Cyber Attacks Types
## Topics:
- Social Engineering Attacks
- Malware Attack
- Web-Based Attacks
- Network infrastructure Attacks
- Supply Chain Attacks
- Cloud/IoT Threats

## SOCIAL ENGINEERING ATTACKS
### PHISHING
Phishing is a cyber-attack in which attackers impersonate legitimate organisations or contacts via email, text messages, or websites to deceive people into providing critical information such as passwords, credit card numbers, or bank account details. These messages often look convincing, exploiting trust and urgency to lure victims into clicking on malicious links or downloading harmful files

### WHALING
Whaling is a specialised form of phishing that targets high-profile individuals, such as CEOs, CFOs, or other senior executives. Unlike broad phishing campaigns, whaling attacks are highly personalised and thoroughly researched to maximise credibility and success. Attackers often use sophisticated techniques, referencing real company details or business scenarios, to trick executives into divulging sensitive business information or authorising large financial transactions

### SMISHING
Smishing (SMS phishing) is a variant of phishing that uses text messages to trick victims. Attackers send fraudulent SMS messages, often posing as banks, delivery companies, or other trusted sources, instructing recipients to click links or call numbers. These links usually lead to malicious websites or prompt the user to share sensitive details, enabling attackers to steal information or install malware

### BAITING
Baiting is a form of social engineering attack where attackers use enticing offers to draw victims into performing risky actions. A common digital baiting example involves fake online promotions for free movies or music downloads, which actually deliver malware. Physical baiting—involving malware-infected USB drives left in public places—relies on victims’ curiosity to insert the device, thereby compromising the system

## MALWARE ATTACKS
### VIRUS
A virus is a form of malware that attaches itself to legitimate programs or files, enabling it to spread when those files are shared or executed. Once inside a system, a virus may corrupt, delete, or steal data and can often replicate itself to infect additional files or systems

### TROJAN HORSE
A Trojan horse is malicious software that disguises itself as legitimate or useful software to trick users into installing it. Unlike viruses, Trojans do not self-replicate but grant unauthorised access, steal data, or deliver more payloads, such as ransomware, after deceiving the user. Common examples include backdoor Trojans and banking Trojans

### RANSOMWARE
Ransomware is a type of malware that encrypts a victim's files or locks their system, demanding a ransom (usually in cryptocurrency) to restore access. Victims may lose access to all important data unless backups exist or the ransom is paid. Ransomware typically spreads via phishing emails or malicious downloads and is a significant threat to both individuals and organisations

### SPYWARE
Spyware covertly monitors and collects data from a user's device without their consent. It is typically used for commercial purposes or to facilitate identity theft, track browsing activity, collect keystrokes, or harvest sensitive information such as passwords or banking details. Spyware can be more difficult for users to detect compared to Trojans

## WEB-BASED ATTACKS

### SQL INJECTION
Injection attacks involve inserting malicious code into a web application, typically in the form of input data such as SQL queries, commands, or scripts. Injection attacks are successful when an application fails to properly validate and sanitise input data. These attacks can be prevented by properly validating and sanitising input data and using parameterised queries to access databases.

### CROSS-SITE SCRIPTING (XSS)
Cross-site scripting (XSS) is a type of web application attack that involves injecting malicious scripts into web pages that are viewed by other users. This is typically accomplished by injecting the script into a form input field or URL parameter that is then stored in the web application’s database.

### CROSS-SITE REQUEST FORGERY (CSRF)
Cross-site request forgery (CSRF) is a type of web application attack that tricks a user into executing an unwanted action on a web application which they are already authenticated. This is typically accomplished by sending a specially crafted link or script to the user, which then performs the unwanted action when clicked.

### ZERO-DAY EXPLOIT
A zero-day exploit is a type of cybersecurity attack that occurs on the same day the software, hardware, or firmware flaw is detected by the manufacturer. As it’s been zero days since the security flaw was last exploited, the attack is termed a zero-day exploit or zero-day attack. This kind of cyber-attack is considered dangerous because the developer has not had the chance to fix the flaw yet. Zero-day exploits typically target large organisations, government departments, firmware, hardware devices, IoT, users having access to valuable business data, etc.


## NETWORK & INFRASTRUCTURE ATTACKS

### DENIAL OF SERVICE (DoS)
A Denial of Service (DoS) attack attempts to make a machine or network resource unavailable to its intended users by flooding it with excessive traffic or sending data in a way that causes the system to crash or become unresponsive. Attackers can use a single computer or, in more advanced Distributed DoS (DDoS) attacks, a botnet of many compromised machines. Common types include SYN floods, ICMP floods, and application-layer attacks

### BGP HIJACKING
BGP Hijacking (Border Gateway Protocol Hijacking) refers to rerouting internet traffic through a malicious or misconfigured Autonomous System (AS) by pretending to own IP address blocks that actually belong to someone else. This corrupts global internet routing tables and can cause interception, data theft, service disruption, or redirection to malicious sites. Real-world cases have enabled attackers to intercept cryptocurrency transactions and disrupt global internet traffic

### PACKET SNIFFING
Packet sniffing is a technique where an attacker uses software or hardware tools to intercept, monitor, and capture data packets travelling across a network. On unsecured or unencrypted networks, this allows attackers to eavesdrop on sensitive information like passwords, emails, or banking details. There are passive sniffing attacks (listening unobtrusively on hubs or wireless networks) and active sniffing attacks (introducing traffic or exploiting switches to collect data).

### DNS SPOOFING/POISONING
DNS Spoofing, also known as DNS Cache Poisoning, is an attack where a DNS resolver's cache is injected with false information, causing users attempting to reach a legitimate website to be redirected to a malicious one. Attackers exploit vulnerabilities in how DNS servers handle name resolution and caching, manipulating users to visit phishing sites, steal credentials, or distribute malware. Once poisoned, users will continue to be redirected until the malicious entry expires from the cache


## SUPPLY CHAIN & ADVANCED THREATS

### SUPPLY CHAIN ATTACKS
Attackers target companies through their suppliers, software vendors, or service providers. If a supplier is compromised, malware or a backdoor can be spread to the main company through updates or other trusted connections. Recent attacks often use hacked software libraries or fake updates to infect many organizations at once

### ADVANCED PERSISTENT THREAT (APT)
APT is a long-term, highly targeted attack, usually by organized groups or even governments. The attackers first sneak into a network using tricks like phishing or exploiting software flaws. They stay hidden, spread through the network to collect secrets, and finally steal sensitive data. They often set up multiple hidden entry points to maintain ongoing access for weeks or months

### DISTRIBUTED DENIAL OF SERVICE (DDoS)
In a DDoS attack, a hacker controls thousands of devices (a botnet) to flood a website or network with fake requests. The overload makes the service slow or completely unavailable. Cloud and gaming platforms are common targets, and attacks are getting stronger every yea

### FIRMWARE ATTACKS
Firmware is the low-level code controlling hardware like your computer’s boot system or routers. Attackers infect or alter the firmware, which often survives reboots and normal antivirus scans. Once compromised, attackers get deep access and can remain hidden for a long time, making detection and removal very difficult.


## CLOUD & IoT BASED ATTACKS

### IoT BOTNETS


### CLOUD MISCONFIGURATION EXPLOIT


### SMART HOME HACKS




## 💡KEY TAKEWAYS
- Cybersecurity is not a learning path; it's a need of today's era
- Data is the new oil
- Awareness is the first antivirus

