---
title: 'Bulk Terminal Dust Control: Why Conventional Methods Stop Working'
date: 2026-10-22 09:26:43
tags:
  - Bulk Terminal
  - Dust Control
  - Fugitive Dust
  - Fog Cannon
  - Dry Fog
  - Grab Unloader
  - Coal Terminal
  - Iron Ore Terminal
  - Dust Suppression
categories:
  - Case Studies
description: 'Why sprinklers, water carts and fixed nozzles underperform at bulk terminals: the pulse-versus-average mismatch, droplet size limits, the moisture ceiling and the measurement gap.'
keywords: 'bulk terminal dust control, port dust suppression, grab unloader dust, hopper dust suppression, dry fog dust suppression, fog cannon terminal, coal terminal dust, iron ore terminal dust, fugitive dust control, transfer point dust'
cover: /images/bulk-terminal-dust-source-chain-timing.svg
---

Dust control at a bulk terminal is usually procured as a coverage problem. A site is measured in hectares, a machine is selected by throw distance, and success is defined as the yard being visibly wet. The logic is intuitive: dust comes off the material, water holds the material down, so more water over more area should produce less dust.

On a berth handling coal, iron ore, bauxite or grain, that logic breaks down — not because water is the wrong medium, but because the emission and the application are mismatched on the three axes that decide whether droplets ever meet particles: **time, size and position**. The emission lasts seconds and repeats on a cycle set by the crane. The application runs on a cycle set by a pump and a driver. Between those two cycles there is a gap of roughly two orders of magnitude, and no volume of water applied at the wrong moment closes it.

This article examines why conventional methods underperform at bulk terminals, using the physics of grab discharge, the published emission relationships, and the moisture constraints that terminals actually operate under. It is written for terminal engineers, HSE managers and environmental officers who have to explain to a regulator why the equipment is running and the concentration has not moved.

<!-- more -->

## A Terminal Is Not One Dust Source. It Is Two.

The first analytical error is treating a terminal as a single dust problem. It is at least two, and they require opposite solutions.

**The moving point.** Grab discharge into a receiving hopper, the hopper outlet onto the belt, every transfer tower, the loader spout at the ship, the truck loading spout. These are compact, semi-enclosed sources with a violent, intermittent emission. The dust is fine, the air velocity is high, the duration is a few seconds, and the whole source relocates every few minutes as the crane travels along the hatch.

**The open surface.** Stockpiles, haul roads, rail sidings, the apron between the quay and the yard. These are large, unconfined and continuous. The emission is driven by wind passing over a surface, it scales with area and wind speed, and it never stops — it merely varies.

The two require different droplet sizes, different delivery methods and different control logic. A long-throw monitor aimed at a grab discharge point delivers most of its water past the source and into the hold or onto the apron. A fine mist installed over a stockpile disperses before it reaches the surface and leaves the pile dry twenty metres away. Much of what is recorded as "dust control installed but ineffective" at terminals is one of these two solutions applied to the other problem. The same terminal needs both, sized separately.

A terminal also has a third category that is not a suppression problem at all: spillage. Material that leaves the grab, the belt or the truck and lands on the apron becomes a dust source later, under traffic and wind. That is a housekeeping and containment task, and no nozzle solves it.

![The two dust problems at a bulk terminal: a moving point source and an open surface, with the timing of each](/images/bulk-terminal-dust-source-chain-timing.svg)

## What the Grab Bucket Does to the Air

The mechanism of grab discharge is worth stating precisely, because it explains why containment fails and why ordinary spray is scattered.

When the grab opens, tens of tonnes of material fall as a single mass. The falling material does not merely displace its own volume of air; it drags air with it and compresses the air in the receiving hopper. The result is a strong positive pressure inside the hopper and a return flow that moves upward against the falling stream. Published numerical modelling of grab coal discharge — the flow field visualised in a study of a Yangtze riverfront terminal published in the *Journal of Environmental Engineering Technology* in 2025 — shows the resulting structure clearly: air moves downward in the centre of the hopper and upward along the walls, forming an **annular vortex**. Dust pressed outward by the falling mass is carried up the walls by that vortex, and a fraction escapes over the rim.

Two consequences follow.

First, the dust does not leave the hopper in the direction the operator is watching. It climbs the walls, which is why a hood fitted above the opening captures less than its geometry suggests, and why the visible plume often appears at the corners and along the far wall rather than in the middle.

