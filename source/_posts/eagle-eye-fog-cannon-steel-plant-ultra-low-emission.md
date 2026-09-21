---
title: Application of "Eagle Eye" Fog Cannons in Ultra-Low Emission Control for Iron and Steel Enterprises
date: 2026-09-15 13:05:10
tags:
  - Ultra-Low Emission
  - Fugitive Dust Control
  - Fog Cannon
  - Dry Fog System
  - Steel Plant
  - AI Vision
  - PM10
categories:
  - Case Studies
slug: eagle-eye-fog-cannon-steel-plant-ultra-low-emission
description: 'The hardest part of ultra-low emission retrofits in steel plants is fugitive dust. Starting from policy and real site conditions, this article sets out the five-layer architecture of AI vision plus intelligent fog cannon linkage, the principles of droplet-to-particle matching, the parameters that actually decide selection, an evaluation method that survives audit, and the suppression rule for each of six dust hot spots in an integrated steel plant.'
keywords: 'ultra-low emission steel plant, fugitive dust control, fog cannon, dry fog system, AI dust detection, PM10 suppression, stockyard dust'
cover: /images/eagle-eye-fog-cannon-system-architecture.svg
---

Steel has replaced power generation as the largest industrial source of air pollutants in China. According to figures released with the 2019 national policy, the sector emitted about 1.06 million tonnes of SO2, 1.72 million tonnes of NOx and 2.81 million tonnes of particulate matter in 2017, roughly 7, 10 and 20 percent of the national total. That is why the five central ministries issued the guideline on ultra-low emission in the iron and steel industry, setting hourly average caps of 10, 35 and 50 mg/m3 for particulate matter, SO2 and NOx at sintering machine heads and pelletizing roasting, and 10, 50 and 200 mg/m3 for other major sources, with at least 95 percent of hourly averages in a month required to comply.

Most of the engineering capacity in the past five years went into the stack: desulfurization, denitrification, bag houses, electrostatic precipitators. Those are solved problems with mature vendors and verifiable continuous monitoring. The part that still decides whether a plant passes the assessment is the part that has no stack at all - fugitive dust from stockyards, belt transfer points, cast houses, slag handling and haul roads.

<!-- more -->

## The Hardest Half: Why Ultra-Low Emission Stalls at Fugitive Dust

Public assessment data cited in policy reporting puts fugitive dust at more than half of the steel sector's particulate emissions, and the uncontrolled particulate emission per tonne of crude steel at more than double the level of advanced steelmaking countries. The gap is not in the bag house. It is in the open.

Fugitive emission is difficult for three structural reasons. It is **distributed**: a single integrated plant may have dozens of genuine emission points scattered over several square kilometres. It is **intermittent**: a truck dumps for forty seconds, a ladle taps for three minutes, a gust crosses an open pile and the plume is gone. And it is **unmeasured**: unlike a stack with CEMS, most open sources have nothing attached to them, so there is no baseline and no proof.

The policy drafting anticipated this. Beyond concentration limits, it requires enclosed or sealed storage and conveying, and it states plainly that **no visible dust may escape from dust-generating points or workshops**. That sentence is a visual criterion, not a numerical one - which is exactly why the newest wave of projects is being built around cameras and inference rather than around timers.

## What "Eagle-Eye" Actually Changes: From Timed Spraying to Event-Driven Suppression

The conventional setup is a timer and a contactor. Every thirty minutes the whole stockyard sprays for five minutes, whether or not anything is moving. It is simple, it is defensible on paper, and it fails in three ways at once. Water and power are consumed on empty yard. Operators turn the system off in winter because of icing and in summer because material gets too wet for the belt. And when an inspector asks what happened during last Tuesday's shift, there is no record of anything.

An eagle-eye system replaces the clock with an event. Multi-source perception - AI cameras, online particulate monitors, weather station - feeds a threshold engine that decides whether dust is being generated, where, and how severely. Suppression equipment in that specific zone is then triggered automatically, with a preset spray programme, and the result is verified against the same sensors that raised the alarm.

The practical difference is not philosophical. Response moves from minutes to seconds, only the affected zone runs instead of the whole yard, and every action leaves an image pair and a concentration curve behind. Water and power consumption typically drop substantially simply because the system stops spraying at nothing.

## System Architecture: Five Layers from Perception to Verification

![Eagle-eye fog cannon system architecture: perception, edge AI, control, execution and data layers forming a closed loop](/images/eagle-eye-fog-cannon-system-architecture.svg)

The architecture that works in a plant environment is a five-layer loop, and the loop matters more than any single layer.

**Perception.** AI cameras are aimed at emission points rather than at the skyline; online TSP, PM10 and PM2.5 monitors are placed at hot spots and at the fence line; a small weather station supplies wind speed, wind direction, temperature and humidity. Wind data is not optional - it is the difference between a spray programme that lands and one that drifts onto a road.

**Edge AI.** Vision models detect dust plumes and, importantly, distinguish them from steam and water vapour, which is the single most common false-alarm source in a steel plant. A second class of models recognizes the *operation* - truck dumping, loader movement, belt transfer, tapping, slag pouring - so that suppression can start before the plume is visible rather than after.

