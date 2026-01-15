# Concepts
Current: How much
Voltage: How Fast
Power: How much how fast

Resistivity: 'friction' per length of wire, or between components

HEAT: Energy released when Current meets Resistivity. Causes more resistivity, which then consumes more current, releasing more heat.
- Must shed heat faster than it builds up, or build up VERY LITTLE.

Where does resistivity come from? 
- Long runs of wire
- Wire too small
- Connectors too small
- Loose nuts/bolts/screws
- Incomplete crimps (wire must be crushed solid)
- Low strand or aluminum wire breaking internally, making wire 'smaller'

# Rules to Stop Fires
Heat buildup must be slower than your ability to cool the wires.
Fuses pop when current builds, but not heat.
All powered circuits must have power switched off when not used, or they can build up heat over weeks, months, years.

# Wires
## General Purpose
| Type | Wire | Strand Count | Temp Rating | Notes |
| --- | --- | --- | --- | --- |
| SAE J1128 SXL | Bare Copper | 19-65 strands | 125°C | Cross-linked polyethylene, thin wall, abrasion resistant |
| SAE J1128 TXL | Bare Copper | 19-41 strands | 125°C | Extra thin wall, flexible, tight spaces |
| SAE J1128 GXL | Bare Copper | 19-65 strands | 125°C | General purpose, most common automotive wire |
| Tyco Spec 55 i.e MIL-W-22759/44 | Silver Plated Copper | 19-133 strands | 200°C | PTFE insulation, aerospace/mil-spec, chemical resistant |

- Use with Prowire ident kit or printed

##  High Current Wires
| Type | Good for current? | Flexible? | Temp | Notes |
|------|-------------------|-----------|------|-------|
| Welding Cable | Excellent (up to 600A) | Very flexible | 90-105°C | Many fine strands, but insulation not fuel/chemical resistant |
| SGX/SGT Battery Cable | Excellent | Good | 125-150°C | Automotive-specific, chemical resistant |
| Ancor Marine Grade | Very Good | Excellent | 105°C | Tinned copper, corrosion resistant |

## Sheathed Wires
| Type | Gauge | Config | Heat ? |
|------|-------|--------|--------|

# Connectors
## Low/Medium Current
| Type | Pins | Gauges | Current | Temp | Notes | 
|---|---|---|---|---|---|
|TE Deutsch 369| 3, 6, or 9 pin | 20-22 AWG | 5A/pin | 175°C | Great for corrosive environments i.e. bonneville |
| Deutsch DTM / Amphenol Sine | 2, 3, 4, 6, 8, 12 | 16-24 AWG | 7.5A/pin | 150°C | Great general purpose, easy crimp | 
| Deutsch DTP | 2, 3, 4, 6, 8, 12 | 10-14 AWG | 25A/pin | 150°C | Larger pins for higher current |
| Deutsch DT | 2, 3, 4, 6, 8, 12 | 14-20 AWG | 13A/pin | 150°C | Solid crimp, good sealing |
| Deutsch DT04/06 | 2-12 pin | 12-20 AWG | 13A/pin | 150°C | OEM common, wedge lock |
| AMP Superseal | 1-6 pin | 14-20 AWG | 15A/pin | 125°C | Cheaper alternative to DT |
| Delphi Metri-Pack 150/280/480 | Various | 20-24 AWG | 7-15A | 125-150°C | OEM standard, numbered for series |
| Molex MX150 | 1-24 pin | 16-22 AWG | 8A/pin | 150°C | Good sealing, common on imports |

## High Current
| Type | Notes | Price | Tool |
|------|-------|-------|------|
| FTZ Lugs | Easy/cheap, but be cautious of bolts or nuts loosening. Use Nord-Lock washers | Cheap ($1-3/ea) | FTZ Correct Crimp |
| Surlock | Inherently strain relieved, rotates, quick and easy to work with, great current capacity (150-300A) | Expensive ($15-30/ea) | Surlock Hand Tool |
| Radlok | Works with ECUMaster PMU, Haltech Nexus, nice compact design, 40-60A | Expensive ($10-20/ea) | Radlok Crimp Tool |
| Radsok | Lots of mating cycles (10,000+), great conductivity, 80-150A | Expensive ($8-15/ea) | Radsok Crimp Tool |
| Anderson Powerpole | Genderless, 15-45A common sizes, DC power standard | Moderate ($2-5/ea) | Anderson PP Crimper |
| AMP MCP 2.8 | OEM high current (20-35A), good sealing | Moderate | Standard open barrel |


