# ProcessKeepAlive (PKA) — Feedback

> Public feedback repository for the **ProcessKeepAlive (PKA) Xposed / LSPosed module**.
> The source code is maintained in a private repository, but **feedback is fully open** — bug reports and feature requests are welcome.

## Download

Search for `ProcessKeepAlive` in the LSPosed repo, or visit the official module listing:

**[https://github.com/Xposed-Modules-Repo/io.github.guys222.processkeepalive](https://github.com/Xposed-Modules-Repo/io.github.guys222.processkeepalive)**

## How to report

| Type | Channel |
| --- | --- |
| Bug reports, compatibility issues | [Issues](https://github.com/Guys222/ProcessKeepAlive-Issues/issues) |
| Usage questions, discussion | [Discussions](https://github.com/Guys222/ProcessKeepAlive-Issues/discussions) |

### Please include in your report

1. **Module version** (visible in the module manager page, e.g. `3.4.4 / 4025`)
2. **ROM and Android version** (e.g. ColorOS 15 / Android 15; note if you use clone profiles / app dual-instance)
3. **LSPosed version and scope** (whether System Framework and target apps are checked)
4. **Symptoms**: expected vs. actual behavior, and whether it reproduces reliably
5. **Logs**: preferably the diagnostic bundle exported from the module (Settings → Export diagnostic info), or the `ProcessKeepAlive` / `PKA` related section of your LSPosed log

> Privacy note: the diagnostic bundle only contains information needed to debug this module — no contacts, SMS, or other personal data. Still, skim it before uploading.

### Issue template

```
[Symptom]

[Expected behavior]

[Environment]
- Module version:
- ROM / Android:
- LSPosed version:
- Clone profile / dual instance in use:

[Steps to reproduce]

[Logs / diagnostic bundle]
```

## Notes

- This repository contains **no source code**. The main repository is private; this repo exists solely to track issues and requests for the PKA module.
- Labels (`bug` / `enhancement` / `question`) are managed by the maintainer — just describe the problem clearly.
- Please search for existing issues before opening a new one to avoid duplicates.
