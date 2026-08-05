# Samson Laird · SamsonCyber

**AI / LLM security engineer (OSCP).** I build detectors, red-team harnesses, and control planes for tool-using agents.

Authorized labs, CTF, and in-scope bounty only. No production fire without a written engagement.

**Reach me:** [Portfolio](https://samsoncyber.github.io) · [LinkedIn](https://www.linkedin.com/in/sam-laird-50446021b) · [GitHub](https://github.com/SamsonCyber) · [Email](mailto:sam.lairdd@gmail.com)

---

## Featured work (start here)

| Project | What it demonstrates | Maturity |
|---------|----------------------|----------|
| [**garbleworks**](https://github.com/SamsonCyber/garbleworks) | Authorized LLM red-team harness: recipes, scoped fire, evolutionary search, Wilson ASR. MCP + API + TUI. | Independently validated |
| [**stegoff**](https://github.com/SamsonCyber/stegoff) | Scan text/files for stego and prompt injection before they hit an LLM. CLI + Python API. | Independently validated |
| [**agentic-dm-gateway**](https://github.com/SamsonCyber/agentic-dm-gateway) | Security control plane for agents over private DMs: allowlist, PIN, kill switch, injection heuristics, audit log. | Independently validated |
| [**llm-injection-field-guide**](https://github.com/SamsonCyber/llm-injection-field-guide) | Dark Promptery: 324 prompt-injection techniques, crosswalked to OWASP / MITRE ATLAS / NIST / CWE. | Live catalog + site |
| [**agent-trap-lab**](https://github.com/SamsonCyber/agent-trap-lab) | 29 adversarial web pages + StegOFF matrix + Ollama harness for browsing agents. | Partial (Ollama for full matrix) |
| [**oscp-notes-2026**](https://github.com/SamsonCyber/oscp-notes-2026) | OSCP field notebook: authorized lab methodology and study notes. | Study notes |

Reproduce any validated flagship:

```bash
git clone https://github.com/SamsonCyber/<repo>.git
cd <repo>
python scripts/repro.py
```

Expected: exit code `0` and a line ending with `REPRO_OK`.

---

## Maturity labels

| Label | Meaning |
|-------|---------|
| **Implemented** | Source ships. You can clone and install. |
| **Independently validated** | Automated tests pass on a clean machine with no private lab. One-command repro documented. |
| **Maintained** | Public default branch under SamsonCyber; issues/PR path open. |

### Flagship detail

| Repo | Implemented | Independently validated | Maintained | Proof |
|------|:-----------:|:-----------------------:|:----------:|-------|
| [stegoff](https://github.com/SamsonCyber/stegoff) | yes | yes | yes | `python scripts/repro.py` / CI · offline unit suite |
| [agentic-dm-gateway](https://github.com/SamsonCyber/agentic-dm-gateway) | yes | yes | yes | `python scripts/repro.py` / CI · security unit tests |
| [garbleworks](https://github.com/SamsonCyber/garbleworks) | yes | yes | yes | `python scripts/repro.py` / CI · security + math audit |

### Research / content

| Repo | Implemented | Independently validated | Maintained | Notes |
|------|:-----------:|:-----------------------:|:----------:|-------|
| [llm-injection-field-guide](https://github.com/SamsonCyber/llm-injection-field-guide) | yes | content + sync scripts | yes | [Live page](https://samsoncyber.github.io/llm-injection-field-guide/) · 324 techniques |
| [agent-trap-lab](https://github.com/SamsonCyber/agent-trap-lab) | yes | partial | yes | Offline detector tests; full matrix needs local model |
| [oscp-notes-2026](https://github.com/SamsonCyber/oscp-notes-2026) | yes | methodology notes | yes | Study notes only · authorized labs |

### Early / supporting

| Repo | Notes |
|------|-------|
| [agent-canary](https://github.com/SamsonCyber/agent-canary) | Tripwires for agent file / MCP / API activity (app-layer, not EDR) |
| [mcpdoctor](https://github.com/SamsonCyber/mcpdoctor) | Lint and pin MCP tool catalogs for schema poison and rugpulls |
| [blockjail](https://github.com/SamsonCyber/blockjail) | Tiny local jailbreak / prompt-injection gate for solo LLM apps |
| [cantina](https://github.com/SamsonCyber/cantina) | OSCP-legal network recon orchestrator (enumeration only) |

---

## How I work

1. Mechanism first. Name the failure mode, not only the meme payload.
2. Measure, then claim. Re-fire, bounds, honest gaps. One lucky hit is not a result.
3. Scope gates. SSRF and engagement receipts on harness fire paths. Authorized targets only.
4. Defense next to attack. Field guide cards carry detection fields. Trap lab publishes what still breaks.
5. Repro or it did not ship. Flagships expose a single repro script and CI.

## Stack

Python, FastAPI, MCP, local Ollama models, Discord bot control planes, static HTML field references, authorized HTB / PG / OSCP-style labs.

## Contact

- Portfolio: [samsoncyber.github.io](https://samsoncyber.github.io)
- LinkedIn: [sam-laird-50446021b](https://www.linkedin.com/in/sam-laird-50446021b)
- GitHub: [SamsonCyber](https://github.com/SamsonCyber)
- Email: [sam.lairdd@gmail.com](mailto:sam.lairdd@gmail.com)
