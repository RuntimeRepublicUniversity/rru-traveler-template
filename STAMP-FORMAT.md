# Stamp Format

At the end of every lesson, your instructor (the Claude Project) writes a stamp.
Copy it into the matching log in `logs/`, newest at the bottom, and commit it.

## Format

    ## STAMP <ID> | <YYYY-MM-DD>
    Lesson:   <lesson name>
    Quiz:     <points>/<possible> rubric points (Pass / Retry)
    Evidence: <what proves it: file in evidence/, link, or commit>
    Gaps:     <what you missed and how it was fixed, or "None">
    Station:  <which Project: Claude AI / GitHub / Discord>

## Stamp IDs

- `D` = Discord, `G` = GitHub, `C` = Claude AI
- `D1-L3` = Discord, Thread 1, Lesson 3
- `D1-S0` = Discord, Thread 1, Station 0 (setup)
- `D1-PT` = phase test, `D1-CAP` = capstone

## Example

    ## STAMP D1-L3 | 2026-11-20
    Lesson:   Scope it (channel overrides)
    Quiz:     8/10 rubric points (Pass)
    Evidence: evidence/D1-L3-locked-instructors-channel.png
    Gaps:     Permission calculation order; re-taught, passed on retry
    Station:  Discord Project (Claude)
