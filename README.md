# Nishitha Tanukunuri

GenAI and full stack engineer building hybrid edge-cloud AI inference systems. Lead AI Engineer at AI20 Labs, where I work on [ZeroGPU](https://zerogpu.ai): a platform that routes high-volume AI tasks (classification, summarization, extraction, PII redaction) to small language models running on edge devices and Cloudflare instead of frontier cloud LLMs.

**Portfolio:** [nishithatanukunuri.com](https://www.nishithatanukunuri.com) | **LinkedIn:** [in/nishithatanukunuri](https://www.linkedin.com/in/nishithatanukunuri)

## What I build

- **Edge/cloud LLM orchestration**: Cloudflare Workers + Durable Objects router deciding per request whether inference runs on a registered edge device or cloud fallback, with WebSocket device sessions and an OpenAI-compatible API surface.
- **Model serving**: ~20 TypeScript model-serving services on Fly.io (Llama 3.1, Phi-4, Qwen3, GLiNER, DistilBART) with autoscaling batch variants.
- **MCP servers**: shipped Model Context Protocol servers over business analytics and bank regulatory data, plus contributions to the [ZeroGPU MCP router](https://github.com/zerogpu/zerogpu-router).
- **Developer tooling**: [langchain-zerogpu](https://pypi.org/project/langchain-zerogpu/) ([source](https://github.com/zerogpu/langchain-zerogpu)), a Python package exposing ZeroGPU as 11 LangChain tools; cookbook tutorials on [docs.zerogpu.ai](https://docs.zerogpu.ai).
- **Full stack AI products**: Next.js dashboards with Stripe usage billing, Supabase auth, SSE-streaming LLM chat over MongoDB aggregation pipelines (980,000+ records).

## Stack

TypeScript, Python, Node.js, React/Next.js, Cloudflare (Workers, Durable Objects, Analytics Engine), AWS (Lambda, S3, ECS), Fly.io, LangChain, MCP, MongoDB, Supabase/Postgres, Redis, Stripe, GitHub Actions.

Most of my production work lives in private org repos ([zerogpu](https://github.com/zerogpu), ai20labs); public pieces are linked above, and case studies with architecture diagrams are on my portfolio.
