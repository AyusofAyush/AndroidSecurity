# Android Security

# Introduction
With time, machines like Computers have been developed to reduce the human efforts.
Advancements in Technology has enabled humans to rely on Smartphones for needs as small as
messaging to needs as significant as banking.
Android is a popular Linux based Smartphone Operating System. It is Open Source and is
developed by Google and Open Handset Alliance. It allows developers to write code in a
Java-like language that utilizes Google-developed Java libraries.
Android security has been a hot issue of consideration in the Information security field with the
increase of use of Android smartphones in the market.

# MOTIVATION
With increase in technology and ease of human works, malicious attackers are also increasing
and so is the probability of exploiting vulnerabilities in the smartphone security. Most of the
Smartphones account to sensitive information such as personal or business information, the
banking transaction information, photographs, Chats,etc.
There is a plethora of opportunity for a maliciously motivated person to misuse the personal data
extracted from the Android smartphone. Therefore, we thought that we can study in depth about
Android Security features and loopholes in order to prevent ourselves from the vulnerabilities of
Android security failures.What is Penetration Testing? A vulnerability assessment simply identifies and reports noted
vulnerabilities, whereas penetrations test (Pen Test) attempts to exploit the vulnerabilities to
determine whether unauthorized access or other malicious activity is possible. Penetration testing
typically includes network penetration testing and application security testing as well as controls
and processes around the networks and applications, and should occur from both outside the
network trying to come in (external testing) and from inside the network.



# COURSE OF ACTION:
1.Motivated, we started to research to gain valuable knowledge w.r.t. Android which included
● What is Android?
● What are the Vulnerabilities associated with it?
● What are the various attacks possible?
● How can we attack a vulnerable Android device?
2. We decided to center our project around ​ Penetration Testing ​ on an Android device using
Kali Linux.
3. We went through an online course ​ “Learn Kali Linux and Hack Android Devices” by
Mohammed Atef.
4.Throughout the course, we learnt about various tools, namely-
● Ettercap
● Netcat
● Nmap
● Armitage
● Metasploit
● Social Engineering Toolkit (SET)5. We then used the tools to gain access to the Android device using various ways such as-
● Malicious Payload embedded in Application : We installed a malicious app on the
target device, using which would enables the attacker to gain access to the device and
perform activities without the consent of the owner-
○ Webcam access
○ Kernel access
○ Call_log access
○ Contacts Access
○ Files access
○ Download/upload media
○ Livestream webcam
● Access through Link: Access to the device by clicking on a certain link also enabled the
attacker to gain access to the target device and perform the aforesaid attacks.
6. After going through various attacks, we went through the counter measures which could be
taken to prevent such attacks.


# TOOLS USED
● The Operating System used : Kali Linux
● Attacks Performed:
○ Metasploit Attack
○ Stage fright Attack
● Applications used:
○ Armitage
○ Social Engineering Toolkit
○ Metasploit (msfconsole)
■ Meterpreter session5.WHY KALI LINUX?
Kali Linux is rated as the #1 security operating system for penetration testing and Security
personnels. Kali Linux offers a multitude of options to scan a single IP, port, or host (or a range
of IPs, ports, and hosts) and discover vulnerabilities and security holes. The output and the
information this provides can serve as a precursor to penetration testing efforts.


# WHAT IS METASPLOIT?
The Metasploit framework is one of the most popular tools for exploiting server-side attacks. It is
considered one of the most useful tools for Penetration Testers. HD Moore created it in 2003. It
is used as a legitimate Penetration Testing tool, as well as a tool used by attackers to conduct
unauthorized exploitation of systems. There are a plenty of sources dedicated to teaching how to
use the Metasploit framework. In the context of this book, we will examine how Metasploit is
used for server-side exploitation for testing potential web applications. Note to make sure
Postgres SQL and Metasploit services are started. You can do so by typing service postgres start
and service metasploit start in the Terminal window as root. The first step is to open up a console
and type in msfconsole to launch Metsaploit. msfconsole is the most popular way to launch
Metasploit. It provides a user interface to access the entire Metasploit framework. Basic
commands such as help and show will allow you to navigate through Metasploit.
(citation : metasploit.com)
