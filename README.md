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
- Pulses: 9 ticks on, 9 ticks off, aligned with the bar and border cycle

Pulse timing follows the selected animation speed, so one full pulse cycle is
18 ticks.

## Active Bar Modes

- Animated — follows the execution cycle
- Solid 11111 — all five bars illuminated
- Off — all five bars disabled