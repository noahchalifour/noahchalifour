# Noah Chalifour

Senior Software Engineer at [Regie AI](https://www.regie.ai), previously at AWS (RDS). I build AI agents and the infrastructure they run on. Based in Vancouver, BC.

- **At Regie AI:** core engineer on Regie Go, an AI sales agent built from scratch: onboarding state machine, BullMQ and SSE pipelines, citation-validated email drafting, voice onboarding.
- **At AWS:** distributed systems for Amazon RDS, including the Global Writer Endpoint and a cleanup that freed 10 PB of storage, plus internal LLM tools on Bedrock.
- **On the side:** agent tooling, a Kubernetes home lab, and products at [chalifour.dev](https://chalifour.dev).

## Agent infrastructure

| Project | What it does |
|---|---|
| [berth](https://github.com/noahchalifour/berth) | A lease-based pool of self-hosted Android emulators. Coding agents check out a phone, tablet or TV over MCP, humans watch and take over live. Python, Kubernetes, Prometheus. |
| [dsh-anthropic-request-size-guard](https://github.com/noahchalifour/dsh-anthropic-request-size-guard) | Keeps long, screenshot-heavy agent sessions under the Claude API's 32 MB request limit (a stuck 38 MB request became 6.1 MB) without breaking the prompt cache. |
| [dsh-anthropic-image-clamp](https://github.com/noahchalifour/dsh-anthropic-image-clamp) | Downscales images so many-image Claude requests never hit the 2000px limit. Deterministic, cached by content hash. |
| [homeassistant-for-openclaw](https://github.com/noahchalifour/homeassistant-for-openclaw) | Gives an AI agent live smart-home context and device control through Home Assistant, with a three-tier read, watch and write access model. |

## Machine learning

| Project | What it does |
|---|---|
| [rnnt-speech-recognition](https://github.com/noahchalifour/rnnt-speech-recognition) | End-to-end streaming speech recognition with RNN Transducers in TensorFlow 2, after Google's on-device RNN-T paper. 250+ stars. |
| [memn2n](https://github.com/noahchalifour/memn2n) | End-to-end goal-oriented dialog with memory networks. |

Published research: *Question Answering Artificial Intelligence Chatbot on Military Dress Policy* (Department of National Defence), fine-tuning BERT-based models for domain-specific QA.

## Stack

Python, TypeScript, Java, Go · React, Node.js, Flutter · AWS (Lambda, Bedrock, RDS), Kubernetes, Terraform, Argo CD · LLM APIs, MCP, RAG

## Links

[noahchalifour.com](https://noahchalifour.com) · [chalifour.dev](https://chalifour.dev) · [LinkedIn](https://linkedin.com/in/noahchalifour) · [Resume](https://noahchalifour.com/resume.pdf)
