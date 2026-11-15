<div align="center">

<img src="https://media.githubusercontent.com/media/pdparchitect/noodle/main/Incubator/Pion/Support/AppIcon.png" alt="Pion" width="96">

# Pion

**An agentic environment for cyber defence.**<br>
A team of AI agents investigates incidents with you, and you decide what changes.

<a href="https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.dmg"><img alt="Download Pion for Mac" src="https://img.shields.io/badge/Download%20for%20Mac-1f2328?style=for-the-badge&logo=apple&logoColor=white" height="44"></a>

[Source](https://github.com/pdparchitect/noodle/tree/main/Incubator/Pion) · [Releases](https://github.com/pdparchitect/noodle/releases/tag/pion-latest) · [Changelog](https://github.com/pdparchitect/noodle/blob/main/Incubator/Pion/CHANGELOG.md) · [Noodle](https://github.com/pdparchitect/noodle)

</div>

<img width="1672" height="941" alt="Pion" src="https://github.com/user-attachments/assets/607d6406-5acf-440c-863b-49bdbbfce711" />

When an alert fires, open an Investigation and bring in the agents that should work it. One agent
leads, sets the severity from the evidence and keeps the team on the objective. The others pull
logs, check indicators, look up users and hosts, and report back in the same conversation.

Everything they learn goes into the case record: findings with the evidence behind them, the
queries that produced that evidence, and the users, hosts and addresses involved. Every change to
the case is written to an audit log that is only ever added to.

Agents never touch a system on their own. They recommend containment and remediation, and you
carry it out.

## Your stack, your models

Agents run on the harnesses you already pay for, such as Codex and Claude Code, signed in with your
own account. Connect them to the tools your team already uses:

- **Identity:** Okta, Microsoft Entra ID, Google Workspace
- **Endpoints:** CrowdStrike Falcon, SentinelOne, Microsoft Defender XDR
- **Logs:** Splunk, Elastic, Microsoft Sentinel, Sumo Logic
- **Cloud:** AWS, Google Cloud, Cloudflare, Wiz, GitHub
- **Threat intelligence:** VirusTotal, Shodan, GreyNoise, AbuseIPDB, urlscan.io, AlienVault OTX,
  Censys, Have I Been Pwned
- **Email and exposure:** Proofpoint TAP, Tenable

Any other service can be added over MCP.

## Built on Noodle

Pion runs on the core of [Noodle](https://github.com/pdparchitect/noodle), the open source app for
personal AI agents. Its agents, groups and harnesses work the way Noodle's do, but Pion keeps its
own agents, conversations and sign-ins apart from Noodle's.

While Pion is incubating, its source lives in Noodle's repository under
[`Incubator/Pion`](https://github.com/pdparchitect/noodle/tree/main/Incubator/Pion). Pion depends
on much of Noodle's code, and keeping both in one repository lets them change together while the
design settles. Once it does, Pion moves here. Until then, this repository is its home page and
releases are published from Noodle's.

## Download

Download the latest
[DMG](https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.dmg) or
[ZIP](https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.zip) from the
[Pion release](https://github.com/pdparchitect/noodle/releases/tag/pion-latest) in Noodle's
repository. Pion needs a Mac with Apple silicon and macOS 26 or later. Open the DMG, drag Pion to
Applications, and it keeps itself up to date from there.

Pion is an early prototype, so expect rough edges.

## License

Source available under the
[PolyForm Noncommercial License 1.0.0](https://github.com/pdparchitect/noodle/blob/main/Incubator/Pion/LICENSE.md).
Free to read, use and change for noncommercial purposes. This is not an open-source license.
