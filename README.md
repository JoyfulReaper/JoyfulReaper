# Hi, I'm Kyle Givler

I'm a .NET developer, code archaeologist, and software tinkerer who likes turning messy systems into useful tools.

Most of my work lives around backend development, small web applications, APIs, SQLite-backed services, self-hosted infrastructure, command-line tooling, networking experiments, and the occasional game mod.

I like practical software: fast enough to feel good, simple enough to run cheaply, and maintainable enough that future-me does not curse present-me too badly.

**I'm available for small paid development projects, debugging, automation, deployment help, and unusual technical problems.**

## What I Can Help With

- **.NET and backend development** — C#, ASP.NET Core, APIs, Blazor, SQLite, integrations, and internal tools
- **Legacy .NET modernization** — moving older .NET Framework, MVC, Web Forms, and VB.NET applications toward modern .NET / ASP.NET Core without throwing away working business logic
- **Websites and small web applications** — landing pages, business sites, custom functionality, modernization, and cleanup
- **Debugging and project rescue** — figuring out why something is broken, untangling unfamiliar code, fixing stalled projects, and making existing systems maintainable
- **Automation and integrations** — scripts, scheduled jobs, webhooks, APIs, data processing, and replacing repetitive manual work
- **Deployment and self-hosting** — Docker/Compose, Linux VPSes, nginx, HTTPS, monitoring, backups, and small-service infrastructure
- **Programming help** — code review, architectural guidance, mentoring, and getting unstuck

I especially like **small or weird projects that are too specialized for a big agency but still need someone who can handle both the code and the system it runs on**.

I'm also open to selected nonprofit, community, and volunteer work when the fit makes sense.

## Featured Projects

### [Mission Control](https://github.com/JoyfulReaper/MissionControl)

A .NET 10 operations system for integration-event history and live infrastructure visibility.

It combines ASP.NET Core, Blazor, NATS JetStream, SQLite, host agents, Docker/service monitoring, GitHub event processing, and a shared dashboard/mobile UI.

This is probably the best example of how I approach larger systems: keep the pieces understandable, make failure visible, and avoid complexity that does not solve a real problem.

### [RandomSteamGame](https://github.com/JoyfulReaper/RandomSteamGame)

A fast Blazor/.NET Steam library picker for people with too many games and not enough decision-making energy.

It uses Steam APIs, server-side caching, SQLite-backed data, rate limiting, telemetry, and a public deployment at:

**https://randomsteam.kgivler.com**

### [ReaperShell](https://github.com/JoyfulReaper/ReaperShell)

An experimental .NET interactive shell for building local developer tools as live-loadable command packs.

Command packs are normal SDK-style .NET projects and can be written in C#, F#, or VB.NET. It is less an attempt to replace Bash or PowerShell and more a playground for turning quick scripts into structured tools.

### [freebsd-c-lab](https://github.com/JoyfulReaper/freebsd-c-lab)

A collection of C and POSIX/BSD programming experiments written while learning C directly against operating-system APIs.

The main attraction is **tcpnoise**, a small network-noise monitor that listens on public TCP ports and records the scanners, bots, probes, and miscellaneous Internet garbage that inevitably arrive.

### [kgivler.com](https://github.com/JoyfulReaper/kgivler_com)

Source for my personal website, portfolio, API playground, and collection of small web/infrastructure experiments.

**https://www.kgivler.com**

It includes project integrations, service/status data, telemetry, networking experiments, and the occasional terminal-flavored nonsense.

### RimWorld Modding

I also maintain and experiment with RimWorld mods, including:

