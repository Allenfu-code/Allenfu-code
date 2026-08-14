# Hi, I'm Allen Fu 👋

I build security-conscious AI agents, data products, and self-hosted web
services. My recent work combines Python, JavaScript, machine learning,
real-time voice systems, and Cloudflare infrastructure.

我專注於具備安全與隱私邊界的 AI Agent、資料產品與 Web 服務。

## Featured projects

### [Restaurant Voice Agent](https://github.com/Allenfu-code/restaurant-voice-agent)

A privacy-conscious restaurant reservation agent built with LiveKit, SIP, and
OpenAI Realtime. It includes a zero-cost dry-run mode, structured tools,
redacted logs, permission-restricted result storage, and offline tests that do
not load production credentials.

`Python` · `LiveKit` · `OpenAI Realtime` · `SIP` · `pytest`

### [Taiwan Stock ML Research](https://github.com/Allenfu-code/taiwan-stock-ml-research)

A leakage-aware quantitative research pipeline with deterministic synthetic
data, time-aligned features, expanding-window validation, and transaction-cost
backtesting. Private datasets, fitted models, rankings, and credentials are
deliberately excluded.

`Python` · `pandas` · `scikit-learn` · `LightGBM` · `walk-forward validation`

### [Secure LINE Webhook](https://github.com/Allenfu-code/line-cloudflare-webhook)

A standalone Node.js security reference for LINE webhooks. It verifies the
exact raw request body with LINE HMAC before parsing, bounds request size and
concurrency, uses generic errors, and includes a loopback-only Cloudflare
deployment pattern. The active bot uses Hermes Gateway's separate LINE adapter.

`Node.js` · `LINE Messaging API` · `HMAC` · `Cloudflare Tunnel` · `CI`

## Engineering principles

- Treat security, privacy, and failure behavior as release requirements.
- Test with synthetic fixtures; keep production data and configuration outside
  public repositories.
- Prefer time-aware evaluation and explicit limitations over inflated claims.
- Use least-privilege automation, dependency auditing, and protected branches.

## Current focus

AI agents · data products · secure web applications · quantitative research

I'm open to software engineering opportunities where I can turn ambiguous
problems into reliable, testable products.