Second, the escaping air carries momentum. Industry field descriptions put the transient air velocity inside a receiving hopper above 10 m/s during discharge. A spray whose droplets leave the nozzle at low velocity is simply a passenger in that flow: it is deflected, diluted or carried out with the dust. This is the technical reason why increasing the number of ordinary nozzles around a hopper produces a diminishing and eventually flat response — the droplets are present, but they are not arriving with enough momentum or in the right place to intercept particles.

A further complication is coastal exposure. A terminal hopper stands in wind that is rarely still, and the same wind that disperses the plume also strips droplets from a fine spray. Any delivery method has to survive both the internal transient flow and the ambient wind at the same time.

## The Scheduling Mismatch: Two Orders of Magnitude

The second mismatch is temporal, and it is the one most often missed in procurement because both sides of it look reasonable in isolation.

Consider the two cycles.

A water cart or a fixed sprinkler line is programmed by shift, by hour, or by a moisture reading. A realistic cycle is 20 to 60 minutes per pass over a stockpile area, or a fixed duration of spraying per hour. This is a control designed for an average: it adds a quantity of water per unit area per unit time, and it assumes the emission is also an average.

Grab discharge is not an average. One grab cycle — close, hoist, travel, open, return — takes on the order of 40 to 60 seconds depending on the machine and the operator. The emission itself occupies only the few seconds of opening and fall. During a single shift, a busy unloader completes hundreds of these cycles. Each one is a dust pulse with a peak concentration one or two orders of magnitude above the shift mean, followed by a rapid decay.

The consequence is structural: **a control that operates on a 30-minute cycle cannot act on an event that lasts 4 seconds and repeats every 50.** Water applied at minute 0 of the cycle is long settled by minute 12, and the pulses at minutes 12 through 30 are uncontrolled. The average water volume can look generous on a monthly report while every individual pulse escapes.

This is also why the visible result of a sprinkler installation is so misleading. After a pass, the apron is dark, the pile surface is damp, and the site looks controlled. The material that was already airborne has gone; the next grab will produce the next plume from material whose surface moisture was raised by a fraction of a percent, several metres below the surface that was wetted.

The correct statement of the control objective is not "keep the yard wet". It is "have droplets in the air at the moment of discharge, in the volume the discharge generates". That is a different specification, and it leads to a different machine.

## Why Droplet Size, Not Water Volume, Sets the Ceiling

If timing decides whether droplets are present, size decides whether they collide. The collision probability between a droplet and a particle depends on their relative size and on their relative velocity. When a droplet is far larger than the particle, the particle follows the airflow around the droplet and never touches it. When the two are comparable, the particle's inertia carries it into the droplet and the aggregate grows until it settles.

Bulk terminal dust is fine. The fraction that matters — the part that stays suspended long enough to travel off site and the part that reaches the alveolar region of the lung — is below 10 µm, and the bulk of the suspended mass is typically below 75 µm. Conventional water spray produces droplets in the hundreds of micrometres. The size ratio is one to two orders of magnitude against capture.

Published Chinese assessment guidance for dry bulk terminals quantifies the result: at a supply pressure of 1 MPa, the suppression efficiency of plain water spray against particles of 5 µm and above is at most about **30%**, and terminal water supply is commonly in the **0.3 to 0.4 MPa** range, where efficiency is lower still. The same guidance records what replaces it: air-atomised dry fog producing droplets of **1 to 10 µm**, with suppression efficiency above **96%** for the respirable fraction, and long-throw monitors whose droplets should stay **below about 150 µm** to remain effective at distance.

There is a hard trade-off inside that number, and it is where most specifications go wrong. Small droplets capture fine particles well but evaporate quickly and lose momentum, so they cannot travel. Large droplets travel but do not capture. The mechanical industry standard for air-assisted spraying devices, JB/T 13562—2018, resolves this by tying droplet size to throw distance in the same table: a machine with a 30 to 50 m throw is specified at droplets below 120 µm, while a machine reaching 200 m is specified at droplets below 250 µm. Droplet size and range are one decision, not two.

![Why droplet size decides capture, and how the working band differs between a hopper and a stockpile](/images/bulk-terminal-droplet-size-window.svg)

