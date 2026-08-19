# Knyte States

Animated visual states for Knyte execution agents.

## States

- Idle — no illumination
- Executing — 5-on / 4-off bar cycle with synchronized border motion
- Waiting for input — all five bars and full border illuminated

## Timing

Execution uses an 18-tick master cycle:

- 6 hexagon sides × 3 ticks per side
- 9 bar states × 2 ticks per state