---
title: 'How Fog Cannons Work: Core Principles of Dust Suppression'
date: 2026-09-18 15:23:18
tags:
  - Fog Cannon
  - Dust Suppression
  - Droplet Size
  - Atomisation
  - Dust Control Principles
  - Explosion Protection
  - Equipment Selection
categories:
  - 环保治理案例分享
description: Droplet size, atomisation, transport and evaporation. The six physical principles that decide whether a fog cannon actually suppresses dust, how to read a specification sheet against them, and the ten questions worth asking any supplier — including automation, service life, explosion protection and coastal corrosion.
---

Ask ten people on a dusty site how a fog cannon works and most will describe a large fan blowing water at a pile. That description is wrong in a way that matters, because it leads to the wrong diagnosis whenever the machine underperforms: more pressure, more water, a bigger pump, a longer barrel. None of those address the actual problem.

A fog cannon is a device for manufacturing a specific droplet spectrum and then transporting that spectrum through the air to a dust source, where the droplets attach to particles and carry them down. Every clause of that sentence is a separate physics problem, and a machine only performs when all of them are solved at the same time. The failure modes are equally specific: a machine can make the right droplets and never deliver them, or deliver the wrong droplets perfectly.

![Diagram of the three droplet-to-particle capture mechanisms: impaction, interception and diffusion](/images/fog-cannon-droplet-particle-capture-mechanisms.svg)

<!-- more -->

## A Fog Cannon Is Not a Watering Can

The difference between a fog cannon and a sprinkler is not scale, and it is not pressure. It is that a sprinkler throws water at the ground, while a fog cannon creates a cloud of droplets small enough to behave almost like a gas, and then moves that cloud with a jet of air.

That distinction decides everything downstream. Water that reaches a stockpile as run-off has done nothing about dust that is already airborne. Water that lands on a haul road is doing something useful, but it is a different job — surface conditioning rather than airborne capture — and it needs a different droplet size and a different application rate.

Most underperforming installations are mixing the two jobs on one machine and doing neither properly.

Mechanically, a fog cannon is two systems bolted together: a hydraulic circuit that decides what size droplets are made, and an aerodynamic circuit that decides whether those droplets arrive. The six principles below are simply what governs each of them.

![Side view of a fog cannon showing the water source, pump, control cabinet, turret, axial fan, barrel and nozzle ring with the transported fog plume](/images/fog-cannon-water-air-energy-chain.svg)

## Principle One: A Droplet Only Captures What It Can Catch

A droplet in an airflow does not sweep particles out of the sky the way a net catches fish. It captures them through three mechanisms, and which one dominates depends entirely on the ratio of droplet diameter to particle diameter.

**Impaction** is the mechanism most people picture. A particle with meaningful inertia cannot follow the airflow as it bends around the droplet, so it leaves the streamline and strikes the surface. It is the dominant mechanism for particles above roughly ten micron.

**Interception** happens when a particle is small enough to follow the streamline faithfully, but the streamline itself passes within one particle radius of the droplet surface. The particle does not hit anything; it touches. It matters most in the one to ten micron band, which is precisely the band that matters most for health and for visible plume.

**Diffusion** governs sub-micron particles. These are buffeted by individual air molecules, travel a random path, and eventually wander into the droplet by accident. It is slow and it depends on residence time, which means it depends on how long the droplet and the particle stay in each other's neighbourhood.

The practical rule that comes out of all this is short: **capture efficiency peaks when the droplet is roughly ten to one hundred times the diameter of the particle being captured.** Below that ratio the droplet is too small to be a reliable target and is swept along with the air. Above it, the droplet's own airflow field deflects the particle around it, single-droplet efficiency falls again, and — more importantly — the droplet is heavy enough to fall out of the plume before it reaches the source.

This is why adding water is not the same as adding suppression. If a machine is producing a coarse spray of 400 micron droplets, it can double its flow rate and capture almost no additional PM10, because the droplets it added are still the wrong size for the particles it is chasing.

### Why the Visible Plume and the Respirable Fraction Need Different Answers

