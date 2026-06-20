# Changelog

All notable changes to this project are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); this project will adopt
[Semantic Versioning](https://semver.org/) once it ships releasable artifacts.

## [Unreleased]
### Added
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
  customers, and the build is solo. Pitch uses the `WCO` / `LCO` aliases.
