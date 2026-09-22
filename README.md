# GameAudits

**Security disclosure infrastructure for gaming communities.**

GameAudits is a managed vulnerability disclosure platform designed for community-run game servers, modding communities, and independent game developers.

It gives server operators and developers a structured, private way to receive, triage, communicate about, and resolve security vulnerabilities while giving security researchers a clear channel for responsible disclosure.

GameAudits is initially focused on **community-run gaming ecosystems such as FiveM, Minecraft, Rust, DayZ, and similar multiplayer games**.

The long-term goal is to expand beyond web-based disclosure into game server integrations, developer APIs, and SDKs for major game engines.

---

## Why GameAudits?

Gaming communities increasingly operate real infrastructure:

* Dedicated game servers
* Web panels
* APIs
* Databases
* Plugins and mods
* Custom scripts
* Discord bots
* Community websites
* In-game economies

Yet many communities have no formal process for handling security vulnerabilities.

A researcher who discovers a vulnerability may have no obvious place to report it, resulting in reports being sent through Discord DMs, public channels, forum posts, or generic issue trackers.

This can create problems for both sides.

Researchers need a legitimate and clearly defined disclosure channel, while server operators need a way to receive, investigate, communicate about, and track vulnerabilities without building their own security workflow.

**GameAudits aims to provide that missing layer.**

---

## Initial Focus

GameAudits is intentionally starting with **community-run game servers** rather than attempting to serve the entire gaming industry from day one.

Initial target ecosystems include:

* **FiveM**
* **Minecraft**
* **Rust**
* **DayZ**
* **Garry's Mod**
* Other community-hosted multiplayer games

These ecosystems have large communities of independently operated servers, extensive modding infrastructure, and developers who often maintain security-sensitive software without dedicated security teams.

The goal is to build something that genuinely fits how these communities operate.

---

## Who Is GameAudits For?

### Server Operators

* FiveM server owners
* Minecraft server administrators
* Rust and DayZ server operators
* Modded server owners
* Community infrastructure administrators

### Developers

* Plugin developers
* Mod developers
* FiveM resource developers
* Community web developers
* Discord bot developers
* Independent game developers

### Security Researchers

Researchers investigating vulnerabilities in:

* Game servers
* Plugins and mods
* APIs
* Web panels
* Custom scripts
* Community infrastructure
* Game-related services

---

## Core Principles

* **Community-first** — build around the realities of gaming communities
* **Managed by default** — operators should not need to run security infrastructure
* **Private by default** — vulnerability reports should not expose sensitive information unnecessarily
* **Responsible disclosure** — provide clear expectations for both researchers and operators
* **Low operational overhead** — security tooling should not become another server for communities to maintain
* **Clear scope** — programs should clearly define what can and cannot be tested
* **Simple workflows** — reporting and triage should be straightforward
* **Security-focused** — prioritize security and reliability over unnecessary complexity

GameAudits is not intended to become a generic enterprise vulnerability management platform.

Its initial purpose is much narrower:

> **Make responsible vulnerability disclosure practical for gaming communities.**

---

## Hosting

GameAudits is initially provided as a **centrally hosted and managed service**.

Community operators do not need to deploy or maintain the platform themselves.

GameAudits will operate the application infrastructure, databases, storage, authentication, email delivery, monitoring, backups, and other supporting services.

This approach allows the platform to maintain a consistent security baseline while keeping adoption simple for smaller communities.

**Self-hosting is not currently supported.**

A self-hosted or dedicated deployment model may be introduced much later for organizations that require greater infrastructure control or privacy.

---

## MVP

The initial MVP focuses on the core vulnerability disclosure workflow.

### Accounts & Programs

* Authentication and account creation
* Operator onboarding
* Program creation
* Program scope
* Out-of-scope definitions
* Disclosure rules
* Safe-harbor policies
* Public program pages

### Vulnerability Reports

* Private vulnerability submissions
* Report status tracking
* Severity and classification
* Threaded operator/researcher communication
* Report history
* Duplicate handling

### Notifications

* Email notifications
* Report activity notifications
* Operator notifications
* Researcher notifications

### Trust & Administration

* Researcher profiles
* Basic moderation controls
* Program administration
* Administrative audit logging
* Permission and access controls

The MVP will prioritize **reliable report delivery, secure permissions, clear communication, and a straightforward operator experience** over feature breadth.