The dust that makes a site look bad and the dust that makes it dangerous are not the same dust. The visible plume at a transfer point is dominated by particles in the tens to hundreds of micron range, which settle out on their own given distance and time, and which are relatively easy to wet and knock down. The respirable fraction — PM10 and below, and especially PM2.5 — is invisible, stays airborne for hours, travels off site, and is the fraction that regulators and occupational hygienists measure.

A coarse spray aimed at the visible plume is therefore doing visible work on the least harmful fraction. Getting to the respirable fraction takes finer droplets, and finer droplets take a completely different operating discipline, which is Principle Three.

## Principle Two: The Droplet Spectrum Is Manufactured, Not Discovered

A nozzle does not produce "water mist". It produces a distribution — a spectrum — and the shape of that spectrum is set by the atomisation method and by a handful of physical variables.

There are two families in industrial use, and they behave differently enough that they belong to different categories of machine.

**Hydraulic or pressure atomisation.** The pump pressurises water, the nozzle converts that pressure energy into velocity, and the resulting liquid sheet breaks up into ligaments and then into droplets. This is what most fog cannon nozzle rings use, because it needs no compressed air and it produces the flow rates required for stockyard duty. Its characteristics are that raising pressure reduces droplet size with diminishing returns, that the spectrum is relatively broad, and that the nozzle is the wear part — orifice wear opens the spectrum up and the machine quietly gets coarser over a season.

**Two-fluid or air atomisation.** Compressed air shears the water at the nozzle, which produces a much finer and much more uniform spectrum at a far lower water flow. This is the family behind dry fog systems, typically in the 5 to 30 micron range, and it is the right tool when the target is respirable dust or when adding moisture to the material is unacceptable. The trade is cost, complexity, and an air supply that has to be dry and reliable.

What shifts the spectrum, whichever family is in use: orifice geometry, working pressure, the air-to-liquid mass ratio in two-fluid nozzles, surface tension, viscosity and temperature. Adding a wetting agent changes surface tension and therefore changes both the droplet spectrum and the way the droplet behaves once it lands.

**One number is never enough.** A claim of "100 micron droplets" describes nothing useful on its own. What a specification should state is a distribution: Dv10, Dv50 and Dv90. Dv50 describes the main duty. Dv10 tells you how much of the spray is fine enough to drift and evaporate before arrival. Dv90 tells you how much of the spray is coarse enough to land immediately under the nozzle. Two machines with the same Dv50 and different spans will behave completely differently on the same site.

## Principle Three: A Droplet That Evaporates Before It Arrives Suppresses Nothing

This is the principle that is most often ignored, and the one that explains most disappointment with long-range machines.

A water droplet suspended in unsaturated air evaporates, and its lifetime scales approximately with the **square** of its diameter. Halving droplet diameter reduces the time it survives in the air to about a quarter. The driving variable is the vapour pressure deficit — the gap between how much moisture the air could hold and how much it currently holds — so low relative humidity, high air temperature, and moving air all accelerate the loss.

The practical numbers are uncomfortable. A droplet of a few tens of microns in hot, dry, windy conditions can be gone in a second or two, which means it never reaches a dust source sixty metres away. A droplet of a few hundred microns is still largely intact after the same journey, which is why coarse spray appears to "carry" better — but by then we are back at Principle One, because those droplets are the wrong size for the fine fraction.

**Put the three principles together and the central conflict of fog cannon design appears:** the droplets that capture dust best are the droplets that survive transport worst. There is no setting that removes the trade-off. There is only a deliberate decision about which penalty a particular site can live with.

![Chart of effective reach against crosswind and droplet lifetime against relative humidity](/images/fog-cannon-effective-throw-vs-wind-and-humidity.svg)

The operational consequences follow directly.

**Rated throw distance is a laboratory number.** It is measured in still air, on a machine at full output, usually to the point where the jet has some residual velocity. Real effective throw — the distance at which droplets actually arrive at the source in a usable size — is shorter, and it collapses much faster in wind and dryness than the marketing figure suggests.

