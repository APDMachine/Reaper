# Part Selection

## Print settings are normal spec

| Setting  | Value |
| ------------- | ------------- |
| Layer height  | 0.2mm  |
| Extrusion width  | 0.4mm, forced  |
| Infill percentage:  | 40% + For the ducts and grill shell, Infill percentage reduced to 15-20% to save weight. |
| Infill type:  | grid, gyroid, honeycomb, triangle, or cubic  |
| Wall count: | 4 |
| Solid top/bottom layers:  | 5 |
| Supports  | None  |

There might be some screws or heat set inserts (definitely for the probe
mounts on the fixed carriages) missing from the CAD file since not all
variants are the same. Klicky PCB heat sets are included in every parts kit
I’ve ever seen so reference them. The others are all M3x5x4. I’ve also used
M3x5x5 on a few spots in my own prototypes, if in doubt measure the depth
of the hole if you have the 5mm long ones.
> [!WARNING]
> THIS IS **NOT** FOR BEGINNERS… but if you’re beta testing this you know what you’re getting yourself into.

## 1: Carriages: ***skip if using TAP***
### Reaper Carriages
![carriages-labeled](https://github.com/APD-Machines/Reaper/assets/5345379/fbcacf18-29ad-463f-90ae-3c9d665c963b)
| Carriage  | Extruder |
| ------------- | ------------- |
| C (Centre)  | Balrog  |
| | Sherpa Mini |
| | Hextrudort High |
| | LGX Lite |
| | LGX Lite Pro |
| | Hummingbird |
| L (Left) | Hextrudort |
| | Orbiter v1.5 |
| R (Right) | Orbiter v2 |
| | Galileo2 Stand-alone |
| | Wristwatch (Galileo2 internals) |
| | Orbiter V2 can be left or right depending on your extruder |

- Choose your rail size
- Choose belt size (if applicable 6mm only for MGN9H).
- The following work with these respective extruders due to motor placement.
X-Carriages covers Mine, Sherpa Mini, VZ Hextrudort High, LGX Lite, LGX
Lite Pro, Hummingbird. Orbiter and Hextrudort are for their respective
extruders.
- Choose length based on hotend and probe type.

## 2: Extruder
These plates match to your specific extruder only, they
are universal for carriages and hotends. They all vary on size based on motor placement, choose which works best. 
> [!WARNING]
> All extruders other than ***LGX Lite Variants***,***Balrog*** & ***G2SA*** will need a solution for the tension screw's.
> This is currently outside the scope of this project. Contact us for more info

***If using TAP, go into the folderstarting with it***

## 3: Hotend
Select the appropriate hotend making sure it matches the carriage style youve selected (Reaper, TAP etc)

## 4: Ducts:

### Ducts
![ducts-labeled](https://github.com/APD-Machines/Reaper/assets/5345379/ee806d09-a794-4884-9879-2c3af0cb90d2)

### Which duct for which Hotend?
| Duct  | Hotend |
| ------------- | ------------- |
| Standard  | Dragon ST/HF  |
| | Dropeffect NextG |
| | Revo Voron |
| | Slice Mosquito|
| | BambuLab |
| Volcano | Rapido V1 HF |
| | Rapido V2 HF |
| | Dropeffect NextG UHF |
| UHF | Rapido V1 UHF |
| | Rapido V2 UHF |
| | Dragon UHF |
| Overkill | Goliath  |
| | Mosquito Magnum+ |

Select which style duct for your appropriate lenght. Table above outlines which ducts support which hotend.
- LED
- NoLed

  
## 5: Grill 
![grills](https://github.com/APD-Machines/Reaper/assets/5345379/cf538094-1d2b-4dbf-82b2-1e5667ebe5ac)

Adds some style, but also a lil bit of weight. 2 Choices for now. I’ve
included 4 logo plates for the upper portion that gets back lit with a
WS2812B or equivalent.
***This is experimental and non-tested***

## 6: My extruder - Balrog
Optional since it’s a standalone. Uses LGX/HGX gears (pretty positive they’re interchangeable). Parts needed are denoted in the reference
pictures as well as their print orientation.

## 7: Strain Relief
Will only work for the Sherpa and My extruder. This has only
been tested for fit on an EBB36, It should work with the SHT36 as well as the
V0 style board if you prefer umbilical with brass standoffs, but am not
positive. ON ALL OTHER EXTRUDERS WHERE THE MOTOR IS ANGLED YOU
WILL NEED TO SOURCE ANOTHER STRAIN RELIEF/ADAPTER.
***The xh connectors in the side are there so the part cooling fans and LED’s
can be removed as a unit without having to reach around to the back side of
the toolhead. COMPLETELY unnecessary over complication on my part.***
