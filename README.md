# Artemis-showcase
Artemis (beta): a desktop recon tool that turns a target’s attack surface into an interactive 3D map. Demo and overview only, the source code is private. Topics (the gear icon next to About): cybersecurity, recon, attack-surface, osint, pentesting, godot, amass

# Artemis (beta)

**Recon, mapped in 3D.** Artemis turns a target's attack surface into an interactive 3D map you can explore, instead of scrolling through walls of text output.

> Source code is private while it's in active development. This repo shows what Artemis does and how it works.

## Demo
https://youtu.be/SV9TmRpNYs4

## How it works
1. **Set scope first.** A Rules-of-Engagement scope engine keeps recon inside the targets you're authorized to test.
2. **Run recon.** It uses OWASP Amass plus custom Python recon scripts to enumerate domains, subdomains, and hosts.
3. **Explore the map.** Results show up as connected 3D nodes, so you can see how the assets relate at a glance.

## Built with
Godot 4 · GDScript · OWASP Amass · Python · Windows desktop

## Roadmap
- CVE correlation
- Extensible in-app terminal
- Preset toolkit
- Responsible-use guardrails

## Responsible use
Only for systems you own or have written permission to test.

## About
Independent project by Kevin Ceniceros, built while moving into SOC and pentesting.
[LinkedIn](https://linkedin.com/in/kevin-ceniceros-it)
