# Keylock — Cybersecurity Terms Matching Game

Open `index.html` in any modern browser — no install or build step.

- **Keys** = malware/security terms; **keyholes** = definitions (15 total).
- Drag a key onto a keyhole, or tap a key then tap a keyhole.
- A correct match unlocks the keyhole and reveals a real-world example; a wrong key shakes the lock.
- **Hints (8 per game):** press 💡 Hint, then select a keyhole.
  - **1st hint** on a keyhole: a clue pop-up that points toward the right key without naming it. The clue stays on the card.
  - **2nd hint** on the *same* keyhole: the matching key shakes and glows for 1.5 seconds.
  - Picking a keyhole that already has both hints replays the glow for free. Press 💡 again or `Esc` to cancel without spending a hint.
  - 8 hints is enough to get 4 keys outright. The rest you have to work out from the clues.

## Versions

- `keylock-v2-clue-hints` (this branch): 8 hints, clue first, then shake & glow.
- `claude/keylock-hints-shake-glow-85bco5`: the original 3 hints, where each one makes a key shake & glow.
