# haras-unicorn

Rust and Nix, mostly, and whatever the problem actually needs. I like
reproducible things, declarative things, and knowing why they work.

`#sfinae` `#pin-box-future` `#fod` `#raft`

---

## What I'm building

**[tower-of-ha](https://github.com/haras-unicorn/tower-of-ha)** — a declarative,
highly-available NixOS platform. CephFS, HAProxy, Patroni/etcd Postgres, Garage
S3, OpenBao, Forgejo, Vaultwarden, mail — all composed from option-typed
modules, with real HA thinking (quorum, failover) and a Nushell CLI.

**[cryl](https://github.com/haras-unicorn/cryl)** — a sandboxed secret manager
in Rust. Hermetic, reproducible, bubblewrap-isolated, sops-nix integration.

**[omw](https://github.com/haras-unicorn/omw)** — an agent runtime in Rust/WASM
with MCP tooling. Built AI-native: I direct the agents and write the critical
paths by hand.

**[dot](https://github.com/haras-unicorn/dot)** — my flake-based NixOS
configuration. Everything declarative: system modules, overlays, secrets, and
per-machine profiles for a desktop and a small Pi cluster.

---

Croatia · remote-friendly · [github@haras-unicorn.net]
