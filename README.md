<div align="center">

<img src="https://media.githubusercontent.com/media/pdparchitect/noodle/main/Incubator/Pion/Support/AppIcon.png" alt="Pion" width="96">

# Pion

**A cyber defence workspace for your Mac.**<br>
Agents investigate incidents with you; you approve anything that changes a system.

<a href="https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.dmg"><img alt="Download Pion for Mac" src="https://img.shields.io/badge/Download%20for%20Mac-1f2328?style=for-the-badge&logo=apple&logoColor=white" height="44"></a>

[Source](https://github.com/pdparchitect/noodle/tree/main/Incubator/Pion) · [Releases](https://github.com/pdparchitect/noodle/releases/tag/pion-latest) · [Changelog](https://github.com/pdparchitect/noodle/blob/main/Incubator/Pion/CHANGELOG.md) · [Noodle](https://github.com/pdparchitect/noodle)

</div>

<img width="1672" height="941" alt="Pion" src="https://github.com/user-attachments/assets/607d6406-5acf-440c-863b-49bdbbfce711" />

Pion is a cyber defence tool for one operator. A team of agents works an incident with you as an
Investigation: they query your security tools, record findings with the evidence behind them, and
recommend what to do. Agents never change a system themselves; every change goes through you, and
each step lands in an audit log that is only ever added to.

Agents run on the harnesses you already use, such as Codex and Claude Code, with your own account,
and connect to services like VirusTotal, Okta, Microsoft Entra ID and Defender XDR, CrowdStrike,
SentinelOne, Splunk, Elastic, Sentinel, AWS, Google Cloud and GitHub.

## Where Pion lives

Pion is built on the core of [Noodle](https://github.com/pdparchitect/noodle), the personal AI agents
app, and runs agents the same way while keeping its own agents, conversations and sign-ins apart.
While it is incubating, its source lives in Noodle's repository under
[`Incubator/Pion`](https://github.com/pdparchitect/noodle/tree/main/Incubator/Pion): sharing one
repository makes it easier to change Pion and the Noodle code it depends on together. Pion moves here
once it settles.

Until then, this repository is Pion's home page, and releases are published from Noodle's repository.

## Download

Get the latest build from the
[Pion release in Noodle's repository](https://github.com/pdparchitect/noodle/releases/tag/pion-latest):
[DMG](https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.dmg) or
[ZIP](https://github.com/pdparchitect/noodle/releases/download/pion-latest/Pion-arm64.zip).
Pion needs a Mac with Apple silicon and macOS 26 or later. Open the DMG and drag Pion to
Applications; it updates itself from then on.

Pion is a prototype, so expect rough edges.

## License

Source available under the
[PolyForm Noncommercial License 1.0.0](https://github.com/pdparchitect/noodle/blob/main/Incubator/Pion/LICENSE.md):
free to read, use and change for noncommercial purposes. This is not an open-source license.
