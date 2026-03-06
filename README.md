# Dev Speak 🚀

> Turn what you actually built into a post people actually read.

Developers ship great things and say nothing about it. This tool fixes that.

Paste what you did in plain technical language. Pick your tone. Get a ready-to-post X thread and LinkedIn post in seconds — powered by AI.

---

## Why I Built This

I'm a PMM surrounded by developers who ship incredible work every day and never talk about it publicly. I got tired of chasing people to post so I built them a tool that does the hard part for them.

The output doesn't sound like marketing. It sounds like a developer who actually built something.

---

## What It Does

- Paste your technical update in plain language
- Choose your tone: Casual, Professional, or Humble Brag
- Get two outputs instantly:
  - **X post** — under 280 characters, hook-first, algorithm-friendly
  - **LinkedIn post** — 3–5 sentences, insight-driven, human

Every output is unique. No templates. Powered by Claude (Anthropic) or GPT-4o-mini (OpenAI) — your choice.

---

## How to Use

1. Open `index.html` in your browser — no install, no setup
2. Paste your Anthropic or OpenAI API key
3. Select your AI provider
4. Type what you built
5. Pick your tone
6. Click Generate
7. Copy and post

That's it.

---

## Example

**Input:**
```
fixed a race condition in the auth middleware that was causing random session drops under high load
```

**X output:**
```
Just squashed a nasty race condition in auth that was randomly killing sessions under load.
The kind of bug that only shows up in production at 2am. Gone. 🔥
```

**LinkedIn output:**
```
Resolved a critical race condition in our authentication middleware affecting session stability
under high concurrency. The root cause was subtle — two async processes competing for the same
state. Small fix, significant impact on reliability.
```

---

## Stack

- Vanilla HTML, CSS, JavaScript — single file, zero dependencies
- Anthropic API (claude-haiku-4-5) or OpenAI API (gpt-4o-mini)
- Built using Command Code CLI

---

## Built By

Farhan Malik — PMM at [Command Code](https://commandcode.ai)

Day 3 of learning to code. AI-assisted. Honest about it.

Follow the build-in-public journey on [X]((https://x.com/MrMalikFarhan)) and [LinkedIn]((https://www.linkedin.com/in/engr-farhan-malik/)).

---

## Note on API Keys

Your API key is used directly in your browser and never stored or sent anywhere except the AI provider's API. Use your own key. Costs are minimal — a few cents per session.

---

## License

MIT — use it, fork it, improve it.