**The worst dust conditions are the worst spray conditions.** Midday in summer, with low humidity, high temperature and strong convection, is when dust generation peaks and when droplet survival is shortest. A machine that works acceptably at dawn may deliver almost nothing by early afternoon. That is a scheduling and expectation issue as much as an equipment issue.

**Long range and fine droplets are contradictory goals.** If the target is respirable dust at a fixed distance, the honest engineering answer is usually to shorten that distance: mount the machine closer, use several machines at lower output each, or move the point of capture to where the dust is generated rather than where it becomes visible.

## Principle Four: The Fan Is a Delivery System, Not a Dust Remover

There is a persistent belief on sites that the fan is there to blow dust away. It is not, and treating it that way produces a machine that moves the problem around the site boundary instead of solving it.

The fan's job is to generate a high-momentum air jet at the nozzle ring, so that the droplets are carried forward inside a coherent plume rather than falling out immediately under the machine. That jet also entrains ambient air as it travels, so the plume grows in volume and slows with distance — which is useful, because the entrained air is what actually delivers the fog across the width of a stockpile face rather than down a narrow corridor.

Two consequences are worth taking seriously. First, throw follows the jet's momentum flux at the duct exit, which grows with duct diameter and with the square of exit velocity. Barrel diameter is therefore a far more honest indicator of real range than fan motor rating, and a specification that quotes only kilowatts is telling you nothing about reach. Second, the jet has to be aimed at the point where dust is **generated**. Aiming at the visible cloud, which by definition has already travelled, means aiming several metres downstream of the problem and paying for the mistake in wasted water and electricity.

## Principle Five: Coverage Is a Geometry Problem, Not a Power Problem

A fog cannon is a point source with a fan-shaped footprint, and the footprint does not have a constant deposition rate. At short range, the same water flow is concentrated into a small area. At long range, it is spread across a very large one.

The variables that decide coverage are unglamorous: the horizontal oscillation arc and its dwell behaviour at the ends, the elevation angle relative to the source elevation, the position of the jet axis relative to the prevailing wind, and the overlap between adjacent machines. A single machine oscillating through 180 degrees spends most of its cycle pointing at areas it is not needed in, while the transfer point that generates the dust gets a thin slice of attention every pass.

Two design habits follow. Aiming across the wind rather than into it reduces the amount of plume blown back onto the machine and improves deposition on the target. And where a face is long, several smaller machines covering overlapping sectors usually outperform one large machine doing the whole job, because coverage is additive while throw distance is not.

## Principle Six: Dust Stays Down Only While the Surface Stays Wet

The last principle is the one that decides what happens in the hours after the machine stops.

Suppression is not a permanent state. Water applied to a surface evaporates, and the surface returns to its previous condition — often worse, because repeated wetting and drying can break a stable crust and create a finer, more mobile dust layer than the one you started with. This is a real and well-documented effect on unpaved haul roads and on stockpiles that are worked by machinery.

It follows that the correct rhythm is not one heavy application per day but repeated light applications at a rate matched to the evaporation rate. Which brings the argument back to droplet size, because the fine mist that captures airborne particles efficiently is also the mist that evaporates before it can condition a surface, and the coarse spray that conditions a surface does almost nothing for airborne dust.

The sites that get this right treat the two jobs as two systems: a fine-droplet regime for capture at the generation point, and, where surface conditioning is required, a separate wetting regime with its own nozzles and its own schedule. Trying to serve both with one nozzle ring and one pressure setting is the most common cause of a site that sprays constantly and still gets dust complaints.

## Reading a Specification Sheet Against the Principles

Most fog cannon datasheets are written to be compared, not to be evaluated. The following items are the ones that actually determine performance, and the ones most often missing.