## Bulkhead Connectors
| Type | Cost | Gauges | Current | Temp | Notes |
|---|---|---|---|---|---|
| DT Bulkhead | Moderate | 14-20 AWG | 13A | 150°C | Panel mount DT series, sealed |
| Deutsch DRB | High | 12-18 AWG | 25A | 175°C | Heavy duty, vibration resistant |
| Amphenol Bulkhead | Low-Moderate | Varies | Varies | 125°C | Budget option, less robust |
| Glenair Mighty Mouse | Very High | 20-22 AWG | 7.5A | 200°C | Aerospace, micro-miniature |

# Fuse Blocks
| Model | Notes | Current | Price |
|-------|-------|---------|-------|
| EGIS Mini | Connectorized! Plug in a Deutsch DTM. Modern solution | 15-30A/circuit | $$$ |
| Bluesea | De-facto standard for a long time. Screw terminals suck but reliable | 30A/circuit | $$ |
| Littelfuse MINI FH | Low profile, common OEM style | 30A/circuit | $ |
| Blue Wire 6-circuit DTM | Deutsch DTM connectorized, serviceable | 15A/circuit | $$$ |


# Distribution Blocks
| Type | Notes | Price |
|------|-------|-------|
| Deutsch Connectorized | Good, OEM, expensive, fixed config but reliable | $$$$ |
| Deutsch w/ 3D printed garage | Good, needs strain relief internally or potting, cheap, configurable | $$ |
| Datapanel | Expensive, big, but very professional appearance | $$$$ |
| EGIS | Nice, connectorized, modular design | $$$ |

# Tricks
- Use DTM as a node instead of splicing
- Don't use shrink tube as a boot
- Offset splices in a harness to avoid bulges
- Use service loops near connections for future rework
- Pot bulkhead connector backs with epoxy for vibration resistance
- Use adhesive-lined shrink on exposed crimps near heat sources
- Star ground topology for noise-sensitive circuits


# Bundling

## Securing
### Wire loom
- Kapton tape
- Dental floss
- Kevlar lace
### Loom to structure
- 'Tray' approach
- Zip Ties: PEEK for high-heat, Ty-Rap

## Shrink Tube
| Type | Ratio | Lining | Chemical | Heat | Notes |
| --- | --- | --- | --- | --- | ---- |
| DR25 | 2:1 | None | Excellent | 135°C | Very common, general purpose |  
| ATUL | 3:1 | Adhesive | Good | 110°C | Good for strain relief and sealing, seals out moisture |
| ATUM | 4:1 | Adhesive | Good | 110°C | High shrink ratio, complex shapes |
| SCL | 3:1 | Adhesive | Excellent | 135°C | Heavy wall, ruggedized |
| HTAT | 3:1 | Adhesive | Excellent | 200°C | High temp, expensive |
| Viton | 2:1 | None | Excellent | 175°C | Fuel/chemical resistant |
| Sumitomo-SWS A | 2:1 | None | Good | 125°C | Economical general purpose | 
| Sumitomo-SWS SFTW-203 | 2:1 | Adhesive | Excellent | 135°C | Semi-rigid, OEM common | 
| Sumitomo-SWS ATUM | 4:1 | Adhesive | Good | 105°C | High shrink, tight spaces | 
| 3M EPS-300 | 3:1 | Adhesive | Excellent | 110°C | General adhesive-lined | 
| 3M HDT | 3:1 | None | Excellent | 175°C | High temp, military spec | 
| Alpha Wire FIT-221 | 2:1 | None | Good | 135°C | Budget-friendly alternative | 
| Alpha Wire ATS | 3:1 | Adhesive | Good | 125°C | Dual wall adhesive | 
| Panduit HSTT | 3:1 | None | Good | 135°C | Thin wall, flexible | 
| Panduit HSTS | 3:1 | Adhesive | Excellent | 135°C | Thick wall with adhesive|

## Wraps 

| Type | Notes | Temp Rating | Pros/Cons |
| --- | --- | --- | --- |
| TESA | Various types for application, 51608 common | 150°C | Clean, professional, expensive, kinda serviceable |
| Electrical tape | Poor serviceability, makes a mess | 80°C | Emergency only, degrades |
| Concentric twist w/ lacing | Very nice for strain relief, traditional | 150°C+ | Time consuming, beautiful, serviceable |
| 


## Sleeving

| Brand | Model | Split | Heat | Chemical | Serviceable | Notes |
|-------|-------|-------|------|----------|-------------|-------|
| Techflex | Flexo-PET Clean-Cut | Closed | Keep Away | Good | Great | Clean cut edges, professional |
| Techflex | High Temp | Closed | 400°F | Excellent | Great | Near exhausts |
| Techflex | F6 Self-Wrap | Split | 250°F | Good | Excellent | Easy installation, serviceable |
| Federal Mogul | Bentley Harris | Closed | Varies | Excellent | Moderate | OEM grade |
| Raychem | BSPT | Closed | 200°C | Excellent | Poor | Aerospace grade |


