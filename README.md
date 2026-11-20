# Hi there, I'm Bruno Cruz 👋

I'm a senior full-stack product engineer with 6+ years of experience, working mostly in remote, lean US-based startups. I build with TypeScript (frontend and backend), Ruby on Rails and Elixir/Phoenix.

I like owning a product end to end: talking to customers, designing the data model, shipping, and running it in production. I work design-doc first and use AI coding agents (Claude Code, Cursor) for most of the implementation, then review and test every change myself.

## Projects

- [Uptime Monitor](https://github.com/brucruz/uptime-monitor) (TypeScript): HTTP and Playwright login checks, results stored in ClickHouse, traced with OpenTelemetry.
- [Legal Case RAG](https://github.com/brucruz/legal-case-rag) (TypeScript, NestJS): semantic search over EU court cases with pgvector and OpenAI embeddings.
- [GlobalDial](https://globaldial.com) (Ruby on Rails 8): international calling service on Twilio. Stripe checkout and webhooks credit purchases in real time, and Stripe early fraud warnings trigger automatic refunds before they become chargebacks. Uses Hotwire and the Solid Trifecta on SQLite, deployed with Kamal 2 to a Hetzner VPS.
- **MentionWave** (Elixir, Phoenix LiveView): AI-powered social listening tool. LLMs filter noise out of keyword mentions, a LiveView dashboard shows them in real time, and a GenServer pipeline under an OTP supervision tree processes 500 mentions per minute with automatic failure recovery.
- [Sentinel](https://github.com/brucruz/sentinel) (Elixir/OTP): VPS and Docker monitor that runs as a single release under systemd. Behaviour-based collectors poll CPU, memory, disk and containers, an evaluator raises threshold alerts with per-alert cooldowns, and a Telegram bot answers status and 24h peak queries.

## Notable work

- **Ribbon**: first engineering hire on an inheritance platform for financial institutions. Owned the architecture, hired and onboarded 8 engineers, and built an AI document verification flow that cut inheritor feedback time from days to under 3 minutes.
- **Canary Technologies**: led a hotel kiosk hardware product that reached $1M USD in CARR in under 2 months after launch.

## Stack

TypeScript, React, NestJS, Ruby on Rails, Elixir, Phoenix, PostgreSQL, AWS, Docker.

## Contact

[LinkedIn](https://linkedin.com/in/brunogcruz) · [Email](mailto:bru.cruz@gmail.com)
