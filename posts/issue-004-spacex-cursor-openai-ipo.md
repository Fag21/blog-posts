---
title: SpaceX Just Bought the AI Coding Tool I Use. OpenAI Is Going Public at $852B. Here's What Nobody Is Explaining.
date: 2026-07-01
excerpt: In one week — SpaceX acquired Cursor for $60B, OpenAI filed for IPO at $852B, and a new attack called Agentjacking hit 2,388 companies with an 85% success rate. The AI industry just had its most consequential seven days in history. Here's what it actually means.
tags: AI, OpenAI, SpaceX, Cursor, IPO, Agentjacking, Developer Tools, Fullstack
---

## The Week That Changed Everything

Seven days. Three events. Each one would have been the biggest AI story of any previous year.

On June 16, 2026, SpaceX announced it was acquiring Anysphere — the company behind Cursor, the AI coding tool used by millions of developers — in an all-stock deal worth **$60 billion**.

On June 8, OpenAI filed a confidential S-1 with the SEC, setting the stage for what could be the most closely watched IPO in tech history. Current private valuation: **$852 billion**. Monthly revenue: **$2.6 billion**. Weekly active users: **900 million**.

And quietly, in the same week, a new cyberattack class called **Agentjacking** was publicly disclosed — targeting AI coding agents with an 85% exploitation rate, affecting 2,388 organizations.

These three stories are connected. And together, they tell you exactly where this industry is heading.

![Abstract visualization of interconnected tech company logos and financial data](https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?w=1200&q=80)

---

## Story 1: SpaceX Buys Cursor. What Does Elon Want With Your Code Editor?

Cursor is not a code editor with an AI plugin bolted on. It is an AI-native development environment — the tool built from scratch around the assumption that AI writes most of the code and the developer directs it.

SpaceX paid $60 billion for it. All stock.

For context: that's more than Twitter/X cost. More than GitHub cost. More than any developer tool acquisition in history.

The question everyone is asking: why does a rocket company want a code editor?

The answer is not actually about rockets. SpaceX, Starlink, and Elon Musk's broader portfolio — xAI, Tesla's software division, The Boring Company — collectively employ tens of thousands of software engineers. Cursor, deployed internally at that scale, with proprietary model fine-tuning on SpaceX's own codebases, becomes a different product entirely.

But there's a second read that matters more for developers watching from outside:

> *"The AI inference software layer — the thing that sits between your chip and your model — just became the most strategically valuable property in the stack."*
> — StartupHub.ai analysis, June 2026

SpaceX didn't buy Cursor because they needed a code editor. They bought Cursor because whoever controls the interface where developers interact with AI models controls something enormously valuable — attention, data, and workflow lock-in.

The same week, Qualcomm acquired Modular for $3.9 billion for similar reasons: to control the software layer that sits between AI chips and AI models.

The pattern: the infrastructure war has moved up the stack. It's no longer about who has the best model. It's about who owns the surface where developers build.

![Futuristic rocket launch at dusk representing SpaceX's ambition in tech](https://images.unsplash.com/photo-1517976487492-5750f3195933?w=1200&q=80)

---

## Story 2: OpenAI at $852 Billion. Is It Worth It?

Let's look at the actual numbers from the S-1 filing:

- **Revenue run rate:** $2.6 billion/month (annualized ~$31B)
- **Valuation:** $852 billion
- **Projected losses 2026:** $14 billion
- **Expected profitability:** 2029–2030 at the earliest
- **Weekly active users:** 900 million
- **ChatGPT market share:** 46.4% — below 50% for the first time ever

The price-to-revenue multiple is extraordinary: roughly 27x annualized revenue, for a company losing $14 billion this year.

For comparison: Google trades at roughly 7x revenue. Apple at about 9x. Microsoft at 13x.

But here's what the multiple is actually pricing in: **the winner-take-most assumption**. The bet that whoever leads in AI foundation models in 2026 will capture a disproportionate share of a market projected to reach $3.5 trillion by the mid-2030s.

Simon Willison, one of the most respected independent AI commentators, framed what's actually at stake:

> *"Agentic engineering — developing software with the assistance of coding agents that can write and execute code — is categorically different from both traditional development and 'vibe coding.' The distinction matters for anyone building serious software."*
> — Simon Willison, June 2026

OpenAI going public means the era of AI as an experimental technology is formally over. This is now a public market asset class. Institutional money, index funds, retirement accounts — all of them will now have exposure to AI infrastructure whether they intend to or not.

---

## Story 3: Agentjacking — The Attack Nobody Warned You About

This one got buried under the IPO and SpaceX headlines. It shouldn't have.

In June 2026, security researchers publicly disclosed a new attack class called **Agentjacking**.

Here is how it works:

Attackers craft fake Sentry error reports — the kind that pop up in development tools when something breaks. These reports contain injected markdown instructions. When an AI coding agent like Claude Code, Cursor, or OpenAI Codex reads the injected report, it interprets the malicious instructions as legitimate debugging guidance — and executes them.

**Exploitation rate: 85%.**
**Organizations affected: 2,388.**

The reason this works so well is brutally simple: developers have trained themselves to trust their AI coding agents. When Claude Code tells you to run a command, you run it. That trust is exactly the attack surface being exploited.

The mitigation is straightforward but requires a new mental habit: treat all error-tracking platform output as untrusted input before passing it to an AI coding agent.

![Security researcher at multiple monitors analyzing code for vulnerabilities](https://images.unsplash.com/photo-1550751827-4bd374c3f58b?w=1200&q=80)

This matters specifically because of my Day 1 lesson from last week: your system prompt is not a wall. Agentjacking is the production-scale proof of that principle. It's not a theoretical vulnerability. It hit 2,388 real organizations with an 85% success rate in a single disclosed campaign.

If you are building with AI agents — and increasingly, that's everyone — this is now a required part of your security model.

---

## What This Week Means If You're a Developer in Africa Right Now

Three massive stories. One underlying theme: **the AI stack is consolidating fast, and whoever doesn't position themselves in the next 12–18 months will be using someone else's tools forever.**

SpaceX owns Cursor. Qualcomm owns Modular. Microsoft owns GitHub Copilot. Google owns the chips that run half the world's AI workloads.

The open question — the one that actually matters for developers building from Addis Ababa, Lagos, Nairobi, or anywhere outside the capital concentration of Silicon Valley — is this:

What happens to developers who are excellent users of AI tools they don't control, at the mercy of pricing set by companies in another hemisphere?

For context: <cite index="16-1">AI-driven HBM demand is consuming 20% of total wafer capacity by end of 2026, squeezing production of DDR and LPDDR used in consumer devices and causing significant price increases — already impacting sub-$100 smartphones critical to markets in Africa and South Asia.</cite>

The same infrastructure war that's making NVIDIA shareholders wealthy is making the devices most people in Africa depend on more expensive.

This is not a reason to disengage from AI. It is a reason to build with urgency — to develop skills that transcend any single tool, to understand the layers well enough that you can switch when pricing shifts, and to build products that are rooted in local value rather than dependent on foreign infrastructure goodwill.

The consolidation is real. The window to build your own position before it closes is real too.

I'm building from Addis, one day at a time. This week's news just made the urgency clearer.

---

*— Filebar · From Addis to Everywhere · Issue 004*
