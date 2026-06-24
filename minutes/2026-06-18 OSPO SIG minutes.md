# Attendees

- Alex Thornton (LF Energy)
- Sven Fritzsche (50Hertz - Elia Group)
- Hugo Pfister (TenneT)
- Kayvan Azari (Axpo)
- Geethu Joseph (CRESYM)
- Kjell Petter Myhren (Statnett)

# Introductions from newcomers

# Updates from the group

## EU Open Source / Digital Sovereignty Policy Forum (Brussels)

- Sven and Hugo attended; government agencies and big players (Siemens, ARM) present. Face-to-face conversations afterward were valuable.
- 3 TSOs in the room — over-represented vs. the market, showing real interest. The Dutch government OSPO presented a very well-developed open source strategy.
- A **position paper** on how LF Energy fits the EU Tech Sovereignty + energy digitalization narrative is still on Alex's list — he'll draft an outline for feedback; could be an early assignment for Stephan (starts in ~a month, Brussels-based).
- LF Energy is working to back the "digital sovereignty" positioning with substance: euro-denominated membership / European legal entity at the LF Energy layer, plus European-resident staff.

## ROSC — regional coordination project

- Large regional coordination project involving most European TSOs (esp. the Core region, many DSOs). ~€80M already spent on a single vendor that hasn't delivered; the board is fed up and is exploring **co-development** instead of full vendor procurement.
- First drafts date to 2017–2019; target is ~2029 (~10 years).
- Open source options in the plan to the ENTSO-E board: **ReFlow** for AC calculations, **GridSuite** for topology optimizations, **OpenRAO** already in use (not yet well).
- Open questions: how to handle IP, and how to reimburse orgs (e.g. TenneT, RTE) that contribute disproportionate effort.
- Good moment for a position paper / draft in the next few weeks; worth influencing ENTSO-E soon.
- ROSC / CSA explainer (vs. ENTSO-E's 100+ page PDFs): https://www.n-side.com/en/insights/navigating-complexity-rosc-for-a-resilient-european-grid/

## Leveraging research to influence regulation

- Kayvan: how can LF Energy use its studies/case studies as evidence to shape upcoming national/cross-national regulation — as a **neutral fact provider**, not a lobbyist?
- Switzerland mandated open-source-first for government entities from 2024 (not yet extended to regulated energy companies). German and Belgian regulators have drafted open source into proceedings:
  - Germany: [BK6-24-210-1_IT_Leitlinien.pdf](https://www.bundesnetzagentur.de/DE/Beschlusskammern/1_GZ/BK6-GZ/2024/BK6-24-210/BK6-24-210-1/Anlagen/BK6-24-210-1_IT_Leitlinien.pdf?__blob=publicationFile&v=2) (point 1.1) — Sven to forward
  - Belgium: regulatory draft (French) — already sent to Alex
- Challenge: many players oppose open source out of misunderstanding, so we must keep proving it works (e.g. PowSyBl case study). E.ON is split — developers pro-open-source, business sells licenses.
- Alex: no plan yet but the ambition exists. Steps: the research, a local hire next month, and a **case study library**. "Lobby" means educating/participating in the regulatory process, not wining and dining; bandwidth is the constraint. Looking for regulator contacts to attend the Summit.

## CRESYM OSPO

- Geethu presented the OSPO roadmap at a Crossroads event ~2 months ago; many members still don't know what an OSPO or open source is. The LF Energy readiness guide/levels are of interest to CRESYM.
- Engagement works best through **project-specific discussions** (esp. with researchers/PhD candidates), not generic governance presentations. Geethu asked the group for effective ways to demonstrate practical value, given CRESYM spans multiple industries, standards, and vendors.

## Engagement advice (Sven, Hugo)

- **Approach everyone** and offer to help with a problem they have (50Hertz offers license compliance, migration paths); those who share the belief become allies.
- A **pro-open-source IT lawyer** is a major unblocker. 50Hertz's lawyer would welcome an EU TSO legal exchange (already in touch with RTE; Hugo to connect TenneT's new legal contact).
- 50Hertz found someone in the regulatory team **genuinely interested** in open source — interested people contribute more than assigned ones.
- LF reference: bi-weekly members-only **legal roundtable** + annual **legal summit**; LF's legal team is among the most experienced in open source (e.g. created an AI-model license recently adopted by NVIDIA). Alex to send Hugo a description.

## LF Energy Summit

- Agenda posted; many members speaking, heavy open source strategy focus (most of Tuesday).
- In-person OSPO SIG meeting the day before the Summit, ~10:30–14:30, at the Smart Village conference venue (50Hertz rooms had guest-access constraints). Alex to send a calendar email.
- Events spread across Berlin (BearingPoint, 50Hertz, E.ON meetups; CRESYM side event 13:00–17:00). A broader PowSyBl community meetup is being requested following the Paris event; venue likely Smart Village, not yet scheduled.
- LF Energy increasingly nurturing individual project communities (PowSyBl, Power Grid Model, SEAPATH) with their own meetups.

## TenneT OSPO

- Real progress: hired a trainee for project management; engaged legal, procurement, marketing/comms, IT, and security.
- Updating internal directives (secure development, open source strategy, reuse-before-buy-before-build); running monthly software scans; preparing for ISO certification by November.
- Following the Alliander model — a **virtual OSPO of ~5–6 people** with business- and IT-side sponsors and a layer of domain experts. 2–3 identified, including a strong ambassador; planning a recruitment lunch session.

# Direction of the group

Alex asked whether the group should build artifacts (the readiness guide) or stay an organic roundtable.

- **Sven** prefers the roundtable — hearing from others, surfacing duplicate efforts before two orgs build/open-source the same thing, and getting help on live problems.
- **Hugo** agrees; tied to maturity level. As the group matures it can get concrete and build a body of knowledge; right now it feels more like consuming than contributing.
- **Kayvan** has strong group buy-in and CIO approval but hits a wall at sea level on budget (a study's results were not rosy, so leadership stopped it). Needs help bringing the C-suite on board.
- **Geethu** values the shared knowledge as a learning path for an OSPO beginner.

**Direction:** Keep it organic/roundtable — not ready for a cohesive readiness guide yet. Instead, turn already-shared materials into a **semi-structured reference library** (how 50Hertz / RTE / Alliander / TenneT each do it, where shareable). Distill into an LF Energy guide later as the group matures. Agreed.

# What is "open source"?

- Kjell Petter asked for a definition: Statnett staff say they don't use open source — yet rely on Linux, PostgreSQL, Red Hat, Kubernetes, often via service providers.
- Hugo: the real issue is **platform vs. business function** — open source as a platform (Kubernetes, Postgres) is accepted, but the same model for a business function (e.g. running PowSyBl on a service contract via Artelys) triggers panic. The mindset, not the definition, is what must change.
- Sven: teams guess ~30 open source libraries; reality is ~100,000 packages (~400 per repo). Statnett's own GitHub (https://github.com/statnett) is a role model. Take everyone on the journey and contribute upstream rather than adding a private "pinch of salt" each download.

# Reference links shared

- Baltic RCC GitHub: https://github.com/Baltic-RCC
- Statnett GitHub: https://github.com/statnett
- ROSC / CSA explainer: https://www.n-side.com/en/insights/navigating-complexity-rosc-for-a-resilient-european-grid/
- Germany BNetzA IT-Leitlinien: [BK6-24-210-1_IT_Leitlinien.pdf](https://www.bundesnetzagentur.de/DE/Beschlusskammern/1_GZ/BK6-GZ/2024/BK6-24-210/BK6-24-210-1/Anlagen/BK6-24-210-1_IT_Leitlinien.pdf?__blob=publicationFile&v=2) (point 1.1)

# Action items

- [ ] Alex to draft an outline of the EU position paper; potential early assignment for Stephan
- [ ] Alex to start a semi-structured reference library (member policies/strategies, shared where possible)
- [ ] Alex to send the in-person OSPO SIG calendar invite for the day before the Summit
- [ ] Alex to send Hugo a description of the LF legal roundtable / legal summit
- [ ] Sven / Hugo to connect their IT lawyers for an EU TSO legal exchange

# Next meeting

- In-person OSPO SIG meeting the day before LF Energy Summit (Smart Village, ~10:30–14:30).