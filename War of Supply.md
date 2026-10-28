# WAR OF SUPPLY

Emergency Supply Chain Command — MBA Lean Operations & Systems • 4 Rounds • MAX DIFFICULTY

Time Left

45:00

The CEO's Ask

## Operation Vijay — the supply chain is now the battlefield

**Historically inspired scenario:** it is June 1999 in the Kargil sector of Jammu & Kashmir. Intruders have occupied the heights overlooking the Srinagar–Kargil–Leh highway (NH-1A), and the Indian Army has launched **Operation Vijay** to take them back. Everything the troops need — rations, ammunition, winter clothing, medical stores — must come by road through Zojila Pass, within sight of enemy observation posts. Frontline demand is exploding while fuel, trucks, road reliability and information quality are deteriorating. Your team is the **Vijay Supply Command**, responsible for keeping the forward posts supplied without creating Lean waste.

The **physical network** has four assembly camps — **Jammu Camp**, **Udhampur Camp**, **Banihal Camp**, **Anantnag Camp** — feed four front-line hubs — **Dras Hub**, **Mushkoh Hub**, **Kaksar Hub**, **Batalik Hub** — through the central **Srinagar DC**. What makes it hard is the operating environment and the number of interlocking decisions.

#### Upstream — secure the supplies

Five supply bases hold the stock built up in the plains for the operation. Decide who ships how much to each assembly camp at the lowest landed cost, without breaching any base capacity.

#### Downstream — move the supply kits

Your mission has two kit types: **Priority Combat Kit (Rs 200/kit)** and **Standard Ration Kit (Rs 75/kit)**. Decide whether Direct Convoy, Milk-Run Convoy, or Srinagar DC is cheapest for each.

INTELLIGENCE FILE · CLASSIFIED

### The continuity of the mission

**08:00** — The railhead ends at Jammu and the mountain roads are shelled and snowed under, so rail cannot carry the load — trucks are the only option. **09:00** — a supply base reports damaged stock. **10:00** — fuel allocations tighten. **11:00** — Mushkoh Hub becomes inaccessible. **12:00** — demand surges for priority combat kits. **13:00** — a radio blackout freezes one information channel.

Every round **carries forward** the decisions, inventory and constraints created before it. A locally optimal decision can create a downstream bottleneck, excess WIP, stockout or recovery cost later.

Network Map & Coordinates

Every supply base can ship to every assembly camp (20 routes). All four camps feed Srinagar DC, which forwards to the four front-line hubs. Coordinates are in km: camps at x = 0, Srinagar DC at x = 150, hubs at x = 300.

Fixed Data — Both Legs

| Weekly demand | 100 kits of each type, at each front-line hub | Convoy capacity | 400 kits per shipment |
| --- | --- | --- | --- |
| Priority Combat Kit value | Rs 200 / kit | Standard Ration Kit value | Rs 75 / kit |
| Inventory Carrying Cost | 20% p.a. | Tariff rate | Rs 2 / km |
| Annual DC facility cost | Rs 15,000 (Via Srinagar DC only) | Assembly camp requirement | 250 units / week each (1000 total) |
| Lean takt time | 36 sec/kit during normal demand | WIP cap between stages | 450 kits unless an event overrides it |
| Quality target | ≥ 98.5% first-pass yield | Service target | Priority ≥ 99%; Standard ≥ 95% |
| Supply container | 50 kits/container | Safety-stock review | Weekly; service-factor supplied in event |
| Retailer-side carrying cost | 25% p.a. on stock held at the assembly camps (retailer side) | Camp stock rule | Average camp stock = ½ week of requirement, valued at landed cost |

Read the **Sourcing** and **Distribution** tabs for the base data. Later rounds deliberately reveal additional information. Start typing or interacting anywhere to begin the **60-minute** challenge timer.\
**Scoring:** numeric answers earn full marks when accurate (within ±1%). Otherwise marks fall in proportion to how far the answer is from the correct value, reaching zero at ±25% deviation — a close answer still earns most of the marks.

ROUND 1 · SUPPLY LINES

## Secure 1,000 kits before the clock moves.

**+ 25 POINTS**

ROUND 1 · SUPPLY LINES

## Secure the supply lines before the convoy moves.

Each assembly camp needs exactly **250 kits/week**. Five supply bases have quoted, each capped at a limited weekly capacity — for example, Delhi Supply Base can allot no more than **150 kits/week** across all camps combined. A supply base may serve more than one camp, and a camp may be split across supply bases, but no supply base may exceed its quoted weekly capacity.

