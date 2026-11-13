# Homelab

My personal homelab for learning, self-hosting, and experimenting with systems administration, networking, automation, and security.

This repository documents the design and evolution of my infrastructure: the decisions behind it, deployment procedures, configuration examples, scripts, and lessons learned along the way.

> This is a personal learning environment and an ongoing project, not a production-ready infrastructure template.

## Overview

The lab is built around **Proxmox VE** and is intended to provide a safe environment to deploy services, experiment with Linux and Windows systems, practice automation, and apply defensive security basics.

## Hardware

| Component | Details |
|---|---|
| CPU | Intel i5-9600K |
| RAM | 2 x 16GB DDR4 |
| Storage | 1TB HDD |
| Network | Router & switches |

## Current Setup

- Proxmox VE 9.2.1 installed on bare metal.
- VMs: Windows Server.
- Services: .

## Roadmap

- Phase 1 — Proxmox installation and initial configuration. *(done)*
- Phase 2 — First Linux and Windows VMs. *(done)*
- Phase 3 — Deployment of personal services. *(in progress)*
- Phase 4 — Backups and recovery testing.
- Phase 5 — Automation and security hardening.

## Next Steps

- [ ] Set up Tailscale for secure remote access.
- [ ] Document each VM and service as it is deployed.
- [ ] Implement a backup routine and test a full restore.

## About

I am an ASIR student — Higher Vocational Training in Networked Computer Systems Administration — developing practical skills in systems administration, cloud infrastructure, and cybersecurity.

This repository is a record of what I build, test, break, recover, and learn.

> **Note:** Features such as high availability, redundancy, and disaster recovery should not be assumed unless explicitly documented and validated. Instructions may require changes for different hardware, software versions, or network layouts.
