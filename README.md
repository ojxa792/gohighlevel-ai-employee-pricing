# gohighlevel ai employee pricing: what the $97 per location really covers, what it doesn't, and how to cut the bill

GoHighLevel's AI isn't one price. It's three, and they're all charged per enabled location, not per agency. That single detail is why two agencies with identical client counts can quote completely different monthly costs and both be right.

Here's how the pricing actually works, where the invoice drifts upward from the sticker, when the $97 plan is genuinely the cheaper option, and what to do when the per-location math stops making sense.

## Three ways HighLevel bills AI

Every location you enable AI for picks one of these. All prices are USD and billed monthly.

| Plan | Monthly fee per enabled location | What's included | What's still metered |
| --- | --- | --- | --- |
| Pay-Per-Use | $0 | Access to supported AI products, billed only when there's billable activity | Conversation AI tokens, Voice AI components, Agent Studio, phone system |
| AI Employee Growth | $50 | 1,000 Conversation AI responses, 100 Voice AI minutes, unlimited Reviews AI and Content AI, included Ask AI and AI Studio usage, 100 Managed Agent runs | Usage beyond the allowances, Agent Studio, phone system |
| AI Employee Unlimited | $97 | Unlimited Conversation AI and Voice AI, unlimited Reviews AI and Content AI, 3x Ask AI and AI Studio usage, 1,000 Managed Agent runs | Agent Studio, phone system |

A few things worth pulling out of that table.

The 100 Voice AI minutes on Growth are shared across inbound calls, outbound calls, and the Voice AI widget. They don't stack. Reviews AI and Content AI are unlimited on both paid tiers, which matters more than it sounds if you're generating social content or chasing review responses for a dozen clients.

And Agent Studio — the newer agent builder with web search, multimodal generation, and external API calls — is **not included in any plan**. It stays pay-per-use whether you're on Pay-Per-Use, Growth, or Unlimited. If you're building custom agentic workflows, budget for it separately or you'll be surprised.

## What AI Employee Unlimited does not cover

The word "unlimited" applies to four products: Conversation AI, Voice AI, Reviews AI, and Content AI, subject to HighLevel's fair-use terms. It doesn't mean the location stops costing money.

Stacked on top, every time:

- **Your HighLevel platform subscription.** Starter runs $97/month, Unlimited $297, Agency Pro $497.
- **Phone system charges.** A Voice AI call still generates telephony costs even when the AI portion is covered by Unlimited. HighLevel's own documentation makes this point twice, in two separate articles, which tells you how often it gets misunderstood.
- **SMS and call usage.** Text delivery isn't free because Conversation AI wrote the message.
- **WhatsApp.** Currently listed at $10/month per enabled sub-account, plus usage.
- **A2P 10DLC registration.** One-time and carrier-related costs for US business messaging, before the texting side works at all.
- **Agent Studio.** Pay-per-use, always.

So a location on Unlimited is really $97 plus telephony plus messaging plus the platform seat underneath it. That's not a hidden fee — it's just a bundle that covers AI processing and nothing else.

## When $97 beats pay-per-use, and when it comfortably doesn't

Pay-per-use Voice AI has three components: a Voice Engine charge of $0.045/minute, a text-to-speech charge, and LLM tokens. Phone system costs sit outside all of it.

On the cheapest voice — OpenAI or Cartesia TTS at $0.015/minute — the base lands at **$0.060 per minute** before tokens. ElevenLabs V3 pushes that to $0.215/minute. Speech-to-speech models run $0.10/minute (Gemini 3.1 Flash Live) or $0.20 (OpenAI GPT Realtime 2/2.1).

Divide $97 by those rates and you get the crossover points:

- Cheapest voice: about **1,617 minutes** a month
- ElevenLabs V3: about **451 minutes** a month

Below those volumes, pay-per-use is cheaper on paper. A location doing 300 minutes a month — roughly three short calls a working day — pays about $18 in AI voice costs instead of $97.

Growth changes the shape of the decision. It costs $47 less than Unlimited and includes 100 minutes. At $0.06/minute, that $47 buys another 783 minutes, putting the crossover at roughly **883 minutes**. With ElevenLabs V3, it drops to about **319 minutes**.

