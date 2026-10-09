# Hi, I'm Hoang

Software development student at [Hive Helsinki](https://www.hive.fi/) in Finland. I write Go, mostly with the standard library, and I'm looking for **DevOps and AI roles**.

I like the part of software that starts after the code compiles. Getting it built the same way every time, running in a container, and not falling over at 3am. I also like building systems where an AI model does a real job instead of sitting in a demo.

## What I'm looking for

- **DevOps, platform or infrastructure roles** where I can grow into owning pipelines and deployments
- **AI engineering roles**, especially agentic systems and anything that connects a model to real tooling
- A team that reviews code and explains the "why" behind decisions

## AI work

- **Winner AI for Good Hackathon ([Norrin Challenge](https://fiveguys-1.lovable.app)).** We built an agentic AI system that classifies systems under the EU AI Act.
- **Junction Quantum Hackathon, QMill challenge.** I worked on an obfuscated quantum circuit problem. Never heard of quantum before, but I can steer AI agent to find the solution. 

## Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

Day to day I work in the terminal with Zsh, VS Code and Claude Code. I've written custom Claude Code skills for manage subagent and multi-agent systems, and for automate development and deployment workflows.

## Learning next

The DevOps side is where I have the most to learn, and I'm building toward it on purpose.

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

- CI/CD with GitHub Actions for my projects, automating build, test and deployment.
- Kubernetes and Terraform, starting with deploying one of my own services
- Observability for Go services, meaning logs, metrics and traces
- LLM tooling in pipelines, such as automated review and incident summaries
- Manage infra, machine, network using Azure

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [HSK tracking](https://github.com/phuocvu911/marina-bay) | BLE asset tracking for a Helsinki sailing marina. Gateways report beacon signals over HTTP POST, and the backend picks the zone with the loudest gateway, using EMA smoothing and hysteresis so assets don't flicker between zones. | Go, Minew G1-E gateways, Minew i3 beacons |
| [Movies API](https://github.com/phuocvu911/movies-api) | REST API for a movies, actors and genres catalog with custom error types, request validation, rate limiting and graceful shutdown. | Go, SQLite (WAL, foreign keys), Postman |
| [Cars](https://github.com/phuocvu911/cars-viewer) | Server-rendered cars website with a filterable gallery, side-by-side comparison and recommendations. Data is fetched concurrently and held in an `RWMutex`-protected store. | Go , `html/template`, Makefile |
| [Literary Lions forum](https://github.com/phuocvu911/literary-lions) | Web forum with cookie sessions, password hashing, categories, likes and filtering, shipped as a Docker container. | Go, SQLite, Docker |
| [PathFinder](https://github.com/phuocvu911/stations) | Train routing on a graph. Vertex-disjoint paths, min-cost flow and time-expanded max-flow models. | Go |


## Elsewhere

Board member at Hexagon Ry, the student association at Hive Helsinki.

- LinkedIn: [Hoang Phuoc Vu](https://www.linkedin.com/in/hoang-phuoc-vu)
- Email: phuocvu091198@gmail.com

<!-- Optional: stats cards. Replace YOUR_USERNAME, then uncomment.
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact)
-->
