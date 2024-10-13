# Intern-Intelligence--Security-Policy-Review-and-Enhancement

The example of Remote Access Tools Policy from https://www.sans.org/:
--------------------------------------------------------
Remote Access Policy

1. Overview
Remote access to our corporate network is essential to maintain our Team’s productivity,
but in many cases this remote access originates from networks that may already be
compromised or are at a significantly lower security posture than our corporate network.
While these remote networks are beyond the control of Hypergolic Reactions, LLC policy,
we must mitigate these external risks the best of our ability.

2. Purpose
The purpose of this policy is to define rules and requirements for connecting to <Company
Name>'s network from any host. These rules and requirements are designed to minimize
the potential exposure to <Company Name> from damages which may result from
unauthorized use of <Company Name> resources. Damages include the loss of sensitive
or company confidential data, intellectual property, damage to public image, damage to
critical <Company Name> internal systems, and fines or other financial liabilities incurred
as a result of those losses.

3. Scope
This policy applies to all <Company Name> employees, contractors, vendors and agents
with a <Company Name>-owned or personally-owned computer or workstation used to
connect to the <Company Name> network. This policy applies to remote access
connections used to do work on behalf of <Company Name>, including reading or sending
email and viewing intranet web resources. This policy covers any and all technical
implementations of remote access used to connect to <Company Name> networks.

4. Policy
It is the responsibility of <Company Name> employees, contractors, vendors and
agents with remote access privileges to <Company Name>'s corporate network to
ensure that their remote access connection is given the same consideration as the
user's on-site connection to <Company Name>.
General access to the Internet for recreational use through the <Company Name>
network is strictly limited to <Company Name> employees, contractors, vendors and
agents (hereafter referred to as “Authorized Users”). When accessing the
<Company Name> network from a personal computer, Authorized Users are
responsible for preventing access to any <Company Name> computer resources or
data by non-Authorized Users. Performance of illegal activities through the
<Company Name> network by any user (Authorized or otherwise) is prohibited. The
Authorized User bears responsibility for and consequences of misuse of the
Authorized User’s access. For further information and definitions, see the
Acceptable Use Policy.
Authorized Users will not use <Company Name> networks to access the Internet for
outside business interests.
For additional information regarding <Company Name>'s remote access connection
options, including how to obtain a remote access login, free anti-virus software,
troubleshooting, etc., go to the Remote Access Services website (<company url>).

4.1Requirements
4.1.1 Secure remote access must be strictly controlled with encryption (i.e.,
Virtual Private Networks (VPNs)) and strong pass-phrases. For further
information see the Acceptable Encryption Policy and the Password
Policy.
4.1.2 Authorized Users shall protect their login and password, even from family
members.
4.1.3 While using a <Company Name>-owned computer to remotely connect to
<Company Name>'s corporate network, Authorized Users shall ensure
the remote host is not connected to any other network at the same time,
with the exception of personal networks that are under their complete
control or under the complete control of an Authorized User or Third
Party.
4.1.4 Use of external resources to conduct <Company Name> business must
be approved in advance by InfoSec and the appropriate business unit
manager.
4.1.5 All hosts that are connected to <Company Name> internal networks via
remote access technologies must use the most up-to-date anti-virus
software (<place url to corporate software site here>), this includes
personal computers. Third party connections must comply with
requirements as stated in the Third Party Agreement.
4.1.6 Personal equipment used to connect to <Company Name>'s networks
must meet the requirements of <Company Name>-owned equipment for
remote access as stated in the Hardware and Software Configuration
Standards for Remote Access to <Company Name> Networks.

5. Policy Compliance
5.1Compliance Measurement
The Infosec team will verify compliance to this policy through various methods,
including but not limited to, business tool reports, internal and external audits, and
feedback to the policy owner.
5.2Exceptions
Any exception to the policy must be approved by the Infosec team in advance.
5.3Non-Compliance
An employee found to have violated this policy may be subject to disciplinary action, up
to and including termination of employment.

6. Related Standards, Policies and Processes
Please review the following policies for details of protecting information when
accessing the corporate network via remote access methods, and acceptable use of
<Company Name>’s network:
• Acceptable Encryption Policy
• Acceptable Use Policy
• Password Policy
• Third Party Agreement
• Hardware and Software Configuration Standards for Remote Access to
<Company Name> Networks
--------------------------------------------------------


***Enhancement:***
1. Overview
Gap: The overview provides general information about remote access risks but does not explicitly mention specific risk management processes or guidelines for securing remote connections.

Enhancement:

Remote access risk assessments must be performed regularly to ensure compliance with security standards, following ISO/IEC 27001 Control A.6.1.2 (Information Security Risk Management).

2. Purpose
Gap: The purpose statement is clear but lacks reference to ongoing risk management or legal compliance (e.g., GDPR, data privacy regulations) which ISO/IEC 27001 emphasizes.

Enhancement:

Not just minimizing damage, but also ensuring compliance with legal, regulatory, and contractual requirements related to remote access. This aligns with ISO/IEC 27001 Control A.18.1.1 (Identification of applicable legislation and contractual requirements).

3. Scope
Gap: The scope section does not mention specific environments where remote access could be used, such as cloud or third-party services, which are essential in modern IT environments.

Enhancement:

Scope covers access from third-party networks and cloud-based services. ISO/IEC 27001 Control A.13.2.4 (Security of network services) and NIST PR.AC-5 recommend security controls for connections to third-party networks and cloud environments.
Updated Text Example:

"This policy applies to all remote access connections used to connect to <Company Name>'s corporate network, including cloud environments, third-party networks, and mobile devices."

4. Policy
4.1 Requirements
Gap: The policy requires VPN and encryption but does not mention the use of multi-factor authentication (MFA) or specific encryption protocols, both of which are best practices.

Enhancement:

Requirement for multi-factor authentication (MFA) for all remote access sessions, as recommended by NIST PR.AC-7 and ISO/IEC 27001 Control A.9.4.3 (Use of privileged utility programs).
Specify acceptable encryption standards such as AES-256 for VPN connections, which aligns with ISO/IEC 27001 Control A.10.1.1 (Cryptographic controls) and NIST PR.DS-1 (Data-in-transit encryption).
Updated Text Example:

"4.1.1. Secure remote access must be controlled using AES-256 encryption for VPNs and multi-factor authentication (MFA) to enhance protection."
"4.1.6. All remote access connections must use MFA, and third-party access must meet equivalent security controls."

Gap: Policy lacks specific mention of logging and monitoring remote access sessions, which is essential for detecting potential breaches.

Enhancement:

Introduce a requirement for logging all remote access activities and monitoring these logs for suspicious behavior. This is supported by ISO/IEC 27001 Control A.12.4.1 (Event logging) and NIST DE.CM-1 (Continuous monitoring).
Updated Text Example:

"4.1.7. All remote access sessions must be logged, and these logs should be monitored regularly for unauthorized access or suspicious activity."

5. Policy Compliance
Gap: While compliance verification is mentioned, the policy doesn't describe incident response actions in case of non-compliance or breach.

Enhancement:

Incident response procedures in case of policy violations or security breaches during remote access, aligning with ISO/IEC 27001 Control A.16.1.1 (Responsibilities and procedures) and NIST Respond (RS) functions.
Updated Text Example:

"5.4. In case of a security breach related to remote access, immediate incident response procedures must be followed, as defined by <Company Name>'s Incident Response Plan."
