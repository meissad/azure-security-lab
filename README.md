# Azure Security Lab

Hands-on labs and projects from my transition into Cloud Security Engineering, starting with Microsoft Azure.

I come from network and systems administration and cybersecurity. This repo documents how I apply that background to the cloud: identity, network security, logging and detection, built and tested in a real Azure environment.

## Status

🚧 In progress: November–December 2026

| Week | Topic | Status |
|---|---|---|
| 1 | Azure foundations: networking, compute, storage | ⏳ |
| 2 | Identity: Entra ID, RBAC, managed identities, Key Vault | ⏳ |
| 3 | Network security, logging, KQL, Defender for Cloud, Azure Policy | ⏳ |
| 4 | Capstone: secure Azure baseline | ⏳ |

## Repository structure

```
week1/   Foundations: CLI deployment scripts, notes
week2/   Identity and secrets
week3/   Monitoring, detection queries (KQL), policies
week4/   Capstone: architecture, deployment, security review
```

## How I work

- Everything is deployed with the Azure CLI, scripted, and torn down after each session
- Each week ends with a write-up: what I built, the security decisions behind it, and what I'd do differently
- No secrets, keys or identifiers are committed to this repo

## Tools

Azure CLI · Bash · KQL · Microsoft Entra ID · Microsoft Defender for Cloud · Azure Policy · Keycloak
