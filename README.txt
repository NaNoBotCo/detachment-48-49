Detachment 48–49

Her ask 2026-10-14: "That's a pretty good short story. Please add it to github for nanobotco. add lots of sharing features and a link to an investor-friendl(ier) business plan. "maximize shareholder value" is the only claim made on it."

Live: https://nanobotco.github.io/detachment-48-49/ (the story) and /plan.html (the business plan for investors).

The story: docs/index.html. The plan: docs/plan.html. Sharing for both: docs/share.js (share bar, passage sharing on text selection, a link to each plan sheet, QR, card download).
QR codes: docs/qr.svg and docs/qr-plan.svg, made with segno, LINE green on dark blue.
Share cards: node tools/card.mjs (docs/card.html → docs/card.jpg and docs/plan-card.jpg).
Check a card: python3 ~/Developer/claude\ code\ projects/site-kit/sharecard.py https://nanobotco.github.io/detachment-48-49/
Publish: ~/.claude/bin/pr-push "<this folder>" "<title>"

Sources on the plan: IOM via UN Thailand (4.6 million Myanmar people in Thailand, Nov 2025); UNHCR Thailand Multi-Country Office (~600,000 registered stateless).
The deck made the same day: claude.ai artifact KMb14Z8krw15sqNcpGTkQE, source in ../motdang-roadmap/wheels/deck.
