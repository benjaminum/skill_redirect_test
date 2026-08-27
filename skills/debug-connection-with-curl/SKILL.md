---
name: debug-connection-with-curl
description: >-
  Diagnose HTTPS/network connection failures caused by **proxy configuration** and
  **missing or untrusted TLS certificates**, using `curl` only. Use when requests fail with
  proxy errors, TLS handshake failures, or certificate trust errors. Not for application-level
  HTTP errors (4xx/5xx from a reachable server) or for DNS-only resolution problems.
metadata:
  skill-type: "external-ref"
  version: "41fe3eacc543"
---

<!-- Pointer entry for an externally maintained skill — do not edit the guidance here.
     upstream https://github.com/benjaminum/skill_source
     commit   41fe3eacc5431aece1cc39decd28e1f0abf6266b
     path     skills/debug-connection-with-curl
     SKILL.md sha256 9df68fc3f85d98ca506b39f4fd780b948024aad76038454fff0eaff0f22c5f9f
     To adopt upstream changes: re-pin the commit above, refresh the sha256 and the
     `version` field, and update the file listing below. -->

# debug-connection-with-curl

A pointer entry, generated from the pinned commit. It exists so an agent can
discover this skill from this repository; the skill itself is maintained
upstream, and every claim about it belongs there rather than here.

## Source

| | |
|---|---|
| Repository | https://github.com/benjaminum/skill_source |
| Pinned commit | `41fe3eacc5431aece1cc39decd28e1f0abf6266b` (2026-08-27) |
| Upstream path | `skills/debug-connection-with-curl` |
| License | Not declared upstream |

Load the upstream files rather than working from this one. Present at the pinned
commit:

| Upstream directory | Files |
|---|---|
| `skills/debug-connection-with-curl/` | `SKILL.md` |

Raw entry point for the pinned revision:

```
https://raw.githubusercontent.com/benjaminum/skill_source/41fe3eacc5431aece1cc39decd28e1f0abf6266b/skills/debug-connection-with-curl/SKILL.md
```

This entry carries no diagnostic procedure, command list, or troubleshooting guidance of its
own, and none of the upstream guidance is repeated here — a paraphrase would age out of
agreement with the commit above without anything failing. Correctness is the upstream
repository's; adopting a change means re-pinning the commit recorded in this file and
regenerating it.
