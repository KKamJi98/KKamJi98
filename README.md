# Taeji Kim (KKamJi)

**SRE / DevSecOps Engineer** at Bungaejangter Inc., Seoul

Making services reliable and infrastructure repeatable.

[Blog](https://kkamji.net) · [LinkedIn](https://www.linkedin.com/in/taejikim/)

## Speaking

| Date | Event | Talk |
| --- | --- | --- |
| 2026.05 | Open Source Summit North America 2026 | Troubleshooting Like a Senior on Day 1: ReAct Agents With Real-Time Cluster Evidence |
| 2026.04 | AWS KRUG 마곡 | EKS Pod Identity로 더 간편하게 Kubernetes 서비스 권한 관리하기 |
| 2026.01 | RAPA x AWS Cloud School | AWS Cloud School 그리고 그 다음 이야기 |
| 2025.09 | Cloud Native Korea Community Day 2025 | ArgoCD와 함께하는 Multi-Cluster 운영 |
| 2024.06 | 제2회 AWS 강의실 온라인 세미나 | MicroK8s Cluster 구축하기 |

## Open Source

- **[KubeRCA](https://github.com/kube-rca/kuberca)** - AI agents that root-cause Kubernetes alerts from live cluster evidence. Project lead, and the subject of the OSS Summit talk above
- **[ssh-connector](https://github.com/KKamJi98/ssh-connector)** - turns `~/.ssh/config` into an interactive host picker, so connecting stops being a hostname you have to remember
- **[aws-pick](https://github.com/KKamJi98/aws-pick)** - switches the default AWS CLI profile from a list, for shells that juggle several accounts
- **[wt](https://github.com/KKamJi98/kkamji-lab/tree/main/tools/git-worktree-tool)** - manages Git bare-repo worktrees in bulk, so a branch is a directory you cd into rather than a checkout you wait for
- **[prj](https://github.com/KKamJi98/kkamji-lab/tree/main/tools/pull-request-jump)** - opens the GitHub or Bitbucket pull request for the current branch straight from the shell

## Contribute

- [aws-observability/helm-charts#190](https://github.com/aws-observability/helm-charts/pull/190) - added `dcgmExporter.enabled` and `neuronMonitor.enabled` so the chart stops creating resources nobody asked for
- [strands-agents/sdk-python#1906](https://github.com/strands-agents/sdk-python/pull/1906) - fixed 19 broken documentation links; listed under New Contributors in v1.35.0

## Currently at Bungaejangter Inc.

- ~190 microservices running on EKS, including cluster upgrades to 1.32+
- Keyless across two clouds: removed static AWS access keys, introduced GCP Workload Identity Federation
- Global traffic analysis and bot traffic mitigation
- Built and operate an in-house SRE agent for incident response
- n8n in production for workflow automation
- Introduced Packer golden images and ClamAV server antivirus

## Stack

| | |
| --- | --- |
| **Cloud** | AWS - EC2, EKS, ECS, RDS, VPC, CloudFront, Lambda, WAF, Route 53 |
| **Kubernetes** | Helm, Karpenter, Cilium, Gateway API, Envoy, IRSA, Pod Identity |
| **IaC / CI-CD** | Terraform, Packer, Jenkins, GitHub Actions, Argo CD |
| **Observability** | Prometheus, Grafana, Thanos, Datadog, ELK |
| **Security** | IAM, Keycloak SSO, RBAC, External Secrets, ClamAV |
| **Languages** | Go, Python, Java |

## Certifications

AWS DevOps Engineer Professional · AWS Solutions Architect Associate · CKA · HashiCorp Terraform Associate

## Awards

- Fastfive x AWS Frugality Fest GameDay - Winner (2025.04)
- Students @ AI Seoul Hackathon - Winner (2025.04)
- AWS PS GameDay (GenAI) - 5th Place (2024.08)
- AWS x RAPA DevOps Jam - Runner-up (2023.12)
