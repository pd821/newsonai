# Anthropic's Mythos Finds 10,000 Vulnerabilities in a Month — 10x Faster Than Humans

Anthropic's security model Mythos Preview uncovered more than 10,000 high and critical vulnerabilities across partner organizations in roughly one month of operation — exposing a stark new reality: AI can now find bugs far faster than humans can fix them.

The results, generated through Anthropic's Project Glasswing initiative, involved partnerships with AWS, Apple, Broadcom, Cisco, CrowdStrike, Google, JPMorgan Chase, the Linux Foundation, Microsoft, NVIDIA, and Palo Alto Networks, among others. Cloudflare alone accounted for approximately 2,000 identified bugs, with around 400 classified as critical. Mozilla reported 271 vulnerabilities in Firefox 130 — a figure that dwarfs what standard automated testing and human reviewers typically surface.

The performance gap between AI and human testers is significant. In a comparable evaluation, Claude Opus 4.6 identified roughly 27 vulnerabilities. Mythos found ten times that number in Mozilla's codebase. Cloudflare noted that Mythos's false positive rate was, in the company's own words, "better than human testers" — a claim that would have seemed implausible two years ago.

The UK's AI Security Institute put Mythos through its own gauntlet. The model is the first AI system to solve both of the Institute's cyber ranges end-to-end, a milestone that signals a new tier of autonomous security capability. The Institute has not yet disclosed specific scores, but the achievement establishes a benchmark that future models will be measured against.

The numbers are striking. But the more consequential implication is structural: the bottleneck has shifted. Finding vulnerabilities is no longer the hard part. Triage, verification, and patching at scale is the hard part.

"We're in a world where the scanner is no longer the constraint," one security engineer at a participating firm said, speaking on condition of anonymity because the work is ongoing. "You can run Mythos and get a list back in hours. You can't fix them in hours."

That tension is already visible in how organizations are structuring their security ops. Bug bounty programs and red teams — built around the assumption that finding flaws is the scarce resource — are being re-evaluated. If AI can surface thousands of potential issues in days, human analysts must be allocated toward higher-order decisions: what to patch first, what to accept, what to escalate.

For open-source projects like those under the Linux Foundation, the challenge is compounded. Many critical libraries lack the maintainer bandwidth to respond to a sudden influx of vulnerability reports. An AI that generates a comprehensive finding list is of limited use if the maintainers cannot process it.

Anthropic has not publicly disclosed the full scope of Glasswing's scanning regime — how often it runs, whether it operates continuously, or how findings are validated before being routed to partners. The company is expected to release a technical report on the program later this year.

Project Glasswing itself is notable for its breadth. It brings together hyperscalers, financial institutions, security vendors, and chip manufacturers under a shared security evaluation framework. The participating firms represent a cross-section of the infrastructure that underpins the internet and global finance. Whether the initiative produces a standardized disclosure methodology — or remains a closed, bilateral arrangement — is an open question the industry will be watching closely.

For now, the immediate problem is not finding bugs. It is surviving the audit.

---
*Sources: Project Glasswing partner disclosures; Cloudflare security blog; Mozilla security report; UK AI Security Institute statement.*
