# Changelog

All notable changes to this project are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); this project will adopt
[Semantic Versioning](https://semver.org/) once it ships releasable artifacts.

## [Unreleased]
### Added
- Interactive guided walk-through on the wireframe (`Project planning/index.html`):
  a scenario-driven product tour (competitor part to cross to captured opportunity
  to worked to measured) with spotlight + popup, persona/view switching, keyboard
  nav, and a `?tour=1` deep-link for auto-start. Stays anonymized (no real names).
- Architecture and governance scaffold: `README`, `ARCHITECTURE`, ADR practice
  (`docs/adr/`), `CONTRIBUTING`, `SECURITY`, this changelog.
- Repo consistency + collaboration tooling: `.editorconfig`, `.gitattributes`,
  expanded `.gitignore`, CODEOWNERS, PR/issue templates, Dependabot, guardrail CI.
- Vetted, Markdown-only Claude Code skills under `.claude/skills/` and an upgraded
  `CLAUDE.md` operating agreement.
- Board pitch under `Board pitch/`: a 2-page decision brief (`.docx`) and an
  8-slide deck (`.pptx`), both generated from the `Project planning/` source of
  truth, plus their build scripts. The deck ends on the ask (read-only access,
  Azure environment, governance liaisons); the brief adds the developer tooling /
  hardware / budget request.

### Changed
- Recalibrated the board pitch per stakeholder review: reframed from "convert
  competitor sell-through for margin" to "give the Owned Brands team the data
  signals to help WCO sellers win deals and hold margin." Clarified that platform
  users are the OB sales team, their call targets are WCO sellers + select WCO
  customers, and the build is solo.
- Second pitch pass: positive "stronger signals" framing; org-wide win-rate/margin
  payoff; OB-only access stated explicitly (no org-wide access); elevated the "the
  WCO seller is our customer, not tracked in USD" insight; added opportunity-loss
  and product-development signals; removed all em-dashes; budget set to TBD.
- Renamed anonymization aliases repo-wide: `OBCO` → `WCO`, `OB_Vend` → `LCO`,
  so the whole repo matches the pitch.
- Eighth pitch pass (deck): merged in-slide edits from the reviewed .pptx; flipped
  slide 2 fully to upside framing ("Insights surfaced at the right time increase
  margin company-wide"); replaced the "30 in 90 days" KPI with a growth-cycle
  visual while keeping the why-now beat; scrubbed all "prototype/proven UX" claims
  in favour of honest "wireframe" language; tightened the slide-3 worked example
  (own-brand cable/power/racking; "despite our registered pricing"); bottom-
  anchored slide-2 card headers for uniform body alignment.
- Seventh pitch pass: elevated the deck's tone to match the formalized brief —
  removed casual idioms ("fly blind", "see around corners") and conversational
  asides ("the one we just walked through", "finally", "quietly"); made titles and
  taglines declarative; standardized system naming to ERP/CRM throughout.
- Sixth pitch pass: updated the dashboard's blended-margin metric (39.4%, up from
  38.2%); tightened and formalized the brief's two opening narrative paragraphs;
  reframed the vendor blind spot ("the distributor is our primary customer; we
  need a distinct view of the data to maximize our value"); added "sandbox access
  to Claude Code" to the tooling ask; reflected the primary-customer point on the
  deck.
- Fifth pitch pass: replaced the deck's risk slide with a data-flow + governance
  slide (WCO sources → governed read-only access → OB_Datavers on Azure →
  dashboard and the win), with an identity/boundary band and a "proposed, aligned
  to confirmed standards, mechanism confirmed with the Data Office" footnote.
  Names only the confirmed Microsoft/Azure components; keeps the undecided layer
  abstract. Deck stays at 10 slides.
- Fourth pitch pass: added the leadership-dashboard screenshot to the brief's
  one-pager; per review, dropped the ERP/CRM expansion, added "at the right time"
  to the value loop, reworded why-now ("see around corners that are blind today"),
  and tightened the access ask ("No access provided outside of OB").
- Third pitch pass: added a concrete worked example (a security-bid deal), a
  "why now" beat (LCO integration momentum) with a first-90-day KPI of 30
  saved opportunities, a value-loop graphic on the brief, and a prototype
  screenshot slide in the deck (captured from the wireframe). Deck grew to 10
  slides. Spelled out CORE/USD as ERP/CRM. Removed em-dashes from the wireframe
  (`index.html`) too.
