# Attendees

- Boris Dolley (RTE)
- Moïse Kameni (Hydro-Québec)
- Alex Thornton (LF Energy)
- Kayvan Azari (Axpo)
- Jonas van den Bogaard (Alliander)
- Hugo Pfister (TenneT)
- Sven Fritzsche (Elia / 50Hertz)
- Benjamin Rilz (E.ON)
- Stephan Gross (LF Energy)
- Marco Gazzuolo (Enel)

# Introductions from newcomers

- Stephan Gross introduced himself as LF Energy's new Community Director for Europe (based in Brussels, background in DSO/TSO institutional representation).

# Updates from the group

## RTE

- Building an AI-enabled open source knowledge base/chatbot for the OSPO — covering questions like "should this go open source" and community viability, driven partly by French/EU sovereignty priorities.
- Starting RTE-local; could later extend to an LF Energy or broader open source version. First deliverable targeted for end of year; RTE open to demoing progress to the group.

## Hydro-Québec

- Largely occupied the past couple months with cybersecurity response tied to the Mythos incident.
- Attended one day of UN Open Source Week; noted a heavy focus this year on AI and digital sovereignty.

## LF Energy

- Stephan Gross has joined as Community Director for Europe.
- Draft position paper on how LF Energy fits the EU tech sovereignty + energy digitalization narrative is still in early/skeleton form [link](https://docs.google.com/document/d/1GWQJujIRFR69LBMPQK4hpb2FIAtmBvqPTEzPx5vn1cc/edit?usp=sharing). Target: turn into a 10–20 page paper over the next ~2 months.
- Akrites and FINOS's OSERA flagged as related initiatives (see discussion below).

# Discussion: AI-augmented cybersecurity / shared vulnerability hardening

- Context: Akrites (cross-industry) and OSERA (FINOS's finance-sector version) pool members' SBOMs, identify shared upstream dependencies, jointly fund AI-assisted vulnerability analysis and remediation, and share CVEs/patches privately before public disclosure.
- Alex floated whether an energy-sector-specific version would be of interest — still idea/feeling-out stage, no concrete ask yet.
- Hugo: supportive, especially for common vendor tooling used across TSOs/DSOs (cloud infra, Kubernetes, etc.); willing to raise with TenneT's security team.
- Kayvan: asked how open these committees are and how to access shared dependency/vulnerability lists; flagged this as a question for the community on the risk/benefit and legal framework of sharing dependency data.
- Moïse: echoed the concern — unclear whether organizations are transparent enough to share that information.
- Boris: raised a sovereignty dilemma — using US-based proprietary AI (e.g. OpenAI, Anthropic) to defend against threats that AI itself enables is uncomfortable, especially with no European frontier-lab equivalent yet. Separately, cited VLC's Jean-Baptiste Kempf and curl's Daniel Stenberg's public stance that generative AI has made open (and closed) source more exposed, and that the community should own this rather than deny it — likely a multi-year (3–5 year) weak period while existing code gets hardened.
- Hugo: also raised IT/OT convergence as its own risk factor — OT systems are more air-gapped and change much more slowly than IT, so any initiative here would likely be IT-focused; patch rollout speed and change management differ significantly for OT.
- Outcome: no action items yet; Alex continuing to gather reactions before scoping whether this becomes a concrete LF Energy initiative.

# AI-assisted contributions to open source projects

- Jonas: OpenSTEF is seeing more AI-assisted external contributions — lowers the barrier to entry, but also creates more noise/low-value PRs for maintainers to triage.
- Alliander is introducing AI-assisted contribution guidelines maintainers can point to when declining a contribution (example shared: [OpenSTEF CONTRIBUTING.md](https://github.com/OpenSTEF/.github/blob/main/CONTRIBUTING.md#ai-assisted-contributions)). Jonas will also present this at the TAC.
- Moïse suggested opening a GitHub issue to track/continue the discussion.

# LF Energy Summit — in-person OSPO SIG meeting

- Scheduled Monday, September 14, 10:30–14:30 (the day before the Summit); open invite for other interested utilities, not just current members.
- Jonas and Stephan to lead prep and will set up a dedicated event page for visibility/registration, similar to other project workshops at the Summit.
- Boris suggested a shared backlog document to crowdsource and rank agenda topics asynchronously ahead of the session.

# Next meeting

- August 20 meeting: discussed keep vs. cancel given the holiday season. Group agreed to keep it — useful as a final sync ahead of the Summit (RTE and Alliander/Stephan confirmed they'd attend).

# Follow-ups / action items

- [ ] Alex to share the draft position paper with the group.
- [ ] Moïse to open a GitHub issue on AI-assisted contributions / dependency-sharing discussion.
- [ ] Jonas and Stephan to develop the agenda and event page for the in-person Summit-adjacent session.

# Reference links

- Akrites launch: https://www.linuxfoundation.org/press/linux-foundation-and-industry-leaders-launch-akrites-to-defend-critical-open-source-software-against-ai-enabled-cyber-threats
- FINOS OSERA announcement: https://www.linuxfoundation.org/press/finos-announces-intent-to-form-osera-a-global-financial-services-led-alliance-for-open-source-supply-chain-resiliency-in-the-era-of-ai
- OpenSTEF AI-assisted contributions guideline: https://github.com/OpenSTEF/.github/blob/main/CONTRIBUTING.md#ai-assisted-contributions

Agenda: https://github.com/lfenergy-ospo-sig/meetings/issues/15
