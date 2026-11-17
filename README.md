<!-- Profile README for github.com/aammasa — model-card layout -->

<h1 align="center">Arun Ammasai</h1>

<p align="center">
  <a href="https://github.com/aammasa">
    <img src="https://readme-typing-svg.demolab.com/?lines=AI+Architect+%40+Trimble+Construction;Building+reliable+systems+for+unreliable+models;16%2B+years+of+enterprise+engineering;Java+%E2%80%A2+Spring+%E2%80%A2+Python+%E2%80%A2+Azure+%E2%80%A2+MCP&font=Fira+Code&center=true&width=600&height=45&color=0F62FE&vCenter=true&pause=1200&size=20" alt="Headline" />
  </a>
</p>

<p align="center">
  <a href="https://builtbyarun.dev/"><img src="https://img.shields.io/badge/builtbyarun.dev-0F62FE?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/grazyarun"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/ArunAmmasai"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.udemy.com/user/arun-1056"><img src="https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=udemy&logoColor=white" alt="Udemy" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-16.0-0F62FE?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/model_type-AI_Architect-005F9E?style=flat-square" alt="Model type" />
  <img src="https://img.shields.io/badge/status-production-2EA043?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/location-Chennai,_India-grey?style=flat-square" alt="Location" />
</p>

---

```yaml
# model card
name:           "Arun Ammasai"
model_type:     AI Architect
organisation:   Trimble Construction
base_model:     backend-engineer-java-spring        # 16+ years, banking · telecom · construction software
fine_tuned_on:  [agents, mcp, retrieval, evaluation, pii-redaction, multi-tenant-apis]
languages:      [java, python, kotlin, typescript]
runtimes:       [azure, google-cloud, aws]
guardrails:     [no-eval-no-ship, tenant-isolation-always, pii-never-leaves-the-boundary]
license:        open-to-collaboration
```

## Intended use

Designing AI systems that behave in production: retrieval pipelines that return the right document to the right tenant, agents that fail safely, MCP tool servers with real auth and rate limits, evaluation gates that stop a bad release before customers see it, and the multi-tenant backend plumbing (observability, billing, migrations) that enterprise software actually runs on.

Not intended for: demos that only work on the happy path.

## Capabilities

