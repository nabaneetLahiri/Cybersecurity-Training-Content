# <u>Introduction</u>

## <u> Fundamental Security Concepts </u>
The whole principle is to avoid **Theft, Tampering and Disruption** of the systems through **CIA Triad** (Confidentiality, Integrity and Availability).

<p align="center">
<img width="50%" src="https://i.ytimg.com/vi/AJTJN4wDBM8/hqdefault.jpg">
</p>

- **Confidentiality**
Keeping systems and data from being accessed, seen, read to anyone who is not authorized to do so.
Information is accessible only to the autorized personnel.

- **Integrity**
TRUSTWORTHINESS OF DATA OR RESOUCES: Protect the data from modification or deletion by unauthorized parties, and ensuring that when authorized people make changes that shouldn't have been made the damage can be undone.

- **Availability**
ACCESSIBLE WHEN REQUIRED BY AUTHORIZED USERS: Systems, access channels, and authentication mechanisms must all be working properly for the information they provide and protect to be available when needed.

- **Authenticity**
Refers to the characterstic of a communication, document, or any data that ensures the quality of being geniune.
	
**Note:** *In addition, other properties, such as authenticity, accountability, non-repudiation and reliability can also be involved. (ISO/IEC 27000:2009)*

- **Auditing & Accountability**
Basically keep tracking of everthing, like, who's been logging in when are they loggin in whose access this data.

- **Non-Repudiation**
Non-repudiation is the assurance that someone cannot deny the validity of something. Non-repudiation is a legal concept that is widely used in information security and refers to a service, which provides proof of the origin of data and the integrity of the data.

### **Security, Functionality and Usability balance**

There is an inter dependency between these three attributes. When **security goes up, usability and functionality come down**. Any organization should balance between these three qualities to arrive at a balanced information system.

<p align="center">
<img width="50%" src="https://gist.githubusercontent.com/Samsar4/62886aac358c3d484a0ec17e8eb11266/raw/f14455ed4def635e1bc93b85657f43dbbf4a3127/triad2.png">
</p>

## <u>Types of Hackers</u>

<p align="center">
<img width="50%" src="https://www.simplilearn.com/ice9/free_resources_article_thumb/types-hacker.JPG">
</p>

- **Black Hat** - Hackers that seek to perform malicious activities.
- **Gray Hat** - Hackers that perform good or bad activities but do not have the permission of the organization they are hacking against.
- **White Hat** - Ethical hackers; They use their skills to improve security by exposing vulnerabilities before malicious hackers.
- **Script Kiddie / Skiddies** - Unskilled individual who uses malicious scripts or programs, such as a web shell, developed by others to attack computer systems and networks and deface websites. 
- **State-Sponsored Hacker** - Hacker that is hired by a government or entity related.
- **Hacktivist** - Someone who hacks for a cause; political agenda.
- **Suicide Hackers** - Are hackers that are not afraid of going jail or facing any sort of punishment; hack to get the job done.
- **Cyberterrorist** - Motivated by religious or political beliefs to create fear or disruption.

## <span style="color:#009fd4">Terminology</span>

- **Hack value** - Perceived value or worth of a target as seen by the attacker.
- **Vulnerability** - A system flaw, weakness on the system (on design, implementation etc).
- **Threat** - Exploits a vulnerability.
- **Exploit** - Exploits are a way of gaining access to a system through a security flaw and taking advantage of the flaw for their benefit.
- **Payload** - Component of an attack; is the part of the private user text which could also contain malware such as worms or viruses which performs the malicious action; deleting data, sending spam or encrypting data.
- **Zero-day attack** - Attack that occurs before a vendor knows or is able to patch a flaw.
- **Daisy Chaining / Pivotting** - It involves gaining access to a network and /or computer and then using the same information to gain access to multiple networks and computers that contains desirable information. 
- **Doxxing** - Publishing PII about an individual usually with a malicious intent.
- **Enterprise Information Security Architecture** (EISA) - determines the structure and behavior of organization's information systems through processes, requirements, principles and models.
 
