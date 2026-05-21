# GitHub Confirms Major Supply Chain Attack — 3,800 Repos Breached via VS Code

GitHub has confirmed a security breach affecting roughly 3,800 internal repositories, after an employee installed a malicious extension from the VS Code Marketplace. The attack, attributed to the TeamPCP hacker group, targeted the developer's own tooling marketplace — a vector that security researchers have long warned about but rarely see at this scale.

The company said it detected and contained the compromise after a device was infected via a poisoned Visual Studio Code extension. "We removed the malicious extension version, isolated the endpoint, and began incident response immediately," GitHub stated. The malicious extension has since been removed from the marketplace.

GitHub's assessment is that the breach involved exfiltration of internal repositories only. There is no evidence customer data was affected, the company said. However, TeamPCP claimed on a cybercrime forum to have accessed around 4,000 repositories of private code, setting a minimum asking price of $50,000.

The group has a track record. TeamPCP has been linked to a string of major supply chain attacks across GitHub, PyPI, NPM, and Docker, as well as a campaign dubbed "Mini Shai-Hulud" — which also impacted two OpenAI employees.

**A known, unresolved problem**

The VS Code Marketplace has faced repeated abuse. Previous incidents include extensions with millions of installs pulled over security risks, extensions that deployed XMRig cryptominers, and as recently as January 2026, extensions that exfiltrated data to servers in China. The platform has become a reliable entry point for supply chain attacks precisely because developers trust it — and because the bar for publishing an extension is low.

This incident underscores a fundamental tension in modern development: the tools developers rely on to stay productive are also increasingly attractive attack surfaces. A single compromised extension can give an attacker access to source code, credentials, and internal infrastructure — everything needed for a thorough breach.

GitHub said it is continuing its investigation and has notified relevant authorities. For the broader developer community, the episode is a reminder that the supply chain runs both ways — and the marketplace you trust to install your code editor plugins is itself part of your attack surface.

The investigation is ongoing.

---
*Sources: BleepingComputer, GitHub statement, cybercrime forum post*