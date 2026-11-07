# inDM

**Instagram DM automation for creators, marketing-led businesses and the agencies that run their accounts.** Someone comments a keyword on your post or reel, replies to your story, or sends you a word by DM, and inDM sends them your link by DM in seconds, in your words.

[Start free](https://indm.social) · [Pricing](https://indm.social/pricing) · [API docs](https://docs.indm.social)

---

## What it does

- **Comment-to-DM on posts and reels.** Someone comments your keyword and gets a DM with your link, while they are still reading.
- **Story reply and keyword DM automations.** A story reply or a word sent by DM starts the same conversation.
- **Public comment replies,** posted under the comment once the DM has gone out.
- **A follow gate and an email capture gate** on any link.
- **Analytics** for every automation, with its journey and funnel.
- **A unified inbox and contacts,** with export. Your audience is yours.
- **A live preview** of the exact DM before anything goes out.

inDM connects an Instagram Business or Creator account through Instagram's own login, with no password shared. It is an approved Meta Tech Provider, and every message goes through Instagram's official API.

## Build on it: the inDM API

inDM has a public REST API at `https://api.indm.social/v1`, on every plan, Free included. Your own script, dashboard or CRM can:

- see the workspace and every Instagram account connected to it, with each account's health;
- list the posts and reels inDM has synced, and fetch new ones now, so a reel posted a minute ago is ready to automate;
- create a comment-to-DM automation on a post (it starts as a draft), check it, and edit it;
- set it live or pause it;
- read its totals: how many times it fired, and how many messages were sent, failed or are still waiting.

You create API keys in inDM under **Settings → API keys**, either read-only or with full access, and each one expires after 30, 90 or 365 days, or never. One key reads every Instagram account in the workspace, which is what an agency running many clients needs. Your plan's limits apply through the API exactly as they do in the app.

```bash
curl https://api.indm.social/v1/workspace \
  -H "Authorization: Bearer $INDM_API_KEY"
```

The full reference, with a playground, is at **[docs.indm.social](https://docs.indm.social)**. [What the API is for](https://indm.social/instagram-automation-api) explains it without the code.

## Use it from ChatGPT

inDM is in ChatGPT's plugin directory, on every plan. Install it from the Plugins page, sign in to inDM, and draft, check and set live comment-to-DM automations by asking. Nothing sends through ChatGPT: your automations send the words you approved. [How inDM works in ChatGPT](https://indm.social/instagram-mcp).

## Pricing

Nothing is metered on any plan: no message allowance and no contact allowance.

| Plan | Price | Instagram accounts | What it includes |
|---|---|---|---|
| **Free** | $0, no card, no expiry | 1 | Unlimited messages, every automation type, both gates, analytics, the inbox, contacts, the API and the ChatGPT plugin |
| **Growth** | 7 days free, then $14.99 a month | Up to 5 | Everything in Free. Removes app branding, lifts the automation limit, adds up to 3 links in one automation, a follow-up message, broadcasts, your whole team, and who clicked your links |
| **Agency Lite** | $39 a month | Up to 15 | Everything in Growth, in one workspace |
| **Agency Pro** | $99 a month | 30, then $3 a month for each one after | Everything in Growth, with a dedicated account manager |

Prices change, and [the pricing page](https://indm.social/pricing) is the one that applies.

## FAQ

**What is Instagram DM automation?**
Software that answers your Instagram comments, story replies and DMs for you, sending a link, starting a conversation or capturing a lead the moment someone engages, instead of hours later by hand.

**How do I turn Instagram comments into DMs automatically?**
Set a keyword on a post or reel. When someone comments it, they get a DM with your link right away. That is the core comment-to-DM automation in inDM, and it runs free.

**Does inDM have an API?**
Yes, on every plan, Free included. The public API at `https://api.indm.social/v1` lists your posts, creates comment-to-DM automations on them, sets them live or pauses them, and reads their totals. Keys are created in Settings, read-only or with full access. The reference is at [docs.indm.social](https://docs.indm.social).

**Can an agency run many clients' accounts on one subscription?**
Yes. Agency Lite holds up to 15 Instagram accounts in one workspace for $39 a month, and Agency Pro holds 30 for $99 a month, then $3 a month for each one after. Clients connect their own accounts from a link the agency sends, without sharing a password.

**How does inDM compare with other tools?**
[The best Instagram DM automation tools, compared](https://indm.social/best-instagram-dm-automation-tool) sets them side by side, and there is a page for each one we track, such as [inDM vs ManyChat](https://indm.social/compare/manychat).

---

[indm.social](https://indm.social)
