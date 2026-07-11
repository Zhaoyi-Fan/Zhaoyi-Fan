<h1 align="center">Zhaoyi Fan</h1>

<p align="center">
  <b>Application Security &amp; Security Research · PhD in Information Security</b><br>
  <i>Secure code review · secure SDLC · web &amp; API security — London, UK</i>
</p>

---

## 🔐 Application Security

Security researcher and application security practitioner. I focus on finding and fixing web and
API vulnerabilities, reviewing source code, and building security into the SDLC — while keeping an
offensive edge through OSCP-style lab work.

- **Web &amp; API security** — OWASP Top 10, authentication / authorization and business-logic
  flaws; responsible disclosure, including a multi-round technical dialogue with Apple Security.
- **Secure code review** — [source-code-security-scanner](https://github.com/Zhaoyi-Fan/source-code-security-scanner):
  my Python triage scanner with severity scoring, entropy-based secret detection, and SARIF / CI
  build-gating output — for hardcoded credentials, injection sinks, weak crypto and insecure deserialization.
- **Secure SDLC / DevSecOps** — a GitLab CI/CD pipeline integrating SAST (SonarQube), DAST
  (OWASP ZAP), container scanning (Trivy) and IaC scanning (Checkov), deployed to AWS
  (EC2 / VPC / IAM / Security Groups).
- **Offensive testing** — web exploitation, Linux &amp; Windows privilege escalation, and Active
  Directory attack paths (OffSec PEN-200 / OSCP preparation).

> 📌 **[oscp-methodology](https://github.com/Zhaoyi-Fan/oscp-methodology)** — my full-chain
> penetration testing playbook, written as a field checklist: recon → foothold → privilege
> escalation → Active Directory.

*Currently exploring: securing enterprise AI adoption and AI-assisted security workflows.*

## 🎓 PhD Research — Browser Privacy &amp; Web Attack Surface

PhD in Information Security (Royal Holloway, University of London). My research
studied a concrete web privacy threat: the standard JavaScript APIs every browser
exposes — keyboard, mouse and mobile motion/orientation events — can be abused by
any web page, **with no permission prompt**, to silently de-anonymise the person
behind the browser, defeating private / incognito mode and logged-out browsing.

- **Browser attack-surface analysis** — mapped which behaviour-leaking APIs are
  reachable without user consent across the major browsers on Windows, macOS, iOS
  and Android, in both normal and private modes.
- **Threat demonstration** — showed how a website (or a third-party script embedded
  across many sites) can build a persistent behavioural profile of a visitor and
  re-identify them across later sessions, even when they believe they are anonymous.
- **Defensive recommendations** — proposed practical browser- and user-side
  mitigations to put this tracking capability back under the user's control.

> 📌 **[browser-behavioural-biometrics](https://github.com/Zhaoyi-Fan/browser-behavioural-biometrics)**
> — sanitised research code: the data-collection browser extension, the browser-API
> attack-surface study, and the identification pipeline. Thesis:
> [*Browser user privacy — identifying users via browser interactions*](https://pure.royalholloway.ac.uk/en/publications/browser-user-privacy-identifying-users-via-browser-interactions/)
> (RHUL, 2023).

## 🏎️ Sim Racing Engineering — Assetto Corsa

Beyond security, I build race-forensics tooling, real-time telemetry, hardware integration, and a
rules engine for a competitive Assetto Corsa league — all league-safe (read-only, no car-file
edits, no checksum impact).

| Project | What it does | Stack |
|---|---|---|
| [assetto-corsa-race-logger](https://github.com/Zhaoyi-Fan/assetto-corsa-race-logger) | "Warcraft Logs for AC": records every car on track (player + AI) at 15 Hz, detects incidents offline, attributes causes with confidence-scored evidence, and renders each race as a self-contained interactive HTML report with a scrubbable 2D replay, lap-pace analytics and season aggregation | Lua · CSP · Python · JS/Canvas |
| [vrc-fa25-simhub-telemetry](https://github.com/Zhaoyi-Fan/vrc-fa25-simhub-telemetry) | Bridges a car's private CAN/ECU channels from CSP into SimHub over a shared memory-mapped file, plus a replica of the in-car dashboard | Lua · C# · SimHub |
| [assetto-corsa-simhub-wheel-leds](https://github.com/Zhaoyi-Fan/assetto-corsa-simhub-wheel-leds) | Replicates the in-game wheel LED patterns (shift / DRS / flags) onto a physical 26-LED rim | JavaScript · SimHub |
| [assetto-corsa-fia-drs-rules](https://github.com/Zhaoyi-Fan/assetto-corsa-fia-drs-rules) | Enforces the real-F1 1-second DRS rule on AI &amp; player using the FIA timing-loop model via the CSP physics API | Lua · CSP |

## 🛠️ Tech

`Python` · `JavaScript` · `PHP` · `SQL` · `Bash` · `Lua` · `C#`
&nbsp;|&nbsp; Burp Suite · OWASP ZAP · SonarQube · Trivy · Checkov · Nmap · AWS · Git

**Certifications:** CompTIA Security+ · OSCP (in preparation)

---

<p align="center"><sub>Building secure software, breaking insecure software — and making cars go faster.</sub></p>
