# Sole — Minimalist Foot Content Subscription Platform (Prototype)

A complete frontend prototype for a subscription-based creator platform focused on foot content.

## All Pages

| Page | File | Description |
|------|------|-------------|
| **Landing / Onboarding** | `index.html` | Hero, how it works, creator CTA |
| **Login / Signup** | `auth.html` | Toggleable auth forms |
| **Become a Creator** | `become-creator.html` | Creator onboarding + pricing |
| **Explore / Feed** | `feed.html` | Creator discovery grid |
| **Creator Profile** | `creator.html` | Profile, stats, locked content grid, subscribe toggle |
| **Single Post** | `post.html` | Locked → unlocked content view |
| **Creator Dashboard** | `dashboard.html` | Earnings, subscribers, recent posts |
| **Messages** | `messages.html` | Conversation list + chat UI |
| **Account Settings** | `account.html` | Profile, subscriptions, settings |

## Design System

- Soft neutral palette (warm beige / gray)
- Inter font
- Clean, minimal, lots of whitespace
- Rounded cards, subtle hover states
- Fully responsive

## How to view

Open any HTML file in a browser. Recommended starting point:

**`index.html`**

You can navigate freely between all pages.

## Current status

This is a **high-fidelity frontend prototype**.

- Forms and buttons work for demo purposes (redirects / toggles)
- Subscribe / unlock interactions are simulated with JavaScript
- No real backend, payments, authentication, or image storage
- Content uses abstract gradients as placeholders

## What’s included for a full product later

- Age verification & ID checks
- Adult payment processor (CCBill / Segpay / etc.)
- Secure media storage + signed URLs
- Real subscription state & access control
- Creator payouts
- Messaging backend
- Moderation tools

## Suggested next technical steps

1. Choose a stack (Next.js + Node, or a white-label OnlyFans-style script)
2. Add real auth + age gate
3. Integrate adult payment processor
4. Build media upload + paywall logic
5. Deploy on adult-friendly hosting
