### Yellow 👋, I'm Solomon

I'm an open-source software developer and Network & Systems Engineer in Tampa, FL, working where cybersecurity, network observability, and AI infrastructure meet. I build SOC tooling, MCP servers, and multi-agent workflows that run on real production gear, not toy demos, and I write about it at [solomonneas.dev/blog](https://solomonneas.dev/blog).

- <img src="https://flagcdn.com/20x15/us.png" alt="US flag" width="20"> US based in Tampa, FL, near the beach.
- 👨‍👧 Father, retired chef of 17 years, OSS contributor, and beach lover when I'm not on a screen.
- 📜 M.S. Cybersecurity Intelligence & Information Security at the University of South Florida.
- 🛡️ Building open-source SOC and threat-intel tooling on bare-metal Proxmox, stitched together with self-hosted n8n.
- 🤖 Deep in multi-agent orchestration, MCP servers, and detection engineering.
- 🗣️ Ask me about **Proxmox, network monitoring, MCP servers, OpenClaw, agent orchestration, and open-source SOC**.
- ⚙️ Big believer in open source, dogfooding everything, and writing it down so the next person doesn't have to figure it out.
- 🫶 If my work helped you, [buy me a coffee](https://www.buymeacoffee.com/solomonneas) or [tip on Ko-fi](https://ko-fi.com/solomonneas).
- 📫 Reach me at [me@solomonneas.dev](mailto:me@solomonneas.dev) · [LinkedIn](https://www.linkedin.com/in/solomon-neas/) · [X](https://x.com/solomonneas) <!-- content-guard: allow pii/email -->

## 🍳 Escoffier Labs

[Escoffier Labs](https://github.com/escoffier-labs) is my studio for harness-agnostic agent infrastructure, named for the chef who systematized the kitchen brigade. Tools that get your agents into _mise en place_ and keep them there.

**Core**
- 🚩 **[brigade](https://github.com/escoffier-labs/brigade)** - **the flagship.** Local operator layer for agent memory, tasks, tools, research, review, and release across every harness.
- 🥘 [skillet](https://github.com/escoffier-labs/skillet) - Agent skills suite: repo audits, bug hunting, security sweeps, publish gates, releases, and memory handoffs.
- 🦞 [solos-cookbook](https://github.com/escoffier-labs/solos-cookbook) - Opinionated, dogfooded guide to running a 24/7 multi-agent AI stack on bare metal.

**Agent ops**
- 🍪 [agentpantry](https://github.com/escoffier-labs/agentpantry) - Encrypted, transport-agnostic sync of browser sessions and secrets so agents wake up authenticated.
- 🩺 [memory-doctor](https://github.com/escoffier-labs/memory-doctor) - Maintenance CLI for the Claude Code and OpenClaw memory systems: status, lint, ingest, compact.
- 🧰 [bootstrap-doctor](https://github.com/escoffier-labs/bootstrap-doctor) - Audits and trims oversize OpenClaw prefix files into reference cards via heuristics and LLM judgment.
- 🛂 [content-guard](https://github.com/escoffier-labs/content-guard) - Policy-driven content scanning that catches secrets, hostnames, and IPs before they leave the machine.
- 🔔 [agent-notify](https://github.com/escoffier-labs/agent-notify) - Privacy-first push notifications for AI coding agents to Discord, Telegram, and Signal with zero telemetry.
- 🛎️ [cloche](https://github.com/escoffier-labs/cloche) - Agent-neutral desktop capture: polished shots with metadata and stable JSON, plus an optional MCP server.

**Dev tools**
- 🔍 [code-search-api](https://github.com/escoffier-labs/code-search-api) - Local semantic code search with Ollama embeddings, SQLite, hybrid search, and LLM summaries.
- 🧩 [code-search-mcp](https://github.com/escoffier-labs/code-search-mcp) - Read-only MCP server and OpenClaw plugin that puts code-search-api in front of any agent.
- 📊 [usage-tracker](https://github.com/escoffier-labs/usage-tracker) - Token usage and cost analytics for OpenClaw sessions across models.
- 🎭 [mise-en-scene](https://github.com/escoffier-labs/mise-en-scene) - Turns source material into self-contained interactive HTML/SVG technical explainers.

**Evidence stack**
- 🧾 [miseledger](https://github.com/escoffier-labs/miseledger) - Turns scattered AI work history into a local, searchable evidence ledger: SQLite FTS5 search, Markdown export, and Brigade-ready evidence bundles.
- 👣 [stationtrail](https://github.com/escoffier-labs/stationtrail) - Exports local agent session logs (Codex, Claude Code, OpenClaw, OpenCode, Hermes) to portable JSONL for MiseLedger.
- 🌾 [sourceharvest](https://github.com/escoffier-labs/sourceharvest) - Exports non-harness sources like notes, chat exports, and issue exports into the same adapter contract.

## Other projects I've built and maintain

**Security & Threat Intelligence**
- 🛡️ [cyberbrief](https://github.com/solomonneas/cyberbrief) - AI threat intel briefings with BLUF reports, ATT&CK mapping, and IOC extraction.
- 🔍 [vervet](https://github.com/solomonneas/vervet) - Network threat hunting for Zeek and Suricata logs with explainable per-host risk scoring and MITRE ATT&CK mapping.
- 🔬 [intel-workbench](https://github.com/solomonneas/intel-workbench) - Threat intel analysis with ACH matrices, evidence weighting, and STIX export.
- 📖 [hotwash](https://github.com/solomonneas/hotwash) - SOC playbook parser with mermaid diagram generation and Wazuh alert ingestion.
- 🏗️ [soc-stack](https://github.com/solomonneas/soc-stack) - Full SOC architecture covering MCP servers, detection pipelines, and deployment playbooks.

**MCP Servers**
- 🧠 [cortex-mcp](https://github.com/solomonneas/cortex-mcp) - Observable analysis for IOCs, reports, and response actions.
- 🛡️ [wazuh-mcp](https://github.com/solomonneas/wazuh-mcp) - SIEM access for agents, alerts, rules, and decoders.
- 🔬 [misp-mcp](https://github.com/solomonneas/misp-mcp) - Threat intel search, IOC correlation, and STIX/Suricata/CSV export.
- 🐝 [thehive-mcp](https://github.com/solomonneas/thehive-mcp) - Incident response workflows for cases, alerts, tasks, and observables.
- ⚔️ [mitre-mcp](https://github.com/solomonneas/mitre-mcp) - MITRE ATT&CK technique mapping, threat group profiling, and detection gap analysis.
- 🔎 [zeek-mcp](https://github.com/solomonneas/zeek-mcp) - Network monitoring access for connection, DNS, HTTP, and SSL logs.
- 🦔 [suricata-mcp](https://github.com/solomonneas/suricata-mcp) - IDS/IPS workflows for managing rules, querying alerts, and analyzing traffic.
- 🕸️ [maltego-mcp](https://github.com/solomonneas/maltego-mcp) - Maltego graph authoring and OSINT lookups for whois, DNS, ASN, and crt.sh.
- ⚙️ [n8n-ops-mcp](https://github.com/solomonneas/n8n-ops-mcp) - Ops control for n8n workflows, validation, and execution lifecycle.
- 🧱 [adguard-mcp](https://github.com/solomonneas/adguard-mcp) - AdGuard Home control with tools across read, safe-write, and destructive tiers.
- 🖥️ [proxmox-mcp](https://github.com/solomonneas/proxmox-mcp) - Proxmox VE control with 12 tools for container/VM lifecycle, snapshots, and backups.
- 📡 [librenms-mcp](https://github.com/solomonneas/librenms-mcp) - LibreNMS control with 10 tools for device, port, and alert reads plus alert acks.

**Network & Infrastructure**
- 🔭 [watchtower](https://github.com/solomonneas/watchtower) - NOC dashboard with interactive topology, L2/L3 views, and LibreNMS/Proxmox integration.
- 🔌 [portgrid](https://github.com/solomonneas/portgrid) - Switch port visualization for LibreNMS with color-coded views and instant search.
- 🔒 [proxguard](https://github.com/solomonneas/proxguard) - Proxmox security auditor with config parsers, CIS benchmarks, and remediation scripts.
- 🐧 [samba-ad-migration](https://github.com/solomonneas/samba-ad-migration) - Windows AD to Samba file share migration scripts for Proxmox.

**Media Automation**
- 🎬 [jellyfin-mcp](https://github.com/solomonneas/jellyfin-mcp) - Control Jellyfin from LLMs with playback sessions, library scans, user admin, and 20 MCP tools.
- 🖼️ [immich-mcp](https://github.com/solomonneas/immich-mcp) - Browse and search Immich photos, manage albums, recognize people, surface memories, and resolve duplicates.
- 🎞️ [reelgrep](https://github.com/solomonneas/reelgrep) - Local video search with ffprobe metadata, Whisper transcription, and FTS5 subtitle search.

I'm always open to building, contributing, collaborating, and chatting. Feel free to [reach out](https://solomonneas.dev).

### Featured Writing

- 💰 [How I Migrated 6 Servers from VMware to Proxmox and Saved $343K](https://solomonneas.dev/blog/vmware-to-proxmox-migration)
- 🖥️ [I Migrated Our Entire Infrastructure from Hyper-V to Proxmox](https://solomonneas.dev/blog/hyperv-to-proxmox-migration-guide)
- 💿 [Replacing SCCM with FOG Project](https://solomonneas.dev/blog/replacing-sccm-with-fog-project)
- 🛡️ [Building an Open-Source SOC](https://solomonneas.dev/blog/building-open-source-soc)
- 🧩 [I Built 7 MCP Servers for Security Tools. The Protocol Was the Easy Part.](https://solomonneas.dev/blog/building-security-mcp-servers)
- 📡 [A Fiber Cut at 2 PM Taught Me Why I Needed to Build Watchtower](https://solomonneas.dev/blog/building-watchtower)
- 🎓 [3 Days, 18 Hours: What I Learned at NDG's Proxmox Workshop](https://solomonneas.dev/blog/ndg-proxmox-workshop)
- 🤖 [Anthropic Broke My OpenClaw Stack. GPT 5.4 Put It Back Together](https://solomonneas.dev/blog/openclaw-after-anthropic-how-i-made-gpt-54-work)

<!--
### Tech
- **Languages:** Python (FastAPI), TypeScript (React, Next.js, Astro), Rust, SQL, Shell
- **Infrastructure:** Cisco IOS/IOS-XE, Dell PowerEdge, Proxmox, Fortinet, Juniper/Mist
- **Security:** Zeek, Suricata, Wazuh, TheHive, Cortex, MISP, MITRE ATT&CK
- **AI:** Claude, GPT, Gemini, MCP Servers, Ollama, OpenClaw, agent workflows
- **Tooling:** LibreNMS, Netdisco, Docker, Linux, Git
-->