| Capability | Evidence | Maturity |
| --- | --- | --- |
| **Agents & MCP** | MCP servers over Streamable HTTP with key-based auth, rate limiting and structured tracing; ERP and line-of-business APIs exposed as agent tools; support and help-assistant agents that stay inside their guardrails | ![production](https://img.shields.io/badge/-production-2EA043?style=flat-square) |
| **Retrieval (RAG)** | Tenant-isolated RAG on Azure AI Search + Cosmos DB + Azure OpenAI, and on Vertex AI; index construction pipelines; per-user access enforced at query time | ![production](https://img.shields.io/badge/-production-2EA043?style=flat-square) |
| **Document, speech & PII** | OCR and extraction with Azure Document AI; batch transcription with Azure Speech and WhisperX; multilingual PII detection and redaction with Presidio + spaCy; offline-first variants for regulated environments | ![production](https://img.shields.io/badge/-production-2EA043?style=flat-square) |
| **Enterprise backend** | Multi-tenant REST services in Spring Boot, Dropwizard and FastAPI; Stripe billing with webhook monitoring; Firebase push and auth; AWS-to-Azure migration | ![production](https://img.shields.io/badge/-production-2EA043?style=flat-square) |
| **Evaluation & reliability** | Promotion gates enforced in code, async job patterns with polling, replayable decision functions so a configuration is validated before it touches anything real | ![growing](https://img.shields.io/badge/-growing-BF8700?style=flat-square) |

## Architecture

<table align="center">
  <tr>
    <td align="center" valign="top" width="33%">
      <h4>Languages</h4>
      <img src="https://skillicons.dev/icons?i=java,python,kotlin,ts,js,bash&perline=6" alt="Java, Python, Kotlin, TypeScript, JavaScript, Bash" /><br/>
      <sub>Java · Python · Kotlin · TypeScript · JavaScript · Bash</sub>
    </td>
    <td align="center" valign="top" width="33%">
      <h4>Backend & frameworks</h4>
      <img src="https://skillicons.dev/icons?i=spring,fastapi,flask,nodejs,react,nextjs,tailwind,flutter&perline=4" alt="Spring, FastAPI, Flask, Node.js, React, Next.js, Tailwind, Flutter" /><br/>
      <sub>Spring Boot · Dropwizard · FastAPI · Flask · Node.js · React · Next.js · Tailwind · Flutter</sub>
    </td>
    <td align="center" valign="top" width="33%">
      <h4>AI & agents</h4>
      <img src="https://img.shields.io/badge/MCP-111111?style=for-the-badge" alt="MCP" />
      <img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=for-the-badge" alt="Azure OpenAI" /><br/>
      <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Vertex AI" />
      <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy" /><br/>
      <sub>Model Context Protocol · Azure OpenAI · Azure AI Search · Vertex AI · Copilot Studio · Presidio · spaCy · WhisperX</sub>
    </td>
  </tr>
  <tr>
    <td align="center" valign="top">
      <h4>Cloud & platform</h4>
      <img src="https://skillicons.dev/icons?i=azure,gcp,aws,firebase,docker,kubernetes&perline=6" alt="Azure, GCP, AWS, Firebase, Docker, Kubernetes" /><br/>
      <sub>Azure · Google Cloud · AWS · Firebase · Docker · Kubernetes</sub>
    </td>
    <td align="center" valign="top">
      <h4>Data & integration</h4>
      <img src="https://skillicons.dev/icons?i=mysql,postgres,sqlite&perline=3" alt="MySQL, PostgreSQL, SQLite" /><br/>
      <sub>MySQL · PostgreSQL · SQLite · Cosmos DB · Oracle SOA / OSB · Stripe · REST / SOAP</sub>
    </td>
    <td align="center" valign="top">
      <h4>Delivery & tooling</h4>
      <img src="https://skillicons.dev/icons?i=git,github,githubactions,postman,vscode&perline=5" alt="Git, GitHub, GitHub Actions, Postman, VS Code" /><br/>
      <sub>Git · GitHub Actions · Azure DevOps · Postman · VS Code</sub>
    </td>
  </tr>
</table>

## Training data

| Period | Source | Role | What it taught |
| --- | --- | --- | --- |
| 2023 – present | Trimble Inc | AI Architect | AI agents and retrieval services for construction software; MCP integrations; AWS-to-Azure migration; Stripe billing and webhook monitoring; Firebase push; Microsoft Copilot agents for products |
| 2018 – 2022 | Bank of America | Software Engineer II-A | REST services at bank scale; GitHub and Autosys migrations; vulnerability remediation; decommissioning programmes; training lead for Java 8, 9 and 11 |
| 2012 – 2018 | Verizon Data Services India | Senior Software Analyst | SOA integration with BPEL and Mediator; fault-policy based error handling; Oracle OSB 11g proxy services; EJB backends |
| 2011 – 2012 | IAP Company Ltd | Senior Java Developer | Centralised pensioner data platform; Jasper reporting on Oracle |
| 2010 – 2011 | Ascent Technosoft | Technical Consultant | J2EE web applications; Oracle stored procedures |

**Pre-training** · Master of Computer Applications, Bharathiar University (2007 – 2010) · B.Sc. Chemistry, Bharathiar University (2004 – 2007)

## Evaluation

Public code lives on my long-standing account, **[@arun-ammasai](https://github.com/arun-ammasai)**, which grew out of the Java training material I wrote for colleagues and students.

| Benchmark | About | Score |
| --- | --- | --- |
| [java8-functional-programming](https://github.com/arun-ammasai/java8-functional-programming) | Lambdas, streams and functional patterns in Java 8, with worked examples | ★ 6 · 29 forks |
| [employee-rest-service](https://github.com/arun-ammasai/employee-rest-service) | Reference Spring Boot REST service | ★ 4 · 11 forks |
| [soap_web_service_employee_management](https://github.com/arun-ammasai/soap_web_service_employee_management) | SOAP web services on Spring Boot | ★ 3 · 7 forks |
| [studentservice_H2_JPA](https://github.com/arun-ammasai/studentservice_H2_JPA) | Spring Data JPA with H2, end to end | 6 forks |
| [SpringCloudWithNetflix](https://github.com/arun-ammasai/SpringCloudWithNetflix) | Spring Boot and Flask services registered with Eureka | ★ 1 |
| [design-pattern-repo](https://github.com/arun-ammasai/design-pattern-repo) · [java-collections](https://github.com/arun-ammasai/java-collections) · [spring-concepts](https://github.com/arun-ammasai/spring-concepts) | Study repositories for design patterns, the Collections framework and core Spring | |

Courses and tutorials: [Udemy](https://www.udemy.com/user/arun-1056) · [TutorialsPoint](https://market.tutorialspoint.com/profile/arun_ammasai)

## Limitations

Does not ship an agent without an evaluation. Does not hallucinate uptime. Occasionally unavailable while photographing a landscape or on a trek.

---

<p align="center">
  <sub>Day-to-day work is in private Trimble repositories; this card covers what I can share publicly. Last updated October 2026.</sub><br/>
  <img src="https://komarev.com/ghpvc/?username=aammasa&label=Inference+requests&color=0F62FE&style=flat-square" alt="Profile views" />
</p>
