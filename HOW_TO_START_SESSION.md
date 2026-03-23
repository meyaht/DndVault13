# How to Start a Session — Prisoner 13
# Paste the prompt below at the start of every session. Fill in [BRACKETED] parts.

---

## STANDARD SESSION START PROMPT

Read the following files in this order before responding:

1. system/dm_protocol.md
2. system/narration.md
3. world/world.md
4. world/npcs.md
5. party/party_stats.md
6. session/checkpoint.md
7. session/threads.md

When you have read all seven files, confirm with:
"Ready. [one sentence describing where we are and what is immediately in front of us.]"

Then wait. Do not begin narrating until I respond.

---

## COMBAT START PROMPT

Read session/combat/combat_active.md. It has been reset for this fight.
Current combatants: [list enemies and any relevant terrain or positioning notes].
Chugguh acts on initiative [ROLL RESULT].
Roll initiative for Diana, Nameroc, Korda, Aldric, Keeper, [any companions present], and all enemies.
List the full initiative order before taking any turn.

---

## END OF SESSION PROMPT

Session is ending. Before we stop:
1. Update session/checkpoint.md — current location, time, party HP, and the last thing that happened.
2. Update party/party_stats.md — final HP and resource state for all characters.
3. Move any resolved threads from session/threads.md to archive/session_summaries.md with a one-line resolution note.
4. If combat just ended, archive session/combat/combat_active.md to archive/combat/combat_[name]_day[DAY].md and clear combat_active.md.
5. Confirm when done.

---

## WHAT TO LOAD AND WHEN

Always (every session):
- system/dm_protocol.md
- system/narration.md
- world/world.md
- world/npcs.md
- party/party_stats.md
- session/checkpoint.md
- session/threads.md

During combat only:
- session/combat/combat_active.md

Only when directly asked about the past:
- archive/session_summaries.md
- archive/combat/ (specific fight)

Never load proactively:
- Archive files of any kind

---

## FILE SIZE TARGETS

| File | Current | Target |
|------|---------|--------|
| system/dm_protocol.md | ~400 words | < 500 |
| system/narration.md | ~450 words | < 500 |
| world/world.md | ~300 words | < 400 |
| world/npcs.md | ~350 words | < 500 |
| party/party_stats.md | ~900 words | < 1000 |
| session/checkpoint.md | ~200 words | < 300 |
| session/threads.md | ~400 words | < 500 |

Total session load: ~3,000 words. Target ceiling: 4,000 words.
If any file grows past its target, archive the resolved content that crept back in.