Applied to a terminal, this produces a clean split. The semi-enclosed, high-velocity sources — grab hoppers, transfer towers, loading spouts — need **fine droplets delivered with velocity**, which is why air-assisted delivery, in which compressed air accelerates the droplets into the emission rather than relying on pump pressure alone, is the appropriate family there. The open surfaces need **larger droplets delivered with range and coverage**, which is the domain of the long-throw monitor. Selecting one technology for the whole terminal guarantees that one of the two problems is treated with the wrong tool.

## The Moisture Ceiling: Where More Water Stops Being an Option

The instinct when dust persists is to add water. At a bulk terminal, water addition is bounded — legally, commercially and physically — and the bound is reached sooner than most sites expect.

The Chinese code for environmental impact assessment of port construction projects gives the relationship used across the industry. Its unloading emission equation places moisture inside an exponential term with a critical value, denoted w₀, which for coal is **6%**. The meaning of that constant is precise and often misread: above w₀, further increases in moisture produce progressively less reduction in emission. The equation is telling the operator that water has a **diminishing return**, not that the material is now safe. Design reports accordingly work to a working moisture of about 7 to 8%, and treat anything beyond that as waste rather than control.

The American emission-factor compilation reaches the same conclusion by a different route. In the AP-42 batch-drop relationship for a clamshell or grab discharge, moisture content appears in the denominator, squared, while drop height, wind speed and silt content appear to the first power. The practical reading: moisture is the most sensitive variable in the whole expression, which is why damping a pile works at all — and why, once the material is near its practical moisture limit, further gains cannot be bought with water. Doubling moisture reduces the emission by roughly a factor of four; after the limit is reached, that lever no longer moves.

The constraints that set the limit are commercial and operational, not environmental:

- **Calorific value.** Coal is bought and sold on energy content per tonne. Water is not energy. A published field study of grab coal discharge notes explicitly that raising the water supply beyond the point where suppression plateaus makes the coal too wet and reduces calorific value — the suppression gain flattens at around 2.5 L/min of liquid supply in that test, while the commercial loss keeps rising.
- **Product quality.** Ore moisture affects sintering and blast-furnace charging; grain is water-sensitive in a different way again, with mould and spoilage risk rather than a quality penalty.
- **Winter.** In northern terminals, spray water produces ice on structures, on the belt and in the hopper, and frozen lumps that damage belts and block chutes. Water-based suppression becomes a seasonal liability.
- **Runoff.** Water that leaves the pile as runoff carries solids and has to be collected and treated. A site that sprays heavily to control air emissions creates a water-treatment obligation.
- **Corrosion and carry-back.** Wet material adheres to belts, idlers and chutes, generating carry-back and spillage that becomes the next dust source.

None of this argues against water. It argues that water is a **metered resource at a terminal**, and that a control strategy whose only variable is volume will hit the ceiling and then stop. The variable that remains available is the one the ceiling does not constrain: the size of the droplet and the moment it is released.

## Fixed Nozzles and a Moving Source

A grab unloader travels the length of the hatch. A ship loader's boom slews and luffs. A stacker-reclaimer runs along a rail. The dust source at a terminal is, in the literal sense, a moving target.

Fixed nozzle rings around a hopper are the standard response, and the design code requires them: the Chinese design code for environmental protection in water transport engineering specifies that grab-type, bucket-wheel, chain-bucket and screw unloaders are to be fitted with nozzle groups at the upper edge of the receiving hopper and at the chute feeding the quay belt, and that gantry cranes are to be fitted with a deflector plate and nozzle groups at the discharge point. That requirement is a floor, not a solution. A nozzle ring sized for a stationary hopper has to deliver across an opening several metres wide, into a flow that is moving upward at the walls, while the material enters off-centre as the crane positions for the next bite. Coverage at the rim is not coverage in the emission.

The same logic explains the limited value of wind fences as a suppression measure. A porous fence reduces wind speed in its lee and is genuinely useful against wind erosion of a stockpile. It does nothing about a grab discharge, because that emission is generated by the falling material, not by ambient wind. A fence installed around a hopper is treating the second-order cause and leaving the first-order one untouched. Wind fences and dust suppression are complementary measures with different targets, and a fence should not be counted against the hopper's emission budget.

