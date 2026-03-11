# Hey, I'm Collin

Cybersecurity analyst based in the DMV. I build and break things in my homelab and write about what actually happens — the friction, the tradeoffs, the stuff that doesn't work the first time.

Currently looking for full-time security roles.

---

## What I'm Working On

- **Security Onion deployment** — Standing up a full NSM stack in my homelab. Documenting the process from hardware selection through traffic validation and tuning. ([Signal and Noise series →](https://secblues.com/category/signal-and-noise/))
- **Self-hosted infrastructure** — Proxmox cluster, OPNsense firewall, VLAN segmentation, AdGuard Home, reverse proxy stack, Home Assistant. All documented.
- **TCM Security PSAA cert** — Completed. Working toward Security+.

---

## Homelab Stack

| Layer | Tech |
|-------|------|
| Hypervisor | Proxmox (two nodes) |
| Firewall / Router | OPNsense |
| Switching | UniFi (VLAN segmentation) |
| DNS | AdGuard Home + Unbound |
| Security Monitoring | Security Onion 2.4 (standalone) |
| Reverse Proxy | Traefik v3 |
| IoT / Automation | Home Assistant OS |
| Blog | WordPress @ [secblues.com](https://secblues.com) |

Network is segmented into six VLANs — Management, Lab, TrustedHome, ServerMedia, IoTUntrusted, and Guest — all running through OPNsense on a default-deny model. Details in [homelab-docs](https://github.com/SecBlues/homelab-docs).

---

## Writing

I document real deployments on my blog — not sanitized walkthroughs, but the actual decisions and tradeoffs. Recent series:

- [**The Mailroom**](https://secblues.com/category/the-mailroom/) — Self-hosted email server: architecture, deployment, hardening, and client access. Four parts.
- [**Signal and Noise**](https://secblues.com/category/signal-and-noise/) — Security Onion in the homelab. In progress.
- [**Hardening the Stack**](https://secblues.com/hardening-the-stack-a-comprehensive-guide-to-wordpress-security/) — WordPress security from default install to production hardened.

---

## Certs & Training

- TCM Security PSAA (Practical Security Analyst Associate)
- TryHackMe — active
- Security+ — in progress

---

## Links

- 🌐 Blog: [secblues.com](https://secblues.com)
- 💼 LinkedIn: *(coming soon)*
- 📁 Homelab docs: [homelab-docs](https://github.com/SecBlues/homelab-docs)

---

*Based in the DMV. Open to full-time security roles.*