Those thresholds exclude LLM tokens and phone charges, so treat them as ceilings rather than exact invoice breakpoints.

Which raises the real question: why put anyone on Unlimited at all? Predictability. A pay-per-use bill moves with call volume, and HighLevel's AI usage limits let you cap a sub-account (up to $1,000/month) so it either notifies you or blocks the AI when the limit is hit. Unlimited is the only option where a busy month doesn't cost more than a quiet one. For a client on a fixed retainer, that's usually worth the premium.

## The part that bites at scale

Per-location pricing is painless at three clients. It gets uncomfortable fast.

Ten locations on Unlimited is $970/month in AI subscription fees alone — before phone charges, before messaging, before your $297 or $497 platform plan. On Pay-Per-Use, ten locations with light text volume might cost the platform very little. But you lose the unlimited Voice AI, and you inherit metered billing you have to watch.

There's another constraint most pricing roundups skip: **HighLevel requires the $497/month Agency Pro plan to rebill AI Employee usage to clients.** Rebilling and reselling are separate features — reselling lets you package Growth or Unlimited as a recurring client subscription at your own price, while rebilling passes supported usage charges through with an optional markup — but if your margins depend on charging clients for AI usage, the $497 plan is the entry ticket. That's a real line item in the math, and it's often missing from comparisons.

## The two levers when the math stops working

You have two honest options when per-location AI gets expensive.

**Lever one: mix plans.** Nothing forces you to put every client on Unlimited. A quiet location on pay-per-use, a moderately busy one on Growth, and your two heaviest on Unlimited is a legitimate configuration. Check the usage mix before upgrading — a location that mostly texts rarely needs unlimited voice minutes.

**Lever two: change what the conversational layer costs.** This is where the pricing model itself matters, because a per-message tool doesn't multiply with your client count.

That's the gap [CloseBot](https://app.closebot.com/a?fpr=li87) is built for. It's a conversational AI agent platform for lead qualification and booking that connects to HighLevel (and HubSpot, LeadConnector, or a custom CRM), and it bills by plan and message volume rather than by location. You can run unlimited account connections on every plan, including the free tier.

One limit worth stating plainly: CloseBot handles text channels. SMS, email, website chat, and whatever else lives in your CRM inbox. It does not do voice. If your clients need an AI receptionist answering the phone, that stays with Voice AI — and the comparison becomes about text volume, not replacements.

## CloseBot pricing: the full current lineup

