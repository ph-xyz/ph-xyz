<p align="center">
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/showdown/393.gif" width="90" alt="Piplup">
</p>

<h1 align="center">Pedro Henrique · Web Application Security</h1>

<p align="center">
  <b>Web security research · Bug bounty / VDP · Security tooling</b><br>
  Hands-on testing of authentication, authorization, session management, and application logic.
</p>

<p align="center">
  <a href="https://github.com/ph-xyz/web-security-writeups">Security write-ups</a> ·
  <a href="https://github.com/ph-xyz/web-security-labs">Practice labs</a> ·
  <a href="https://github.com/ph-xyz/Caido-Bridge">CaidoBridge</a>
</p>

---

### About

I spend a lot of time exploring how web applications handle authentication, permissions, and business logic. I like understanding how a feature is supposed to work and finding out what happens when those rules aren't enforced properly.

I also build small labs, write up things I learn while testing, and develop tools to make the process easier.

### Selected work

| Project | What it demonstrates |
| --- | --- |
| **[CaidoBridge](https://github.com/ph-xyz/Caido-Bridge)** | A Go-based local MCP bridge connecting ChatGPT to Caido for HTTP history and sitemap analysis, scope checks, and optional scope-bound request replay. |
| **[Web Security Write-ups](https://github.com/ph-xyz/web-security-writeups)** | Technical documentation of practical testing, observed behavior, impact, and remediation; includes a dedicated [Bug Bounty / VDP collection](https://github.com/ph-xyz/web-security-writeups/tree/main/bug-bounty-vdp). |
| **[Web Security Labs](https://github.com/ph-xyz/web-security-labs)** | Local intentionally vulnerable applications for practicing authorization boundaries, session handling, LDAP injection, mass assignment, and related concepts. |

### Areas of focus

- **Authentication & sessions:** token validation, session lifecycle, logout and password-reset behavior
- **Authorization:** IDOR / BOLA, horizontal and vertical access controls, object ownership
- **Business logic:** state transitions, workflow assumptions, and server-side invariants
- **Web testing:** request analysis, controlled comparisons, injection testing, evidence and reporting
- **Security engineering:** Go, HTTP tooling, Model Context Protocol (MCP), Caido integrations

### How I work

I usually start by using a feature normally and understanding what it does. Then I look at the requests, try different accounts or inputs, and compare how the application responds.

When something looks off, I try to reproduce it and understand why it happened before writing it up.

