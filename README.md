<h1 align="center">Prateekshit Jaiswal</h1>

<p align="center">
  <b>AI / ML Engineer</b> &nbsp;·&nbsp; LLMs &amp; Deep Learning &nbsp;·&nbsp; Production ML Systems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prateekshit-jaiswal-18b024229"><img src="https://skillicons.dev/icons?i=linkedin" height="36" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://gitlab.com/prateekshitjaiswal73"><img src="https://skillicons.dev/icons?i=gitlab" height="36" alt="GitLab" /></a>
  &nbsp;
  <a href="mailto:prateekshitjaiswal73@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="36" alt="Email" /></a>
</p>

---

I build ML systems end to end, from the autograd engine up to production serving. I'm a Software Engineer at [Entropy Intelligence](https://theentropy.ai), where I own a 15+ service data-extraction platform and its ML inference stack. I was a **Google Summer of Code 2025** contributor with the Python Software Foundation.

**Currently**

- **At work:** I run the extraction platform end to end. Every service ships, scales and fails on its own, so one bad source can't take the rest down. The stack is PyTorch models behind FastAPI, pooled Playwright browsers, AWS ECS Fargate managed with Terraform, and OpenTelemetry tracing.
- **On the side:** I'm training [P.H.O.E.N.I.X.](https://gitlab.com/prateekshitjaiswal73/p.h.o.e.n.i.x), an 88M-parameter GPT built on my own autograd engine.
- **In open source:** I'm still contributing to [Open World Holidays](https://github.com/vacanza/holidays) after GSoC.
- **In research:** I reviewed AI/ML submissions for the IC-AIMLC 2026 programme committee.

## Featured projects

Most of my personal work lives on [GitLab](https://gitlab.com/prateekshitjaiswal73).

| Project | What it does | Stack |
| --- | --- | --- |
| [**P.H.O.E.N.I.X.**](https://gitlab.com/prateekshitjaiswal73/p.h.o.e.n.i.x) | An 88M-parameter GPT trained from scratch on `minigrad`, an autograd engine I wrote, with a custom BPE tokenizer. Post-training uses STaR self-improvement followed by DPO. It powers a local agent runtime with planning, persistent memory and voice. | Python, NumPy, CUDA / Metal |
| [**Smart LLM Router**](https://gitlab.com/prateekshitjaiswal73/extensions/-/tree/main/smart-llm-router) | A VS Code / Cursor extension that scores how complex each prompt is. Simple prompts go to local Ollama models and hard ones go to Claude. | TypeScript, Ollama |
| [**Minimal Search Engine**](https://gitlab.com/prateekshitjaiswal73/minimal-search-engine) | A crawler, inverted index, TF-IDF ranker and web UI, written with no third-party dependencies. | Python (stdlib only) |

## Open source

| Project | Contributions |
| --- | --- |
| [**vacanza/holidays**](https://github.com/vacanza/holidays)<br><sub>Holiday data library used by Home Assistant and Meta's Prophet</sub> | **Google Summer of Code 2025.** I added [17 countries](https://github.com/vacanza/holidays/pulls?q=is%3Apr+author%3APrateekshit73+is%3Amerged), 12 of them as my GSoC project. Each one covers fixed, floating and regional holiday rules, with tests and docs. I also wrote repo-wide spell-check tooling (cspell, pre-commit, CI), which is [in review](https://github.com/vacanza/holidays/pull/2898). |
| [**kornia/kornia**](https://github.com/kornia/kornia)<br><sub>Differentiable computer vision for PyTorch</sub> | I fixed error handling in augmentation and geometry ([#5455](https://github.com/kornia/kornia/pull/5455), [#4988](https://github.com/kornia/kornia/pull/4988)). A CLAHE half-precision fix is in review ([#6018](https://github.com/kornia/kornia/pull/6018)). |
| [**psf/black**](https://github.com/psf/black)<br><sub>The Python code formatter</sub> | I'm adding a preview style that splits binary operations before the operator ([#5517](https://github.com/psf/black/pull/5517), in review). |

## Tech

| | |
| --- | --- |
| **ML & data** | <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv" height="40" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV" /><br><sub>Transformers · pretraining · SFT · DPO · RAG · BERT NLU · Ollama · STT/TTS</sub> |
| **Backend & web** | <img src="https://skillicons.dev/icons?i=fastapi,ts,nodejs,nestjs,express,react,tailwind" height="40" alt="FastAPI, TypeScript, Node.js, NestJS, Express, React, Tailwind" /> |
| **Data stores** | <img src="https://skillicons.dev/icons?i=postgres,redis,mongodb" height="40" alt="PostgreSQL, Redis, MongoDB" /> |
| **Infra** | <img src="https://skillicons.dev/icons?i=aws,terraform,docker,githubactions,linux,bash" height="40" alt="AWS, Terraform, Docker, GitHub Actions, Linux, Bash" /> |