| Plan | Core configuration | Price | Billing | Purchase |
| --- | --- | --- | --- | --- |
| Free | 1 agent, 100 messages/month, 1 user seat, 1 MB knowledge storage, unlimited account connections | $0 | Free forever while under 100 messages/month | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| Core (Business) | Message costs included in the base price, 15+ templates, human support, additional users at $5/seat, add-on storage and agents | $64/month, or $53/month billed as $640/year | Monthly or annual | [Get Core for your business](https://app.closebot.com/settings?tab=subscription&plan=business&fpr=li87) |
| Core (Agency) | Unlimited agents, white-label client portal, rebill all costs, 50+ templates on annual plans, human support | $397/month, or about $331/month billed annually | Monthly or annual | [Get Core for your agency](https://app.closebot.com/settings?tab=subscription&plan=agency&fpr=li87) |
| Growth | 50+ templates, HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support | Custom quote | Annual or custom terms | [Talk through the Growth plan](https://app.closebot.com/a?fpr=li87) |

On the business track, Core scales with the monthly reply volume you select — the plans page slider runs from 100 up to 100,000+ replies. Published reviews of that page in 2026 list about $84/month at 1,000 replies, $109 at 2,000, and $176 at 5,000, with message costs included rather than metered on top. If you go over your ceiling, overage comes from a wallet.

On the agency track it's simpler: a flat rate of **$0.012 per message**, which you can rebill at whatever markup you set. Clients top up their own wallets through your Stripe account, and the marked-up amount is your margin.

Two structural differences from HighLevel's model are worth naming. CloseBot charges $0 per sub-account connection and has no per-location subscription, so adding a tenth client doesn't add a tenth subscription. And a "message" equals one segment — unless you enable the Agent Node's unlimited potential with many tools and unlimited instruction size, at which point billing switches to token costs and one message can consume several segments. Heavy agents deserve conservative budgeting.

There's a 7-day trial on any paid plan before you're billed, no contract, and no refunds after the trial. Which is exactly the argument for doing your testing inside those seven days.

## How the two approaches actually differ

|  | HighLevel AI Employee | CloseBot |
| --- | --- | --- |
| Pricing unit | Per enabled location | Per plan + message volume |
| Voice AI | Yes, included on Unlimited | No, text channels only |
| Rebill requirement | Agency Pro at $497/month | Available on the $397/month agency plan |
| Agent builder | Agent Studio, pay-per-use on every plan | Drag-and-drop flow builder included |
| CRM scope | HighLevel native | HighLevel, HubSpot, LeadConnector, custom CRMs |
| Entry cost | $0 pay-per-use, $50 Growth, $97 Unlimited per location | Free forever under 100 messages/month |

The split usually lands in one of two places. If your clients need phone coverage, Voice AI is the reason to stay inside HighLevel, and the $97 plan earns its price at higher call volumes. If the volume is mostly text — inbound SMS, DMs routed through the CRM, website chat — then you're paying per location for something that a per-message plan covers without multiplying by client count.

## A worked example with real numbers

Take an agency with 12 client locations. Six are quiet, mostly form fills and a few texts a week. Four are busy with texts only. Two take steady phone calls.

On the HighLevel route, the two phone-heavy locations go on Unlimited at $97 each. The four text-heavy ones go on Growth at $50 each, with overage once they pass 1,000 responses. The six quiet ones on pay-per-use. That's $194 + $200 = **$394/month in AI subscriptions** before overages, plus phone charges, plus the platform plan, plus Agent Studio if you're using it.

On a per-message layer for the four text-heavy locations, 2,000 replies each at $0.012 is about **$96/month total** on an agency plan — 8,000 messages and no per-location fee. Note that this is a partial swap, not a full replacement: the two phone-heavy locations stay where they are.

Which option wins depends entirely on your call volume. If your phone-heavy clients each run under 450 minutes a month on premium voice, pay-per-use may be cheaper than Unlimited. If they're well past that, Unlimited is the answer and the per-location fee is simply the cost of doing business.

Over to you: 👉 [Check your own numbers on CloseBot's plans](https://app.closebot.com/a?fpr=li87) and compare against your current AI line item.

## Questions that come up constantly

**Is AI Employee free?**
No. There's a pay-per-use mode with no monthly AI subscription fee, but billable activity still creates charges. HighLevel offers a 14-day platform trial, not a permanent free AI tier.

**Does AI Employee Unlimited include unlimited Voice AI?**
Yes, for inbound, outbound, and widget usage, subject to fair use. Phone system charges remain separate, which is why a Voice AI call can still generate a charge on Unlimited.

**What happens when a Growth location hits 1,000 Conversation AI responses?**
It depends on the location's AI usage limit setting. With "keep AI running, just notify" or spending limits disabled, usage continues at pay-per-use rates. With "block AI at the limit," it stops.

**Can I put different clients on different AI plans?**
Yes. Plans are configured per enabled location, and there's no requirement to standardize.

**Does CloseBot work if a client isn't on HighLevel?**
Yes. It integrates with HighLevel, HubSpot, LeadConnector, and custom CRM systems. What it needs is a CRM inbox to work inside — it doesn't connect to Instagram or WhatsApp directly, since those channels come through your CRM.

## What to take away

The $97 figure is accurate and, on its own, not expensive for what it includes — unlimited Conversation AI, unlimited Voice AI, and unlimited Reviews and Content AI for one location. It becomes expensive when you multiply it across locations that only ever needed text handling.

Run two numbers before you commit. First, each location's real voice minutes per month, compared against the crossover thresholds. Second, your total AI subscription across all locations, compared against a per-message model that doesn't scale with client count. Whichever number is smaller is the one that should be in the proposal you send.

👉 [See CloseBot's current plans and start free](https://app.closebot.com/a?fpr=li87) if the second number looks better than the first.
