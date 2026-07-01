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
- **Secure code review** — Python tooling for pattern-based detection of hard-coded credentials,
  SQL / command-injection sinks, and dangerous calls across Python &amp; PHP codebases.
- **Secure SDLC / DevSecOps** — a GitLab CI/CD pipeline integrating SAST (SonarQube), DAST
  (OWASP ZAP), container scanning (Trivy) and IaC scanning (Checkov), deployed to AWS
  (EC2 / VPC / IAM / Security Groups).
- **Offensive testing** — web exploitation, Linux &amp; Windows privilege escalation, and Active
  Directory attack paths (OffSec PEN-200 / OSCP preparation).

> 📌 **[oscp-methodology](https://github.com/Zhaoyi-Fan/oscp-methodology)** — my full-chain
> penetration testing playbook, written as a field checklist: recon → foothold → privilege
> escalation → Active Directory.

*Currently exploring: securing enterprise AI adoption and AI-assisted security workflows.*

## 🏎️ Sim Racing Engineering — Assetto Corsa

Beyond security, I build real-time telemetry, hardware integration, and a rules engine for a
competitive Assetto Corsa league — all league-safe (read-only, no car-file edits, no checksum impact).

| Project | What it does | Stack |
|---|---|---|
| [vrc-fa25-simhub-telemetry](https://github.com/Zhaoyi-Fan/vrc-fa25-simhub-telemetry) | Bridges a car's private CAN/ECU channels from CSP into SimHub over a shared memory-mapped file, plus a replica of the in-car dashboard | Lua · C# · SimHub |
| [assetto-corsa-simhub-wheel-leds](https://github.com/Zhaoyi-Fan/assetto-corsa-simhub-wheel-leds) | Replicates the in-game wheel LED patterns (shift / DRS / flags) onto a physical 26-LED rim | JavaScript · SimHub |
| [assetto-corsa-fia-drs-rules](https://github.com/Zhaoyi-Fan/assetto-corsa-fia-drs-rules) | Enforces the real-F1 1-second DRS rule on AI &amp; player using the FIA timing-loop model via the CSP physics API | Lua · CSP |

## 🛠️ Tech

`Python` · `JavaScript` · `PHP` · `SQL` · `Bash` · `Lua` · `C#`
&nbsp;|&nbsp; Burp Suite · OWASP ZAP · SonarQube · Trivy · Checkov · Nmap · AWS · Git

**Certifications:** CompTIA Security+ · OSCP (in preparation)

---

<p align="center"><sub>Building secure software, breaking insecure software — and making cars go faster.</sub></p>
