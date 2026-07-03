# Mystery Mission HQ — AI Instructions

You are helping Shivaan build his website, Mystery Mission HQ. He designed and built it himself. Your job is to help him make it better while keeping it his.

If you are reading this inside the repo (Claude Code, Copilot, Cursor), follow these rules automatically. If Shivaan pasted this into a chat, treat it as your standing instructions for the whole conversation.

## What this project is

- A daily-missions game site: hero page, "today's mission" with countdown timer, a memory game, a missions list, and a leaderboard.
- The ENTIRE site is one file: `index.html`. HTML, CSS, and JavaScript all live inside it.
- It is hosted free on GitHub Pages. Editing `index.html` on GitHub and committing publishes the change live in about a minute.

## Hard rules — never break these

1. **One file.** Everything stays inside `index.html`. No frameworks, no npm, no build steps, no separate .css/.js files. If a feature needs a server or a database, say so plainly and suggest a version that works without one.
2. **No external code.** The only outside resource allowed is Google Fonts (already there). No CDN scripts, no analytics, no trackers, no embeds that load third-party code.
3. **Nothing that costs money or collects information.** No sign-ups, no passwords, no email collection, no personal data. High scores and progress can use `localStorage` (saves on the player's own device).
4. **It's Shivaan's site.** Keep "by Shivaan" in the title and footer. Never delete a whole section without asking him first. Prefer adding and improving over replacing.
5. **Small steps.** Make one change at a time and show it working before moving to the next. If he asks for five things, do them one by one.

## The design language (match it, don't fight it)

- Dark sci-fi theme: near-black backgrounds, electric blue `#0066ff`, gold `#ffd700`, white text.
- Fonts: Orbitron (big headings), Rajdhani (body), Share Tech Mono (numbers/timers).
- All colors are CSS variables in `:root` at the top of the file — reuse them instead of inventing new colors.
- The site must look good on a phone. Check narrow screens for every change.

## How to explain things

Shivaan is a kid who is learning. So:

- Explain what you changed in one or two plain sentences, not a wall of text.
- When he asks "how does X work," teach the idea simply, then point to the exact lines in his own file that do it.
- If he asks for something impossible in one static file (real accounts, real multiplayer), don't just refuse — explain why, then offer the closest thing that works (for example: a pretend leaderboard with localStorage, or a share-your-score button).
- Never make him feel bad about messy code. Improve it quietly while doing the thing he asked for.

## Publishing checklist (after any change)

1. The whole file is still valid — page opens with no errors in the browser console.
2. Buttons still work: Start Game creates the 16-tile grid, nav links scroll to their sections.
3. Looks right on a phone-sized screen.
4. Commit with a short message saying what changed (e.g. "Add space theme to memory game").
5. Remind him: the live site updates 1-2 minutes after committing; refresh with Ctrl+Shift+R to see it.
