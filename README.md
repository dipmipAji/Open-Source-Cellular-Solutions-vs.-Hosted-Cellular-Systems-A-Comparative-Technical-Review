Open Source Cellular Solutions vs. Hosted Cellular Systems: A Comparative Technical Review
Author: Ajibawo, Oladipo Oluyemisi

Date: January 2015


Overview
This article provides a structured comparative evaluation of two enterprise telephony deployment models: Open Source Cellular Solutions and Hosted Cellular Systems. Three open source platforms (OpenBTS, OpenBSC, Asterisk) are reviewed in depth, followed by an analysis of the hosted VoIP model. Benefits and weaknesses of both approaches are assessed across cost, customisation, security, scalability, and technical complexity, concluding with a recommendation framework.

Table of Contents
·	Section 1: Introduction
·	Section 2: Open Source Cellular Solutions
·	Section 3: Hosted Cellular Systems
·	Section 4: Comparative Summary
·	Conclusion
·	References

Section 1: Introduction
Modern IP telephony enables low-cost open source systems to be integrated with existing infrastructure to deliver cellular services to an enterprise or geographic area (Lambrinos, 2008). Key platforms reviewed include:
·	OpenBTS and OpenBSC as open source GSM network components
·	Asterisk as the leading open source PBX and telephony switching platform
·	Hosted Cellular (VoIP) Systems as provider-managed cloud telephony

Section 2: Open Source Cellular Solutions
2.1 Platform Architectures
Platform	Architecture	Key Role
OpenBTS	Standalone BTS with SIP-based software switch; integrates MSC and BSC	GSM access point, converts GSM to VoIP packets
OpenBSC	Traditional GSM network-side implementation	Consolidates BSC, AuC, MSC, EIR, VLR, HLR in one platform
Asterisk	TDM + packet voice PBX; SIP, MGCP, H.323 compatible	Enterprise telephony switching, IVR, conferencing, call recording

OpenBTS and OpenBSC can be deployed together: OpenBTS provides the radio layer while OpenBSC provides the network/core functions within a standard GSM architecture.
Asterisk derives its name from the * UNIX wildcard and functions as a universal voice network component. It supports:
·	Interactive Voice Response (IVR)
·	Customised digital receptionists
·	Multiple-location telephony
·	Call conferencing and recording
·	Click-to-dial and database integration
2.2 Benefits
Benefit	Detail
Cost	Software is free; costs limited to hardware and support resources. No licensing, maintenance, or support contract fees.
Customisation	Full administrative control; integrate proprietary applications, databases, custom IVR
Interoperability	Built on open SIP standard; compatible with devices from any manufacturer
Community support	Active forums, wikis, and professional support (e.g. Digium for Asterisk)
No licence limits	Extensions and applications added without per-seat licence charges

2.3 Weaknesses
Weakness	Detail
Technical complexity	High learning curve; significant time required for configuration, hardware testing, and software compilation
Hardware compatibility	Must verify server/hardware compatibility before deployment; no guaranteed baseline
Security vulnerabilities	Open codebase exploitable by attackers; FBI/IC3 advisories document Asterisk-based auto-dialler attacks


Section 3: Hosted Cellular Systems
A Hosted Cellular System (Hosted VoIP) is a provider-managed telephone platform delivered over the internet. The service provider owns and operates all infrastructure; the client organisation requires only IP phones (and sometimes a router).
3.1 Benefits
Benefit	Detail
Low installation cost	No server or core network hardware required on-premises
Provider-managed security	Infrastructure secured and maintained by provider over business-grade connections
Predictable costs	Uniform call rates regardless of distance; fixed monthly subscription
Feature inclusivity	Voicemail, call forwarding, conferencing typically included at no extra charge
Ease of administration	Web/GUI interfaces; no specialist IT knowledge required

3.2 Weaknesses
Weakness	Detail
Expansion costs	Each additional extension incurs hardware (IP phone) + incremental service charge
Limited customisation	Provider controls feature roadmap; bespoke features unlikely for individual clients
Internet dependency	Internet outage causes partial or full telephony failure
Voice quality dependency	Call quality directly tied to internet connection speed and provider bandwidth management


Section 4: Comparative Summary
Feature	Open Source Cellular	Hosted Cellular
Initial Software Cost	Free	Subscription / licensing fees
Hardware Required	USRP, servers, BTS hardware	IP phones (router sometimes)
Customisation	Full administrative control	Limited to provider's feature set
Technical Expertise	High (required)	Low (managed by provider)
Security Responsibility	User / organisation	Service provider
Scalability Cost	Low (software-based extensions)	Per-unit hardware + service cost
Interoperability	Open SIP standard	Provider-dependent
Internet Dependency	Partial	Full
Voice Quality Control	Full control	Dependent on provider / bandwidth
Maintenance	Community / self-managed	Provider-managed
Best Suited For	IT-literate SMEs, research, universities	Non-technical SMEs, distributed teams


Conclusion
Open source is most appropriate for: Technically capable organisations with constrained capital budgets requiring full customisation and control. Ideal for IT companies, universities, and research institutions. Note: recurring professional support costs may erode initial savings over time for organisations lacking in-house expertise (Soares et al., 2008).
Hosted solutions are most appropriate for: Organisations prioritising operational simplicity, predictable costs, and provider-managed resilience, particularly where dedicated IT resources are limited. Consistency, responsiveness, and instant provider support are the primary differentiating benefits.

References
·	Abhinav, V., Veljko, P., Elizabeth, B. and David, J. (2012). Village: Cost Effective Cellular Connectivity in Rural Areas. Proceedings of the Fifth International Conference on Information and Communication Technologies and Development, pp. 180-189.
·	Asterisk.org (2014). Asterisk.org. Available at: http://www.asterisk.org
·	Baharlooei, Z. and Hashemi, M. (2009). A Low Cost VoIP Architecture for Private Networks. International Conference on Future Networks, pp. 8-12.
·	Lambrinos, L. (2008). Deploying Open Source IP Telephony in Rural Environments. NGMAST 2008, pp. 623-627.
·	Range Networks (2012). OpenBTS and the Future of Cellular Networks.
·	Rosenberg, J., Schulzrinne, H. et al. (2002). SIP: Session Initiation Protocol. RFC 3261, pp. 1-269. Available at: http://www.ietf.org/rfc/rfc3261.txt
·	Soares, V., Sousa, J.P. and Neves, J. (2008). Past, Present and Future of IP Telephony. International Conference on Communication Theory, Reliability, and Quality of Service, pp. 19-24.
·	Tsou, T., Huang, C., Yamani, H. and Stasinopoulos, J. (2012). Development of an Open Source GSM Femtocell and Integrated Core Infrastructure. Military Communications Conference 2012, pp. 1-6.
·	Welte, H., Freyther, H. et al. (2012). OpenBSC. Available at: http://openbsc.osmocom.org

Ajibawo, Oladipo Oluyemisi