- [Better Trade Colors](https://github.com/JoyfulReaper/BetterTradeColors) — improves trade-screen readability with quality, durability, and condition coloring
- [Replace Stuff: Performance Edition](https://github.com/JoyfulReaper/RimWorld-ReplaceStuff) — a performance-focused modernization and refactor of Replace Stuff

## Professional Experience

Before focusing primarily on my own projects, I worked professionally on business applications, legacy-system modernization, integrations, and internal tooling.

### Pennsylvania Automotive Association

As a .NET developer, I maintained existing .NET and VB.NET applications while also replacing older systems with modern C# applications.

Some of that work included:

- **Modernizing legacy .NET applications** — maintained an ASP.NET MVC payment application on .NET Framework 4.7.2, replaced its PayPal integration with PayTrace, and later rewrote the application in **.NET 6**
- **Auction platform** — built an ASP.NET MVC fundraising auction application with configurable auctions, bidding rules, user accounts, administrator bidding, themes, and PayTrace payment processing
- **Internal business applications** — built or replaced systems for event registration, help-desk tickets, hardware asset tracking, bond tracking, secure power-of-attorney reporting, and employee alerts
- **Admin portal** — built a modular .NET application that consolidated smaller internal tools using Razor Class Libraries
- **Grants workflow** — added electronic application and approval workflows to existing internal and external applications, replacing paper-heavy processes
- **Integrations and reporting** — worked with SQL Server, SSRS, Lansweeper, Lucene.NET, WMI, Exchange-related workflows, Twilio, and payment providers

A lot of that work was less about greenfield development and more about understanding existing business processes, preserving the parts that worked, and replacing the parts that had become painful to maintain.

### Foot Locker

Earlier, I worked on Xstore point-of-sale modernization using Java.

That included:

- replacing older SOAP integrations with JSON/REST APIs;
- integrating OpenAPI Generator into the Ant build process to generate internal API client libraries;
- helping upgrade Xstore environments while preserving and merging custom configuration;
- earlier operational/project work supporting store openings, hardware deployment, POS systems, and high-priority technical incidents.

That mix of development and operational work is part of why I tend to think about software as something that has to survive contact with actual users and infrastructure.

## Networking & Infrastructure Lab

I also run a small multi-POP hobby network and use it as a hands-on lab for routing, IPv6, Linux networking, and service operations.

### DN42 — AS4242420425

I operate **AS4242420425** on DN42 across multiple VPS locations, including
GreenCloud-hosted nodes.

That environment includes:

- BGP routing with BIRD
- multiple external peers and geographically separate edge nodes
- IPv4 and IPv6 routing
- WireGuard-based inter-router links
- controlled transit policies and policy routing
- authoritative DNS and internal service naming
- HTTPS services and certificate automation
- traffic monitoring, routing diagnostics, and failure testing

The public landing/service code lives in [DN42Landing](https://github.com/JoyfulReaper/DN42Landing).

### Yggdrasil

I also run services over **Yggdrasil**, an IPv6 overlay network, and use it to experiment with overlay routing, service discovery, self-hosting, and reducing accidental dependence on the normal Internet.

A lot of this work is intentionally experimental, but it has been a very good way to learn what actually happens below the application layer when routing, DNS, IPv6, and service availability stop being somebody else's problem.

## Hosting I Use

A good chunk of the public infrastructure behind the projects above runs on
[GreenCloud VPS](https://greencloudvps.com/billing/aff.php?aff=10295).

I currently use GreenCloud for **Clanker** and **ScopeCreep**, two Linux VPS nodes
that host applications, Docker services, monitoring, routing experiments, DN42
infrastructure, and assorted other projects.

They've worked well for the kind of small Linux VPS workloads I run, and their
pricing has made it practical to keep multiple public nodes online without
spending much on infrastructure.

**Affiliate disclosure:** The GreenCloud link above is an affiliate link. I may
earn a commission if you sign up through it.

## Currently Building

### [HappyPortal](https://github.com/JoyfulReaper/HappyPortal)

An early-stage ASP.NET Core client and billing portal intended both for my own development/hosting work and as an example of the kind of custom small-business software I can build.

The project is currently in planning/pre-MVP development.

## Core Stack

- **Primary:** C#, .NET, ASP.NET Core, Blazor, SQLite
- **Infrastructure:** Docker / Compose, Linux, nginx, Cloudflare Tunnel, WireGuard, self-hosted services
- **Also working with:** C, JavaScript, SQL Server, POSIX/BSD APIs
- **Things I enjoy:** backend systems, debugging, refactoring, networking, automation, command-line tools, game modding, and weird Internet infrastructure

---

🌐 [Portfolio](https://kgivler.com)  
💼 [LinkedIn](https://www.linkedin.com/in/kyle-givler)  
🎮 [Steam](https://steamcommunity.com/id/Mister_God/)
