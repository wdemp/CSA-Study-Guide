# CSA + -Study-Guide
Study Guide for passing the Comptia CSA+ certification
Primary Source will be from the "Comptia CSA+ Study Guide by Mike Chapple and David Seidl

Chapter 1: Defending Against Cybersecurity Threats

Domain 1 Threat Management: 
1.3: Given a network based threat implement, or recommend the appropriate response and countermeasures
1.4: Explain the purpose of practices used to secure a corporate environment

The CIA Triad(Confidentiality, Integrity, Availability)
Confidentiality: "ensures the unauthorized individuals are not able to gain access to sensitive information"(pg.3 Chapple & Seidl 2017)
Confidentiality: ensures unauthorized individual are not able to gain access to sensitive information(pg.3 Chapple & Seidl 2017)


Integrity: "ensures that there are no unauthorized modifications to information or systems either intentionally or unintentionally." (pg.3 Chapple & Seidl 2017)

Availability: "ensures that information and systems to are ready to meet the needs of legitimate users at the time those users requewst them. Availability conrols are: fault tolerance, clustering, and backups, seeks to ensure that legitimate users may gain access as needed."  (pg.3 Chapple & Seidl 2017)
Evaluating Security Risks: Three important terms: vulnerabilities, Risks, Threats(pg.3 Chapple & Seidl 2017)

Vulnerability: "A weakness in a device, system, application, or process, that might allow an attack to take place."(pg.3 Chapple & Seidl 2017) "Vulnerabilities are internal factors that may be controlled by cybersecurity professionals."(pg.3 Chapple & Seidl 2017)' 
An example of an exploited vulnerability wouild be "A web server that is running an outdated version of the Apache service may contain a vulnerability that would allow an attacker to conduct a DoS attack against the websites hosted in that server, jeopardizing their availabiltiy (pg.3 Chapple & Seidl 2017)

Threat: "An outside source that may exploit a vulnerability" (pg.4 Chapple & Seidl 2017) This outside source is usually hackers , but in some cases this could be natural diaster related; such as floods, earthquakes, etc. There is obviously nothing a cybersecurity analyst can do about those, however mitigating any hardware/software/ human error will fall upon the Cybersecurity Analyst and other IT related staff.

Risk: The combination of a threat and a corresponding vulnerability. Both of these must be present to classify as risk to the organization. As A result of the chronic rise in threats and vulnerabilities NIST has been publishing many guides to try and guide companies and organizations on how to test, prevent, and conduct risk assessments. 


Identify Threats: 
All organizations for the most part all test and take preventive measures traditionally against: viruses, malware, spyware, trojans etc. However, certain organization. As are more prone to specific attacks that are geared towards them specifically 
For example " governemnt sponsored advanced persistent threats typcially target government agencies, military organizations, and companies that operate in related fields.

Accidental threats only occur when the proper staff dont perform their daily duties properly. In other words it's usually caused by human error that there is a problem within the organization.  This can range from a system admin accidently deleting a critical disk volume, causing loss of availability. When a Cyber Security Analyst encounters a problem in the organization they must consider everything ranging from brown-out to a hacker, or an accidental unplugging of a vital piece of hardware. The take out message is that you must be able to think outside the box and come to a rationale conclusion based on the problem. 


Structural Threats: "This occurs when equipment, software, environmental controls fail due to the exhaustion of resources (such as running out of gas), exceeding their operational capability (such as extreme heat), or simply failing due to age."(pg.6 Chapple & Seidl 2017)
Environmental threats: occur when natural or man-made disaters occur that are outside the control of the organization. These could include fires, flooding, severe storms, power failures, or widespread telecommunication disruptions.  The CSA must be able to consider the impact of various threats to the organization.  

Identify Vulnerabilities: CSA's must focus on the organization's security effort from both external and internal sources.

Determine Likelihood, Impact, and Risk:

After the CSA has seekd out and determined possible risks to the company/organization's CIA model.  The next step is to form a plan to remediate, plan ahead, and predict the outcomes and incoming threats. When considering the likelihood of the risk that it will have on the organization; in addition to the likelihood of it actually happening. In the case of an adversarial threat the CSA needs to determine the likelihood of the adversary actually succeeding in the attack on the organization. 

Rreviewing Controls:
CSA professionals use risk management strategies for protecting the organization. The forms of  "Risk" are": risk acceptancem risk avoidance, risk mitigation, and risk transference. In addition the CSA is also responsbile for adivsing on the use of technical controls such as the implenmentation of endpoints and securing networks. 
Building a Secure Network: This will involve the proper setting configuration of the NACL. The protection of the network security should be a priority. This will invole some of the following: firewall configurations, NACL configurations, and using deceptive measures for defensive purposes.

Network Access Control

Utilizing the NACL is one of the most basic forms of securing a network, there are many other layers of protection that must be added to the network but this is a good place to start. This helps CSA's with limiting network access to to authorized personel onlyand ensuring that systems accessing the organizations network meet basic security requirements.
802.11x is a common standard that is used for NAC. 


Different NAC solutions: 
Agent based VS Agentless: "Agent Solutions, such as 802.11x, require that the device requesting access to the network run special software designed to communicate with the NAC service. Agentless approaches to NAC conduct authentication in the web browser and do not require special software(pg.9 Chapple & Seidl 2017).
In-Band vs Out0 of Band: In-band(or incline) NAC solutions use dedicated appliances that sit in between devices and that they wish to access. They deny or limit network access to devices that do not pass the NAC authentication process. the "captive portal" NAC solutions found in hotels that hijack all web requests until the guest enters a room number aer examples of in-band. Out-of-band NAC solutions, such as 802.11x, leverage the existing network infrastructure and has network devices communicate with authentication servers and then reconfifure the network to grant or deny newtwork access, as needed.
NAC solutions are often used to simply limit access to authorized users based on those users successfully authenticating, but they may also make network admission decisions based on other criteria. Some of the criteria used by NAC soltuions include:
Time of Day: Users may be authorized to access the network only during specific time periods, such as during business hours.
Role: Users amy be assigned to particular network segments based on their role in the organization. "An example of this would be when a colllege asssigns faculty and staff to an administrative network that may access administrative systems while assigning students to an academic network that does not allow such access"(pg.10 Chapple & Seidl 2017).


Location: Users may be granted or denied access to network resources based on their physical location