**Control.** Each dust source is mapped to a dedicated group of actuators, each with stored presets for azimuth, pitch, flow, droplet size and duration. The gateway speaks the plant's language: dry contact, Modbus or MQTT, with a proper handshake to the DCS so that operators keep authority.

**Execution.** Long-range fog cannons cover open areas; dry fog and micro-mist systems cover belt transfer points and bunkers where added water is unacceptable; enclosure, local dedusting, sweepers and wheel washes do the work that water cannot.

**Data and verification.** Zone status, alarm lists, equipment availability, image pairs, water and power logs and compliance records - all exported on a schedule an auditor can read.

## Where the Dust Is: Six Hot Spots in an Integrated Steel Plant

![Fugitive dust source map of an integrated steel plant with matching suppression measures](/images/steel-plant-fugitive-dust-sources-map.svg)

| Hot spot | Dust behaviour | Primary measure | Notes |
| --- | --- | --- | --- |
| Raw material yard | Wide, low, wind-driven, driven by loader traffic | Long-range fog cannon, 80-300 m | Seal first where possible; spray is supplementary |
| Belt transfer station | High concentration, confined, continuous | Dry fog + enclosure + local dedusting | Water load must stay low to avoid belt slip |
| Sintering plant | Hot, fine, mixed with process gas | Enclosure + mist assistance | Capture hood takes priority over spray |
| BF cast house | Intense but short, thermal buoyancy | Event-triggered cannon linked to tapping signal | Start before tapping, not after |
| Steel making (BOF / EAF) | Short, high intensity, high temperature | Secondary dedusting hood first | Spray only as support, never as primary |
| Slag yard and haul road | Coarse, re-suspended by vehicles | Cannon + sweeper + wheel wash | Road hardening and cleaning matter more than spray |

The matching rule is straightforward. **Open and wind-driven** sources need reach and volume. **Confined and continuous** sources need fine droplets and very little water. **Hot process sources with strong gas flow** need capture first; spraying into a rising thermal plume mostly wastes water.

## The Parameters That Actually Decide the Outcome

### Throw distance: the nameplate number is measured in still air

Manufacturers quote throw under calm conditions. In a working yard, side wind above roughly 3 to 4 m/s visibly shortens effective reach and pushes the plume off target, which is why mounting height, overlap between adjacent units and wind-aware presets matter more than the headline figure. A practical design covers the target area with at least two units so that one can fail without leaving a gap.

### Droplet spectrum: match the droplet to the dust

![Droplet size versus dust particle size matching curve for fog cannon selection](/images/fog-cannon-droplet-size-matching.svg)

Inertial capture works best when droplet diameter and dust diameter are of the same order. Coarse spray above 200 micron knocks visible plumes down over stockpiles but barely touches respirable dust. Fine mist in the 10 to 50 micron range is the right regime for PM10 and PM2.5 - and it only works if the nozzle is close to the source, because fine droplets evaporate and lose momentum quickly over a long throw. This is why long-range cannons and dry fog systems are complements, not substitutes.

### Water, wetting and winter

Every litre added to the material is a litre that ends up on a belt, in a bunker, or frozen on a road. Define an acceptable moisture increase with the production team before selecting flow rates, and specify antifreeze drainage and heat tracing from the start in northern sites. A system that is bypassed in January has an annual availability problem, not a winter problem.

### Linkage delay

A loader pass generates a plume that peaks within seconds. If recognition plus actuation takes more than about half a minute, the spray arrives after the dust has already left. Measure and specify end-to-end latency, not model accuracy alone.

### Duty cycle in a steel environment

Lenses get dirty, bearings get dust, and cast-house areas are hot. Specify IP55 or better on electrical cabinets, corrosion protection appropriate to a sinter or slag atmosphere, automatic lens cleaning or a maintainable cleaning interval, and a spare-part list that matches the site's own maintenance rhythm.

## Control Logic: The Six-Step Closed Loop

![Closed-loop control workflow from monitoring and identification to verification and recording](/images/ultra-low-emission-control-loop.svg)

Monitor, identify, grade, trigger, verify, record. The value is concentrated in steps three and five.

Grading turns a binary alarm into a proportionate response: Level I runs a short local burst, Level II runs the full preset for the zone, Level III escalates to the operator console with the image attached. Verification closes the loop - if the plume does not clear within the expected window, the system escalates instead of silently spraying forever, which is also what prevents a stuck valve from running a pump all shift.

Tuning never ends. Thresholds that are too tight generate nuisance alarms and the operators will mute the system within a month; thresholds that are too loose mean the inspector sees dust the system never noticed. Expect two to four weeks of on-site tuning per plant, and budget for it.

## How to Prove It Works: An Evaluation Method That Survives Audit

Dust projects lose credibility through bad measurement, not bad equipment. A defensible evaluation follows four rules.

**Same point, same weather window.** Compare concentration before and after intervention at the same monitor, in comparable wind speed and direction. Comparing a calm afternoon with a windy morning proves nothing.