There is a related specification confusion worth naming. Fire monitors at a bulk terminal — the fixed water cannon required by fire-safety design codes for enclosed coal storage and stockyard fire protection — are sized by fire load and code requirements, not by dust generation. Their flow rates are an order of magnitude above what suppression requires, their jets are designed to reach the far corner of a store in a fire, and they operate on a fire scenario, not a dust scenario. They are a safety obligation, correctly specified as such. They are not a dust control system, and a terminal that counts them as one has not solved the problem it thinks it has solved.

## What Enclosed Systems Can and Cannot Do at a Berth

The most robust answer to a fine, high-velocity dust source is enclosure plus extraction: hood the source, draw the dust-laden air into a baghouse, return clean air. Where the source can be enclosed, this works, and it works without adding water to the product.

At a berth, the constraint is geometric and economic. The source is defined by the trajectory of a grab bucket swinging on a rope or a rigid arm, arriving from a moving vessel at a moving hatch. Enclosing that trajectory means either enclosing the grab path — which conflicts with the crane's operating envelope, with visibility for the driver, and with wind loading on a tall structure at the quay edge — or accepting a partial hood with a large open face, in which case the capture velocity at the open face is what limits performance, and the required exhaust volume rises steeply with the distance to the emission.

Add the environment. Quay air is salt-laden and humid; bag filters, fans and ductwork at the waterfront have a corrosion duty that inland plants do not. A baghouse large enough to capture a grab discharge at the open face is a substantial structure on a machine that has to travel, and the weight and wind area sit on the same boom that has to handle a 40-tonne grab.

The realistic conclusion is not that extraction is wrong but that its economic range at a terminal is narrower than in a closed plant. Where a source can be genuinely enclosed — a transfer tower, a belt-to-belt chute, a loading spout with a telescopic skirt, a truck load-out — extraction and dry fog are both strong options and are frequently combined. At the open hopper under a travelling grab, the practical answer is suppression designed for a transient, high-velocity, semi-confined emission: fine droplets, delivered with momentum, timed to the discharge.

## The Measurement Gap That Lets a Failing System Look Fine

The final reason conventional methods persist beyond their useful range is that the feedback loop is too slow and too far away to contradict them.

The regulatory measurement for this class of source is ambient, at the site boundary. The Chinese design code for water transport environmental protection sets the criterion for fugitive emissions as a concentration difference between a monitoring point and a reference point of no more than **1 mg/m³**, with the monitoring point located in the highest-concentration position downwind, generally within 10 m outside the boundary of the unit downwind of the source; the same code requires coal and ore terminals to be equipped with dust monitoring instruments so that suppression can respond to measurement. These are sensible provisions, and they measure the right thing for the purpose they serve: what leaves the site.

They do not measure what leaves the hopper. Between the emission and the boundary there is transport, dilution and deposition, and the boundary instrument reports an hourly or daily average. A grab pulse lasting four seconds contributes to that average in proportion to its duration, which is to say very little. A terminal can be in compliance on the boundary record and still be coating the apron, the belt gallery and the neighbouring berth with dust at every discharge.

The same gap appears in commissioning. A suppression system is accepted on the basis of installation — nozzle count, pump pressure, coverage drawings, a demonstration that the nozzles spray. All of those can be satisfied by a system that does not intercept the plume, because none of them is a measurement of interception. The failure mode is therefore quiet: the site is wet on the day of acceptance, the yard looks controlled for the first season, and the shortfall only becomes visible when a dry, windy month arrives and the boundary record finally moves — by which time the equipment has been in service for two years and the specification is treated as settled.

Closing the gap requires a measurement at the source and a measurement of the timing. What matters operationally is the concentration at the discharge point, and whether suppression was active during the seconds of discharge. A terminal that records only the boundary average is flying on instruments that report the weather, not the emission.

## Time-Matched Suppression: Three Conditions and One Sequence

Everything above converges on a control objective that is narrower and more demanding than "reduce dust": **droplets of the right size must be present, at the emission, for the duration of the emission, in a quantity that exceeds the dust generation rate.**

Three conditions, all necessary:

1. **Size.** Droplets in the working band for the dust — fine enough to be captured by particles below 10 µm, delivered with enough momentum to enter a flow moving above 10 m/s.
2. **Timing.** Suppression active during discharge and not otherwise. This is both an effectiveness requirement and an economic one: water consumed between grabs buys nothing and costs calorific value, runoff and ice.
3. **Position.** Coverage of the actual emitting zone, including the walls where the annular vortex carries dust, not merely the geometric centre of the opening.

