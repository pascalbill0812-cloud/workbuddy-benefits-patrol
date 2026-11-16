# 🐾 WorkBuddy Benefits Patrol

> Oops — did you forget to claim your WorkBuddy points again? This little radar scans every corner of your account and lays out a clean, friendly checklist: what you can claim today, where to find it, and what's about to expire. No more hunting through menus.

## What it does

- 🧭 **Benefits map**: Buddy Gas Station daily check-in, streak rewards, task center, cat trips, lottery & blind boxes, official events — claimable, human-verification-only, and expiring items all in one place.
- 🔔 **Friendly nudges**: Points reset monthly. In the last 3 days of the month it reminds you in bold.
- 🐱 **Read-only by default**: General questions never trigger a click. It looks, lists, and leaves your mouse alone.

## Two modes, you decide

| What you say | What it does |
|---|---|
| "What benefits are available?" / "Check my points" / "What can I claim today?" | **Read-only patrol** — lists items and entry points, performs no clicks |
| "Claim these for me" / "Check me in" / "One-click claim" | **Claim mode** — only then does it click to claim |

When unsure, it defaults to read-only and gently adds: "Say 'claim these for me' if you'd like me to grab them."

## Install

Copy this folder to `~/.workbuddy/skills/workbuddy-benefits-patrol/`, or import the directory via WorkBuddy's skill install entry.

Then just say "WorkBuddy check-in", "what benefits can I claim", or "check my points".

## Requirements

- Browser control capability (for the web growth center / task center) — without it, only the web portion is reported, never faked as claimed.
- Windows local GUI automation (for the desktop client check-in) — without it, that item is listed as "manual claim".
- You must already be logged into WorkBuddy. It **never touches** passwords or verification codes — login is always yours.

## "Is this point farming?"

No. It claims the everyday points the platform openly offers — one per user per day — not loopholes, bulk accounts, or fake activity. The core of this skill is **showing you what's available**; auto-claiming is a default-off switch you must explicitly opt into.

## The short, serious part

- Your own account only, once a day; no bulk accounts, no faked behavior, no reverse-engineered APIs.
- Never reads local credentials, never calls internal endpoints — hard rules.
- Figures and entry points reflect the live page; the bundled catalog is a clue, not a price list.
- Respect the WorkBuddy Terms of Service; if the platform changes its rules or disallows automation, the skill switches to hints-only.
- Whether and how to use it is your call, and so is the risk.

## License

MIT — see [LICENSE](LICENSE).
