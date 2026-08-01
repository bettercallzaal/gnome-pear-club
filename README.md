# The Gnome Pear Club

A cozy, gamified community hub for seed savers. Bringing back what's natural - home-grown food and the seeds that carry it.

Founded by **MetaM00**, who brought in **BetterCallZaal / Zaal** to build it (via the @frankythefrog ecosystem). This repo is the website + the eventual backend for the club.

## The idea

A whimsical gnome-themed world you log into. You get a profile (bio, goals, favorites) and a home on a map. A daily **check-in** (tapping your tree) earns **pears** - points you redeem for rare seeds and items in a **seed bank**. As you level up you unlock rare outfits and badges via crafting, and a **marketplace** lets you trade coveted items. It's a supportive, creator-focused little economy built around growing your own.

## Feature map (the backend build)

| Area | What it is |
|---|---|
| **Profiles** | Sign up with a bio, goals, favorites; a gnome-you with a spot on the map. |
| **The map** | The whimsical world you walk into; your patch grows as you do. |
| **Daily check-in** | Tap your tree once a day -> earns pears. The habit loop. |
| **Pears** | The currency. Earned by showing up, spent in the seed bank + marketplace. |
| **Seed bank** | Redeem pears for rare seeds + coveted items. The reward. |
| **Level up + crafting** | Unlock rare outfits + badges as you climb. |
| **Marketplace** | Trade coveted items; the community sets what's precious. |
| **Events** | Gatherings + drops with Luma sign-up links. |
| **Community** | Comments, message boards, and hidden notes tucked around the map. |

## Status

**v0 - landing page** (`index.html`): a static, whimsical landing that captures the vision. No build tooling, opens directly in a browser. This is the thing to show MetaM00 + iterate on.

**Next (to align with MetaM00):**
- Confirm the surface: website vs Farcaster miniapp vs a snap/frame (a miniapp/snap lives where the community already is; the website is the full world).
- Start with the heart of the loop: **check-in -> pears -> seed bank**.
- Then the profile + map, then crafting/marketplace.

## Stack

Starting as plain static HTML/CSS (no framework, no build) so it's instant to open, edit, and show. When the gamified backend lands (profiles, pears ledger, seed bank, marketplace), the natural path is a lean app (Next.js + a simple DB) - but not before the concept is locked with MetaM00.

## Design

Cozy + earthy, not neon: warm cream, forest green, pear-gold, soft blush. Fraunces (display) + Nunito (body). Whimsical but clean, mobile-first.

## Local

Just open `index.html` in a browser. No install.
