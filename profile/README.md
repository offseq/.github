## OffSeq – Offensive Sequence

European offensive security company: penetration testing, red teaming, OT and critical infrastructure security, NIS2/DORA readiness.

### Products

- **[Threat Radar](https://radar.offseq.com)** – live CVE, CISA KEV, EPSS and exploit intelligence; SBOM scans, REST API and MCP server (free plan)
- **[Mirage](https://mirage.offseq.com)** – honeypot threat intelligence console
- **[Breach](https://breach.offseq.com)** – leaked-credential monitoring for company domains
- **[Guard](https://guard.report)** – free website security and NIS2/GDPR scan
- **[Pulse](https://pulse.offseq.com)** – device posture agent for NIS2 and CIS v8.1, hosted in the EU

### Open data and integrations

- **[mirage-feed](https://github.com/offseq/mirage-feed)** – free daily attacker IPs, exploited CVEs and payload URLs from our honeypots, CC BY 4.0 ([feeds.offseq.com](https://feeds.offseq.com))
- **[zeek-offseq-mirage](https://github.com/offseq/zeek-offseq-mirage)** – `zkg install zeek-offseq-mirage`
- **[radar-scan-action](https://github.com/offseq/radar-scan-action)** – scan an SBOM or lockfile in CI, upload SARIF, gate the build
- Radar MCP server: `com.offseq/radar` in the [MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=com.offseq/radar)

### Tools

- **[threat-finder](https://github.com/offseq/threat-finder)** – runtime CVE scanner, ranks findings by network exposure (Rust; `brew install offseq/tap/threat-finder`, `cargo install threat-finder`)
- **[threadsrecon](https://github.com/offseq/threadsrecon)** – OSINT for threads.net
- **[servicediscovery](https://github.com/offseq/servicediscovery)** – CIDR-aware Nmap scanner with per-host XML output
- **[rockyou-lv](https://github.com/offseq/rockyou-lv)** – Latvian password wordlist for credential audits
- **[xcompare](https://github.com/offseq/xcompare)** – mutual followers between two X accounts, no API needed
- **[homebrew-tap](https://github.com/offseq/homebrew-tap)** – `brew tap offseq/tap`

Research and disclosures: [offseq.com/en/research](https://offseq.com/en/research/) · [offseq.com/en/case-studies](https://offseq.com/en/case-studies/)
Found a bug in our tools? [cvd.cert.lv/programs/view/101](https://cvd.cert.lv/programs/view/101)

[offseq.com](https://offseq.com/en/)
