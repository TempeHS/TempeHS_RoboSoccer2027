# RoboCup Junior Soccer 2026 — Rules Summary for First-Time Teams

A plain-language summary of the rules that matter most when you are just
starting out. This is **not** a replacement for the official rules — read the
full document for anything you are unsure about.

Full rulebook: [RCJA Soccer Rules 2026 (PDF)](RCJA-Soccer-Rules-2026.pdf)
(Version 26.0, last modified 17 February 2026)

> The section numbers in brackets (e.g. _§4.1_) point to the matching section in
> the full PDF.

---

## 1. The basics

- Two teams, **two robots each**, play autonomous robot soccer on a green (or
  charcoal) carpet field. Robots must find the ball and score in the goal. (§1.1, §4.4)
- A game is **two 5-minute halves** with a 5-minute break. (§5.2)
- The game ends early at a **10-goal difference**. (§5.2.6)
- Win = 3 points, tie = 1, loss = 0. (§5.15)

## 2. Pick your league

All leagues are open to any age. Choose based on parts and ball type: (§1.2)

| League       | Ball             | Max weight | Parts                                                  |
| ------------ | ---------------- | ---------- | ------------------------------------------------------ |
| Simple Simon | Infrared         | 1.0 kg     | LEGO only + one IR sensor (max 2 years in this league) |
| Standard     | Infrared         | 1.0 kg     | LEGO + approved third-party sensors                    |
| Lightweight  | Infrared         | 1.4 kg     | Any parts (cameras allowed)                            |
| Open         | Orange golf ball | 2.5 kg     | Any parts (cameras allowed)                            |

## 3. Robot must-haves (most common scrutineering failures)

- **Fits in a 220 mm diameter cylinder** and is **no taller than 220 mm**. The
  cylinder must spin freely around the robot. Design to ~210 mm to be safe. (§4.1)
- **Stays within the weight limit** for your league (see table above). (§4.1)
- **Drives in all directions** and is **fully autonomous**. (§4.2)
- **Started manually** by a team member — no laptops, phones, or remote control. (§4.2)
- Has a **sturdy handle** that lets you lift the robot from 50 mm above its
  highest point. Cable ties make a good lightweight handle. (§4.5.7)
- **Does not hold or trap the ball.** The ball can only sit inside your
  "capture zone" by a small amount: 30 mm (Simple Simon / Standard / Lightweight)
  or 15 mm (Open). (§4.6)
- **No buzzers or speakers during play** — making noise gets you marked
  "damaged". Speakers are allowed only for debugging. (§4.5.8, §5.7.1.7)
- Avoid showing **cyan, yellow, or orange** on the outside — it can confuse
  other teams' cameras and your own. (§4.3.2)

## 4. Kick-offs and scoring

- Each half and each goal restarts with a **kick-off**. Your robots start on
  your defensive half and must not be moving. (§5.4)
- On kick-off the ball must roll clear by **at least 50 mm**, or your robot must
  start at least 50 mm from the ball. (§5.4.7)
- **Goal** = the ball hits the back wall of the goal. (§5.5.1)
- **Own goals count** for the other team. (§5.5.4)

## 5. Things that get your robot pulled off the field ("damaged")

A "damaged" robot is removed for ~30 seconds (or until a goal is scored). Common
triggers: (§5.7)

- Not responding to the ball. (§5.7.1.1)
- Sitting in the goal area for more than 20 seconds, or stuck on a wall. A small
  reverse command in your code usually frees a stuck robot. (§5.7.1.2)
- Tipping over and being unable to move. (§5.7.1.3)
- **Lightweight/Open only:** fully driving into the out area (between the wall
  and the white line). (§5.7.1.6)
- Damaging the ball or the field — do this twice and you are **disqualified**. (§5.7.4–5.7.8)

## 6. Good behaviour rules

- **No charging robots that don't have the ball** — that's a foul, and the robot
  is marked damaged. Repeated fouling gets it removed or disqualified. (§5.12)
- **Multiple defence:** only one robot may sit defending in your penalty area.
  A second defending robot gets moved to the centre. (§5.11)
- **Goalies** must move in all directions and respond _forward_ toward the ball —
  not just slide side to side. (§5.8)
- **The referee's decision is final.** Arguing earns a warning, then a forfeit. (§6.1)

## 7. Don't forget the paperwork

You can't compete (or win awards) without these: (§7.4)

- **Annotated code** submitted before the event — comments explaining your
  sensors, decision logic, and motor control. No submission = no play. (§7.4.1)
- **A3 digital poster** (team name, members + roles, one cool feature, a
  challenge you overcame, what you learned) — required for special awards. (§7.4.2)
- Be ready for **scrutineering** and a **team interview**: the work must be your
  own and you must be able to explain how it works. (§7.1–7.3)

## 8. Quick pre-event checklist

- [ ] Robot fits 220 mm cylinder and height, with margin
- [ ] Under the weight limit for your league
- [ ] Drives in all directions, starts by hand, no remote control
- [ ] Handle attached and easy to grab
- [ ] Ball is never trapped/held; capture zone within limits
- [ ] No game-time buzzers; no cyan/yellow/orange on the shell
- [ ] Reverse-out logic so the robot frees itself from walls/goals
- [ ] Annotated code submitted
- [ ] A3 poster submitted (if going for awards)
- [ ] Calibrate sensors/camera for the venue's lighting on the day (§2.5)

---

_Always check the [full rulebook](RCJA-Soccer-Rules-2026.pdf) for exact wording —
this summary highlights the essentials but leaves out detail._
