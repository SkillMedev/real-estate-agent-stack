# Real Estate Agent Stack

**For residential agents: listings that sell, nurture that converts, negotiations you control.** — built in-house by [Skill&nbsp;Me](https://skillme.dev/?utm_source=github&utm_medium=readme&utm_campaign=pack-real-estate-agent-stack).

Reach for this when you sell residential real estate and the between-showings work decides your year: listing copy, pricing conversations, follow-up, and negotiation prep. It covers the agent's actual workflow - write listing descriptions that sell the property without fair-housing risk, turn a CMA into a pricing story sellers accept, convert open-house visitors with same-evening follow-up, keep unready buyers warm for months with context-rich nurture, win listings before the competition is invited via seller-lead touches, and walk into offer and inspection negotiations with a prepared position instead of improvisation. Every skill carries fair-housing and brokerage-compliance guardrails. One worked example - a suburban agent building from 14 toward 24 transactions - threads throughout.

## Install

- **Claude, ChatGPT, Codex, Cursor (connector):** [install the whole pack from skillme.dev](https://skillme.dev/pack/real-estate-agent-stack?utm_source=github&utm_medium=readme&utm_campaign=pack-real-estate-agent-stack) — one connection, then ask for any skill by name.
- **As files for Codex, Cursor, or Claude Code:** `npx @skillme/cli add listing-description-writer cma-narrative-builder open-house-follow-up buyer-nurture-sequence seller-lead-nurture re-negotiation-prep --target all`
- **With the skills CLI:** `npx skills add SkillMedev/real-estate-agent-stack`
- **Manually:** copy any `skills/<slug>/SKILL.md` into `.agents/skills/`, `.cursor/skills/`, or `.claude/skills/`.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Skills in this pack

- **[Listing Description Writer](skills/listing-description-writer/SKILL.md)** — Writes MLS and portal listing copy that sells the property - lead with the differentiator, translate features into benefits, specifics over adjectives, platform length limits, and a fair-housing-safe banned-claims list.
- **[CMA Narrative Builder](skills/cma-narrative-builder/SKILL.md)** — Turns a comparative market analysis into a pricing story a seller accepts - defensible comp selection, plain-language adjustments, the overpricing-cost math, and a price-band recommendation aligned to portal search brackets.
- **[Open House Follow-Up](skills/open-house-follow-up/SKILL.md)** — Converts open-house visitors into clients with door capture, a same-evening first touch, a 3-touch follow-up sequence, and buyer-signal triage by financing and timeline.
- **[Buyer Nurture Sequence](skills/buyer-nurture-sequence/SKILL.md)** — Keeps not-yet-ready homebuyers warm for months with timeline-based segmentation, listing alerts with a why-this-one note, a monthly market-update touch, the pre-approval nudge, and re-engagement triggers.
- **[Seller Lead Nurture](skills/seller-lead-nurture/SKILL.md)** — Wins listings before competitors are invited by nurturing homeowner leads with quarterly home-value updates, an equity-position letter, lifecycle triggers like a neighborhood sale, and the CMA offer as the conversion event.
- **[RE Negotiation Prep](skills/re-negotiation-prep/SKILL.md)** — Prepares real estate agents for offer and inspection negotiations with a two-sided position worksheet, offer-strength evaluation beyond price, repair-vs-credit-vs-price-reduction decision rules, escalation-clause mechanics, and a pre-set walk-away number.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev/browse?utm_source=github&utm_medium=readme&utm_campaign=pack-real-estate-agent-stack).
