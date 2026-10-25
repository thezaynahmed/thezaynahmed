<p align="center">
  <a href="https://zainahmed.net">
    <img src="./assets/banner.svg" alt="Zain Ahmed: Senior Software and Platform Engineer, Multi-Cloud Architecture, MLOps, and 5x Certified" width="100%" />
  </a>
</p>

# Zain Ahmed

**[zainahmed.net](https://zainahmed.net)** · **[Engineering Blog](https://zainahmed.net/blog)** · **[Certifications](https://zainahmed.net/certifications)** · **[LinkedIn](https://www.linkedin.com/in/thezainahmed)** · **[Microsoft Learn](https://learn.microsoft.com/en-us/users/thezainahmed/)** · **[hello@zainahmed.net](mailto:hello@zainahmed.net)**

I build Internal Developer Platforms (IDPs) and operate infrastructure across AWS, Google Cloud, Microsoft Azure, and Oracle Cloud Infrastructure. Most of my work comes down to two outcomes: giving engineering teams self-service paths to production and cutting cloud waste by 30 to 40 percent.

Over the past eight years, I wrote infrastructure the same way I write backend software. Every resource lives in Terraform and ships through automated GitOps pipelines. Kubernetes clusters and GPU inference endpoints share the same release gates. The production environments I run hold a 99.99 percent availability SLA using zero-trust identity and Pod Disruption Budgets.

Today I focus on agentic infrastructure and LLM serving workloads from Toronto, Canada.

## Open Source and Systems

| System | Focus | Stack |
| :--- | :--- | :--- |
| **[zainahmed.net](https://zainahmed.net)** | Personal platform with an OpenAPI 3.1 contract and live HTTP Model Context Protocol (MCP) server. | Next.js 16, TypeScript, MCP. |
| **[ghostty-config](https://github.com/thezaynahmed/ghostty-config)** | Terminal configuration with Monaspace texture healing and 18 calibrated themes across 16 editors. | Ghostty, Zsh, Tmux, Bash. |
| **[zainahmed-agent-skills](https://github.com/thezaynahmed/zainahmed-agent-skills)** | Reusable MCP plugin and workflows for multi-cloud SRE blueprints and FinOps analysis. | MCP, JSON Schema. |
| **[zainahmed-go](https://github.com/thezaynahmed/zainahmed-go)** | Typed Go client SDK generated from the `zainahmed.net` OpenAPI 3.1 specification. | Go, OpenAPI 3.1. |
| **[nutriguard-clinical-ops](https://github.com/thezaynahmed/nutriguard-clinical-ops)** | Clinical MLOps pipeline with real-time model drift detection and GKE orchestration manifests. | Python, GKE, Docker, GCP. |
| **[summitlms-azure-terraform](https://github.com/thezaynahmed/summitlms-azure-terraform)** | Zero-trust Azure infrastructure with VNet isolation and Key Vault managed identities. | Terraform, Azure, Docker. |

## Selected Writing

- **[Pod Disruption Budgets: The Floor Kubernetes Won't Let You Fall Below](https://zainahmed.net/blog/pod-disruption-budgets-the-floor-kubernetes-wont-let-you-fall-below)** · Node drains and eviction math during production cluster upgrades.
- **[SOC 2 Continuous Compliance Blueprint](https://zainahmed.net/blog/soc2-continuous-compliance-blueprint)** · Automated audit evidence and IAM least privilege across cloud accounts.
- **[Zero-Trust Identity Architecture on Azure](https://zainahmed.net/blog/zero-trust-identity-azure)** · Conditional Access policies and workload identity federation in Entra ID.
- **[Essential AI Coding Feedback Loops for TypeScript](https://zainahmed.net/blog/essential-ai-coding-feedback-loops-for-typescript)** · Static type gates and test harnesses for autonomous coding agents.

## Certifications

Five active credentials across four cloud providers. Select any link in the table to verify the credential with its issuing authority.

| Provider | Certification | Level | Credential ID | Active Window | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="./assets/providers/aws.svg" width="22" height="22" align="absmiddle" alt="AWS" /> **AWS** | **AWS Certified DevOps Engineer** | Professional | `9906ccb7-1339-4eb9-b714-2c6cbcd56954` | 2025 – 2028 | [Credly ↗](https://www.credly.com/badges/9906ccb7-1339-4eb9-b714-2c6cbcd56954). |
| <img src="./assets/providers/oci.svg" width="22" height="22" align="absmiddle" alt="Oracle" /> **Oracle** | **OCI 2025 Certified DevOps Professional** | Professional | `066828C64B2A78` | 2025 – 2027 | [Oracle CertView ↗](https://catalog-education.oracle.com/pls/certview/sharebadge?id=066828C64B2A78C45B111478C769FE1F6C8AF57B654ACA771B72E7912DE0A57E). |
| <img src="./assets/providers/aws.svg" width="22" height="22" align="absmiddle" alt="AWS" /> **AWS** | **AWS Certified Solutions Architect** | Associate | `e07463a6-2d96-4cf0-9938-8e1b9e98aba9` | 2025 – 2028 | [Credly ↗](https://www.credly.com/badges/e07463a6-2d96-4cf0-9938-8e1b9e98aba9/). |
| <img src="./assets/providers/azure.svg" width="22" height="22" align="absmiddle" alt="Azure" /> **Azure** | **Microsoft Certified: Azure Administrator (AZ-104)** | Associate | `2B4E57EA7BFDB97F` | 2026 – 2027 | [Microsoft Learn ↗](https://learn.microsoft.com/api/credentials/share/en-us/thezainahmed/2B4E57EA7BFDB97F?sharingId=605545774BA842AF). |
| <img src="./assets/providers/gcp.svg" width="22" height="22" align="absmiddle" alt="Google Cloud" /> **Google Cloud** | **Google Cloud Certified: Associate Cloud Engineer** | Associate | `6762cdc7b1ee4bea958e613927dc20af` | 2026 – 2029 | [Credly ↗](https://www.credly.com/badges/baeb2fdc-7115-456e-a5e2-b87204910419/public_url). |

## Quick Start: Query via Terminal or MCP

Connect an MCP client, install the Go SDK, or stream Markdown directly from `zainahmed.net`:

```bash
# Register the live HTTP MCP server
claude mcp add --transport http zainahmed https://zainahmed.net/mcp

# Install the typed Go SDK
go install github.com/thezaynahmed/zainahmed-go@latest

# Stream the architecture profile as plain Markdown
curl -sL -H "Accept: text/markdown" https://zainahmed.net/about
```
