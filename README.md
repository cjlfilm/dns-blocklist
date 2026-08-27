# DNS Blocklist

The 1-million-domain list (`short.txt`) is best for low-powered hardware and trouble-free daily use, while the 16-million-domain list (`bulk.txt`) is best for maximum security isolation.

### short.txt (1 Million Domains)
* **Best Purpose:** Everyday home networks, smart TVs, and standard family devices.
* **Advantages:** 
  * Uses very little system memory (RAM).
  * Extremely rare website breakage.
  * Low administrative maintenance.
* **Disadvantages:**
  * Misses niche malware and emerging phishing links.
  * Allows aggressive, lesser-known tracking scripts to pass.
  * Leaves specialized corporate telemetry unblocked.

### bulk.txt (16 Million Domains)
* **Best Purpose:** High-security labs, dedicated privacy setups, and advanced power users.
* **Advantages:**
  * Blocks obscure, newly registered, and parked malicious domains.
  * Eliminates almost all corporate data harvesting.
* **Disadvantages:**
  * Consumes high amounts of system memory (RAM).
  * High false-positive rate that breaks normal web browsing.
  * Requires constant manual whitelist troubleshooting.

Use the 1 million list if you want a trouble-free internet experience for daily tasks.Use the 16 million list if you prioritize total privacy and have the time to fix broken websites.

# Disclaimer

This blocklist is provided **as is** for advanced DNS filtering, privacy, security, and content-blocking purposes.

With approximately **18 million domains**, this is an extremely aggressive blocklist. False positives are expected, and legitimate services may be blocked either partially or completely. This can include websites, APIs, CDNs, streaming services, gaming platforms, software updates, authentication systems, telemetry endpoints, and other commonly used online services.

By using this blocklist, you acknowledge and accept that:

- Legitimate websites or applications may stop functioning correctly
- Some services may fail to connect, update, authenticate, or load content
- Network troubleshooting may become more difficult
- You are responsible for maintaining your own whitelist/allowlist
- No guarantee is provided regarding accuracy, completeness, or suitability for any purpose

This blocklist is intended for users who understand how DNS filtering works and who are comfortable diagnosing and resolving issues caused by blocked domains.

## Liability

The maintainer(s) of this blocklist are **not responsible** for:

- Broken websites or applications
- Service interruptions
- Data loss
- Network instability
- Financial losses
- Any direct or indirect damages resulting from use of this blocklist

**Use at your own risk.**

---

## Recommendation

Before deploying this blocklist widely, it is strongly recommended to:

- Test in a non-critical environment first
- Monitor DNS logs regularly
- Maintain a personal whitelist
- Use staged rollouts where possible
- Temporarily disable the list during troubleshooting

---

> ⚠️ This is an extremely aggressive blocklist. False positives will occur.
> Use only if you understand DNS filtering and are prepared to maintain your own whitelist.
