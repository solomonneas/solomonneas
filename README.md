### Yellow 👋, I'm Solomon

I'm a Network & Systems Engineer / Teaching Lab Aid focused on cybersecurity, network observability, and AI infrastructure. I build SOC tooling, MCP servers, and agent workflows that run on real production gear, not toy demos. I write about it at [solomonneas.dev/blog](https://solomonneas.dev/blog).

- <img src="https://flagcdn.com/20x15/us.png" alt="US flag" width="20"> US based in Tampa, FL, near the beach.
- 👨‍👧 Father, retired chef of 17 years, OSS contributor, and beach lover when I'm not on a screen.
- 📜 M.S. Cybersecurity Intelligence & Information Security at the University of South Florida.
- 🛡️ Building open-source SOC + threat intel tooling on bare-metal Proxmox.
- 🤖 Deep in multi-agent orchestration, MCP servers, and detection engineering.
- 🪢 n8n enthusiast, wiring up self-hosted automation for intel pipelines, monitoring, and SOC ops.
- 🧭 Currently exploring self-hosted AI stacks, network observability, and incident response automation.
- 🗣️ Ask me about **Proxmox migrations, network monitoring, MCP servers, OpenClaw, agent orchestration, and open-source SOC**.
- ⚙️ Big believer in open source, dogfooding everything, and writing it down so the next person doesn't have to figure it out.
- 🫶 If my work helped you, [buy me a coffee](https://www.buymeacoffee.com/solomonneas) or [tip on Ko-fi](https://ko-fi.com/solomonneas).
- 📫 Reach me at [me@solomonneas.dev](mailto:me@solomonneas.dev) · [LinkedIn](https://www.linkedin.com/in/solomon-neas/) · [X](https://x.com/solomonneas) <!-- content-guard: allow pii/email -->

Some of the projects I've built or maintain:

**OpenClaw & Dev Tools**
- 🔍 [code-search-api](https://github.com/solomonneas/code-search-api) - Local semantic code search with Ollama embeddings, SQLite, hybrid search, and LLM summaries.
- 🦞 [solos-cookbook](https://github.com/solomonneas/solos-cookbook) - Opinionated, dogfooded guide to running a 24/7 multi-agent AI stack on bare metal.
- 🍳 [solo-mise](https://github.com/solomonneas/solo-mise) - Mise en place for the cookbook: one `pipx install` lays down 6 agent profiles, content scrubber, handoff scaffolding, and a memory ingester.
- 📊 [usage-tracker](https://github.com/solomonneas/usage-tracker) - Token usage and cost analytics for OpenClaw sessions across models.
- 📚 [prompt-library](https://github.com/solomonneas/prompt-library) - Dual-mode prompt management with browse/copy UI and a REST API for sub-agents.
- 🛂 [content-guard](https://github.com/solomonneas/content-guard) - Policy-driven content scanning and publish checks.
- 🩺 [memory-doctor](https://github.com/solomonneas/memory-doctor) - Maintenance CLI for the Claude Code / OpenClaw memory system with status, lint, ingest, and compact verbs, dry-run defaults, and atomic writes.

**Security & Threat Intelligence**
- 🛡️ [cyberbrief](https://github.com/solomonneas/cyberbrief) - AI threat intel briefings with BLUF reports, ATT&CK mapping, and IOC extraction.
- 🔍 [bro-hunter](https://github.com/solomonneas/bro-hunter) - Threat hunting for Zeek and Suricata logs with beaconing detection and MITRE mapping.
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
- 📮 [postiz-mcp](https://github.com/solomonneas/postiz-mcp) - Postiz social scheduling control with full public-API coverage, env-gated writes, and a 30/hr rate-limit guard.
- 🧱 [adguard-mcp](https://github.com/solomonneas/adguard-mcp) - AdGuard Home control across one or more instances with 28 tools across read, safe-write, and destructive tiers with three-tier confirm gates.
- 🖥️ [proxmox-mcp](https://github.com/solomonneas/proxmox-mcp) - Proxmox VE control with 12 tools covering status, container + VM lifecycle, snapshots, backups, and recent tasks.
- 📡 [librenms-mcp](https://github.com/solomonneas/librenms-mcp) - LibreNMS network monitoring control with 10 tools for device, port, and alert reads, port health rankings, alert ack, and maintenance windows.

**Network & Infrastructure**
- 🔭 [watchtower](https://github.com/solomonneas/watchtower) - NOC dashboard with interactive topology, L2/L3 views, and LibreNMS/Proxmox integration.
- 🔌 [portgrid](https://github.com/solomonneas/portgrid) - Switch port visualization for LibreNMS with color-coded views and instant search.
- 🔒 [proxguard](https://github.com/solomonneas/proxguard) - Proxmox firewall rule visualization with conflict detection and rule simulation.
- 📶 [eero-cli](https://github.com/solomonneas/eero-cli) - Tiny CLI for the eero mesh API with non-interactive SMS auth, regex/MAC filtered device listing, and bulk blocking.
- 🐧 [samba-ad-migration](https://github.com/solomonneas/samba-ad-migration) - Windows AD to Samba file share migration scripts for Proxmox.

**Media Automation**
- 🎬 [jellyfin-mcp](https://github.com/solomonneas/jellyfin-mcp) - Control Jellyfin from LLMs with playback sessions, library scans, user admin, and 20 MCP tools.
- 🎞️ [reelgrep](https://github.com/solomonneas/reelgrep) - Local video search and analysis with ffprobe metadata, Whisper transcription, FTS5 subtitle search, pluggable person-finding, and a browser UI.
- 🔍 [reelgrep-mcp](https://github.com/solomonneas/reelgrep-mcp) - MCP wrapper for reelgrep so agents can answer "which lecture mentioned X?" with citation-formatted timestamps from your local video library.

**Streaming & OBS**
- 🎛️ [deckctl](https://github.com/solomonneas/deckctl) - Cross-platform declarative driver for the Elgato Stream Deck with YAML config, hot reload, OBS execution, and auto profile switching, no Elgato app required.
- 🎥 [obsctl](https://github.com/solomonneas/obsctl) - kubectl-style multi-host wrapper around grigio/obs-cmd for managing OBS Studio across multiple machines from one CLI.

**Currently Contributing To**
- 🧃 [vincentkoc/tokenjuice](https://github.com/vincentkoc/tokenjuice) - Lean output compaction for terminal-heavy agent workflows.
- 📝 [steipete/summarize](https://github.com/steipete/summarize) - Fast summaries from URLs, files, and media. CLI + Chrome Side Panel + Firefox Sidebar with video slides, OCR, and transcript extraction.
- 📬 [steipete/gogcli](https://github.com/steipete/gogcli) - Google Suite CLI for Gmail, Calendar, Drive, and Contacts.
- 🦞 [openclaw/openclaw](https://github.com/openclaw/openclaw) - Agent harness and CLI that runs my entire multi-agent stack on bare metal.
- 🦞 [openclaw/plugin-inspector](https://github.com/openclaw/plugin-inspector) - Offline compatibility inspector for mocking OpenClaw and testing plugins.
- 🔌 [openclaw/acpx](https://github.com/openclaw/acpx) - Headless CLI client for stateful Agent Client Protocol (ACP) sessions.
- 💬 [steipete/discrawl](https://github.com/steipete/discrawl) - CLI for Discord with a SQLite backend.
- 🎭 [microsoft/playwright](https://github.com/microsoft/playwright) - Cross-browser automation and testing framework, including the Playwright MCP server for agents.


I'm always open to building, contributing, collaborating, and chatting. Feel free to [reach out](https://solomonneas.dev).

### Featured Writing

- 💰 [How I Migrated 6 Servers from VMware to Proxmox and Saved $343K](https://solomonneas.dev/blog/vmware-to-proxmox-migration)
- 🖥️ [I Migrated Our Entire Infrastructure from Hyper-V to Proxmox](https://solomonneas.dev/blog/hyperv-to-proxmox-migration-guide)
- 💿 [Replacing SCCM with FOG Project](https://solomonneas.dev/blog/replacing-sccm-with-fog-project)
- 🛡️ [I'm a Lab Assistant. So I Built My Own SOC](https://solomonneas.dev/blog/building-open-source-soc)
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