One sequence, which is the part most retrofits skip:

- **Characterise the emission.** Material, silt content, moisture as received, drop height, grab capacity, cycle time, wind exposure. These are measurements, not assumptions, and they determine everything downstream.
- **Fix what geometry can fix first.** Reduce drop height where the hopper design allows, close the gaps between hopper and belt, fit a skirt or curtain on the open faces that does not obstruct the grab, and deal with spillage as spillage. Suppression should not be sized to compensate for an avoidable free fall.
- **Then size suppression to the residual emission**, at the discharge point, with the droplet band that matches the dust.
- **Interlock to the crane, not to the clock.** The most reliable trigger signal is the machine's own state: grab closing, hoist position, trolley position, spreader status. A system that starts on the hoist's upward travel with a loaded grab and stops when the grab leaves the hopper is matched to the emission by construction.
- **Measure at the source.** A dust sensor at the hopper and a record of suppression state give the terminal something the boundary monitor cannot: evidence that the system performed during the events that mattered.

Where ambient conditions dominate — a dry pile and a rising wind — the sequence extends upstream. Published terminal practice in China now couples moisture measurement, wind speed and suppression: one riverfront terminal reports a control rule derived from wind-tunnel testing in which suppression is started pre-emptively when wind speed exceeds 5 m/s and surface moisture falls below 8%, with reported water savings of about 35% against manual operation and a reduction of roughly 45% in PM10 and PM2.5 at the site boundary. The specific numbers belong to that site and its material. The principle does not: **prediction is cheaper than response, because a pulse that has already left the hopper cannot be caught.**

This is the operative difference between a terminal that suppresses dust and a terminal that wets a yard. The first schedules water against the emission; the second schedules it against the shift.

## A Specification Sequence for a Terminal Retrofit

In order, with each step narrowing the options:

1. **List the sources and classify them** as moving point, open surface or spillage. Do not allow one technology to be proposed for all three.
2. **For each moving point, record the emission parameters** — material, moisture as received, drop height, grab or spout capacity, cycle time, ambient wind at the quay.
3. **Establish the moisture limit for that material and that customer.** Ask the commercial team, not only the environmental team: the point at which added water becomes a quality or calorific penalty is a business constraint that the dust specification must respect.
4. **Choose the droplet band from the dust, then the delivery method from the band and the flow field.** Fine and fast for the semi-enclosed high-velocity sources; larger and longer-throw for open surfaces.
5. **Specify the trigger and the interlock**, in terms of machine state rather than time of day, and specify the fail-safe behaviour when water pressure or air pressure is lost.
6. **Specify the measurement**: source-level dust sensing where feasible, suppression-state logging always, and a boundary record that is understood as a compliance instrument rather than a performance instrument.
7. **Size the water and energy budget from the duty cycle**, not from the installed capacity. A system that runs continuously because it has no trigger will be judged on its water bill before it is judged on its dust result.
8. **Then select equipment**, and require the supplier to state the droplet band, the throw, the required supply pressure and the consumption at the specified duty — parameters that can be checked, rather than a coverage claim.

Steps two, three and five require information that a supplier does not have. That is why the useful supplier conversation at a terminal starts with the material and the crane cycle, not with the machine.

## Working With a Supplier

The value a manufacturer can add at a bulk terminal is not a coverage claim. It is the ability to size a suppression system to measured conditions and to deliver droplets that match the dust, at the moment the machine discharges.

Guangdong Fenghua Environmental Protection Equipment builds air-assisted spraying devices as first drafting unit of the mechanical industry standard JB/T 13562—2018, with a product range spanning 30 to 300 m, and supplies configurations for terminals that combine long-throw suppression over open stockyard surfaces with fine, air-assisted delivery at hoppers and transfer points. The engineering position behind that range is the one argued in this article: droplet size and throw distance are one decision, the source decides which, and a terminal needs both answers rather than one machine applied twice.

## Keep the Conversation Going

If a terminal you operate has suppression installed and a dust problem that has not moved, the most useful next step is a source-by-source review rather than more equipment. Tell us the material, the moisture it arrives at, the drop heights and the crane cycle, and we will tell you which sources are being treated with the wrong droplet size, which are being treated at the wrong moment, and which are not a suppression problem at all.

Website: http://www.cannonsprayer.com/
Email: greenpath19960117@gmail.com
