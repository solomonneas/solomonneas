### Yellow 👋, I'm Solomon

I'm a Network & Systems Engineer and teaching lab aid in Tampa, FL, working where cybersecurity, network observability, and AI infrastructure meet. I build SOC tooling, MCP servers, and multi-agent workflows that run on real production gear, not toy demos, and I write about it at [solomonneas.dev/blog](https://solomonneas.dev/blog).

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

- 🚩 **[brigade](https://github.com/escoffier-labs/brigade)** - **the flagship.** Mise en place for agent memory: an installable starter kit for a harness-agnostic agent workspace.
- 🍪 [agentpantry](https://github.com/escoffier-labs/agentpantry) - Encrypted, transport-agnostic sync of browser sessions and secrets from your daily driver to the box your agents run on, so they wake up authenticated.
- 🩺 [memory-doctor](https://github.com/escoffier-labs/memory-doctor) - Maintenance CLI for the Claude Code and OpenClaw memory systems: status, lint, ingest, compact.
- 🧰 [bootstrap-doctor](https://github.com/escoffier-labs/bootstrap-doctor) - Audits and trims oversize OpenClaw prefix files into reference cards via heuristics and LLM judgment.

## Other projects I've built and maintain

**OpenClaw & Dev Tools**
- 🔍 [code-search-api](https://github.com/solomonneas/code-search-api) - Local semantic code search with Ollama embeddings, SQLite, hybrid search, and LLM summaries.
- 🧩 [code-search-mcp](https://github.com/solomonneas/code-search-mcp) - Read-only MCP server and OpenClaw plugin that puts code-search-api in front of any agent.
- 🦞 [solos-cookbook](https://github.com/solomonneas/solos-cookbook) - Opinionated, dogfooded guide to running a 24/7 multi-agent AI stack on bare metal.
- 🍳 [solo-mise](https://github.com/solomonneas/solo-mise) - Mise en place for the cookbook: agent profiles, content scrubber, handoff, and memory ingester.
- 📡 [upstream-drift](https://github.com/solomonneas/upstream-drift) - Upstream drift watcher: LLM-summarized diffs of tracked repos with weekly Discord digests.
- 📊 [usage-tracker](https://github.com/solomonneas/usage-tracker) - Token usage and cost analytics for OpenClaw sessions across models.
- 📚 [prompt-library](https://github.com/solomonneas/prompt-library) - Dual-mode prompt management with browse/copy UI and a REST API for sub-agents.
- 🛂 [content-guard](https://github.com/solomonneas/content-guard) - Policy-driven content scanning and publish checks.
- 🔔 [agent-notify](https://github.com/solomonneas/agent-notify) - Privacy-first push notifications for AI coding agents to Discord, Telegram, and Signal with zero telemetry.
- 🖥️ [ops-deck-oss](https://github.com/solomonneas/ops-deck-oss) - Self-hosted operational dashboard for OpenClaw users: React UI plus a minimal FastAPI sidecar.
- 📸 [appshots](https://github.com/solomonneas/appshots) - Agent-neutral app screenshot capture CLI for clean, repeatable product shots.
- 🎞️ [appreels](https://github.com/solomonneas/appreels) - Agent-neutral demo-video recorder, the moving-picture sibling of appshots.

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
- 🧱 [adguard-mcp](https://github.com/solomonneas/adguard-mcp) - AdGuard Home control with tools across read, safe-write, and destructive tiers.
- 🖥️ [proxmox-mcp](https://github.com/solomonneas/proxmox-mcp) - Proxmox VE control with 12 tools for container/VM lifecycle, snapshots, and backups.
- 📡 [librenms-mcp](https://github.com/solomonneas/librenms-mcp) - LibreNMS control with 10 tools for device, port, and alert reads plus alert acks.

**Network & Infrastructure**
- 🔭 [watchtower](https://github.com/solomonneas/watchtower) - NOC dashboard with interactive topology, L2/L3 views, and LibreNMS/Proxmox integration.
- 🔌 [portgrid](https://github.com/solomonneas/portgrid) - Switch port visualization for LibreNMS with color-coded views and instant search.
- 🔒 [proxguard](https://github.com/solomonneas/proxguard) - Proxmox firewall rule visualization with conflict detection and rule simulation.
- 🧮 [config-diff-explainer](https://github.com/solomonneas/config-diff-explainer) - Offline CLI that turns before/after network device configs into operator-ready reports on what changed, what's risky, and how to roll back. 8 vendor parser paths.
- 📶 [eero-cli](https://github.com/solomonneas/eero-cli) - CLI for the eero mesh API with SMS auth, filtered device listing, and bulk blocking.
- 🐧 [samba-ad-migration](https://github.com/solomonneas/samba-ad-migration) - Windows AD to Samba file share migration scripts for Proxmox.

**Media Automation**
- 🎬 [jellyfin-mcp](https://github.com/solomonneas/jellyfin-mcp) - Control Jellyfin from LLMs with playback sessions, library scans, user admin, and 20 MCP tools.
- 🖼️ [immich-mcp](https://github.com/solomonneas/immich-mcp) - Browse and search Immich photos, manage albums, recognize people, surface memories, and resolve duplicates.
- 🎞️ [reelgrep](https://github.com/solomonneas/reelgrep) - Local video search with ffprobe metadata, Whisper transcription, and FTS5 subtitle search.
- 🔍 [reelgrep-mcp](https://github.com/solomonneas/reelgrep-mcp) - MCP wrapper for reelgrep with citation-formatted timestamps from your local video library.
- 🎚️ [media-cli](https://github.com/solomonneas/media-cli) - Single-file bash CLI for the self-hosted *arr media stack: Sonarr, Radarr, Prowlarr, qBittorrent, and more, locally or over SSH.

**Streaming & OBS**
- 🎛️ [deckctl](https://github.com/solomonneas/deckctl) - Declarative driver for the Elgato Stream Deck with YAML config and OBS execution.
- 🎥 [obsctl](https://github.com/solomonneas/obsctl) - kubectl-style multi-host wrapper for managing OBS Studio across machines from one CLI.

**Currently Contributing To**
- 🧃 [vincentkoc/tokenjuice](https://github.com/vincentkoc/tokenjuice) - Lean output compaction for terminal-heavy agent workflows.
- 📝 [steipete/summarize](https://github.com/steipete/summarize) - Fast summaries from URLs, files, and media via CLI and browser sidebars.
- 📬 [steipete/gogcli](https://github.com/steipete/gogcli) - Google Suite CLI for Gmail, Calendar, Drive, and Contacts.
- 🦞 [openclaw/openclaw](https://github.com/openclaw/openclaw) - Agent harness and CLI that runs my entire multi-agent stack on bare metal.
- 🦞 [openclaw/plugin-inspector](https://github.com/openclaw/plugin-inspector) - Offline compatibility inspector for mocking OpenClaw and testing plugins.
- 🔌 [openclaw/acpx](https://github.com/openclaw/acpx) - Headless CLI client for stateful Agent Client Protocol (ACP) sessions.
- 💬 [steipete/discrawl](https://github.com/steipete/discrawl) - CLI for Discord with a SQLite backend.
- 🎭 [microsoft/playwright](https://github.com/microsoft/playwright) - Cross-browser automation and testing framework.


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