## <span style="color:#009fd4">Attack Vectors</span>
*Path by which a hacker can gain access to a host in order to deliver a payload or malicious outcome*

- **APT - Advanced Persistent Threats**
  - An advanced persistent threat is a stealthy threat actor, typically a nation state or state-sponsored group, which gains unauthorized access to a computer network and remains undetected for an extended period; Typically uses zero day attacks.
- **Cloud computing / Cloud based technologies**
  - Flaw in one client's application cloud allow attacker to access other client's data
- **Viruses, worms, and malware**
  - Viruses and worms are the most prevalent networking threat that are capable of infecting a network within seconds.
- **Ransomware**
  - Restricts access to the computer system's files and folders and demands an online ransom payment to the attacker in order to remove the restrictions.
- **Mobile Device threats**
- **Botnets**
  - Huge network of compromised systems used by an intruder to perform various network attacks
- **Insider attacks**
    - Disgruntled employee can damage assets from inside.
    - Huge network of compromised hosts. (used for DDoS).

- **Phishing attacks**
- **Web Application Threats**
  - Attacks like SQL injection, XSS (Cross-site scripting)...
- **IoT Threats**

## <span style="color:#009fd4">Threat actor types and attributes.</span>

1. Types of actors:
    - **Script kiddies**: A person who uses pre-existing code and scripts to hack into machines, because they lack the expertise to write their own.
    - **Hacktivist**: An individual who is someone who misuses computer systems for a socially or politically motivated agenda. They have roots in the hacker culture and ethics. Hacker on a mission.
    - **Organized crime**: These are professionals motivated ultimately by profit. They have enough money to buy the best gear and tech. Multiple people perform specific roles: gathering data, managing exploits, and one who actually writes the code.
    - **Nation states/APT**: An APT is an advanced persistent threat, these are massive security risks that can cost companies and countries millions of dollars. Nation states have very sophisticated hacking teams that target the security of other nations. They often attack military organizations or large security sites, they also frequently attack power plants.
    - **Insiders**: Someone who is inside the company who has intricate knowledge of the company and how its network works. They can pinpoint a specific vulnerability and may even have access to multiple parts of the network.
    - **Competitors**: Rival companies, can bring down your network or steal information through espionage.
2. Attributes of actors:
    - **Internal/external**: Internal is inside the company, can be intentional, unintentional. External is someone outside the company trying to get in.
    - **Level of sophistication**: Is the skill of the hacker and the complexity of the attack.
    - **Resources/funding**: The amount of money and the value of the tech and gear being used.
    - **Intent/motivation**: The reason for the attack, can be for political, monetary, or social reasons.
    - **Use of Open-source intelligence (OSINT)**: Data that is collected through publicly available information. This can be used to help make decisions. Can be used by threat actors to help find their next target or how to best attack their target. OSINT is also incredibly helpful for mitigating risks and for identifying new threat actors.
    
## <span style="color:#009fd4">Type of malware.</span>

- **Malware**: A malicious software that performs bad functions to our computer or other devices on the network.
- **Viruses**: An unsolicited and unwanted malicious program that can reproduce itself.
- **Crypto-malware**: A malicious program that encrypts programs and files on the computer in order to extort money from the user.
- **Ransomware**: Denies access to a computer system or data until a ransom is paid. Can be spread through a phishing email or unknowingly infected website.
- **Worm**: A self-contained infection that can spread itself through networks, emails, and messages.  
- **Trojan**: A form of malware that pretends to be a harmless application.
- **Rootkit**: A backdoor program that allows full remote access to a system.
- **Keylogger**: A malicious program that saves all of the keystrokes of the infected machine.
- **Adware**: A program that produces ads and pop ups using your browser, may replace the original browser and produce fake ads to remove the adware in order to download more malware.
- **Spyware**: Software that installs itself to spy on the infected machine, sends the stolen information over the internet back to the host machine.
- **Bots**: AI that when inside an infected machine performs specific actions as a part of a larger entity known as a botnet.
- **RAT** (Remote Access Trojan): A remotely operated Trojan.
- **Logic bomb**: A malicious program that lies dormant until a specific date or event occurs.
- **Backdoor**: Allows for full access to a system remotely.

