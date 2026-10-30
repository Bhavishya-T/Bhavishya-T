# Bhavishya Tarun

Software engineer focused on agent systems, inference infrastructure, and the backend work that makes them reliable.

At Cognida.ai, I worked on production LLM adaptation and Ray-based inference for legal and financial workflows. Before that, I built Java and Spring services for banking products at Nuclei. That code is private, so the public work below is where you can inspect my engineering decisions.

## Selected work

### [Kubernetes microservice diagnosis](https://github.com/chrono-rca-lab/microservice-blackbox-rca)

A team research project on finding the source of failures when symptoms spread across services. The system collects Prometheus metrics from Google Online Boutique, injects faults with Chaos Mesh, and uses change points and service dependencies to reason about propagation. My contributions included metric smoothing, pipeline timing, experiment logging, and persisted diagnostic output. The team evaluated 33 fault-injection experiments.

### [Visual support agent](https://github.com/Benonii/facetime-support-agent/pull/10)

My contribution to a team voice and video agent was the caller-facing guidance layer. It renders the camera frame, observations, and next step into a live guide card. Annotations only appear when they match the current frame; stale or invalid targets stay hidden. The screen also reports its visible state back to the agent so spoken guidance can agree with what the caller sees. The linked PR includes the implementation and tests.

### [Coherence](https://github.com/Bhavishya-T/coherence)

A personal prototype for finding the through line across technical work without losing the evidence behind it. It tracks source-backed claims, lets a person choose a direction, and keeps the portfolio, introduction, and visual reel consistent with that choice. The public browser demo runs locally without model calls; the README explains what is implemented and what remains a prototype.

## More experiments

- [Spatial shopping](https://github.com/jerelvelarde/fast-forward-spatial-shop/pulls?q=is%3Apr+author%3ABhavishya-T) — Team hackathon work on live Shopify search, voice and Quest controls, 3D preview generation, protected model polling, and an instant saved-model demo. The link shows my PRs.
- [BankGPT](https://github.com/Bhavishya-T/bankgpt-knowledge-system) — A smaller experiment in date-aware, evidence-grounded answers. The README covers the benchmark results, weak cases, and the retrieval tradeoffs.

Current interests: agent execution, tool and context design, inference efficiency, and making system failures easier to understand.

[LinkedIn](https://www.linkedin.com/in/bhavishyat/)