| Item | Why it matters |
| --- | --- |
| Droplet spectrum: Dv10, Dv50, Dv90 | Decides capture efficiency and drift. A single average value is not a specification. |
| Throw distance, with the criterion stated | "80 m" means nothing unless it says what residual velocity, what flow and what wind speed. |
| Water flow at working pressure | Determines deposition rate and the size of the water supply and drainage system. |
| Nozzle type, count and replacement interval | The spectrum degrades with orifice wear, silently. This is a consumable, not a fixture. |
| Fan air volume and duct exit velocity | Determines momentum flux, and therefore real reach. |
| Duct or barrel diameter | A better indicator of range than motor rating. |
| Oscillation arc, elevation range, rotation speed | Coverage geometry. |
| Water quality requirement | Suspended solids and hardness determine how fast the nozzles clog. |
| Start sequence and dry-run protection | Determines whether the pump survives operator error and frozen lines. |
| Control method and interoperability | Decides whether the machine is a job or a background task. |
| Explosion protection class (hazardous areas) | Not a bonus feature. It is the admission ticket, and it comes with a certificate, not a verbal assurance. |
| Corrosion class and coating system (coastal) | Marine atmosphere is ISO 12944 C5-M. Miss either the alloy or the coating and you lose years, not percentages. |
| Design service life and consumable schedule | A different number from the warranty period, and it belongs in the technical agreement on its own line. |

The single most useful question to ask any supplier is not "how far does it throw" but "what droplet spectrum does it produce at the flow rate I actually need, and how does that spectrum change after a season of wear". A supplier who can answer that is selling an engineered machine. One who answers with a distance and a kilowatt rating is selling a brochure.

## Ten Questions That Separate an Engineered Machine from a Brochure

The first five decide whether the physics is right. The last five decide whether the machine is still doing its job in year three.

**Droplet size and reach**

1. At the flow rate I actually need, what are the **Dv10, Dv50 and Dv90**?
2. What does that spectrum look like **after a season of nozzle wear**?
3. The throw distance on the datasheet — measured at **what wind speed, what residual velocity and what flow**?
4. How often do the **nozzles** need replacing, and how long does it take?
5. Can the start sequence guarantee **air before water**, and is there dry-run protection?

**Automation, reliability, service life and hostile conditions** (developed further in the next section)

6. **How automated is it?** Can it interlock with my dust-generating equipment, report into the control system I already run, and does anyone have to stand next to it? That is one question wearing three hats: is this a job, or a background task?
7. **How do you demonstrate reliability?** What grade are the critical components, where do the spares sit, and how quickly does someone arrive when the machine stops? Adjectives are not evidence. Those four things are.
8. **What is the warranty period, and what service life is the machine designed for?** Ask for both, separately, and have both written into the contract. They are not the same number, and conflating them is how disputes begin.
9. **Will it hold up under very high, intermittent dust loading?** Listen for whether the answer is "we turn the water up" or "here is how it is staged". The first answer means there is no design behind it.
10. **What is the package for hostile conditions?** For coal, silo or petrochemical duty, ask for the **explosion protection class and the certificate**. For coastal sites, ask for the **corrosion class and the material grades**. For kiln or cooler duty, ask what the atomising components are made of. A supplier who answers with a class has done it before; "we can do anything" is the wrong answer.

## Where a Fog Cannon Is the Wrong Answer

An honest account of the principles has to include the cases where they point elsewhere.

In a fully enclosed transfer building, a fog cannon adds moisture to a confined volume, raises humidity, accelerates corrosion and creates handling problems with sticky material. The correct answer there is enclosure plus local exhaust ventilation, with a fabric filter or wet scrubber on the outlet.

Where material moisture is a process specification — cement, lime, fertiliser, or coal destined for a customer with a moisture limit — adding water is not a dust control measure, it is a quality defect. Enclosure and extraction are the only options.

Where the target is respirable dust in a confined chute, a two-fluid dry fog system at the generation point usually outperforms a jet-based machine, because it can be placed at the source with no throw distance to lose.

And where the dust source is a small area far from the nearest safe machine position, the limiting factor is the distance itself. More fan power does not fix a droplet survival problem.

## Conditions That Need a Different Package, Not a Bigger Machine

