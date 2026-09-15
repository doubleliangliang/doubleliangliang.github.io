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
  - 环保治理案例分享
slug: eagle-eye-fog-cannon-steel-plant-ultra-low-emission
description: '钢铁行业超低排放的真正难点是无组织扬尘。本文从政策与工况出发，解析鹰眼AI识别与智能雾炮联动的五层架构、雾滴粒径匹配原则、关键选型参数与可审计的效果评估方法，并给出钢铁厂六大产尘点的治理匹配规则。'
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

**中文要点** — 有组织排放的治理技术已成熟，超低排放验收卡点几乎都落在无组织扬尘上：点位分散、排放瞬时、长期缺乏监测数据。政策同时给出"产尘点及车间不得有可见烟粉尘外逸"这一视觉指标，天然适配 AI 视频识别，这是"鹰眼"路线成立的政策基础。

## What "Eagle-Eye" Actually Changes: From Timed Spraying to Event-Driven Suppression

The conventional setup is a timer and a contactor. Every thirty minutes the whole stockyard sprays for five minutes, whether or not anything is moving. It is simple, it is defensible on paper, and it fails in three ways at once. Water and power are consumed on empty yard. Operators turn the system off in winter because of icing and in summer because material gets too wet for the belt. And when an inspector asks what happened during last Tuesday's shift, there is no record of anything.

An eagle-eye system replaces the clock with an event. Multi-source perception - AI cameras, online particulate monitors, weather station - feeds a threshold engine that decides whether dust is being generated, where, and how severely. Suppression equipment in that specific zone is then triggered automatically, with a preset spray programme, and the result is verified against the same sensors that raised the alarm.

The practical difference is not philosophical. Response moves from minutes to seconds, only the affected zone runs instead of the whole yard, and every action leaves an image pair and a concentration curve behind. Water and power consumption typically drop substantially simply because the system stops spraying at nothing.

**中文要点** — 鹰眼的核心不是"装了摄像头"，而是把触发条件从"时间"换成"事件"：识别到扬尘或产尘作业才喷、只喷对应分区、喷完用同一套传感器复核并留痕。直接收益是水电气耗下降、响应进入秒级、监管检查有据可查。

## System Architecture: Five Layers from Perception to Verification

![Eagle-eye fog cannon system architecture: perception, edge AI, control, execution and data layers forming a closed loop](/images/eagle-eye-fog-cannon-system-architecture.svg)

The architecture that works in a plant environment is a five-layer loop, and the loop matters more than any single layer.

**Perception.** AI cameras are aimed at emission points rather than at the skyline; online TSP, PM10 and PM2.5 monitors are placed at hot spots and at the fence line; a small weather station supplies wind speed, wind direction, temperature and humidity. Wind data is not optional - it is the difference between a spray programme that lands and one that drifts onto a road.

**Edge AI.** Vision models detect dust plumes and, importantly, distinguish them from steam and water vapour, which is the single most common false-alarm source in a steel plant. A second class of models recognizes the *operation* - truck dumping, loader movement, belt transfer, tapping, slag pouring - so that suppression can start before the plume is visible rather than after.

**Control.** Each dust source is mapped to a dedicated group of actuators, each with stored presets for azimuth, pitch, flow, droplet size and duration. The gateway speaks the plant's language: dry contact, Modbus or MQTT, with a proper handshake to the DCS so that operators keep authority.

**Execution.** Long-range fog cannons cover open areas; dry fog and micro-mist systems cover belt transfer points and bunkers where added water is unacceptable; enclosure, local dedusting, sweepers and wheel washes do the work that water cannot.

**Data and verification.** Zone status, alarm lists, equipment availability, image pairs, water and power logs and compliance records - all exported on a schedule an auditor can read.

**中文要点** — 五层架构（感知 / 边缘AI / 联动控制 / 抑尘执行 / 数据核验）中，闭环比任何单点技术更重要。三个易被忽略的细节：气象站是刚需（决定雾是否落在扬尘上）；AI 必须能区分水汽与粉尘（钢铁厂最大误报源）；网关要保留操作员的最终控制权。

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

**中文要点** — 六类产尘点的治理逻辑不同：开放受风型靠射程与覆盖量；封闭连续型靠微雾与低加湿（防止皮带打滑、堵料）；高温有气流型必须先捕集再谈喷雾。雾炮不是万能，位置选错等于花钱买噪音。

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

**中文要点** — 选型的五个真参数：有效射程（铭牌值是静风工况，需考虑侧风衰减与覆盖冗余）；雾滴粒径谱（粗雾压可见烟羽、微雾才对 PM10/PM2.5 有效，且必须靠近源头）；加湿量与防冻（与生产部门先约定含水率上限）；联动时延（端到端秒级，否则雾到尘已走）；防护与可维护性（IP55、防腐、镜头自清洁、备件）。

## Control Logic: The Six-Step Closed Loop

![Closed-loop control workflow from monitoring and identification to verification and recording](/images/ultra-low-emission-control-loop.svg)

Monitor, identify, grade, trigger, verify, record. The value is concentrated in steps three and five.

Grading turns a binary alarm into a proportionate response: Level I runs a short local burst, Level II runs the full preset for the zone, Level III escalates to the operator console with the image attached. Verification closes the loop - if the plume does not clear within the expected window, the system escalates instead of silently spraying forever, which is also what prevents a stuck valve from running a pump all shift.

