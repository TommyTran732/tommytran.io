---
title: "My Projects"
date: 2022-09-02
---

These are some of my most notable projects. For a complete list, please visit my [GitHub profile](https://github.com/TommyTran732).

## PrivSec.dev

[PrivSec.dev](https://privsec.dev) is a website created by me and a few friends to provide practical privacy and security advice for end users. Think of it as a shared blog focused on this topic.

We emphasize in-depth system configuration, security analysis, and software/hardware recommendations, prioritizing technical merits over ideologies or politics.

## Polarix Containers

[Polarix Containers](https://github.com/Polarix-Containers) is a collection of OCI containers designed to enhance security compared to upstream builds.

Some containers are daily rebuilds of upstream containers, while others are rebuilt from scratch using Alpine Linux or Red Hat UBI with unprivileged users, maintaining upstream compatibility. Most builds include `hardened_malloc` for added security.

Polarix Containers serve as the foundation for my other projects, such as [Metropolis.nexus](https://metropolis.nexus).

## Metropolis.nexus

[Metropolis.nexus](https://metropolis.nexus) is a collection of services I offer free of charge, including but not limited to:
- Matrix
- Mastodon
- Vaultwarden
- Redlib
- Traccar
- Stirling PDF
- Signature PDF

The [Metropolis-nexus GitHub organization](https://github.com/Metropolis-nexus) contains repositories documenting the system's setup. Key subprojects include:

### Linux Setup Scripts

These [setup scripts](https://github.com/Metropolis-nexus/Linux-Setup-Scripts) are used on my Linux systems and include hardening configurations such as:

- Removal of unnecessary packages
- Hardened boot parameters
- Hardened `sysctl` settings
- Kernel module blacklist from [SecureBlue](https://github.com/secureblue/secureblue)
- SSH client and server hardening
- Systemd hardening
- Installation of Hardened Malloc on Red Hat systems
- NTS setup

### Fedora CoreOS Ignition Files

These [Butane/Ignition configuration files](https://github.com/Metropolis-nexus/Fedora-CoreOS-Ignition) enable rapid deployment of Fedora CoreOS servers with the same hardening as the Linux Setup Scripts.

They also include systemd services to:
- Install and update gVisor at boot
- Update containers in a Docker Compose stack daily

### NGINX Configs

My reverse proxy setup is available in [this repository](https://github.com/Metropolis-nexus/NGINX-Setup). It includes:
- TLS configuration with strong cipher suites
- A robust set of security headers
- Content security policies for various services
- ModSecurity configuration
- Systemd hardening for system services

## QubesOS scripts

My [QubesOS scripts](https://github.com/TommyTran732/QubesOS-Script) configure Qubes virtual machines with the same hardening as my Linux setup scripts, tailored for Qubes' unique environment. I also provide documentation on how I set up my daily driver — a ThinkPad P53 — with Qubes for maximum privacy and security.

## Microsoft Egde Policies

Microsoft Edge can be one of the best browsers when configured properly, but it is privacy-invasive and has a large attack surface by default. My [list of policies](https://github.com/TommyTran732/Microsoft-Edge-Policies) configures it for improved privacy and security.