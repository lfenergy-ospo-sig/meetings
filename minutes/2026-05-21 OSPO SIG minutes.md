# Attendees

- Alex Thornton (LF Energy)
- Max Capraro (Capraro-Dorner)
- Michael Dorner (Capraro-Dorner)
- Boris Dolley (RTE)
- Christopher Atkins (MISO)
- Hugo Pfister (TenneT)
- Kayvan Azari (Axpo AG)
- Marco Gazzuolo (Enel)
- Misho Chigrichenko (Göteborg Energi)
- Sven Fritzsche (Elia / 50Hertz)

# Introductions from newcomers

- Max Capraro & Michael Dorner (Capraro-Dorner) — introduced themselves as part of their presentation.

# CapEx, OpEx & Open Source — research project intro (Capraro-Dorner)

Max and Michael presented their ongoing research into why CapEx/OpEx accounting treatment discourages TSOs/DSOs from *creating* open source, and asked the group for input and interview volunteers ([slides](../assets/2026-05-21%20-%20CapEx%2C%20OpEx%20%26%20Open%20Source%20-%20Capraro-Dorner.pdf)).

## Discussion

- **Sven (50Hertz):** Highly relevant — often hears "we'd open source it, but we can't" for software built up over years.
- **Hugo (TenneT):** Disincentive is even bigger for TSOs, who earn a **regulated profit on CapEx**, so there's a positive pull to spend it. Open-sourcing self-developed software gives away the **IP** (where the balance-sheet value sits). Separately: EU TSOs/DSOs are mostly public/semi-public, so bilateral code-sharing risks legal/state-aid issues — the **full open source route is the cleanest way to collaborate**. Also cautioned that TSOs aren't software vendors and must avoid **interfering with the market/competition**.
- **Boris (RTE):** Flagged **IAS 19 vs. IAS 38** (OT vs. IT). Raised a "kill switch" angle — you can retain exclusive control of your **private instantiation/implementation** even without controlling the open source project itself. Asked whether anyone has ever been **penalized** for capitalizing open source (Max: not aware — the chilling effect hits earlier, via risk-averse controllers). Sketched a "vicious life cycle" and a theory that IAS 38's ~20% maintenance/new-feature threshold could enable an **"infinite CapEx loop."**
- **Misho (Göteborg Energi):** For a smaller DSO the amounts are tiny vs. grid infrastructure, so controllers likely won't scrutinize. The real intangible asset is the **capability** (people, knowledge) around the software, not the (free) software itself. Standardized OSS also creates an **operations ("drift") market** that can be outsourced.
- **Christopher (MISO):** For entities that "don't put steel in the ground," software is the **majority of CapEx**, so it matters more. Asked whether **joint development companies / consortiums** could be a capitalization vehicle (possibly retaining marketability via business-source licensing). Max: source-available/BSL is a possible but likely **anti-pattern** for community building (fewer users, OSPO licensing friction). Christopher registered **ospo.energy** for a forkable, energy-focused OSPO bootstrap + onboarding toolkit (US accounting, FERC, NERC).
- **Kayvan (Axpo):** The persuasion target is the **municipality/regulator**, not the company — software-as-asset is a public good like a transformer and the argument should run on that line, rather than getting trapped in accounting wording that leaves no room to justify CapEx.

## Interview volunteers

- Hugo (TenneT); Boris (RTE — hopes to bring finance colleagues + RTE's external consultant); Misho (will try to recruit a Göteborg Energi controller).

# Updates from the group

- **World Bank connection:** Boris led a birds-of-a-feather session on this topic at last year's LF Energy (Aachen); the original requester was from the World Bank. Anders Pedersen (World Bank) flagged — Alex to get him involved.
- Sven already emailed the presenters' contacts about whether they'd hit the OpEx/CapEx-with-FOSS problem; group suggested also asking for an **IFRS update**.

# Other notes

- Alex updated the **Open Source Readiness Guide** — the build process is now running; he'll continue incremental updates and share with the group.

# Next meeting

- Next month. Preliminary study results targeted for the LF Energy Summit.