Everything above is general. A handful of site conditions, however, do not respond to a larger pump or a longer barrel. The physics is unchanged; the build has to change.

**Very high and intermittent dust loading.** Crusher discharge, screening houses, loading points and wagon tipplers release dust in pulses rather than in a steady stream. Raising water flow does not help, because the additional water is still the wrong droplet size. The answer is staged: fine fog at the generation point to catch particles the moment they are released, a cannon matrix for area coverage, and a separate wetting regime where surface conditioning is required. Three jobs, three systems — not one nozzle ring doing all three badly.

**Combustible gas, or dust that can explode.** Coal yards, coal silos, petrochemical plants, and parts of the metal powder and battery materials sector. The governing requirement is not capture efficiency but explosion protection: motors, control cabinets, wiring and sensors all have to be rated for the hazardous area, at the correct zone and temperature class. The relevant frameworks are the GB 3836 series for explosive gas atmospheres and the corresponding dust-protection standards, with markings such as Ex d IIB T4, and underground coal applications additionally requiring a mining product safety mark. "We can do that too" is not an answer. The certificate is.

**Coastal and harbour duty.** Salt spray is a slow failure mechanism, and the gap between an inland and a coastal installation is measured in years. Plain stainless steel will pit within a single monsoon season a few hundred metres from breaking surf. Three details decide the outcome: the grade of the wetted parts, the coating system on the structure — classified under ISO 12944, where the marine category is C5-M — and whether the fasteners and hinges are the same alloy as the body. Fitting 304 hardware to a coated structure is one of the commonest shortcuts, and it fails by galvanic corrosion.

**High temperature with abrasive dust**, such as cement kiln hoods and clinker coolers, where ordinary nozzles clog and wear quickly and heat-resistant atomising components are the requirement. And **cold, arid or high-altitude sites**, where the problem is not freezing but evaporation: at low humidity and high temperature a droplet's life is short and effective reach collapses, so the correct response is shorter throw, more machines, and capture closer to the point of generation.

These variants are configured options in the Fenghua Environmental range rather than specials: explosion-protected assemblies for coal, silo and petrochemical duty, with rated motors, cabinets and wiring; corrosion-protected packages for harbour and coastal sites, with stainless wetted parts, a marine-grade coating system, and fasteners matched to the body alloy; staged filtration with automatic backwash so a machine can run on the site's own recycled water instead of a new clean-water supply; heat-resistant atomising components for kiln and cooler duty; and the intelligent control layer that ties dust monitoring, weather data and production signals together so the machine starts where dust is generated rather than where it becomes visible. Throw distances across the range run from 30 to 250 m, selected against the dust source rather than against the brochure.

## What the Principles Add Up To

Fog cannon performance is decided by four numbers that interact: droplet size, transport momentum, distance, and evaporation. Get all four right and the machine is remarkably effective at a modest water consumption. Get any one wrong and no amount of additional pressure, flow or fan power will compensate, because the failure is not one of effort.

This is also why accumulated design detail matters more in this category of equipment than in most. Drain points that can actually be reached in the dark, nozzle rings that survive a season of abrasive water, access panels that let a fitter replace an orifice without dismantling the barrel, a control sequence that will not start water before air — none of these appear on a specification sheet, and all of them decide whether the physics described above still holds in year three. Fenghua Environmental has built its product line around that accumulation, including JB/T 13562-2018, the mechanical industry standard for air-assisted spray dust suppression equipment that the company helped draft.

## Keep the Conversation Going

Every site has a different dust source geometry, a different climate and a different constraint on water. A spectrum that is exactly right for a harbour coal yard is usually wrong for a quarry bench in a dry inland basin, and the calculations that connect the two are the same ones outlined above.

If you are working through a specific problem — a transfer point that will not settle, a machine that underperforms in the afternoon, a specification sheet you are trying to read against a real dust source — feel free to get in touch. We are happy to talk through the physics of your particular case rather than a generic recommendation.

- Website: <http://www.cannonsprayer.com/>
- Email: <greenpath19960117@gmail.com>