## Conduit
- used by OEMs over electrical-taped wrap, avoid


# Sealing
- RT125 RTV and Prowire boots - excellent for bulkhead sealing
- TE S1125 Epoxy also works
- If you pot a connector, place Kapton tape over the wire so you can service it later. You can cut the tape off.
- 3M 4200 - marine adhesive sealant, flexible
- Hylomar - OEM favorite, non-hardening
- Use proper connector seals - don't rely on RTV alone


# Components


## Relays
|Brand and Model|Current|Positions|Form Factor/Socket|Diode Integrated|Notes|
|---------------|-------|---------|------------------|----------------|-----|
|Kilovac/TE EV200|500A|SPST|Custom stud mount|No|EV-grade, continuous duty, DC rated|
|Gigavac GX series|300-500A|SPST|Custom stud mount|No|Extreme high current, EV/battery disconnect|
|Albright SW200|200A|SPST|M6 stud mount|No|Heavy duty winch/traction motor, proven design|
|EZGO 27855G01|200A|SPST|M6 stud mount|No|Heavy duty golf cart/utility vehicle|
|Club Car 1012608|150A|SPST|M6 stud mount|No|OEM golf cart, intermittent duty only|
|BMW 61316913113|130A|SPST|Proprietary 3-pin|Yes|Massive current capacity, great for fuel pumps/fans, expensive but bulletproof|
|Trombetta 12V 100A|100A|SPST|M4 stud mount|No|Common golf cart solenoid, budget friendly|
|Solid State (Crydom)|25-100A|SPST|PCB or panel mount|N/A|No mechanical parts, silent, expensive, heat management required|
|American Zettler AZ2280|80A|SPST|Custom sealed|Yes|High current sealed relay|
|Albright SW80|80A|SPST|M4 stud mount|No|Golf cart grade, continuous duty|
|Tyco/TE V23134|70-80A|SPST|Custom sealed|Yes|High current, sealed, OEM common|
|Omron G8JN|50A|SPST|Custom sealed|Yes|Industrial grade, expensive but reliable|
|Panasonic ACT512|40A|SPDT|ISO Mini 5-pin|Yes|Sealed, automotive grade, reliable|
|Hella 4RA 007 791|40A|SPDT|ISO Mini 5-pin|Yes|OEM quality, good availability|
|Song Chuan 896H|40A|SPDT|ISO Mini 5-pin|Varies|Budget option, decent quality|
|TE Potter & Brumfield VFSH|40A|SPDT|ISO Mini 5-pin|Yes|Sealed, vibration resistant|
|Bosch 0332209150|30-40A|SPDT|ISO Mini 5-pin|Yes|Industry standard, 87/87a configuration, very common|
|Bosch 0332019150|30-40A|SPST|ISO Mini 4-pin|Yes|Standard 30/87 configuration|
|ISO Mini (generic)|20-40A|SPDT|ISO Mini 4/5-pin|Some|Compact, most common automotive relay|
|ISO Micro (generic)|20-25A|SPDT|ISO Micro 4/5-pin|Some|Smaller than mini, tight spaces|
|ATO|20A|SPDT|Blade fuse style|No|Blade-style, fits fuse panel, common for accessories|
- Use a relay with suppression diode for mechanical loads


# Batteries
## Types
|Type|Advantages|Precautions|
|-----|------|-----|
|Lead-Acid|Common, cheap|Can spill acid!|
|AGM|Used for deep-cycle applications like auto stop-start, winching. Sealed.|Must use AGM charge profile on external alternator controller or charge with special charger every few weeks|
|Lithium-Ion|Ultralight, sealed|Big fires if they fail, and they can especially if you have alternator issues.|


# Useful Links

## Info
[RBRacing Wiring Guide](https://www.rbracing-rsr.com/wiring_ecu.html)

[Marine How To](https://marinehowto.com/)

[Bundle calculator](https://efiwires.com/cmaCalculator)

## Stores

[Deutsch connectors](https://www.deutschconnectorstore.com/#)

[ProWireUSA](https://prowireusa.com/)

[RaceSpec Online](http://racespeconline.com/)

[Connector Experts](connectorexperts.com)

[TE Automotive](https://www.te.com/en/products/connectors/automotive-connectors.html)

[]()


# Tools
|Application|Tool|
|---|---|
|Wire stripping| Ideal Stripmaster|
|Sheathed wire stripping | Ideal Ringer|
|Heat Shrink Crimps | Panbo Pro-VDH|
|TE open crimps| Sargeant / Delphi Crimper|
|Wire cutting | Rennsteig Mini|
|Large Lug crimping | FTZ Correct Crimp|
