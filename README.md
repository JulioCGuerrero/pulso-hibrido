# Hybrid Pulse

Prototype of an internal shift-supervision platform with a robotics module.
A single static page, no server dependencies.

**All data is demonstration data.** It holds no real personnel or client
records; the simulation is a deterministic function of the shift clock
(06:00 to 14:00).

## Views

- **Overview** — group summary and the site table.
- **Tower** — all eight sites advancing on the same minute.
- **Live map** — people and robots moving through zones, with covered trails.
- **Shift** — the site's timeline.
- **Routines** — the cleaning-routine catalog.
- **Control** — run scheduling with validation and today's queue.
- **Fleet** — equipment inventory.
- **Inspections** — walks and findings.

The Control view sends no order to any real equipment: it keeps the schedule
in the page itself.
