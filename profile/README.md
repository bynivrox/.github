<p align="center">
  <a href="https://nivrox.be"><img src="https://github.com/bynivrox/.github/raw/main/profile/banner.png" alt="Nivrox" width="100%"></a>
</p>

<h3 align="center">The visual infrastructure control plane for environments that already exist.</h3>

<p align="center">
  <a href="https://nivrox.be"><strong>nivrox.be</strong></a>
</p>

---

Real infrastructure is never a clean slate. Servers already run Docker, WireGuard, firewalls, reverse proxies and
services nobody fully documented. Deploying is the easy part; knowing **what a change will do** is the hard part.

**Nivrox Topology Manager** answers that with one workflow on one model:

**Model → Simulate → Plan → Approve → Deploy → Verify**

- **See it before you touch it.** Every connection is traced through DNS, routing, NAT, WireGuard, the firewall,
  Docker and the reverse proxy, with a plain explanation of where it passes and where it breaks.
- **Change only what is needed.** Configuration is generated from the model, and files Nivrox did not create are
  never overwritten.
- **Prove it worked.** Changes are deployed through signed agents with approval and backups, verified afterwards,
  and can be rolled back.

Built for Linux, Docker and Compose, WireGuard, nftables, DNS, Traefik and Checkmk, with more integrations on the way.

### Editions

**Community** is free and self-hosted. **Professional**, **Business** and **Enterprise** are hosted by Nivrox. See
[pricing](https://nivrox.be/pricing).

### On GitHub

| Repository | |
|---|---|
| [landing-page](https://github.com/bynivrox/landing-page) | The source of the Nivrox website |