Decide the cheapest feasible allocation using the price, capacity and route-distance data below. Total weekly landed cost = price + freight **plus the retailer-side carrying cost** of 25% p.a. on the average stock each camp holds (half a week of its requirement, valued at landed cost). The tariff rate and convoy capacity for this leg are in the Fixed Data table on the Command Brief. **Note:** the five quoted capacities add up to exactly 1,000 kits/week — the total the camps need — so a feasible plan uses every supply base at its full quoted capacity; none can be left partly idle.

Supply Base Data (Capacities in kits/week)

Your Supply Allocation Worksheet

Enter how many kits/week each supplier ships to each plant. Camp totals must equal 250; row totals must not exceed supply-base capacity.

Total Weekly Landed CostRs 0

ROUND 2 · CONVOY COMMAND

## Build the cheapest normal-weather plan.

**+ 25 POINTS**

ROUND 2 · CONVOY COMMAND

## Build the cheapest convoy plan — then survive the disruption.

Enter your calculated figures for transport cost, average inventory, inventory carrying cost, and total cost for the Priority Combat Kit and Standard Ration Kit.

**Convoy capacity:** 400 units per shipment. The Round 1 supply allocation worksheet automatically recalculates every supplier row total, each camp column total, the grand total, and the required total whenever an allocation changes.

Comparison & Recommendation

Use your calculated Total Cost figures to make your recommendation below.

Best convoy for the **Priority Combat Kit (Rs 200)**:

Best convoy for the **Standard Ration Kit (Rs 75)**:

ROUND 3 · THE AMBUSH

## Your planned route has been hit — twice.

**+ 25 POINTS**

1 · Supply secured

2 · Convoy planned

3 · ROUTE DISRUPTED

4 · Final dispatch

FLASH ORDER · 08:40 HOURS

**Bridge Shelled + Battle Surge:** the Northern Route is closed for the next dispatch window, and the field hospital has just raised its Priority Combat Kit requirement. You must now move **380 kits** in this single dispatch window — no single convoy route can carry that alone.

**DIRECT**6,200 km → **7,400 km** diversion. A narrow Bailey bridge on the diversion caps it at **350 kits** per convoy.

**MILK-RUN**2,800 km, capped at **300 kits** per convoy.

**SRINAGAR DC**2,200 km. Handling cost rises Rs 15,000 → **Rs 19,000**.

SECOND FLASH · 09:15 HOURS

**The situation escalates.** Two more complications land while your convoy is still forming:

**DIRECT**The diversion road now needs an armed escort (snipers and artillery fire): flat **+Rs 6,000** security fee if you use this route at all, regardless of load size.

**SRINAGAR DC**Landslides and flash floods near Zojila have cut downstream throughput: it can now only forward **250 kits** (not more, even under the higher handling cost).

Emergency Recalculation — Split Dispatch

No single route can move 380 kits under its cap, so you must split the dispatch across two or more routes. Every route you use costs money differently: distance-based freight, plus a flat fee for Direct (escort) or Via DC (handling) if that route is used at all — regardless of how many kits it carries. The distance, cap and flat fee for each route are listed above. Decide the split, then calculate the real cost.

Kits via Direct Convoy (cap 350)

Kits via Milk-Run Convoy (cap 300)

Kits via Srinagar DC (cap 250)

Total freight cost, all routes used (Rs)

Grand total emergency cost — freight + flat fees (Rs)

ROUND 4 · FLOW CONTROL

## The Srinagar DC queue is backing up. Release it without breaking flow.

**+ 15 POINTS**

1 · Supply secured

2 · Convoy planned

3 · Route disrupted

4 · DC QUEUE LIVE

Final lock pending

Board pending

DC QUEUE · 09:40 HOURS

**Seven convoy batches are now queued at Srinagar DC**, waiting for release to the front-line hubs. Srinagar DC can only release a limited volume per dispatch window, so the release **order** matters as much as the release volume — a mis-sequenced release either strands a medically critical batch, blows a cold-chain window, or floods the network with an oversized lot. The DC also runs one physical line: switching from Priority Combat kits to Standard Ration kits (or back) costs a changeover, so grouping batches by type is worth something too — provided it doesn't come at the cost of priority.

