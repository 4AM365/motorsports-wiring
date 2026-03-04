# Wires
## General Purpose
| Spec | When to Use | Who Makes It | Temp | Flexibility |
|------|-------------|--------------|------|-------------|
| **GXL** (XLPE thin wall) | Engine compartments, general automotive wiring, most common choice, space-conscious applications | Kalas, Southwire, Allied Wire, General Cable | -40°C to 125°C | Good (thinner wall than SXL, fits tighter spaces) |
| **TXL** (XLPE extra-thin wall) | Tight spaces, weight-sensitive builds, complex harnesses, minimal diameter needed, lightest option | Kalas, Southwire, Allied Wire, General Cable | -40°C to 125°C | Excellent (thinnest wall, most flexible SAE wire) |
| **SXL** (XLPE standard wall) | High abrasion areas, heavy-duty applications, motor leads, maximum durability needed | Kalas, Southwire, Allied Wire, General Cable | -40°C to 125°C | Moderate (thickest wall = most abrasion resistant) |
| **MIL-W-22759/32-44** (PTFE) | Motorsports/racing, aerospace, extreme heat environments, chemical exposure, professional harnesses | ProWire, RaceSpec, Glenair, Harbour Industries | -65°C to 200°C | Good to excellent (varies by strand count, more rigid than XLPE) |

- Use with Prowire ident kit or printed

## High Current Wires (6 AWG to 4/0 AWG)

| Spec | When to Use | Who Makes It | Temp | Flexibility |
|------|-------------|--------------|------|-------------|
| **STX** (XLPE thin-wall) | Motorsports/racing, tight spaces, weight-sensitive builds, professional harnesses - same protection as SGX but thinner | Southwire, Allied Wire, Nassau Cable | -40°C to 125°C | Better than SGX (thinner wall = more flexible) |
| **SGT** (PVC) | Standard battery/starter circuits, away from extreme heat, budget-conscious repairs, OEM replacement | Kalas, Southwire, Allied Wire, General Cable | -40°C to 80-105°C | Moderate (stiff enough to stay in place) |
| **SGX** (XLPE) | Hot engine bays, near turbos/exhaust, high-performance engines, maximum service life, chemical/oil exposure | Kalas, Southwire, Allied Wire, General Cable | -40°C to 125°C | Good (stiffer/thicker than SGT) |
| **SGR** (EPDM) | Complex routing with tight bends, high vibration diesels, maximum flexibility needed, RV/marine (if not salt water) | Southwire, General Cable | -40°C to 105°C | Excellent (most flexible) |
| **Welding Cable Class K** (EPDM) | Extreme flexibility, battery relocation to trunk, car audio systems, route AWAY from fuel/gas exposure | TEMCo, Kalas ToughFlex, General Cable | -40°C to 90-105°C | Extremely flexible (high strand count: 30 AWG strands) |
| **Welding Cable Class M** (EPDM/CPE) | Maximum flexibility, same uses as Class K but need even more flex | General Cable Super Vu-Tron | -40°C to 90°C | Ultra-flexible (highest strand count: 34 AWG strands) |



## Shielded Multi-Conductor Wire (MIL-SPEC & Commercial)

| Spec | When to Use | Who Makes It | Temp | Flexibility |
|------|-------------|--------------|------|-------------|
| **M27500-22TE2T14** (2C twisted pair) | VR crank/cam sensors, high-noise environments, twisted pair needed for noise rejection | ProWire, RaceSpec, Harbour Industries, Glenair | -65°C to 150°C | Good (ETFE jacket, 22 AWG stranded) |
| **M27500-22SD3T23** (3C) | MAP/TPS/IAT combo sensors, 3-wire analog sensors, general sensor harnesses | ProWire, RaceSpec, Harbour Industries | -65°C to 150°C | Good (ETFE jacket, tinned copper braid 85%) |
| **M27500-22SD4T23** (4C) | Complex sensor arrays, quad-output sensors, multi-sensor bundles | ProWire, RaceSpec, Harbour Industries | -65°C to 150°C | Good (more bulk than 2-3 conductor) |
| **M27500-22SD6T23** (6C) | Wideband O2 (heater + signal + calibration), complex multi-pin sensors | ProWire, RaceSpec, Harbour Industries | -65°C to 150°C | Moderate (bulkier with 6 conductors) |
| **M22759/32** (2C twisted, CAN spec) | CAN bus (yellow/green pair), specified twist rate for CAN protocol compliance | ProWire, RaceSpec, Aircraft Spruce | -65°C to 150°C | Good (purpose-built for CAN, twisted to spec) |
| **Belden 8723** (2 pair/4C) | Budget sensor wiring, MAP/TPS/IAT, non-critical applications, cost-sensitive builds | Belden | -40°C to 80°C | Good (PVC jacket, foil shield, less heat tolerance) |

