# AI Engineering Academy

A hands-on, engineering-first curriculum for becoming an AI Engineer.

This organization is a collection of independent repositories. Each repository
represents a learning stage and must produce working software, reproducible
experiments, automated tests, and documented engineering decisions.

## Learning principles

1. Learn the concept before adopting an abstraction.
2. Implement a minimal version before using a framework.
3. Measure behavior, quality, latency, and cost.
4. Test deterministic code with conventional tests and model behavior with evaluations.
5. Document trade-offs and limitations.
6. Ship small, reviewable increments.

## Curriculum

| Repository | Focus | Status |
|---|---|---|
| [01-foundations](https://github.com/vitorbitner-ai-engineering/01-foundations) | AI, ML, deep learning, LLM concepts and experiments | In progress |
| [02-python-for-ai](https://github.com/vitorbitner-ai-engineering/02-python-for-ai) | Python, typing, APIs, async, data handling and tests | In progress |
| 03-llm-engineering | LLM APIs, inference, streaming, cost and latency | Planned |
| 04-prompt-context-engineering | Prompt design, structured outputs and context management | Planned |
| 05-model-lab | Model selection, local inference and benchmarking | Planned |
| 06-embeddings-vector-databases | Embeddings and vector retrieval | Planned |
| 07-rag-engineering | Production-oriented RAG pipelines | Planned |
| 08-ai-agents | Tool calling, agent loops, MCP and workflows | Planned |
| 09-ai-evaluation-observability | Evaluation, tracing, monitoring and regression tests | Planned |
| 10-ai-security-safety | Threat modeling, prompt injection and data protection | Planned |
| 11-multimodal-ai | Vision, audio and multimodal applications | Planned |
| 12-ai-deployment-mlops | Containers, CI/CD, cloud deployment and operations | Planned |
| 13-ai-capstone | Integrated enterprise AI platform | Planned |

## Definition of done

A learning unit is complete only when it includes:

- A concise technical explanation and references.
- A working implementation.
- A reproducible experiment and recorded observations.
- Automated tests.
- An independent engineering challenge.
- A short decision or retrospective note.
- A commit with a meaningful message.

## Learning levels

- **Foundation:** explain and reproduce.
- **Practitioner:** implement and test independently.
- **Professional:** design, justify trade-offs, secure, deploy, and operate.

## Suggested weekly workflow

1. Read the unit's theory.
2. Run the starter experiment.
3. Implement the guided task.
4. Write tests and run the quality checks.
5. Complete the independent challenge.
6. Record results in `experiments/`.
7. Open an issue or pull request for review.

## Technology direction

Python is the primary language for AI work. The curriculum also uses
ASP.NET Core where it helps demonstrate integration with existing enterprise
systems. Core concepts are implemented before adopting higher-level frameworks.

Initial stack: Python 3.12+, `uv` or `venv`, pytest, FastAPI, Pydantic,
NumPy, Pandas, Docker, GitHub Actions, PostgreSQL/pgvector, Qdrant,
Ollama, Hugging Face, and selected LLM provider APIs.

## Source roadmap

This curriculum is inspired by the
[AI Engineer Roadmap](https://roadmap.sh/ai-engineer) and extends it with
software engineering, evaluation, security, observability, and production
operations.

## Repository conventions

See [CONTRIBUTING.md](CONTRIBUTING.md), [docs/learning-unit-standard.md](docs/learning-unit-standard.md),
and the issue / pull request templates.

## License

Unless a repository states otherwise, educational source code is released
under the MIT License. External datasets and model assets retain their own licenses.
