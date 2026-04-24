# Attendees

- Boris Dolley (RTE)
- Alex Thornton (LF Energy)
- Moise Kameni (Hydro-Quebec)
- Christopher Atkins (MISO)
- Sven Fritsche (50hertz)
- Marco Gazzuolo (Enel)
- Benjamin Rilx (E.ON)
- Kayvan Azari (Axpo)
- Misho Chigrichenko (Goteborg Energi)
- Hugo Pfister (TenneT)
- Walter van der Klugt (TenneT)
- Leander van der Bijl (Alliander)

# Introductions from newcomers

# Updates from the group

- Kayvan shared that SUSE will be creating a SUSE flavor of SEAPATH
- 50hertz published their 2nd open source repository https://github.com/eliagroup/DCPlus
- TenneT setting up OSPO with Walter in lead for next 6 months. Discussion from the group about how to facilitate compliant submissions to open source projects.
  - We explored specifically compliant contributions to external open source projects and how various companies handle it
  - Sven shared the [11-point contribution checklist from 50Hertz](#50hertz-11-point-contribution-checklist)
- Boris mentioned that RTE is exploring an AI-enabled way of interacting with knowledge management

# Open Source Readiness Guide

Walk through each section of https://osr.finos.org and assess for applicability to energy.

## Artifacts

Largely transferable.
- CVEs, DLP software, IP artifacts — all directly relevant.

## Activities

Largely transferable.
- Level 2 ("Compliant usage") maps onto Hugo's policy question.

## Measurements

Largely transferable.
- Notable point: can't get metrics if contributions are on personal accounts — ties back to account-policy discussion.

## Roles

Some adaption needed.
- Legal, CISO carry over; grid-operator-specific roles need to be defined.

## Regulations

Biggest gap, significant rewrite needed.
- Anti-money-laundering (FINOS) → NERC / NERC CIP (US), plus EU.
- Boris asked how to handle non-EU/US regulation (Asia, Africa); Alex proposed organizing by geography and expanding as engagement grows.
- Marco pushed to broaden beyond regulation to include **ethics, UN SDGs, sustainability**.
- Kayvan added Swiss anti-corruption/compliance framing.
- Boris proposed connecting to **UN Open Source Principles** and **Digital Public Good** assessment (useful for EU/international funding).

## Risks

Mostly agnostic, minor additions. 
- Code-base risk, data leakage, dependency — all carry over.
- Energy-specific additions: **OT/ICS security**, **critical-infrastructure risk**, and **TSO-vs-vendor viewpoint differences** (Boris: an assessment should serve both utilities and vendors/digital-service-providers/OT hardware vendors — not just the utilities on today's call).

## Open Source Maturity Model (OSMM)

Largely transferable, but need to determine structure and consistency. 
- FINOS OSMM is not identical to the TODO Group maturity model.
- Boris noted Ibrahim Haddad's recent work on **AI-aware maturity models** (incl. AI license impact on OSPOs) — suggests a bibliography/landscape review before we choose or author one.
- Moïse suggested **merging Activities and OSMM** so each maturity level explicitly describes the pathway for moving up a level.

## Training

Somewhat transferable.
- Secure-software, license-compliance — directly reusable.
- Need to create energy-specific content.

## Certifications

Adaption needed, and would be useful to create.
- Alex's initial view: no market for it in energy (workforce too small vs. financial services).
- Hugo pushed back: the **combination of cloud-native engineering skill + energy-sector operational understanding** is rare and valuable.
- Christopher reinforced: North American energy industry is heavily credential-oriented; certification should be an **outcome** of a good curriculum, not the goal. Christopher proposed an **"open source radar" for OSPOs** — center = highly adoptable, edges = low adoptability — with heuristics including OpenSSF / OpenChain badges. *"People need badges, and repos need badges, and we should supply both."*

## Compliance / OpenChain / OpenSSF linkage

Needs placement in the guide
- Boris: where does OpenChain (license compliance) and OpenSSF (security) fit relative to our maturity stages?
- Kayvan: maybe a lightweight checklist per stage — not strict, but directional.
- Alex agreed this belongs somewhere, likely alongside Risks/Mitigations or Compliance.

Action items:
- [ ] Set up GitHub Actions for building and deploying the LF Energy fork of the readiness guide https://github.com/lfenergy-ospo-sig/open-source-readiness [Alex and Marco]
- [ ] Update CONTRIBUTING.md for the LF Energy OSR https://github.com/lfenergy-ospo-sig/open-source-readiness/blob/main/CONTRIBUTING.md [Alex and Christopher]
- [ ] Alex to take first pass at proposing some changes to the guide for review next month

# Next Meeting

- Continue readiness guide work together

# 50hertz 11-point contribution checklist

Note: Our Contribution guildeine is in a pilot phase therefore Check 1 is in place.
The actual wiki guide is of course longer and more detailed

✓ Check 1: You received OSPO's okay
✓ Check 2: You have a clear business motivation
✓ Check 3: Your contribution is small
✓ Check 4: Your contribution does not infringe third party's right
✓ Check 5: Your contribution will not disclose trade secrets or any confidential information
✓ Check 6: Your contribution will not disclose colleagues' personal data
✓ Check 7: You adhere to the project's contribution guide
✓ Check 8: You treat community members like you want to be treated
✓ Check 9: You understood & addressed liability risks
✓ Check 10: You received sign-off on CLAs / DCO (if there is one)
✓ Check 11: Your GitHub account is connected to /eliagroup and you signed your commit with the your mail
