# Hey, I'm Justin 👋

**Systems Engineer · Omaha, NE**

I manage a fleet of ~25,000 Windows workstations for a Class I railroad — patch management, software deployment, ConfigMgr/MECM administration, and the occasional "why did 400 machines all do that" mystery.

![PowerShell](https://img.shields.io/badge/PowerShell-012456?style=flat&logo=powershell&logoColor=white)
![ConfigMgr](https://img.shields.io/badge/MECM%2FConfigMgr-0078D4?style=flat)
![Windows](https://img.shields.io/badge/Windows%20Fleet-~25k%20endpoints-blue?style=flat)
![UNO](https://img.shields.io/badge/M.S.%20Cybersecurity-in%20progress-D71920?style=flat)

## About me

No certs. No alphabet soup after my name. Just a bachelor's degree, a master's in progress, and a stubborn refusal to do anything the easy way.

- 🎓 Working on my **M.S. in Cybersecurity (Cyber Operations)** at the University of Nebraska at Omaha
- 🖥️ Day job: keeping ~25k endpoints patched, deployed, and behaving (mostly)
- ⚡ PowerShell is my love language
- 🔐 Currently elbow-deep in software assurance coursework, learning to break things on purpose instead of by accident
- 👨‍👧 Dad. Grad student. Full-time employee. Sleep is theoretical.

I'm not an expert. I'm a guy who's trying really hard and taking notes. If you're a classmate, a coworker, or a rando who wandered in here — welcome. Most of what I know, I learned by getting it wrong first.

## 🛠️ Open source work

Fixing real bugs in projects I use and study. Statuses are honest: nothing counts until it's merged.

| Project | Issue | What I did | Status |
|---|---|---|---|
| [Keycloak](https://github.com/keycloak/keycloak) | [#20008](https://github.com/keycloak/keycloak/issues/20008) UMA policy creation missing from audit log | Reproduced, root-caused, and fixed it so policy creation is audited like update/delete, with an integration test that fails without the fix | 📬 PR open ([#53316](https://github.com/keycloak/keycloak/pull/53316)), approved, waiting on code-owner review |
| [Keycloak](https://github.com/keycloak/keycloak) | [#53249](https://github.com/keycloak/keycloak/issues/53249) Brute-force failure counter not reset on successful SAML login | Reproduced with a failing test (SAML + OIDC), traced it to a side effect of #49996, proposed an opt-in fix to maintainers | 🟡 Awaiting maintainer |
| [Keycloak](https://github.com/keycloak/keycloak) | [#16597](https://github.com/keycloak/keycloak/issues/16597) Policy evaluation tool puts the wrong client in the `azp` claim | Reproduced on current main, confirmed the server side handles it correctly with an integration test, traced it to the admin console's Evaluate tab never sending the selected client, and proposed a UI fix | 🟡 Awaiting maintainer |
| [Sigma](https://github.com/SigmaHQ/sigma) | [CredUI.DLL Loaded By Uncommon Process](https://github.com/SigmaHQ/sigma/blob/master/rules/windows/image_load/image_load_dll_credui_uncommon_process_load.yml) false positive on Spotify | Found it in the CI false-positive allowlist, tuned the rule to exclude the per-user Spotify client, and verified it against all 7 clean-Windows baselines Sigma's CI uses | 📬 PR open ([#6425](https://github.com/SigmaHQ/sigma/pull/6425)) |

<sub>🔍 Investigating → 🟡 Awaiting maintainer → 🔨 In progress → 📬 PR open → ✅ Merged</sub>

📋 What I'm eyeing next: [contribution board](https://github.com/users/JBoogieman/projects/2)

<details>
<summary><b>📊 Stats for nerds</b> <i>(the numbers are small, but they're mine)</i></summary>
<br>
<p align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=JBoogieman&theme=github-dark-blue&hide_border=true">
<img src="https://streak-stats.demolab.com?user=JBoogieman&hide_border=true" alt="Contribution streak"/>
</picture>
</p>
<!-- More stats cards coming: self-generated via GitHub Actions so they can't break when someone else's server dies -->
</details>
