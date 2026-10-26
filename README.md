Full-stack software engineer in Paris. Six years of commercial work: my depth is React and TypeScript, I have owned backend services in production, and I run the infrastructure under what I build.

At Worldia, a white-label B2B travel platform, I was hired as a senior front-end engineer, led the front-end team, then moved full stack and took on backend services. Before that, at MAY, I owned the sync layer against more than a dozen external marketplace and supplier APIs, then architected an LLM and RAG platform from scratch and ran it with real customers on it.

The thing I learned along the way is that the dangerous failure is never the outage. It is the run that stops part way and leaves records quietly wrong until a number downstream looks strange. So I build pipelines that are safe to run twice, and interfaces that say when their data is stale.

Right now I am building [Propely](https://propely.fr), property intelligence for France: enter any address and get a structured, source-backed record of it, built from official open data. Python and PostGIS behind a FastAPI service, a Next.js web app and a Flutter mobile app. I build it agent-first with Claude Code, and I review, test and own every line that ships.

It runs on a server in my flat, next to my sites, CI runners and monitoring. Public web traffic arrives only through an outbound tunnel, and I am the only person on call. I write my own Prometheus exporters; one replaced the off-the-shelf exporter after it kept running but stopped collecting container metrics. Since then I alert on missing data, not only on bad data.

**Depth:** TypeScript · React · Next.js · Node · NestJS<br>
**In production:** Python · FastAPI · PostgreSQL and PostGIS · Docker · GitHub Actions · AWS · GCP<br>
**Also:** Go for workers · Terraform · LLMs, RAG and agents

AWS Solutions Architect Associate · HashiCorp Terraform Associate · NestJS Architecture (official course) · CS50

Open to full-stack roles in Paris. [eugenemk.com](https://eugenemk.com) · [LinkedIn](https://www.linkedin.com/in/evgeniymokrushin)
