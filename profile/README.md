<div align="center">

<img src="https://fhrouter.com/fhrouter-logo.png" width="120" alt="FHRouter" />

# FHRouter

### Free LLM API — frontier AI models, free for everyone

[![Website](https://img.shields.io/badge/fhrouter.com-free_LLM_API-10b981?style=flat-square)](https://fhrouter.com)
[![Free tier](https://img.shields.io/badge/free_tier-no_credit_card-10b981?style=flat-square)](https://fhrouter.com/free-llm-api)
[![OpenAI compatible](https://img.shields.io/badge/API-OpenAI_compatible-6366f1?style=flat-square)](https://fhrouter.com/docs/api-reference)

[Website](https://fhrouter.com) · [Free LLM API](https://fhrouter.com/free-llm-api) · [Pricing](https://fhrouter.com/pricing) · [Docs](https://fhrouter.com/docs) · [Blog](https://fhrouter.com/blog)

</div>

---

## Free LLM API

FHRouter is a **free LLM API and AI gateway** at [fhrouter.com](https://fhrouter.com). Frontier AI models — **Grok, DeepSeek, and GLM families** — are **free on every account**: no credit card, no expiring trial, one [OpenAI-compatible](https://fhrouter.com/docs/api-reference) key.

Free models right now (the [live catalog](https://fhrouter.com/free-llm-api) always shows the current set):

- [Free Grok API — grok-4.6](https://fhrouter.com/pricing/grok-4.6)
- [Free DeepSeek API — deepseek-v4-flash](https://fhrouter.com/pricing/deepseek-v4-flash)
- [Free GLM API — glm-5.3-flash](https://fhrouter.com/pricing/glm-5.3-flash)

## Get started in minutes

```bash
curl https://fhrouter.com/v1/chat/completions \
  -H "Authorization: Bearer $FHROUTER_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"grok-4.6","messages":[{"role":"user","content":"Hello"}]}'
```

Setup guides for the tools you already use:

- [Claude Code setup](https://fhrouter.com/docs/guides/claude-code)
- [Codex CLI setup](https://fhrouter.com/docs/guides/codex)
- [Gemini CLI setup](https://fhrouter.com/docs/guides/gemini)
- [curl examples](https://fhrouter.com/examples-curl) · [Python OpenAI SDK examples](https://fhrouter.com/examples-openai-python) — see the pinned repos below

## Why FHRouter

- **Frontier models free** — not just small open-weight variants. The free set rotates; the [live catalog](https://fhrouter.com/free-llm-api) is authoritative.
- **One key for the whole gateway** — any OpenAI SDK, plus native endpoints for Claude Code, Codex, and Gemini CLI.
- **Fair-use, not expiring trials** — free requests never touch your credit balance.
- **Honest pricing** — every other model at up to 50% below list prices.
- Read the comparison: [Free LLM API providers in 2026: what's actually free](https://fhrouter.com/blog/free-llm-api-providers-2026).

## Repositories

- [`fhrouter`](https://github.com/fhrouter/fhrouter) — the gateway, explained
- [`examples-openai-python`](https://github.com/fhrouter/examples-openai-python) — Python OpenAI SDK examples
- [`examples-claude-code`](https://github.com/fhrouter/examples-claude-code) — free Claude Code setup
- [`examples-codex`](https://github.com/fhrouter/examples-codex) — free Codex CLI setup
- [`examples-gemini-cli`](https://github.com/fhrouter/examples-gemini-cli) — free Gemini CLI setup
- [`examples-curl`](https://github.com/fhrouter/examples-curl) — curl cookbook
- [`demo-free-models`](https://github.com/fhrouter/demo-free-models) — runnable free-tier demo

## Links

- Website: [fhrouter.com](https://fhrouter.com)
- Free tier: [fhrouter.com/free-llm-api](https://fhrouter.com/free-llm-api)
- Docs: [fhrouter.com/docs](https://fhrouter.com/docs)
- Pricing: [fhrouter.com/pricing](https://fhrouter.com/pricing)
- Status: [fhrouter.com/status](https://fhrouter.com/status)

---

<div align="center">
<sub>Frontier AI models, free for everyone. One endpoint, routed for price and speed.</sub>
</div>