---

# Roadmap

## Phase 1 — Gaming Community VDP

**Establish GameAudits as a practical disclosure platform for community-run game servers.**

* Launch the core VDP workflow
* Focus on a small number of gaming ecosystems
* Initially target communities such as FiveM and Minecraft
* Manually onboard early programs
* Learn how communities currently handle security reports
* Improve report quality and triage workflows
* Develop responsible disclosure guidance
* Build credibility through real-world usage

Early development will be intentionally hands-on. This allows the platform and its workflows to be shaped around real community needs rather than assumptions.

---

## Phase 2 — Community Security Platform

**Make vulnerability disclosure part of normal server administration.**

Planned features include:

* Team workspaces
* Staff roles and permissions
* Saved responses
* Structured triage workflows
* Improved operator dashboards
* Researcher reputation signals
* Program verification
* Advanced moderation
* Additional gaming ecosystems

---

## Phase 3 — Developer & Infrastructure Integrations

**Connect GameAudits directly with the infrastructure developers already operate.**

Planned integrations include:

* Game server integrations
* Plugin and mod integrations
* Webhooks
* Public APIs
* Security event APIs
* Automated vulnerability intake
* Community management integrations
* Developer SDKs

The goal is to make GameAudits something developers can integrate into their existing workflows rather than a service they must manually visit.

---

## Phase 4 — Game Engine SDKs

**Bring GameAudits directly into game development workflows.**

Long-term SDK targets include:

* **Godot**
* **Unity**
* **Unreal Engine**

Potential capabilities include:

* Programmatic vulnerability reporting
* Build and version association
* Security metadata
* Development workflow integration
* Automated report submission
* Integration with existing security tooling

This phase represents the transition from **community server security** into broader game development security.

---

## Phase 5 — Gaming Security Infrastructure

**Become a trusted security layer across the gaming ecosystem.**

Potential future capabilities include:

* Verified security programs
* Public security advisories
* Security research partnerships
* Community-specific security standards
* Developer tooling integrations
* Vulnerability intelligence
* Dedicated deployments
* Private infrastructure
* Self-hosted deployments

These are long-term goals and are intentionally outside the initial product scope.

---

# Build Direction

GameAudits is being built primarily around the **C# and .NET ecosystem**.

### Application

* **C#**
* **.NET**
* **ASP.NET Core**
* REST APIs
* Background services
* Automated testing

### Development

* **JetBrains Rider**
* JetBrains developer tooling and services where appropriate
* Git-based development
* CI/CD
* Automated testing

### Infrastructure

* **Microsoft Azure**
* Managed cloud infrastructure
* Managed databases
* Managed storage
* Secure secrets management
* Automated deployments
* Monitoring and logging
* Automated backups

The technology choices are intended to provide a strong foundation for a security-focused application while keeping the operational burden manageable.

The priority is:

**Security → Reliability → Maintainability → Simplicity**

rather than technical novelty for its own sake.

---

# Long-Term Vision

GameAudits starts with a simple problem:

> **Gaming communities need a proper way to receive and handle vulnerability reports.**

The platform will grow from that foundation:

**Community Servers**
↓
**Managed VDP**
↓
**APIs & Integrations**
↓
**Game Server Tooling**
↓
**Developer SDKs**
↓
**Godot / Unity / Unreal Integrations**
↓
**Gaming Security Infrastructure**

The long-term ambition is to help make responsible security disclosure a normal part of operating and developing games.

---

# Success Metrics

### Community Adoption

* Active programs
* Participating communities
* Monthly active operators
* Supported gaming ecosystems

### Security Activity

* Valid vulnerability reports
* Reports successfully triaged
* Reports resolved
* Repeat researchers
* Repeat operators

### Operational Quality

* Median first response time
* Median resolution time
* Report abandonment rate
* Notification reliability
* Percentage of reports handled fully on-platform

### Platform Growth

* API integrations
* Game server integrations
* SDK adoption
* Engine integrations
* Verified programs
* Security partnerships

---

## Project Status

GameAudits is a long-term project currently in development.

The initial focus is on building the core platform, validating the concept with gaming communities, and establishing a strong technical foundation before expanding into additional ecosystems and integrations.

The roadmap is intentionally ambitious, and individual features may change as the project develops and real-world requirements become clearer.

---

## License

*License information will be added as the project reaches its initial public release.*
