# Awesome-Privileged-Access-Management

## Top Privileged Access Management (PAM) Platforms



A curated list of leading Privileged Access Management (PAM) solutions for securing, managing, monitoring, and auditing privileged accounts, credentials, sessions, and just-in-time access across hybrid, multi-cloud, and modern infrastructure.  

**Primary focus: open-source software.**



Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.



---



## SaaS / Hosted Platforms



| Platform | Company Size (Revenue / Valuation) | Description | Key Focus | Pricing (Starting Tier) | Free Tier / Trial |

|---------|-----------------------------------|-------------|-----------|--------------------------|-------------------|

| **[HashiCorp Boundary](https://www.boundaryproject.io/)** | **$6.4B** (IBM acquisition, 2025); ~$300M revenue | Identity-aware proxy for least-privileged access to infrastructure. Integrates with Vault for dynamic credentials, session recording, and automated discovery. | Secure infrastructure access without credential distribution | HCP from **$0.10/resource/mo** (usage-based metering) | **$500 HCP trial credit** (pay-as-you-go); free open-source Community Edition |

| **[Ping Identity](https://www.pingidentity.com/)** (Advanced Identity Cloud / PAM capabilities) | **$2.8B** (Thoma Bravo acquisition, 2022); ~$400M revenue | Identity platform with advanced access management and privileged controls in cloud environments. | Identity governance + privileged access | PingOne Workforce Essential **$3/user/mo** (5,000-user min ≈ $15,000/yr); Customers Essential from $35,000/yr | **30-day free trial** (PingOne for Customers / Workforce); no free-forever tier |

| **[Tailscale SSH](https://tailscale.com/)** | **$1.5B** valuation (2025 raise) | WireGuard-based zero-trust networking with identity-aware SSH access, ACLs, and easy mesh connectivity. Lightweight alternative for secure remote access. | Zero-trust networking + SSH | Standard **$8/user/mo**; Premium **$18/user/mo** | **Free-forever plan**: up to 6 users, unlimited devices |

| **[Teleport](https://goteleport.com/)** | **$1.1B** valuation (2023 Series C) | Modern infrastructure access platform (open-source core + commercial). Certificate-based, passwordless access to SSH, Kubernetes, databases, Windows, and web apps with session recording. | Identity-based, vault-free PAM for cloud-native teams | from **$12–$18/resource/mo** (Team tier, cloud) | **14-day free trial** (Enterprise Cloud/Self-Hosted); free open-source Community Edition |

| **[CyberArk](https://www.cyberark.com/)** | **~$1.0B** revenue (2025, NASDAQ: CYBR) | Industry-leading PAM platform with Enterprise Password Vault, Privileged Session Manager, secrets management, and zero standing privileges. Strong for hybrid/multi-cloud and high-risk access. | Full lifecycle privileged credential & session management | ~$600–$1,100 per user/year (~$50–$90/user/mo), quote-based | **30-day free trial** (Privilege Cloud sandbox); no free-forever tier |

| **[ManageEngine PAM360](https://www.manageengine.com/privileged-access-management/)** | **~$1B+** revenue (parent Zoho, 2023) | Full-stack PAM with privileged account/session management, privilege elevation, discovery, recording, and strong compliance reporting. | Affordable enterprise PAM with ITSM integrations | Enterprise Edition **$7,995/yr** (10 admins, 25 SSH keys, unlimited users/resources) | **Free-forever Free Edition** (1 admin, up to 10 resources) + **30-day full trial** |

| **[One Identity Safeguard](https://www.oneidentity.com/)** | **~$500M** est. revenue (Quest Software portfolio) | PAM suite including Privileged Passwords, Privileged Sessions, and Analytics. Part of broader One Identity/Quest portfolio for password vaulting and session management. | Privileged passwords + session recording | quote-based (module licensing) | **30-day free trial** (Safeguard for Privileged Passwords / Privilege Manager) |

| **[BeyondTrust](https://www.beyondtrust.com/)** | **~$400M** est. revenue (private) | Modern PAM with Pathfinder platform, True Privilege graph, JIT access, identity security insights, and AI agent security. Leader in Gartner Magic Quadrant. | Identity security posture, JIT, and cross-domain visibility | from ~$1,995/mo (base enterprise remote-support tier) | **14-day free trial** (Remote Support / Privileged Remote Access); no free-forever tier |

| **[StrongDM](https://www.strongdm.com/)** (now part of Delinea) | **~$400M** (2024 acquisition valuation) | Zero Trust PAM with protocol-aware proxy for databases, servers, Kubernetes, and apps. Ephemeral credentials, continuous authorization, and developer-friendly workflows. | Infrastructure access proxy & JIT | **$50/user/mo** (single SKU, annual commitment) | **14-day free trial** (full Control Plane + proxy, no credit card); no free-forever tier |

| **[Delinea](https://delinea.com/)** | **~$250M** est. revenue (Thoma Bravo portfolio) | AI-driven, cloud-native identity security and PAM platform (includes Secret Server and Cloud Suite). Acquired StrongDM for enhanced JIT proxy capabilities. | Unified identity discovery, vaulting, and multi-cloud PAM | ~$45–$180+/user/year by tier (Professional/Premium/Platinum), quote-based | **30-day free trial** (Secret Server / Privilege Manager / Server PAM); no free-forever tier |

| **[Akeyless](https://www.akeyless.io/)** | **$250M** valuation (2023 Series C) | Modern SaaS PAM with short-lived credentials, identity-based policies, and support for humans, machines, and AI agents. Secrets management + secure remote access. | Zero standing privileges & secrets | enterprise quote-based (aggregators list base from ~$7/mo) | **Free-forever plan**: 5 clients, 500 static secrets, 5 dynamic secrets, 5 rotated secrets, 3 targets, 1 gateway cluster, 3-day audit retention |

| **[KeeperPAM](https://www.keepersecurity.com/)** | **~$100M+** est. revenue (private) | Cloud-native PAM consolidating password management, secrets, connection management, ZTNA, remote browser isolation, and session recording. | Unified vault + privileged connections | Business Starter **$2/user/mo** (annual, min 5 users); full KeeperPAM custom-quoted | **30-day free trial** (Business/Enterprise/KeeperPAM); reverts to limited free local view |

| **[Senhasegura](https://www.senhasegura.com/)** | **~$100M** est. revenue (private, Brazil) | Comprehensive PAM with credential management, session monitoring, and audit features. Strong presence in Latin America and growing globally. | Full PAM suite with high reliability | quote-based (advertises ~70% lower TCO than competitors) | Free demo / evaluation environment on request; no self-service trial |

| **[SecureAuth](https://www.secureauth.com/)** / related identity platforms | **~$50M** est. revenue (private) | Advanced identity and access solutions that include privileged access controls and adaptive authentication. | Identity-centric access security | from ~**$1/user/mo** (baseline Secure plan) | **14-day free trial** (Customer Authority / CIAM platform, no credit card); no free-forever tier |

| **[WALLIX](https://www.wallix.com/)** | **~€44M (~$48M)** revenue (2024, Euronext: ALLIX) | European PAM (Bastion) with strong session management, credential vaulting, and compliance focus (NIS2, etc.). | Session recording & European regulatory fit | ~$4–$6/user/mo (Capterra estimate) | **30-day free trial** (WALLIX PAM platform, no credit card); no free-forever tier |

| **[ARCON](https://arconnet.com/)** | **<$50M** est. revenue (private, India) | Modular PAM suite (on-prem, virtual, or PAMaaS) focused on privileged account management, session control, and compliance, especially strong in APAC and financial services. | Comprehensive privileged access control | from **$390/user/year** (1–99 user band, AWS Marketplace) | No free tier; custom demo / proof-of-concept on request |



---



## Open-Source Softwares



Open-source PAM and secure access tools have matured significantly. Leading options provide identity-based access, session recording, just-in-time privileges, and support for SSH, RDP, Kubernetes, databases, and more — often without traditional credential vaults.



### Core Frameworks & PAM Platforms



| Project | Description | License | Notes |

|---------|-------------|---------|-------|

| **[JumpServer](https://github.com/jumpserver/jumpserver)** [![Stars](https://img.shields.io/github/stars/jumpserver/jumpserver?style=social&color=white&label=Stars)](https://github.com/jumpserver/jumpserver/stargazers) | Full open-source PAM / bastion host platform. Web-based access to SSH, RDP, Kubernetes, databases, and RemoteApp with credential vault, session recording, and on-demand access. | GPL-3.0 | Mature, widely used alternative to commercial bastions |

| **[Teleport](https://github.com/gravitational/teleport)** (Community Edition) [![Stars](https://img.shields.io/github/stars/gravitational/teleport?style=social&color=white&label=Stars)](https://github.com/gravitational/teleport/stargazers) | Leading open-source infrastructure access platform. Certificate-based, short-lived credentials for SSH, Kubernetes, databases, Windows, web apps, and more. Built-in session recording, audit logs, RBAC, and SSO. | Apache 2.0 | Most complete open-source modern PAM; commercial edition adds enterprise features |

| **[Pomerium](https://www.pomerium.com/)** (open-source core) [![Stars](https://img.shields.io/github/stars/pomerium/pomerium?style=social&color=white&label=Stars)](https://github.com/pomerium/pomerium/stargazers) | Identity-aware access proxy for zero-trust access to internal applications and services. | Apache 2.0 | Zero-trust application access |

| **[HashiCorp Boundary](https://github.com/hashicorp/boundary)** (Community Edition) [![Stars](https://img.shields.io/github/stars/hashicorp/boundary?style=social&color=white&label=Stars)](https://github.com/hashicorp/boundary/stargazers) | Identity-aware proxy for secure, least-privileged access to infrastructure. Supports dynamic credentials (via Vault), session recording, automated target discovery, and Terraform automation. | MPL-2.0 | Excellent for platform teams; pairs perfectly with Vault |

| **[Apache Guacamole](https://guacamole.apache.org/)** [![Stars](https://img.shields.io/github/stars/apache/guacamole-client?style=social&color=white&label=Stars)](https://github.com/apache/guacamole-client/stargazers) | Clientless remote desktop gateway supporting RDP, VNC, SSH, and more via HTML5. Can be extended for privileged session management and recording. | Apache 2.0 | Lightweight remote access gateway |

| **[FreeIPA](https://www.freeipa.org/)** / Red Hat IdM [![Stars](https://img.shields.io/github/stars/freeipa/freeipa?style=social&color=white&label=Stars)](https://github.com/freeipa/freeipa/stargazers) | Open-source identity management for Linux/Unix with LDAP, Kerberos, DNS, host-based access control, and sudo policies. Strong foundation for Linux privileged access. | GPL | Centralized Linux identity & access control |



### Specialized Libraries & Related Tools



| Project | Description | Focus Area |

|---------|-------------|---------|

| **[Headscale](https://github.com/juanfont/headscale)** [![Stars](https://img.shields.io/github/stars/juanfont/headscale?style=social&color=white&label=Stars)](https://github.com/juanfont/headscale/stargazers) | Open-source, self-hostable control server implementing the Tailscale coordination protocol for zero-trust mesh VPNs. | Zero-trust networking control plane |

| **[Keycloak](https://github.com/keycloak/keycloak)** [![Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white&label=Stars)](https://github.com/keycloak/keycloak/stargazers) | Open-source identity and access management with SSO, MFA, and fine-grained authorization that integrates with PAM workflows. | Identity provider for PAM |

| **[HashiCorp Vault](https://github.com/hashicorp/vault)** [![Stars](https://img.shields.io/github/stars/hashicorp/vault?style=social&color=white&label=Stars)](https://github.com/hashicorp/vault/stargazers) | Secrets management platform frequently paired with Boundary or Teleport for dynamic credentials and rotation. | Secrets & dynamic credentials |

| **[Tailscale](https://github.com/tailscale/tailscale)** [![Stars](https://img.shields.io/github/stars/tailscale/tailscale?style=social&color=white&label=Stars)](https://github.com/tailscale/tailscale/stargazers) | Open-source client for WireGuard-based zero-trust networking with identity-aware SSH access and ACLs. | Zero-trust networking + SSH |

| **[Infisical](https://github.com/Infisical/infisical)** [![Stars](https://img.shields.io/github/stars/Infisical/infisical?style=social&color=white&label=Stars)](https://github.com/Infisical/infisical/stargazers) | Open-source secrets management platform with dynamic secrets, encryption, and universal sync for teams. | Secrets management |

| **[Authelia](https://github.com/authelia/authelia)** [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white&label=Stars)](https://github.com/authelia/authelia/stargazers) | Open-source authentication and authorization server providing SSO, 2FA, and access control for protected apps. | Identity provider for PAM |

| **[Authentik](https://github.com/goauthentik/authentik)** [![Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white&label=Stars)](https://github.com/goauthentik/authentik/stargazers) | Open-source identity provider with SSO, MFA, and flexible outposts for securing internal applications. | Identity provider for PAM |

| **[age](https://github.com/FiloSottile/age)** [![Stars](https://img.shields.io/github/stars/FiloSottile/age?style=social&color=white&label=Stars)](https://github.com/FiloSottile/age/stargazers) | Simple, modern, and secure file encryption tool used to encrypt secrets at rest. | Encryption for secrets at rest |

| **[SOPS](https://github.com/getsops/sops)** [![Stars](https://img.shields.io/github/stars/getsops/sops?style=social&color=white&label=Stars)](https://github.com/getsops/sops/stargazers) | Editor of encrypted files (YAML/JSON/ENV) supporting KMS, PGP, and age — a staple for GitOps secret workflows. | Secrets ops (GitOps) |

| **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)** [![Stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=social&color=white&label=Stars)](https://github.com/open-policy-agent/opa/stargazers) | Policy engine for fine-grained, context-aware access decisions across infrastructure and applications. | Policy-based access control |

| **[step-ca](https://github.com/smallstep/certificates)** [![Stars](https://img.shields.io/github/stars/smallstep/certificates?style=social&color=white&label=Stars)](https://github.com/smallstep/certificates/stargazers) | Private certificate authority for short-lived SSH/TLS certificates as an alternative to static keys. | Certificate-based access |

| **[Warpgate](https://github.com/warp-tech/warpgate)** [![Stars](https://img.shields.io/github/stars/warp-tech/warpgate?style=social&color=white&label=Stars)](https://github.com/warp-tech/warpgate/stargazers) | Smart SSH & HTTPS bastion with recording, audit, and easy access control. | Lightweight bastion |

| **[OpenBao](https://github.com/openbao/openbao)** [![Stars](https://img.shields.io/github/stars/openbao/openbao?style=social&color=white&label=Stars)](https://github.com/openbao/openbao/stargazers) | Community-driven, open-source fork of HashiCorp Vault for secrets management and dynamic credentials. | Secrets & dynamic credentials |

| **[Kanidm](https://github.com/kanidm/kanidm)** [![Stars](https://img.shields.io/github/stars/kanidm/kanidm?style=social&color=white&label=Stars)](https://github.com/kanidm/kanidm/stargazers) | Modern, Rust-based identity management platform designed to be simple and secure with built-in MFA. | Identity management |

| **[Bastillion](https://github.com/bastillion-io/Bastillion)** [![Stars](https://img.shields.io/github/stars/bastillion-io/Bastillion?style=social&color=white&label=Stars)](https://github.com/bastillion-io/Bastillion/stargazers) | Web-based SSH console with key management and session control. | Web SSH management |

| **[Conjur](https://github.com/cyberark/conjur)** [![Stars](https://img.shields.io/github/stars/cyberark/conjur?style=social&color=white&label=Stars)](https://github.com/cyberark/conjur/stargazers) | CyberArk's open-source secrets management solution for machine identities with policy-based access. | Secrets & machine identity |

| **Linux PAM modules + sudoers management** | Standard Pluggable Authentication Modules and tools for fine-grained privilege control on Linux systems. | OS-level privilege elevation |

| **Custom certificate authorities & short-lived cert tools** | Various open-source projects (e.g., step-ca) for issuing ephemeral SSH/TLS certificates as an alternative to static keys. | Certificate-based access |



### Additional Notable Open-Source Tools



- **Session recording & audit tools** — Many projects build on Guacamole or custom proxies for DVR-style playback.

- **Zero-trust networking** — Tailscale (open-source client components), Headscale, and WireGuard-based solutions complement PAM.

- **Secrets engines** — Vault, SOPS, age, and community secrets managers.

- **Kubernetes-native access** — Teleport, Boundary, and projects like kube-apiserver proxies or OPA/Gatekeeper for policy.

- **Community bastions and jump hosts** — Numerous self-hosted solutions for SSH/RDP gatewaying with logging.



**Note:** Traditional credential vaulting and deep Windows/Active Directory privileged account discovery remain stronger in commercial PAM. Open-source tools excel at modern infrastructure (SSH, Kubernetes, databases, cloud), certificate-based access, session recording, and just-in-time workflows. Many organizations combine Teleport or Boundary with Vault and an IdP for a complete open-source stack.



---



## Quick Start Recommendations



| Goal | Recommended Starting Point |

|------|---------------------------|

| Full open-source modern PAM (SSH, K8s, DBs, recording) | **Teleport Community Edition** |

| Identity-aware proxy + dynamic credentials | **HashiCorp Boundary** + **Vault** |

| Web-based multi-protocol bastion (SSH/RDP/DB) | **JumpServer** |

| Lightweight remote desktop / gateway | **Apache Guacamole** |

| Linux identity & host-based access control | **FreeIPA** |

| Enterprise commercial PAM leaders | **CyberArk**, **BeyondTrust**, or **Delinea** |

| Cloud-native / developer-friendly access | **Teleport**, **StrongDM/Delinea**, or **Akeyless** |

| Secrets + PAM combination | **KeeperPAM** or **Akeyless** + open-source tools |

| European / compliance-focused | **WALLIX** or **Senhasegura** |

| Affordable full-stack PAM | **ManageEngine PAM360** |



---



## Contributing



Contributions, corrections, and new open-source projects are welcome.  

Please open an issue or pull request.



---



**Last updated:** August 2026  

Emphasizing open-source tools while documenting the major commercial platforms for context. Teleport, Boundary, and JumpServer represent the strongest open-source foundations for modern privileged access management.