## <span style="color:#009fd4">Types of attacks.</span>

1. Phishing: Sending a false email pretending to be legitimate to steal valuable information from the user.
    - **Spear phishing**: Attacks that target specific users with inside information.
    - **Whaling**: An attack on a powerful or wealthy individual like a CEO.
    - **Vishing**: An attack through a phone or voice communications.
    - **Tailgating**: Closely following individuals with keys to get access to secure areas.
    - **Impersonation**: Taking on the identity of an individual to get access into the system or communications protocol.
    _ **Dumpster diving**: Going through a business’s or person’s trash to find thrown away valuable information or possessions.
    - **Shoulder surfing**: Watching as a person enters information.
    - **Hoax**: False information that deceives the user into compromising security by making them believe they are at risk.
    - **Watering hole attack**: A security attack that targets a specific highly secured group by infecting a commonly visited website by the group’s members.
    - **Social engineering**: The practice of using social tactics to gain information from people or get people to do something.  
    Principles (reasons for effectiveness):
        > - **Authority**: The actor acts as an individual of authority.
        > - **Intimidation**: Frightening or threatening the victim.
        > - **Consensus**: Convince based on what's normally expected.
        > - **Scarcity**: Limited resources and time to act.
        > - **Familiarity**: The victim is well known.
        > - **Trust**: Gain their confidence, be their friend.
        > - **Urgency**: Limited time to act, rush the victim.
2. Application/service attacks:
    - **DoS (Denial of Service)**: Flooding a target machine or resource with many requests to overload the system and prevent use of its resources.
    - **DDoS (Distributed Denial of Service)**: DoS launched from multiple sources.
    - **Man-in-the-middle**: The attacker alters the communication between two parties who believe they are directly communicating.
    - **Buffer overflow**: A program attempts to write more data than can be held in a fixed block of memory.  
    - **Injection**: Occurs from processing invalid data, inserts code into the vulnerable computer program and changes the course of execution.
    - **Cross-site scripting (XXS)**: Found in web applications, allows for an attacker to inject client-side scripts in web pages.
    - **Cross-site request forgery (XSRF)**: Unauthorized commands are sent from a user that is trusted by the website. Allows the attacker to steal cookies and harvest passwords.
    - **Privilege escalation**: An attack that exploits a vulnerability that allows them to  gain access to resources that they normally would be restricted from accessing.
    - **ARP poisoning**: The act of falsifying the IP-to-MAC address resolution system employed by TCP/IP.
    - **Amplification**: The amount of traffic sent by the attacker is originally small but then is repeatability multiplied to place a massive strain on the victim’s resources, in an attempt to cause it to fail or malfunction.  
    - **DNS poisoning**: Is a type of attack that exploits vulnerabilities in the domain name system (DNS) to divert Internet traffic away from legitimate servers and towards fake ones.
    - **Man-in-the-browser**: A proxy Trojan horse that infects web browsers and capture browser session data.
    - **Zero day**: The aim is to exploit flaws or vulnerabilities in targeted systems that are unknown or undisclosed to the world in general. Meaning that there is no direct or specific defense to the attack; which puts most systems vulnerable assets at risk.
    - **Replay**: Is a network-based attack where a valid data transmission is rebroadcasted, repeated, or delayed.  
    - **Pass the hash**: An authentication attack that captures and uses the hash of a password. The attacker then attempts to log on as the user with the stolen hash. This type of attack is commonly associated with the Microsoft NTLM (New Technology LAN Manager) protocol.
    - Hijacking and related attacks:
        > - **Clickjacking**: Deceives the user into clicking on a malicious link by adding the link to a transparent layer over what appears to be a legitimate web page.
        > - **Session hijacking**: An attack in which an attacker attempts to impersonate the user by using their legitimate session token.  
       	> - **URL hijacking**: Redirects the user to a false website based on misspelling the URL, is also referred to **typosquatting**.
       	> - **Domain hijacking**: The act of changing the registration of a domain name without the permission of the victim.
    - **MAC spoofing**: The attacker falsifies the MAC address of a device.
    - **IP spoofing**: An intruder uses another site's IP address to masquerade as a legitimate site.  