**Use continuous data, not spot checks.** Online TSP and PM10 at hot spots and at the fence line, logged at one-minute resolution, give a distribution you can actually argue with.

**Count the visible events.** Let the vision system count visible-dust-escape events per week. This is the direct translation of the policy wording into a KPI, and it is the number an assessment team cares about.

**Track the inputs.** Water, electricity, run hours and equipment availability per zone. A system that halves consumption while holding concentrations is the result a CFO and an EHS manager can both sign.

## Six Common Pitfalls

1. **Buying on nameplate throw alone.** Reach without droplet data, coverage drawing and wind assumptions is marketing, not engineering.
2. **One giant cannon for the whole yard.** Distance kills droplet momentum and precision. Several properly placed medium units beat one headline unit.
3. **Ignoring wind.** No wind-aware presets means spraying onto roads, into workshops and onto neighbours.
4. **Coarse spray for fine dust.** Visible plume disappears, PM10 barely moves, and the monitoring data says nothing changed.
5. **No interlock with operations.** Linking to tapping signals, belt running signals and truck presence turns a reactive system into a predictive one.
6. **No maintenance contract, no data owner.** Both are cheap to plan and expensive to retrofit.

## The Purchase Price Is the Smallest Number: Reliability Decides the Real Cost

Most sourcing decisions are still made on a three-column sheet: throw, flow, price. None of those three predicts what the machine will cost over five years. In this industry the gap between a cheap unit and a durable one shows up in exactly three places.

**1. Underperformance means buying twice.** If effective reach, droplet spectrum or coverage falls short, the visible plume stays and the assessment does not pass. The remedy is rarely a settings change - it is additional units, new foundations, new cable runs and a second round of shutdown coordination. The second purchase almost always costs more than the difference that was saved, and it usually happens against a compliance deadline, which is the most expensive schedule there is.

**2. Unstable quality is paid for in production hours.** Nozzles clog, pumps lose pressure, slewing drives wear, cabinets fail in a sinter atmosphere. Every failure removes suppression from that zone, and the compliance requirement is continuous rather than average: at least 95 percent of hourly values in a month have to meet the limit. Worse, repairs in a live stockyard or on a transfer gallery have to be coordinated around production. The real cost of an unreliable machine is therefore measured in operating hours, not in spare parts.

**3. Poor industrial design shortens service life.** Outdoor structural steel, corrosion protection, bearing and motor protection, winter drainage, and whether a technician can actually reach the parts that fail - these decide whether a unit lasts three seasons or fifteen years. Early replacement is never priced at the equipment tag: it includes foundations, piping, electrical work, reinstallation and another shutdown window.

A more useful comparison sheet has different columns:

| Ask this | Not only this |
| --- | --- |
| Brand and local availability of pump, motor, gearbox, PLC and nozzles | Total unit price |
| Corrosion class, protection grade, measured duty hours in similar plants | Nameplate throw |
| Documented continuous-operation records at comparable sites | Site photos |
| How many design iterations the maker has shipped in this industry | Delivery time |
| Spare-part lead time and service response, in writing | Warranty sentence |

One practical proxy for the last two: how long the supplier has been doing this exact job, in this exact industry. Vendors with years of accumulated field cases in steel, mining and bulk material handling design against the failure modes that actually occur - nozzle clogging, icing, corrosion, continuous duty - because they have already paid for them. Fenghua Environmental is one of them: decades of work on air-assisted spray dust suppression, the first drafting unit of the industry standard JB/T 13562-2018, and a range that runs from 30 m dry-fog units to 300 m long-range cannons. The brochure is the least interesting part. What matters is that the design iterations, the spare parts and the service people already exist when a plant needs them in year six.

## Outlook: Dust Control Is Becoming an Operational Data Problem

The direction of travel is clear. Fugitive dust management is shifting from "install equipment" to "run a data loop" - event recognition instead of schedules, per-zone accountability instead of yard-wide averages, and evidence generated as a by-product of operation rather than assembled before an audit. As more plants complete ultra-low emission retrofits, the competitive differentiator will not be whether a cannon can throw 120 metres. It will be whether the plant can show, for any given shift last year, what the air did and what it did about it.

One useful instrument for getting there is the sector's own technical baseline: JB/T 13562-2018, *Technical specification for air-assisted spray dust suppression devices*, issued on 4 July 2018 and implemented on 1 May 2019. Writing performance requirements in the terms that standard uses - rather than in brochure terms - is the cheapest way to make competing quotations genuinely comparable.

## Keep the Conversation Going

No two plants share the same dust geometry. A coastal stockyard and an inland transfer station generate the same compliance problem from completely different sources, and a zone logic that fits one is rarely right for the other.

If you are working through a specific case — a stockyard that keeps failing the visible-emission check, an interlock that was specified but never commissioned, or a monitoring system whose data nobody acts on — feel free to get in touch. We would rather talk through the sensing and suppression layout of your particular site than send a generic proposal.

- Website: <http://www.cannonsprayer.com/>
- Email: <greenpath19960117@gmail.com>
