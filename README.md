# Taeji Kim (KKamJi)

**SRE / DevSecOps Engineer** at Bungaejangter Inc., Seoul

Making services reliable and infrastructure repeatable.

[Blog](https://kkamji.net) · [LinkedIn](https://www.linkedin.com/in/taejikim/)

## Speaking

| Date | Event | Talk |
| --- | --- | --- |
| 2026.05 | [Open Source Summit North America 2026](https://osselcna2026.sched.com/event/2JQq9) | [Troubleshooting Like a Senior on Day 1: ReAct Agents With Real-Time Cluster Evidence](https://github.com/KKamJi98/KKamJi98/blob/main/slides/2026-05-oss-na-kuberca.pdf) ([video](https://www.youtube.com/watch?v=UzUPqU9FCaw)) |
| 2026.04 | [AWS KRUG 마곡](https://www.meetup.com/awskrug/events/314064008/) | [EKS Pod Identity로 더 간편하게 Kubernetes 서비스 권한 관리하기](https://github.com/KKamJi98/KKamJi98/blob/main/slides/2026-04-aws-krug-magok-eks-pod-identity.pdf) |
| 2026.01 | RAPA x AWS Cloud School | [AWS Cloud School 그리고 그 다음 이야기](https://github.com/KKamJi98/KKamJi98/blob/main/slides/2026-01-rapa-aws-cloud-school.pdf) |
| 2025.09 | [Cloud Native Korea Community Day 2025](https://community.cncf.io/events/details/cncf-cloud-native-seoul-presents-cloud-native-korea-community-day-2025/) | [ArgoCD와 함께하는 Multi-Cluster 운영](https://github.com/KKamJi98/KKamJi98/blob/main/slides/2025-09-kcd-argocd-multi-cluster.pdf) ([video](https://www.youtube.com/watch?v=niByoNg-waY)) |
| 2024.06 | 제2회 AWS 강의실 온라인 세미나 | [MicroK8s Cluster 구축하기](https://github.com/KKamJi98/KKamJi98/blob/main/slides/2024-06-aws-seminar-microk8s-cluster.pdf) ([video](https://www.youtube.com/watch?v=Vzre2DdzCTs)) |

## Open Source

- **[KubeRCA](https://github.com/kube-rca/kuberca)** - AI agents that root-cause Kubernetes alerts from live cluster evidence. Project lead, and the subject of the OSS Summit talk above
- **[ssh-connector](https://github.com/KKamJi98/ssh-connector)** - turns `~/.ssh/config` into an interactive host picker, so connecting stops being a hostname you have to remember
- **[aws-profile-pick](https://github.com/KKamJi98/aws-profile-pick)** - `awspick` switches the default AWS CLI profile from a grouped, filterable list, for shells that juggle several accounts
- **[wtree](https://github.com/KKamJi98/wtree)** - `wt` manages Git bare-repo worktrees in bulk, so a branch is a directory you cd into rather than a checkout you wait for. On PyPI
- **[prjump](https://github.com/KKamJi98/prjump)** - `prj` opens the GitHub or Bitbucket pull request for the current branch straight from the shell. On PyPI

## Security Research

- **[CVE-2026-87776](https://github.com/advisories/GHSA-vc2v-76pw-4v95)** / [GHSA-vc2v-76pw-4v95](https://github.com/expressjs/compression/security/advisories/GHSA-vc2v-76pw-4v95) - credited as **Finder** on the Express.js `compression` advisory. When a client hung up mid-response, the zlib stream was never destroyed, so repeatedly aborted requests leaked native memory until the process fell over. Found it from heap snapshots while chasing steadily climbing memory on a self-hosted n8n instance. High, CVSS 7.5; fixed in compression 1.8.2

## Contribute

- [oras-project/oras-www#610](https://github.com/oras-project/oras-www/pull/610) - fixed the docs, blog, and community "Edit this page" links so they open GitHub's edit flow instead of a read-only tree view
- [jaegertracing/jaeger-ui#4412](https://github.com/jaegertracing/jaeger-ui/pull/4412) - made the span-details divider draggable from the timeline header: moved the resizer into `TimelineHeaderRow` so one divider owns the boundary instead of two instances coordinated by CSS
- [grafana/loki#24300](https://github.com/grafana/loki/pull/24300) - clarified the default `fake` tenant directory for Ruler local storage in single-tenant mode and how it differs from `rule_path`
- [istio/istio#61512](https://github.com/istio/istio/pull/61512) - sped up `TestConvertResources` by parallelizing its 28 subtests (~50% faster), part of the slow-unit-tests effort (#37555)
- [aws-observability/helm-charts#190](https://github.com/aws-observability/helm-charts/pull/190) - added `dcgmExporter.enabled` and `neuronMonitor.enabled` so the chart stops creating resources nobody asked for
- [strands-agents/harness-sdk#1906](https://github.com/strands-agents/harness-sdk/pull/1906) - fixed 19 broken documentation links; listed under New Contributors in v1.35.0

## Currently at Bungaejangter Inc.

- Run 150+ microservices on EKS: Istio service mesh, Gateway API, Envoy Gateway
- Keyless across two clouds: removed static AWS access keys, introduced GCP Workload Identity Federation
- Global traffic analysis and bot traffic mitigation
- Built and operate an in-house SRE agent for incident response
- Operate self-hosted n8n on Kubernetes as the automation platform other teams build on
- Introduced Packer golden images and ClamAV server antivirus

## Stack

| | |
| --- | --- |
| **Cloud** | AWS - EC2, EKS, ECS, RDS, VPC, CloudFront, Lambda, WAF, Route 53 |
| **Kubernetes** | Istio, Helm, Karpenter, Cilium, Gateway API, Envoy Gateway, IRSA, Pod Identity |
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