3. Wireless attacks:
    - **Replay**: This is a passive attack where the attacker captures wireless data, records it, and then sends it on to the original recipient without them being aware of the attacker's presence.
    - **IV (Initialization Vector)**: A random number used to increase security by reducing predictability and repeatability.
    - **Evil twin**: Has same SSID (Service Set Identifier) as a proper access point (AP). Once a user connects to it, all wireless traffic goes through it instead of the real AP.
    - **Rogue AP (Access Point)**: An unauthorized WAP (Wireless Access Point) or Wireless Router that allows for attackers to bypass many of the network security configurations and opens the network and its users to attacks.
    - **Jamming**: Disabling a wireless frequency with noise to block the wireless traffic.
    - **WPS (WiFi Protected Setup)**: Allows users to easily configure a wireless network, sometimes by using only a PIN. The PIN can be found through a brute force attack.
    - **Disassociation**: Removes clients from a wireless network.
4. Cryptographic attacks
   - **Birthday**: Used to find collisions in hashes and allows the attacker to be able to create the same hash as the user. Exploits that if the same mathematical function is performed on two values and the result is the same, then the original values are the same.
   - Known plain text/cipher text:
       > - **Plain text**: The attacker has both the plaintext and its encrypted version.
       > - **Cipher text**: The attacker has access only to the encrypted messages.
   - **Rainbow tables**: Large pregenerated data sets of encrypted passwords used in password attacks.
   - **Dictionary**: A password attack that creates encrypted versions of common dictionary words and then compares them against those in a stolen password file. Guessing using a list of possible passwords.
   - **Brute force**: A password-cracking program that tries every possible combination of characters through A to Z.
       > - Online: Is against a live logon prompt.
       > - Offline: The attack is working on their own independent computers to compromise a password hash.
   - **Collision**: When two different inputs produce the same hash value.
   - **Replay**: The attacker captures network packets and then retransmits them back onto the network to gain unauthorized access.

## <span style="color:#009fd4">Vulnerabilities</span>

- **CVSS - Common Vulnerability Scoring System** [[+]](https://nvd.nist.gov/vuln-metrics/cvss)
  - Places numerical score based on severity
  - ![cvss](https://3.bp.blogspot.com/-5V1cb_wTvsk/Wl78iF4Sd8I/AAAAAAAAF7U/KmK4pMXi54YworDgh4uI8aZtHgy0bbznQCLcBGAs/s1600/CVSS.png
  )
- **CVE – Common Vulnerabilities and Exposures** [[+]](https://cve.mitre.org/)
  - Is a list of publicly disclosed vulnerabilities and exposures that is maintained by MITRE.
  - ![cve](https://i0.wp.com/gbhackers.com/wp-content/uploads/2016/10/cve.png?resize=486%2C408&ssl=1)
- **NVD - National Vulnerability Database**  [[+]](https://nvd.nist.gov/)
  -  is a database, maintained by NIST, that is fully synchronized with the MITRE CVE list; US Gov. vulnerabilities repository.

### Vulnerability Categories

- **Misconfiguration** - improperly configuring a service or application
- **Default installation** - failure to change settings in an application that come by default
- **Buffer overflow** - code execution flaw
- **Missing patches** -  systems that have not been patched
- **Design flaws** - flaws inherent to system design such as encryption and data validation
- **Operating System Flaws** - flaws specific to each OS
- **Default passwords** - leaving default passwords that come with system/application
