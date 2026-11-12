# Rodrigo Barros

**Engenheiro de software, backend e IA.** Construo, automatizo e protejo software que roda em produção: backend e integrações, IA aplicada e segurança de aplicações.

Hoje sou responsável técnico, e único engenheiro, da **Lexfy (4Juris)**, uma plataforma com IA usada por 112 escritórios de advocacia, em que agentes conduzem cerca de 39 mil conversas por mês no WhatsApp. Tenho mais de 5 anos de experiência em saúde, crédito, antifraude, jurídico e varejo.

<p>
  <a href="https://rodrigobarros.tech"><img src="https://img.shields.io/badge/rodrigobarros.tech-1d6fd1?style=flat-square&logo=googlechrome&logoColor=white" alt="Site" /></a>
  <a href="https://rodrigobarros.tech/Rodrigo_Barros_CV.pdf"><img src="https://img.shields.io/badge/Curr%C3%ADculo%20em%20PDF-1d6fd1?style=flat-square&logo=readdotcv&logoColor=white" alt="Currículo em PDF" /></a>
  <a href="mailto:rodrigo@rodrigobarros.tech"><img src="https://img.shields.io/badge/rodrigo@rodrigobarros.tech-1d6fd1?style=flat-square&logo=maildotru&logoColor=white" alt="E-mail" /></a>
  <a href="https://wa.me/5589981200084"><img src="https://img.shields.io/badge/WhatsApp-(89)%2098120--0084-1d6fd1?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <a href="https://www.linkedin.com/in/rodrigobarros3"><img src="https://img.shields.io/badge/LinkedIn-1d6fd1?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

## No que eu trabalho

- **Backend e integrações:** APIs em Node.js, TypeScript e NestJS, filas com retentativas e idempotência, fallback entre provedores e circuit breaker, desempenho e estabilidade em produção.
- **IA aplicada:** agentes de atendimento com RAG e MCP, guardrails, avaliação automática de conversas e custo medido por chamada de modelo.
- **Segurança de aplicações:** proteção contra SSRF, rate limiting em APIs públicas e webhooks, e gitleaks, Semgrep e Dependabot no CI.
- **Observabilidade:** OpenTelemetry com tracing distribuído, métricas e logs centralizados, sem dados pessoais nos spans.

## Resultados em produção

| | |
|---|---|
| **39 mil conversas/mês** | conduzidas por agentes de IA no WhatsApp, do primeiro contato ao contrato assinado |
| **600 → 155 ms** | de p50 numa API, depois de diagnosticar e ajustar o banco de dados |
| **−31% de custo de IA** | medindo o custo de cada chamada de modelo |
| **15+ integrações** | WhatsApp Business, Stripe, Meta, PJe, Google Calendar, ZapSign, Clicksign, Docusign |
| **0 cobranças duplicadas** | depois de levar 11 tipos de consulta para jobs em background com idempotência |
| **770+ commits e 180 PRs** | em micro-frontends do Hospital Israelita Albert Einstein |

## Projetos

- **[appsec-aws-lab](https://github.com/rodrigobarros2/appsec-aws-lab):** laboratório público de AppSec e DevSecOps num SaaS serverless na AWS (Lambda, SQS, DynamoDB, KMS, Secrets Manager e WAF, em Terraform), com versão vulnerável e versão corrigida. A esteira (gitleaks, Semgrep, osv-scanner, Checkov, Trivy, Hadolint e OWASP ZAP) roda nas duas e prova que pega cada falha.
- **[CardápioSimples](https://cardapiosimples.com):** SaaS de cardápio digital e delivery que eu construí e opero sozinho. Tem vários lojistas com isolamento por RLS, pagamentos via webhook, agentes de IA e impressão automática na cozinha.
- **Lexfy (4Juris):** atendimento com IA para escritórios de advocacia, com RAG, MCP, cobrança por créditos com Stripe e assinatura eletrônica com cinco provedores.
- **Autoinsp:** plataforma de consultas e análise veicular para seguradoras. Trabalhei nas integrações com bureaus de dados, nas consultas em background com fallback entre provedores, nos relatórios em PDF e no fluxo de aprovação.
- **Hospital Israelita Albert Einstein:** micro-frontends do catálogo de serviços do Portal Empresas, com unidades, especialistas, produtos, regras e mailing.

Mais detalhes no meu site: **[rodrigobarros.tech](https://rodrigobarros.tech)**.

## Tecnologias

TypeScript · Node.js · NestJS · React · Next.js · React Native · PostgreSQL · MongoDB · Redis · Supabase · Prisma · BullMQ · Python · LLMs, RAG e MCP · WhatsApp Business API · Stripe · Docker · AWS (SQS, Lambda, ECS, S3) · Terraform · GitHub Actions · Vercel · Jest, Vitest e Cypress · OpenTelemetry · Grafana · Sentry · Datadog · Semgrep · OWASP