** Notes:**
- **M27500 prefix** = Military spec shielded cable (NEMA WC27500), motorsport/aerospace grade
- **M22759 prefix** = Military spec single conductor wire, used in twisted pairs for CAN
- **Shield grounding:** Connect at ECU end ONLY (sensor end floating) to prevent ground loops
- **Twisted pair required:** VR crank/cam sensors, CAN bus - maintains signal integrity
- **Jacket codes:** T14 = White ETFE, T23 = White XL-ETFE
- **Conductor codes:** TE = ETFE insulated, SD = Modified ETFE, RC = M22759/11 component
- **Price:** M27500 cables $1-3/ft, Belden 8723 $0.50-1/ft, Alpha Wire $0.40-0.80/ft
- **Minimum orders:** RaceSpec/ProWire typically 50ft minimum for M27500

**Application Guide:**
- **VR Crank/Cam Sensors:** M27500-22TE2T14 (2-conductor twisted, shielded)
- **Hall Effect Sensors:** M27500-22SD3T23 (3-conductor for 5V/signal/ground)
- **MAP/TPS/IAT Combo:** M27500-22SD3T23 or Belden 8723
- **Wideband O2:** M27500-22SD6T23 (6-conductor for heater+signal+ground+cal)
- **CAN Bus:** M22759/32 twisted pair (yellow/green) or M27500-22TE2T14
- **Knock Sensors:** M27500-22TE2T14 (shielded twisted pair)
- **Budget Applications:** Belden 8723 or Alpha Wire 6454 (industrial grade)



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
| FTZ Lugs | Easy/cheap, but be cautious of bolts or nuts loosening. | Cheap ($1-3/ea) | FTZ Correct Crimp |
| Surlock | Inherently strain relieved, rotates, quick and easy to work with, great current capacity (150-300A) | Expensive ($15-30/ea) | Surlock Hand Tool |
| Radlok | Works with ECUMaster PMU, Haltech Nexus, nice compact design, 70-500A | Expensive ($10-20/ea) | Radlok Crimp Tool |
| Anderson Powerpole | Genderless, 15-45A common sizes, DC power standard | Moderate ($2-5/ea) | Anderson PP Crimper |
| AMP MCP 2.8 | OEM high current (20-35A), good sealing | Moderate | Standard open barrel |


## Bulkhead Connectors
| Brand | Type | Positions | Gauges | Current | Notes |
|-------|------|-----------|--------|---------|-------|
| Amphenol | AT (Sine) | 2, 3, 4, 6, 8, 12 | 16-24 AWG | 7.5A/pin | Deutsch DTM compatible, 30-50% cheaper, IP67 |
| Amphenol | ATP (Sine) | 2, 3, 4, 6, 8, 12 | 10-14 AWG | 25A/pin | Higher current version of AT series |
| Amphenol | AT Bulkhead | 2, 3, 4, 6, 8, 12 | 16-24 AWG | 7.5A/pin | Panel mount with threaded coupling, IP67 |
| Amphenol | ARB | 2-16 pins | 16-20 AWG | 13A/pin | Economical bulkhead, 150°C, bayonet lock, good value |
| Deutsch | DTM | 2, 3, 4, 6, 8, 12 | 16-24 AWG | 7.5A/pin | Industry standard, most common in racing |
| Deutsch | DTM Bulkhead | 2, 3, 4, 6, 8, 12 | 16-24 AWG | 7.5A/pin | OEM standard, panel mount |
| Deutsch | DTP | 2, 3, 4, 6, 8, 12 | 10-14 AWG | 25A/pin | Higher current for fuel pumps, fans |
| Deutsch | DTP Bulkhead | 2, 3, 4, 6, 8, 12 | 10-14 AWG | 25A/pin | Higher current bulkhead option |
| Deutsch | DT | 2, 3, 4, 6, 8, 12 | 14-20 AWG | 13A/pin | Solid wedge lock, very common OEM |
| Deutsch | DRB | 2-12 pins | 12-18 AWG | 25A/pin | Heavy duty bulkhead, 175°C, rally/offroad |
| Deutsch | DT04/06 | 2-12 pins | 12-20 AWG | 13A/pin | OEM wedge lock style, motorsports common |
| AMP Superseal | 1-6 pins | 14-20 AWG | 15A/pin | Cheaper alternative to DT, 125°C |
| Molex MX150 | 1-24 pins | 16-22 AWG | 8A/pin | Common on import ECUs, 150°C |
| Souriau | 8STA | 2-19 pins | 22-26 AWG | 3-7.5A | High-end European racecars, compact, IP68 |

# Crimps and Splices

