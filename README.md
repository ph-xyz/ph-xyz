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

I'm focused on offensive web application security: understanding how real applications handle identity, object ownership, state, and trust boundaries — then testing whether those assumptions hold.

My work combines **hands-on security research**, small reproducible labs, technical write-ups, and development of tools that make web traffic analysis easier. I'm especially interested in the gap between an application's intended business rules and what its backend actually enforces.

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

`Understand the flow → establish a baseline → vary a trust boundary → verify impact → document evidence`

I value reproducible testing, explicit uncertainty, and reports that explain **why** a security boundary failed rather than just providing a payload.

---

<p align="center">
  <sub>Security research is performed in labs or on systems where testing is explicitly authorized. Public case studies follow the relevant disclosure rules.</sub>
</p>