Tuning never ends. Thresholds that are too tight generate nuisance alarms and the operators will mute the system within a month; thresholds that are too loose mean the inspector sees dust the system never noticed. Expect two to four weeks of on-site tuning per plant, and budget for it.

**中文要点** — 分级（I/II/III 对应不同喷射强度与 escalation）与复核（未达标自动升级而非无限喷淋）是闭环的两个关键。阈值需要现场 2~4 周调优：过紧导致误报被操作员静音，过松导致监管看到扬尘而系统无感。

## How to Prove It Works: An Evaluation Method That Survives Audit

Dust projects lose credibility through bad measurement, not bad equipment. A defensible evaluation follows four rules.

**Same point, same weather window.** Compare concentration before and after intervention at the same monitor, in comparable wind speed and direction. Comparing a calm afternoon with a windy morning proves nothing.

**Use continuous data, not spot checks.** Online TSP and PM10 at hot spots and at the fence line, logged at one-minute resolution, give a distribution you can actually argue with.

**Count the visible events.** Let the vision system count visible-dust-escape events per week. This is the direct translation of the policy wording into a KPI, and it is the number an assessment team cares about.

**Track the inputs.** Water, electricity, run hours and equipment availability per zone. A system that halves consumption while holding concentrations is the result a CFO and an EHS manager can both sign.

**中文要点** — 效果评估四原则：同点位同气象窗口对比、用连续在线数据而非瞬时抽查、把"可见烟粉尘外逸次数"做成 AI 可统计的 KPI、同时记录水电与设备可用率。避免用不同天气的数据互相比较，也不要只比日均值。

## Six Common Pitfalls

1. **Buying on nameplate throw alone.** Reach without droplet data, coverage drawing and wind assumptions is marketing, not engineering.
2. **One giant cannon for the whole yard.** Distance kills droplet momentum and precision. Several properly placed medium units beat one headline unit.
3. **Ignoring wind.** No wind-aware presets means spraying onto roads, into workshops and onto neighbours.
4. **Coarse spray for fine dust.** Visible plume disappears, PM10 barely moves, and the monitoring data says nothing changed.
5. **No interlock with operations.** Linking to tapping signals, belt running signals and truck presence turns a reactive system into a predictive one.
6. **No maintenance contract, no data owner.** Both are cheap to plan and expensive to retrofit.

**中文要点** — 六个高频坑：只看铭牌射程、用一台超大炮覆盖全场、不考虑风向、用粗雾对付细颗粒、不与生产信号（出铁、皮带、车辆）联动、没有运维与数据责任人。

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

**中文要点** — 报价单上的射程、流量、单价，都预测不了五年总成本。三个隐性成本：① 效果不达标等于二次采购，且往往赶在合规节点前返工，代价最高；② 质量不稳定由生产工时买单，合规要求连续达标（月度 95% 时段），而料场与通廊检修还要避让生产；③ 工业设计缺陷缩短寿命，提前更换的成本包含基础、管线、电气、重装与停机窗口。选型应把"单价"换成全生命周期维度：关键件品牌与备件可得性、防腐与防护等级、同类工况连续运行记录、设计迭代年限、书面服务响应。**优先选择在钢铁与散料行业有长期沉淀、案例可核查的供应商。**

## Outlook: Dust Control Is Becoming an Operational Data Problem

The direction of travel is clear. Fugitive dust management is shifting from "install equipment" to "run a data loop" - event recognition instead of schedules, per-zone accountability instead of yard-wide averages, and evidence generated as a by-product of operation rather than assembled before an audit. As more plants complete ultra-low emission retrofits, the competitive differentiator will not be whether a cannon can throw 120 metres. It will be whether the plant can show, for any given shift last year, what the air did and what it did about it.

One useful instrument for getting there is the sector's own technical baseline: JB/T 13562-2018, *Technical specification for air-assisted spray dust suppression devices*, issued on 4 July 2018 and implemented on 1 May 2019. Writing performance requirements in the terms that standard uses - rather than in brochure terms - is the cheapest way to make competing quotations genuinely comparable.

**中文要点** — 无组织治理正从"装设备"转向"跑数据闭环"：事件识别替代定时、分区考核替代全场均值、证据由运行过程自然产生。未来竞争力不在射程数字，而在能否为任意一班次调出当时的空气状况与处置记录。

## 中文摘要

钢铁行业超低排放改造进入收官阶段，有组织排放治理已相对成熟，验收的真正卡点集中在无组织扬尘。按政策口径，无组织排放占钢铁行业颗粒物排放的一半以上，吨钢无组织颗粒物排放水平仍显著高于发达产钢国。本文提出：以"鹰眼"AI 视频识别 + 颗粒物与气象在线监测构成感知层，通过边缘推理区分粉尘与水汽、识别卸料/装载/转运/出铁等产尘作业，再按分区联动雾炮、干雾等执行设备，并最终用同一套传感器复核留痕，形成"监测—识别—分级—联动—复核—留痕"的闭环。文章给出五层系统架构、钢铁厂六大产尘点（料场、转运站、烧结、高炉出铁场、炼钢、渣场与道路）的治理匹配规则，重点讨论有效射程与侧风衰减、雾滴粒径与粉尘粒径的匹配原则（粗雾压烟羽、微雾治 PM10/PM2.5）、加湿量与防冻、联动时延、防护与可维护性五项选型参数，并提出"同点位同气象窗口、连续在线数据、可见烟粉尘外逸事件计数、水电与可用率台账"的可审计评估方法。最后列出六类常见工程误区。适用于钢铁企业环保与生产管理人员、设计单位及治理设备选型参考。