| Type | Brand/Model | Wire Gauge (Input) | Wire Gauge (Output) | Crimp Style | Seal Type | Current Rating |
|------|-------------|-------------------|---------------------|-------------|-----------|----------------|
| Perma-Seal Butt | Molex 19164-0013 | 22-18 AWG | 22-18 AWG | Heat shrink | NiAc adhesive lined | 19A |
| Perma-Seal Butt | Molex 19164-0044 | 16-14 AWG | 16-14 AWG | Heat shrink | NiAc adhesive lined | 26A |
| Perma-Seal Butt | Molex 19164-0056 | 12-10 AWG | 12-10 AWG | Heat shrink | NiAc adhesive lined | 44A |
| Perma-Seal Butt | Molex 19164-0079 | 8 AWG | 8 AWG | Heat shrink | NiAc adhesive lined | 80A |
| Perma-Seal Step-Down | Molex 19164-0043 | 16-14 AWG | 22-28 AWG | Heat shrink | NiAc adhesive lined | 19A |
| Perma-Seal Step-Down | Molex 19164-0077 | 12-10 AWG | 16-14 AWG | Heat shrink | NiAc adhesive lined | 26A |
| Scotchlok Heat Shrink | 3M MH18BCX | 22-18 AWG | 22-18 AWG | Heat shrink | Adhesive lined | 19A |
| Marine Heat Shrink | Ancor 309099 | 22-18 AWG | 22-18 AWG | Heat shrink | Adhesive lined | 19A |
| Marine Heat Shrink | Ancor 309101 | 16-14 AWG | 16-14 AWG | Heat shrink | Adhesive lined | 26A |
| Marine Heat Shrink | Ancor 309202 | 12-10 AWG | 12-10 AWG | Heat shrink | Adhesive lined | 44A |
| DuraSeal Butt | TE/Raychem D-406-0002 | 22-18 AWG | 22-18 AWG | Heat shrink | Nylon adhesive lined | 19A |
| MiniSeal Butt | TE/Raychem D-436-37 | 20-16 AWG | 20-16 AWG | Crimp | PVDF insulated | 26A |
| PIDG Step-Down | TE 327639 | 12-10 AWG | 22-18 AWG | Crimp | Nylon insulated | 19A |
| Uninsulated Hex Butt | FTZ B-8 | 8 AWG | 8 AWG | Hex crimp | None | 80A |
| Uninsulated Hex Butt | FTZ B-6 | 6 AWG | 6 AWG | Hex crimp | None | 120A |
| Uninsulated Hex Butt | FTZ B-4 | 4 AWG | 4 AWG | Hex crimp | None | 150A |

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





# Components


## Relays
|Brand and Model|Current|Positions|Form Factor/Socket|Continuous Duty|Diode Integrated|Notes|
|---------------|-------|---------|------------------|---------------|----------------|-----|
|Albright SW200|200A|SPST|M6 stud mount|Yes|No|Heavy duty winch/traction motor, proven design|
|BMW 61369198302|130A|SPST|Proprietary 3-pin|Yes|Yes|Massive current capacity, great for fuel pumps/fans, expensive but bulletproof|
|Trombetta 12V 100A|100A|SPST|M4 stud mount|Yes|No|Common golf cart solenoid, budget friendly|
|American Zettler AZ2280|80A|SPST|Custom sealed|Yes (derate 20%)|Yes|High current sealed relay|
|Albright SW80|80A|SPST|M4 stud mount|Yes|No|Golf cart grade, continuous duty|
|Tyco/TE V23134|70-80A|SPST|Custom sealed|Yes|Yes|High current, sealed, OEM common|
|Omron G8JN|50A|SPST|Custom sealed|Yes|Yes|Industrial grade, expensive but reliable|
|Panasonic ACT512|40A|SPDT|ISO Mini 5-pin|Yes|Yes|Sealed, automotive grade, reliable|
|Hella 4RA 007 791|40A|SPDT|ISO Mini 5-pin|Yes|Yes|OEM quality, good availability|
|Song Chuan 896H|40A|SPDT|ISO Mini 5-pin|Yes|Varies|Budget option, decent quality|
|TE Potter & Brumfield VFSH|40A|SPDT|ISO Mini 5-pin|Yes|Yes|Sealed, vibration resistant|
|Bosch 0332209150|30-40A|SPDT|ISO Mini 5-pin|Yes|Yes|Industry standard, 87/87a configuration, very common|
|Bosch 0332019150|30-40A|SPST|ISO Mini 4-pin|Yes|Yes|Standard 30/87 configuration|
|ISO Mini (generic)|20-40A|SPDT|ISO Mini 4/5-pin|Yes|Some|Compact, most common automotive relay|
|ISO Micro (generic)|20-25A|SPDT|ISO Micro 4/5-pin|Yes|Some|Smaller than mini, tight spaces|
|ATO|20A|SPDT|Blade fuse style|Yes|No|Blade-style, fits fuse panel, common for accessories|



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
|TE open crimps| Sargeant 12085271|
|Wire cutting | Rennsteig Mini|
|Large Lug crimping | FTZ Correct Crimp|
