# GUIDE FOR METASPLOIT

## CYBERSECURITY
Cyber security is the practice of defending computers, servers, mobile devices, electronic systems, networks, and data from malicious attacks.
The global cyber threat continues to evolve at a rapid pace, with a rising number of data breaches each year. It is really important that we in order to protect our data, system assess our security before the any attacker does.

# PENETRATION TESTING
Penetration testing is the practice of testing a computer machine, network, or web application to discover security vulnerabilities/weakness that an attacker could exploit and do unauthorised intrusion. It is also termed as pen testing or ethical hacking.
# METASPLOIT
Metasploit is one of the commonly used penetration testing frameworks. It has made hacking way simpler than it used to be. It is a very important tool for both defenders and attackers.
It is a collaboration between the open source community and Rapif7. It helps security teams to do more than just verifying vulnerabilities, improving security awareness, and managing security assessments. It basically empowers and arms defenders to always stay a step or two ahead in the game.
In our project we will be using this framework to learn to scan the vulnerabilities of the target machine (i.e. Metasploitable 2) and exploit the same.
# METASPLOITABLE 2
Metasploitable 2 is a vulnerable Ubuntu Linux virtual machine that can be used as a target for attacks, security testing and for practicing common penetration testing techniques.
In our project we will be using this as the target machine which will be attacked upon by the Metasploit framework.
 
 
The typical process used by attackers in exploitation and privilege escalation:
   •	Find an open port and running service: As in our case we are using metasploitrable 2 as the target machine we will have to get its IP address manually, for that we will run the command “ifconfig” in the command shell of metasploitable 2 machine.
   •	Determine that the service has a vulnerability: This step basically comes under information gathering in which network scanning tools like Nmap are used. In our project we have used Nmap. Nmap uses the IP packets to identify all the devices connected to the network. It also provides information on the services and operating systems they are running on.
   •	Determine whether that vulnerability has an exploit available: After knowing what all vulnerabilities are there in the device we search if there are any exploit corresponding to the vulnerabilities.