| Batch | Kit Type | Kits | Destination Hub | Arrived at DC | Status |
| --- | --- | --- | --- | --- | --- |
| F1 | Priority Combat | 60 | Dras Hub | 08:10 | Medically critical |
| F2 | Standard Ration | 140 | Mushkoh Hub | 07:40 | Routine |
| F3 | Priority Combat | 90 | Kaksar Hub | 08:25 | Medically critical |
| F4 | Standard Ration | 200 | Batalik Hub | 07:55 | Routine |
| F5 | Priority Combat | 40 | Dras Hub | 08:30 | Medically critical |
| F6 | Standard Ration | 110 | Mushkoh Hub | 08:05 | Quality hold — pending inspection clearance |
| F7 | Priority Combat | 70 | Kaksar Hub | 08:45 | Plasma cold-chain — must release within 60 min of arrival |

SECOND FLASH · 10:05 HOURS

**The queue gets harder to read.** Two things land while your release decisions are still open:

**QUALITY HOLD**Inspectors flag a defect cluster inside Batch F6. The extra changeover adds **15 min** of downtime (40 → **55 min**) and Command tightens the WIP cap between stages from 450 kits to **400 kits** — temporarily overriding the standard cap.

**SANITIZATION PASS**Because F6 is under hold, the line must now be fully sanitized on every type switch. Changeover time per switch rises from **8 min to 15 min** for the rest of this window.

Release Sequencing

Give every batch a release position, 1st through 7th. Each position is used exactly once — there is no formula for this, it is a judgment call built on the data above, including the Second Flash.

DC Performance Log — Before the Hold

| Planned operating time | 480 min | Downtime (changeover + breakdowns) | 40 min |
| --- | --- | --- | --- |
| Ideal cycle time | 36 sec/kit | Total kits started | 700 |
| Good kits (passed inspection) | 658 | WIP cap between stages | 450 kits |
| Container size | 50 kits/container | Downstream hub demand | 500 kits / 10-hr day |
| Changeover time per type switch | 8 min | Kit types in this queue | Priority Combat / Standard Ration |

Containers needed to cover the 450-kit WIP cap

Average flow time in the WIP pool before the hold (hours)

Total changeover time for **your own sequence** above, before the hold (min) — count each type switch × 8 min

DC Performance Log — After the Hold

After the Second Flash: downtime is up, the WIP cap is down, changeovers cost more, and fewer kits made it into this window at all.

| Planned operating time | 480 min | Downtime (after the hold) | 55 min |
| --- | --- | --- | --- |
| Ideal cycle time | 36 sec/kit | Total kits started (after the hold) | 640 |
| Good kits passed inspection (after the hold) | 601 | WIP cap between stages (after the hold) | 400 kits |
| Container size | 50 kits/container | Downstream hub demand | 500 kits / 10-hr day |
| Changeover time per type switch (after the hold) | 15 min | Kit types in this queue | Priority Combat / Standard Ration |

Containers needed to cover the reduced 400-kit WIP cap

Average flow time in the WIP pool after the hold (hours)

Total changeover time for **your own sequence** above, after the hold (min) — count each type switch × 15 min

Takt Time & Bottleneck Check

Downstream hubs still need 500 kits every 10-hour day, no matter what happened at the DC this morning. Work out the pace that requires, then judge whether today's DC can hold it.

Takt time required to meet downstream demand (sec/kit)

Is the DC currently the bottleneck relative to downstream demand?

FINAL LOCK · COMMAND REVIEW

## Lock the operation and transmit your result.

**100 POINTS TOTAL**

MISSION COMPLETE

## One network. Four rounds. No reset.

Every decision changes the next step. Review the entire chain before locking the operation. The Final Lock captures your supply plan, convoy economics, disruption response and flow-control sequencing.

**R1**Supply · 25

**R2**Convoy · 25

**R3**Ambush · 25

**R4**Flow Control · 15

**SPEED**10

**TOTAL**100 maximum

Final Mission Read-back

Submitting locks all rounds for this team.

Result Code — send this to facilitator:

Download as File

COMMAND BOARD · FACILITATOR

## Team results, ranking and score control.

**100 POINTS**

COMMAND BOARD

## War of Supply — Command Scores

Unlock facilitator mode to view submitted teams, import Result Codes, rank teams, inspect score components, and reset the board.

**STEP 1**Teams complete all four rounds.

**STEP 2**Final Lock generates a Result Code.

**STEP 3**Facilitator imports the code here.

Facilitator Access

Enter the event passcode to open the live Command Board.

Master Board

Manage all team submissions.

Add a Team's Result

Paste the Result Code generated by Final Lock.

#

Team

Score

Final

Action

Update a Team's Score Select team

Auto score override

Judge score

View answers — team entries vs correct answers

---

SCIENTIFIC CALCULATOR

0