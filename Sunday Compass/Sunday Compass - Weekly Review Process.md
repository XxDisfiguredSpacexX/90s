---
type: process
tags: [sunday-compass, weekly-review]
---
# Sunday Compass: Weekly Review Process

Sunday morning, coffee. 15 minutes for the short-ish version, an hour for the full one.
**A short review done beats a full one skipped.**

## Pages
- [[ESSENTIAL LIFE 2026 to 2027]]: the document. Read the top every Sunday.
- [[Weekly Review Template]]: new note each week, saved in `Weekly Reviews/`.
- Name each note: `Weekly Review DDMM -> DDMM YYYY` (Monday to Sunday of the week just finished).

## Steps (one at a time)
1. Read the Essential Life document: Goals, Purpose, the one project. Then read the Essential Scene.
2. **Did the project move forward this week? Yes or no.** Not how much. Just whether.
3. Statistics: gym sessions, videos uploaded, paid offers made, hours in the protected slot.
4. Reflection questions:
   - 3 great things that happened last week
   - The main struggle
   - What I'd tell someone with the same struggle
   - One decision that would have made life better or moved me faster
5. Score the ten life areas 1 to 10. Note the lowest and any big drop.
6. Calendar: two weeks back, two weeks forward. What could sneak up on me?
7. Choose the next 2 to 4 Pieces. Pieces first, everything else after. Leave gaps.
8. Fill the NEXT WEEK block and put the blocks in the calendar **now**.
9. After: clear inbox, clear downloads folder, review the week's notes (action or calendar each one).
10. Relax. Actually see the progress.

## Patterns to check
- **Two NOs in a row:** the alarm, not the end. What really took the time? Shrink the next Piece until it's embarrassingly small.
- **Missed week:** don't make it up, don't binge. Smallest Piece, do that one thing, name the cause.
- **Planning instead of doing:** redesigning the system is not a Piece. One Piece beats a better system.
- **Project finished:** celebrate properly. Name project two, add it under Projects.
- **Drift:** three weeks with nothing tied to Purpose. Is the document still true, or am I avoiding it?

## Short review (rough week)
Read the document → yes or no → NEXT WEEK block. Done.

## All reviews
```dataview
TABLE project-moved AS "Moved", protected-hours AS "Protected hrs", gym AS "Gym", videos AS "Videos", offers AS "Offers"
FROM "Sunday Compass/Weekly Reviews"
SORT file.name DESC
```
*(Needs the Dataview plugin. Without it, this block just shows as code.)*
